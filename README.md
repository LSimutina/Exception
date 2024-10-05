Необходимо написать приложение, которое принимает набор чисел в качестве параметров командной строки, складывает их и результат выводит в консоль. Формат запуска приложения следующий:

``` 
java Sum 10 34 1
```

здесь **Sum** название класса, а числа после него будут переданы в массив строк, указанный в параметрах метода **main**. Таким образом, метод main принимает массив строк, в каждом из которых записано число. Необходимо эти числа преобразовать в тип **double** с использованием **Double.parseDouble()**, а затем сложить их между собой. Метод **parseDouble** выкидывает исключение **NumberFormatException** в случае, если вместо числа было передано что-то иное. Обработайте данное исключение и все строки, не являющиеся числами, считайте за 0.

```
Пример:
java Sum 10 3qq4 1
результат: 11
```