Как строгий старший брат, я ограничиваю своего младшего брата Васю во времени, которое он проводит за компьютерными играми. Я определяю прайм-тайм как период времени, в котором Вася может играть в компьютерные игры. Начальный час и конечный час я задаю как пару целых чисел.

Я написал функцию, которая принимает три числа - текущий момент (текущий час), начальный час разрешенного периода времени и конечный час разрешенного периода времени. Функция дает ответ на вопрос (в виде boolean): "Может ли Вася играть в указанное время?".

Если я скажу, что прайм-тайм с 12 до 15, это значит, что в 12:00 можно играть на компьютере, а в 15:00 игр уже быть не должно.

Я разрешаю Васе играть хотя бы один час в день.

# Задание

Напишите четыре теста в файле index.test.js используя Jest, которые бы проверяли все возможные ситуации, где функция может вернуть неверный результат.

``` javascript
isVasyaCanPlay(12, 10, 15); // true
isVasyaCanPlay(15, 10, 15); // false
```

Ваши тесты будут проверены в ручную преподавателем.
