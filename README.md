Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Описание:
Объявляем два массива одинаковой длины. Пишем метод, в котором цикл соразмерный длине массива, где внутри цикла идет проверка условия (<=3). Если ответ ДА, тогда элемент первого массива заносится в COUNT элемент второго. После этого идет увеличение COUNT на 1 и мы возвращаемся к циклу FOR, где i увеличиваем на 1.
Таким образом проверяем все до конца.