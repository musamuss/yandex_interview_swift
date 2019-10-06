# yandex_interview_swift
Тестовые задания на интервью Яндекса при приёме на работу
Тестовые задания на интервью Яндекса при приёме на работу
---------------------------------------------------------

### A. Камни и украшения

Ограничение времени | 1 секунда
---|---
Ограничение памяти | 64Mb
Ввод | стандартный ввод или input.txt
Вывод | стандартный вывод или output.txt

Даны две строки строчных латинских символов: строка J и строка S.
Символы, входящие в строку J, — «драгоценности», входящие в строку S — «камни».
Нужно определить, какое количество символов из S одновременно являются «драгоценностями».
Проще говоря, нужно проверить, какое количество символов из S входит в J.

Это разминочная задача, к которой мы размещаем готовые решения. Она очень простая и нужна для
того, чтобы вы могли познакомиться с нашей автоматической системой проверки решений.
Ввод и вывод осуществляется через файлы, либо через стандартные потоки ввода-вывода,
как вам удобнее.

### B. Последовательно идущие единицы

Ограничение времени|1 секунда
---|---
Ограничение памяти|64Mb
Ввод|стандартный ввод или input.txt
Вывод|стандартный вывод или output.txt

Требуется найти в бинарном векторе самую длинную последовательность единиц и вывести её длину.

Желательно получить решение, работающее за линейное время и при этом проходящее по входному
массиву только один раз.


### C. Удаление дубликатов

Дан упорядоченный по неубыванию массив целых 32-разрядных чисел.
Требуется удалить из него все повторения.

Желательно получить решение, которое не считывает входной файл целиком в память, т.е.,
использует лишь константный объем памяти в процессе работы.


### D. Генерация скобочных последовательностей

Ограничение времени|1 секунда
---|---
Ограничение памяти|20Mb
Ввод|стандартный ввод или input.txt
Вывод|стандартный вывод или output.txt

Дано целое число n. Требуется вывести все правильные скобочные последовательности длины
2 ⋅ n, упорядоченные лексикографически (см.
[Лексикографический порядок](https://ru.wikipedia.org/wiki/Лексикографический_порядок)).

В задаче используются только круглые скобки.

Желательно получить решение, которое работает за время, пропорциональное общему
количеству правильных скобочных последовательностей в ответе, и при этом использует
объём памяти, пропорциональный n.

### E. Анаграммы

Ограничение времени|1 секунда
---|---
Ограничение памяти|20Mb
Ввод|стандартный ввод или input.txt
Вывод|стандартный вывод или output.txt

Даны две строки, состоящие из строчных латинских букв. Требуется определить, являются ли эти строки анаграммами, т. е. отличаются ли они только порядком следования символов.


### F. Слияние k сортированных списков

Ограничение времени|1 секунда
---|---
Ограничение памяти|10Mb
Ввод|стандартный ввод или input.txt
Вывод|стандартный вывод или output.txt

Даны k отсортированных в порядке неубывания массивов неотрицательных целых чисел, каждое из которых не превосходит 100. Требуется построить результат их слияния: отсортированный в порядке неубывания массив, содержащий все элементы исходных k массивов.

Длина каждого массива не превосходит 10 ⋅ k.

Постарайтесь, чтобы решение работало за время k ⋅ log(k) ⋅ n, если считать, что входные массивы имеют длину n.
Формат ввода
Первая строка входного файла содержит единственное число k, k ≤ 1024.

Каждая из следующих k строк описывает по одному массиву. Первое число каждой строки равняется длине соответствующего массива, оставшиеся числа этой строки описывают значения элементов этого же массива. Элементы массивов являются неотрицательными целыми числами и не превосходят 100.

Формат вывода
Выходной файл должен содержать отсортированный в порядке неубывания массив, содержащий все элементы исходных массивов.
