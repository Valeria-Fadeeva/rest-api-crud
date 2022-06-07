# rest-api-crud

## План

Выяснить про REST API:
* HTTP-методы
* Стандартные HTTP-коды возврата состояний
* Примеры реализации на нужном языке

Реализовать:
* Первый грубый вариант реализации без базы данных и текста SQL-запросов
* Клиент на основе CURL, Python-библиотеки Requests, JS-frontend
* Первый грубый вариант реализации на основе PDO + SQLite
* Первый грубый вариант реализации на основе PDO + PostgreSQL
* Клиент на основе Python-библиотеки Requests
* Клиент на основе JS-frontend

### Первая информация

https://www.positronx.io/create-simple-php-crud-rest-api-with-mysql-php-pdo/
https://www.phpzag.com/how-to-create-simple-rest-api-in-php/
https://www.allphptricks.com/create-and-consume-simple-rest-api-in-php/
https://github.com/topics/php-rest-api
https://code.tutsplus.com/tutorials/how-to-build-a-simple-rest-api-in-php--cms-37000
https://only-to-top.ru/blog/programming/2019-11-06-rest-api-php.html
https://wp-kama.ru/handbook/rest/basic/http-status-codes
https://help.useresponse.com/ru/knowledge-base/article/%D0%B2%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-restful-api
https://starkovden.github.io/status-error-codes.html
https://qsusha.wordpress.com/2017/10/31/rest-api-%D0%BA%D0%BE%D0%B4%D1%8B-%D0%BE%D1%82%D0%B2%D0%B5%D1%82%D0%BE%D0%B2/
https://habr.com/ru/post/440900/
https://developer.mozilla.org/ru/docs/Web/HTTP/Status
https://docs.microsoft.com/ru-ru/rest/api/storageservices/common-rest-api-error-codes
https://restapitutorial.ru/httpstatuscodes.html

### Задание

> Backend:
 + PHP, PostgreSQL

> rest-api:
 + create, update, delete, view, list, search

> использовать СУБД postgres [базовые данные (*- обязательные поля)]:

> структура бд
  + название*,
  + описание*,
  + цена*,
  + фото*,
  + контакты*
> тех. характеристика (has one) (не обязательная запись, но если пользователь решиль добавить, то все поля обязательны)
  + марка*,
  + модель*,
  + год выпуска*,
  + кузов*,
  + пробег*
> доп. опции (has many), например:
  + кондиционер
  + подушки безопасности
  + мультимедия
  + круиз контроль
  + или любая другая опция
