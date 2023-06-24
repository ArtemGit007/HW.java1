# Домашнее задание к семинару 1

1. Выбросить случайное целое число в диапазоне от 0 до 2000 и сохранить в i

2. Посчитать и сохранить в n номер старшего значащего бита выпавшего числа

3. Найти все кратные n числа в диапазоне от i до Short.MAX_VALUE сохранить в массив m1

4. Найти все некратные n числа в диапазоне от Short.MIN_VALUE до i и сохранить в массив m2

[Вариант выполнения задания](https://github.com/ArtemGit007/HW.java1/blob/master/Homework1/hwork1.java)


# Домашнее задание к семинару 2

Задание
Дана строка sql-запроса "select * from students where ". Сформируйте часть WHERE этого запроса, используя StringBuilder. Данные для фильтрации приведены ниже в виде json-строки.

Если значение null, то параметр не должен попадать в запрос.

Параметры для фильтрации: {"name":"Ivanov", "country":"Russia", "city":"Moscow", "age":"null"}

Дополнительные задания

Дана json-строка (можно сохранить в файл и читать из файла)

[{"фамилия":"Иванов","оценка":"5","предмет":"Математика"},{"фамилия":"Петрова","оценка":"4","предмет":"Информатика"},{"фамилия":"Краснов","оценка":"5","предмет":"Физика"}]

Написать метод(ы), который распарсит json и, используя StringBuilder, создаст строки вида: Студент [фамилия] получил [оценка] по предмету [предмет].

Пример вывода:

Студент Иванов получил 5 по предмету Математика.

Студент Петрова получил 4 по предмету Информатика.

Студент Краснов получил 5 по предмету Физика.


[Вариант выполнения задания](https://github.com/ArtemGit007/HW.java1/blob/master/Homework2/hwork2.java)


# Домашнее задание к семинару 3

Задание

Пусть дан произвольный список целых чисел.

1) Нужно удалить из него чётные числа

2) Найти минимальное значение

3) Найти максимальное значение

4) Найти среднее арифметическое значение

[Вариант выполнения задания](https://github.com/ArtemGit007/HW.java1/tree/master/Homework3)
