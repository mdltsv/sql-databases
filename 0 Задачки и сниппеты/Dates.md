#### 1) При выборке прибавить к дате 1 день.

### 5. Спец типы данных
#### 5.1. Показать текущий день недели.
    Неочевидно. Надо понять, какая функция вытащит, что хранит.
    Через TO_CHAR, вроде, выходит
	Выведете на экран дату ближайшего понедельника.
#### 5.2. Показать вчерашнюю дату в формате 22:10:2018 23-11-11.
#### 5.3. Показать вчерашнюю дату в формате 22-10-18 23-11-11.
#### 5.4. Показать вчерашнюю дату в формате 2018-10-22 23:11:11.
#### 5.5. Привести строку «20.01» к типу NUMBER.
#### 5.6. При выборке из таблицы прибавьте к дате 1 день.
Есть функции ADD_MONTHS, INTERVAL. В других СУБД:
```SELECT DATE_ADD(date, 1 DAY) as new_date FROM table;```
#### 5.7. При выборке из таблицы workers запишите день, месяц и год в отдельные поля.
#### 5.8. Выберите из таблицы workers записи, в которых минуты больше секунд.
#### 5.10. При выборке из таблицы workers прибавьте к дате 4 дня, 3 часа, 2 минуты, 1 секунду.
#### 5.11. При выборке из таблицы workers прибавьте к дате 3 дня и отнимите 2 часа.
#### 5.12. Выберите из таблицы workers все записи за пятый день апреля любого года.
#### 5.13. Выберите из таблицы workers все записи за вторник.
#### 5.14. При выборке из таблицы workers создайте новое поле today, в котором будет номер текущего дня недели.
#### 5.15. При выборке из таблицы workers запишите год, месяц и день в отдельные поля с помощью EXTRACT.
#### 5.16. Вычислить значение выражения 100*sIN (1) *cos (3).
#### 5.18. Вывести последний день месяца 80 дней назад.
#### 5.19. Преобразовать следующую строку к дате 01.11.2011 21:11.
#### 5.20. Вывести с помощью запроса значение sin числа от 0 до 1 с шагом 0,1.
#### 5.21. Вывести с помощью запроса число и день недели (TO_CHAR (DATE,«DY»)) всех дней за 2008 год.
#### 5.22. Выберите из таблицы workers записи с id равным 3, 5, 6, 10 и логином, равным 'eee', 'zzz' или 'ggg'.

Which datatype stores data outside the Oracle database?
A. UROWID
B. BFILE
C. BLOB
D. NCLOB
E. EXTERNAL

70.2. Создайте таблицу из двух полей: первое поле – идентификатор, второе – TIMESTAMP (ID, TMS).
70.3. Добавьте в таблицу запись с идентификатором 1 и текущей датой-временем.
70.4. С помощью запроса извлеките из таблицы идентификатор «дата-время», выберите час, минуту, секунду из текущего значения «дата-время».
