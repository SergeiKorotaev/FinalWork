# Задача :
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

**Описание решения:**
Создаем метод для печати массива.
Объявляется два массива: первый и вторый.
Создаем еще один метод, где внутри цикла проверяем содержит ли элемент массива 3 или мньше символов и создаем переменную count (счетчик). В случае выполнения условия, проверенный элемент первого массива добавляется в счетчик элементов второго массива. После присвоения увеличиваем счетчик на 1 и снова заходим в цикл, где i увеличиваем на 1. Прграмма выполняется, пока все элемены не пройдут проверку условия цикла.