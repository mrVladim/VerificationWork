#Описание решения задачи#

1. Создаём метод PrintArray для вывода значений массива 
2. Путем ввода значения size, задаём размер массива 
3. Объявляем массив arrayStrings Циклом for (int i = 0; i < size; i++) наполняем массив значениями, которые вводим с клавиатуры: Объявляем массив arrayFinal, такой же длины как и arrayStrings 
4. Объявляем две переменные length и count. length - количество символов в элементе, count - счетчик для определения длины финального массива 
5. Выполняем цикл for (int i = 0; i < size; i++) 
6. Цикл выполняется столько раз, сколько элементов в массиве, при этом, при каждой итерации проверяется условие: if (arrayStrings[i].Length <= length) в котором проверяется сколько символов в текущем элементе массива, и если количество символов меньше или равно заданному количеству length, то значение записывается в элемент массива. 
7. Делаем отступ строки Console.WriteLine() и методом PrintArray выводим массив arrayFinal на экран
