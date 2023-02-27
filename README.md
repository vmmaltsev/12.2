# Домашнее задание к занятию 12.2. «Работа с данными (DDL/DML)» - `Мальцев Виктор

---

Задание 1

1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

1.2. Создайте учётную запись sys_temp.

1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

1.4. Дайте все права для пользователя sys_temp.

1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

1.6. Переподключитесь к базе данных от имени sys_temp.

Для смены типа аутентификации с sha2 используйте запрос:

ALTER USER 'sys_test'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.

1.7. Восстановите дамп в базу данных.

1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

Результатом работы должны быть скриншоты обозначенных заданий, а также простыня со всеми запросами.


Ответ:

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_1.png)

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_2.png)

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_3.png)

---

Задание 2

Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца: в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. Пример: (скриншот/текст)

Название таблицы | Название первичного ключа
customer         | customer_id


Ответ:

![alt text](https://github.com/vmmaltsev/12.2/blob/main/PrimaryKey.xlsx)

Название таблицы | Название первичного ключа
actor            | actor_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_4.png)

address          | address_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_5.png)

category         | category_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_6.png)

city             | city_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_7.png)

country          | country_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_8.png)

customer         | customer_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_9.png)

film             | film_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_10.png)

film_actor       | actor_id
		   film_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_11.png)

film_category    | film_id
                   category_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_12.png)

film_text        | film_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_13.png)

inventory        | inventory_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_14.png)

language         | language_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_15.png)

payment          | payment_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_16.png)

rental           | rental_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_17.png)

staff            | staff_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_18.png)

store            | store_id

![alt text](https://github.com/vmmaltsev/screenshot2/blob/main/Screenshot_19.png)
	
	


