# Общее описание решений

### 1. Сделал git clone своего репозитория
### 2. Открыл через папку geometric_lib терминал
### 3. Создал ветку documentatio_(Номер ИСУ)
### 4. Описал решение файлов rectangle.py и triangle.py в PyCharm
### 5. Сделал git add и git commit каждому файлу
___

# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a

___

## Описание каждой функции с примерами вызова

### Circle:
_def area(r):_
    
_return math.pi * r * r_


    
    in: 5
    out: 78.5



### Rectangle:
_def rectangle (a, b):_

_return a*b_

    in: 5 6
    out: 30

### Square:
_def square(a):_

_return a*a_


    in: 5
    out: 25


### Circle:
_def circle(r):_

_return meth.pi * r * 2_

    in: 5
    out: 31.4

### Rectangle:
_def rectangle(a,b):_

_return 2 * a + 2 * b_

    in: 5 6
    out: 22

### Square:
_def square(a):_

_return 4 * a_

    in: 5
    out: 20

___
## Rectangle.py
Функция нахождения площади прямоугольника.

**def area(a,b):**

_'''Принимает число a и число b, возвращает их умножение, возвращает площадь'''_

**return a*b**

    Ввод: 5 2
    Вывод: 10

**def perimeter(a,b):**

_'''Принимает число a и число b, возвращает умноженную на два их сумму, возвращает периметр'''_

**return 2 * (a+b)**

    Ввод: 5 2
    Вывод: 14

## Triangle.py
Функция нахождения площади треугольника.

**def area(a,h):**

_'''Принимает число a и число h, возвращает площадь треугольника, a умноженную на половину h'''_

**return a * h / 2**

    Ввод: 10 8
    Вывод: 40

___
## История изменения проекта с хешами комитов (кроме последней записи)
commit
**e9902fa481ab23ff4e6b530baeffaecbdfe6e361**

Date Wed Sep 27 15:35:16 2023 +0300

     New file rectangle.txt added

commit
**25e2c8129801cb6e52f972be1a9f44221b74e5c2**

Date Wed Sep 27 15:39:04 2023 +0300

      Fix formula and added triangle.txt

commit
**74d10883b2af2706f1356516beb713b56662d16b**

Date Wed Oct 11 15:35:36 2023 +0300

       docs rectangle.py

commit
**201065e48e656cc7d40b56c0aa0496e15c2cfa8b**

Date Wed Oct 11 15:36:07 2023 +0300

       docs triangle.py









 