# Задание:
Возьмите 1-3 задачи из тех, что были на прошлых
семинарах или в домашних заданиях. Напишите к ним
классы исключения с выводом подробной информации.
Поднимайте исключения внутри основного кода. Например
нельзя создавать прямоугольник со сторонами
отрицательной длины.

# Решение
Исключения ко всем задачам реализованы в [class My_exception](My_exception.py)
## В качестве примеров взяты три задачи:
1. Rectangle.py - расчет площади, периметра прямоугольника,
селадывание и вычитание двух прямоугольников.
<br>
<br>
    Exceptions:

- [ValueError](Rectangle.py) - формат ввода , при возникновении ошибки, по умолчанию стороны всех прямоуголников = 1
- [class ValError](My_exception.py) - валидность значений сторон прямоугольника на отрицательные значения

2. Bank.py - банкомат по выдачи и зачислению cash  с учетом комиссии на снятие денег и начисленнию процентов
<br>
<br>
    Exceptions:
- [ValueError](Bank.py) - формат ввода
- [class ValueBankError](My_exception.py) - валидность значений cash

3. Matrix - сравнение, умножение, сложение двух матриц
<br>
<br>
    Exceptions:
- [ValFormatError](My_exception.py) - валидность формата матриц при различных операциях


