# Module11_homework
Module11_homework
# Задание

Напишите функцию `getPercents(percent, number)`, которая возвращает {percent} процентов от {number}.

Напишите тесты, которые проверяют успешное и неуспешное выполнение функции, а также корнер-кейсы.

## API

### `getPercents(percent, number)`

Вычисляет процент от числа.

- `percent` (number): Процент, который нужно вычислить.
- `number` (number): Число, от которого нужно вычислить процент.

Возвращает вычисленный процент в виде числа.

Выбрасывает ошибку, если любой из аргументов не является числом или если значение процента не находится в диапазоне от 0 до 100.

## Тесты

Напишите тесты, которые проверяют следующие случаи:

1. Успешное выполнение функции с различными значениями для `percent` и `number`.
2. Неуспешное выполнение функции при передаче неверных аргументов, таких как строки, объекты или `undefined`.
3. Неуспешное выполнение функции при передаче процентного значения, находящегося за пределами диапазона от 0 до 100.
4. Неуспешное выполнение функции при передаче `NaN` в качестве одного из аргументов.
5. Корнер-кейсы, такие как передача максимально возможных и минимально возможных значений для `percent` и `number`.

