# Итоговая работа

## Задача:
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Алгоритм выполнения:
1. Определили путь решения - будем использовать два массива.
2. Решили, что пользователь указывает сколько элементов он хочет задать и заполняет стартовый массив элементами в цикле, нужное количество раз.
3. Далее проходим по стартовому массиву (*arrayStrings*) в цикле и проверяем, подходит ли элемент условию "длина символов <= 3". 
4. Если элемент подходит под данное условие, то мы добавляем его в новый массив (*arrayFinal*), используя при этом дополнительный счетчик, чтобы элементы в новом массиве заполнялись последовательно (без пропусков).
5. Выводим итоговый массив на печать при помощи метода *PrintArray*.  

## Блок схема:
С блок-схемой к задаче можно ознакомиться в папке "Diagram".
## Код программы:
В папке "Task" находится решение задачи на C#. 