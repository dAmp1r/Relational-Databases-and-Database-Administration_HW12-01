# Relational-Databases-and-Database-Administration_HW12-01

*«Базы данных» - Горбунов Д.Н.*

Задание 1.

- Сотрудники:
    - идентификатор, первичный ключ, serial
    - ФИО сотрудника, varchar(50) 
    - Дата найма, date
    - Оклад, decimal(10,2)
    - Идентификатор Структурное подразделение, внешний ключ, integer
    - Идентификатор Роль в проекте, внешний ключ, integer

- Проект на который назначен
    - идентификатор, первичный ключ, serial
    - Проект, varchar(50)

- Адрес филиала
    - идентификатор, первичный ключ, serial
    - адрес филиала, varchar(50)

- Структурное подразделение
    - идентификатор, первичный ключ, serial
    - Подразделение, varchar(50)
    - Идентификатор Адрес филиала, внешний ключ, integer
    - Идентификатор Тип подразделения, внешний ключ, integer
 
- Тип подразделения
    - идентификатор, первичный ключ, serial
    - тип подразделения, varchar(50)

- Должность
    - идентификатор, первичный ключ, serial
    - должность, varchar(50)

- Роль в проекте
    - идентификатор, первичный ключ, serial
    - Идентификатор Должность, внешний ключ, integer
    - Идентификатор Проект на который назначен, внешний ключ, integer
