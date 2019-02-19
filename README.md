## Дипломная работа по курсу «PHP/SQL: back-end разработка и базы данных»

+ Разработан типовой сервис вопросов и ответов. Pеализована клиентская часть сервиса и интерфейс администратора.
+ Система реализована на PHP, использована MVC архитектура, компоненты реализованы с использованием ООП, данные администраторов, тем, вопросов и ответов хранится в СУБД MySQL
+ [Клиентская часть](http://university.netology.ru/u/nfomina/php/index.php?c=front&a=categories&categoryId=all)
+ [Интерфейс администратора](http://university.netology.ru/u/nfomina/php/index.php)

### Клиентская часть
![Клиентская часть](./resources/clientInt.jpg)

+ Пользователи могут просматривать категории, вопросы и ответы.
+ Любой пользователь может задать вопрос, указав своё имя, адрес электронной почты, выбрав категорию и написав текст вопроса.

### Интерфейс администратора
![Интерфейс администратора 1](./resources/admin_1.jpg)
![Интерфейс администратора 2](./resources/admin_2.jpg)
+ Для попадания в интерфейс администратора нужно ввести логин и пароль.
+ По умолчанию создан единственный администратор с логином admin и паролем admin.

### Инструкции по установке 
+ В файле config.php указать имя базы данных, логин и пароль к ней
+ Поместить содержимое папки на ваш сервер
+ Создать базы данных по структуре баз данных dump.sql


### UML-схема базы данных
![UML-схема базы данных](./resources/uml.jpg)

