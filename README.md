# Решение задачи
**Задача**

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

**Решение**

Для начала мы создадим 2 массива одного размера, первый из них заполним самостоятельно с клавиатуры. Составим цикл где будет проверка условия <= 3 символов, если условие выполняется записывам это значение во второй массив под нулевым индексом. Значение индекса воторого массива будем изменять при помощи переменной count, которая увеличивается на 1 после каждого прохождения условия. И так до завершения цикла.