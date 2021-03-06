# Практикум на 5 група

### Git & GitHub

* [Git website](https://git-scm.com/) 	
* ["Git Started with GitHub" free course](https://www.udemy.com/course/git-started-with-github/) 	
* [Git cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)

### Библиотечна система - мини проект

Да се реализира програма, която поддържа обектите и операциите на библиотечна система. 
Участници в нея са служителите и читателите, които могат да вземат за определен период от време книги или списания.

__Общи условия:__

* Всички полета, които не са с фиксиран размер в условието (като име или масив с неограничено добавяне), да се заделят динамично.
* За всеки клас да се създаде “голяма четворка” (конструктор, деструктор, оператор= и copy конструктор).
* За всички описани полета да се направят getters и setters (селектори и мутатори).


Програмата да поддържа следните команди:

|key|описание|
|-|-| 	
|__add employee__		|Регистрира служител (чрез супер потребител (admin/admin))
|__remove employee__	|Премахва служител (чрез супер потребител (admin/admin))
|__login employee__		|Служителя се аутентикира
|__add reader__			|Добавя читател (чрез служител)
|__remove reader__		|Премахва читател (чрез служител)
|__add book__ 			|Добавя нова книга (заглавие, автор, ISBN, брой страници, дата на издаване)|
|__list books__ 		|Отпечатва всички налични книги|
|__add magazine__ 		|Добавя новo списание (заглавие, издателство, ISBN, дата на издаване)|
|__list magazines__		|Отпечатва всички налични списания|
|__rent__ 				|Заемане на книга/списание на читател|
|__list all users__		|Отпечатва всички служители и читатели|
|__list rented__		|Отпечатва всички заети книги/списания като най-рано дадените са първи|
|__save <filename\>__	|Записва информация за състоянието на системата във файл|
|__open <filename\>__	|Прочита информация за състоянието на системата от файл|

Обекти:

* Книга 	
	- заглавие
	- автор
	- [ISBN](https://en.wikipedia.org/wiki/International_Standard_Book_Number)
	- брой страници
	- дата на издаване
	- служител, който я е добавил

* Списание 	
	- заглавие
	- издателство
	- [ISBN](https://en.wikipedia.org/wiki/International_Standard_Book_Number)
	- дата на издаване
	- служител, който го е добавил

* Читател 	
	- име
	- фамилия
	- дата на регистрация

* Служител 	
	- име
	- фамилия
	- позиция