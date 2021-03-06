## Съдържание

* **seminar_01.md** съдържа материала, за който говорихме по време на първия семинар. Най-отдолу има 2 задачи.
* **Complex numbers** съдържа решението на втората от двете задачи.
* **assets** съдържа помощни материали, използвани в **seminar_01.md**

---
## Какво трябва да можем, за да кажем, че разбираме материала?
Най-важното нещо е да можем да използваме структури и да разделяме правилно кода си в отделни файлове, когато решаваме задачи.
Въпроси отдолу са помощни, ако можем да отговорим на тях и да решаваме задачи, значи със сигурност разбираме материала. Отговори на тях може да откриете в **seminar_01.md**.

#### Header files

 * Какво слагаме в началото на всеки `.h` или `.hpp` файл?
 * Как бихме описали кода, който пишем в **header** файл.
 * Къде слагаме `#include <iostream>`, ако имаше нужда от конзолата в `.cpp` файл?
 * Каква е разликата между `#include "iostream"` и `#include <iostream>`?
 * Имате задача, която изисква да използвате 2 структури и функции, които работят върху двете структури, опишете файловата структура на вашето решение.

#### Структури

 * Какво е структура? Нарисувайте картинка.
 * Кога бихме използвали структура?
 * Как се създава структура?
 > Тук се има предвид дефиниране на структурата като тип, а надолу използването на променливи от този тип.


 * Как достъпват отделните **полета** на структурата?
 * Как да дадем първоначално стойност на дадена структура?
 * Как се дефинира функция, която използва структура за параметър?
 * Можем ли да върнем структура от функция?
 * Как се подава структура на функция?
 * Как се достъпват отделните полета на променлива, чийто тип е структура, чрез друга променлива, която е указател към първата.
 * Какво заменя оператор `->`?
 * Как се създава масив от структури?
 * Можем ли да имаме структура в структура? Защо?
 * Как се достъпват полетата на вложената структура?
 * Ако трябва да използвате структура "играч", как бихте я наименовали - `Player` или `player`?

#### Бележка
 * **Полета** наричаме променливите, които принадлежат на дадена структура, например `name`, `facultyNumber`, `major` и `address` са             **полета** за структурата `Student`. От своя страна `country`, `city`, `street` и `building` са полета за структурата `Address`.

```c++
struct Address
{
    char * country;
    char * city;
    char * street;
    char * building;
}

struct Student
{
    char * name;
    unsigned int facultyNumber;
    char * major;
    Address address;
}
```

 * Структури наименоваме с главна буква, а полетата в тях с малка буква.
