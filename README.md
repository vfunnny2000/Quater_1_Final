__Итоговая проверочная работа__

___Задача работы___:
1. Создать репозиторий на GitHub
2. Нарисовать блок-схему
3. Снабдить репозиторий файлом README.md
4. Написать программу, решающую следующую задачу:
        ```Создать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.```
      
    ```
    ["hello", "2", "world", ":-)"] -> ["2", ":-)"]
    ["12345", "1567", "-2", "computer science"] -> ["-2"]
    ["Russia", "Denmark", "Orel"] -> []

5. Использовать контроль версий в работе над этим проектом

*Решение задачи*

Переменная lengthLimit согласно условию задачи равна 3.

* __CheckArray__ - метод подсчета количества элементов, размер которых меньше lengthLimit.
    * подсчет осуществляется перебором элементов массива arrayOfStrings, сравнением количества их элементов с переменной lengthLimit
    * результат выводится в переменную numbersItems

Инициализируется новый массив строк newArrayOfStrings размером равный переменной numbersItems

* __FillNewArray__ - метод формирования нового массива строк
    * формирование массива осуществляется путем перебора элементов массива arrayOfStrings, сравнением количества их элементов с переменной lengthLimit и добавлением в массив newArrayOfStrings элемента, удовлетворяющего условию.
    * на выходе метода получается заполненный массив строк newArrayOfStrings, удовлетворяющий условию, что и является решением данной задачи

Для вывода решения на экран используется метод __PrintArray__.



   