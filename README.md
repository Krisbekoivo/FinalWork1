# Итоговая проверочная работа
**Формулировка задачи:** написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна трём символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:

["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []

**Решение задачи:**

1. На экран выводится сообщение "Введите число элементов массива" . Пользователь вводит число, которое является размером массива.
2. С помощью метода CreateArray массив заполняется строками, которые вводит пользователь.
3. Берем переменную count = 0, в которую запишется количество строк, длина которых меньше либо равна 3.Вычисляем количество строк, длинна которых меньше либо равна 3.
4. В цикле проходим по строкам массива: если длина строки меньше или равна трём, то увеличиваем переменную count и увеличиваем счётчик цикла. Если длина больше трёх увеличиваем, то только счётчик цикла.
5. Формируем массив с результатами.
6. Снова в цикле проходим по каждой строке и также сравниваем длину строки. Однако, теперь если длина меньше или равна трём, мы в текущий массив добавляем данную строку, уменьшаем count и увеличиваем счётчик цикла.
7. С помощью метода ShowArray выводим массив результатов.

Блок - схема алгоритма представлена ниже.

![](1.jpg)