# Итоговая проверочная работа
*Задача*: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

*Примеры*:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

## Описание решения
1. Вводим массив данных и задаем пустой массив, в который будут добавляться строки размером 3 или менее символов.
2. Задаем переменную count для подсчета количество соответствующих строк.
3. Задаем цикл подсчета количества символов в строке и заполнения пустого массива.
4. Выводим результат.