# Section 1

# Section 2

# Section 3

## 1. The value of the expressions 4/(3*(2-1)) and 4/3*(2-1) is the same.[Значення виразів 4/(3*(2-1)) і 4/3*(2-1) однакові?]

**a) True**

b) False

Explanation: Although the presence of parenthesis does affect the order of precedence, in the case shown above, it is not making a difference. The result of both of these expressions is 1.333333333. Hence the statement is true.

## 2. What will be the value of the following Python expression?[Яким буде значення наступного виразу Python?]

```4 + 3 % 5```

a) 4

**b) 7**

c) 2

d) 0

Explanation: The order of precedence is: %, +. Hence the expression above, on simplification results in 4 + 3 = 7. Hence the result is 7.

## 3. Evaluate the expression given below if A = 16 and B = 15.[Оцініть наведений нижче вираз, якщо A = 16 і B = 15?]

``` A % B // A ```

a) 0.0

**b) 0**

c) 1.0

d) 1

Explanation: The above expression is evaluated as: 16%15//16, which is equal to 1//16, which results in 0.

## 4. Which of the following operators has its associativity from right to left?[Який з наведених операторів має свою асоціативність справа наліво?]

a) +

b) //

c) %

**d) ****

Explanation: All of the operators shown above have associativity from left to right, except exponentiation operator (**) which has its associativity from right to left.


## 5. What will be the value of x in the following Python expression?[Яким буде значення x у наступному виразі Python?]

```x = int(43.55+2/2)```

a) 43

**b) 44**

c) 22

d) 23

Explanation: The expression shown above is an example of explicit conversion. It is evaluated as int(43.55+1) = int(44.55) = 44. Hence the result of this expression is 44.

## 6. What is the value of the following expression?[Яке значення має наступний вираз?]

```2+4.00, 2**4.0```


**a) (6.0, 16.0)**

b) (6.00, 16.00)

c) (6, 16)

d) (6.00, 16.0)

Explanation: The result of the expression shown above is (6.0, 16.0). This is because the result is automatically rounded off to one decimal place.


## 7. Which of the following is the truncation division operator?[Що з наведеного нижче є оператором поділу усічення?]

a) /

b) %

**c) //**

d) |

Explanation: // is the operator for truncation division. It is called so because it returns only the integer part of the quotient, truncating the decimal part. For example: 20//3 = 6.

## 8. What are the values of the following Python expressions?[Які значення мають наступні вирази Python?]

`2**(3**2)
 (2**3)**2
 2**3**2 `

a) 64, 512, 64

b) 64, 64, 64

c) 512, 512, 512

**d) 512, 64, 512**

Explanation: Expression 1 is evaluated as: 2**9, which is equal to 512. Expression 2 is evaluated as 8**2, which is equal to 64. The last expression is evaluated as 2**(3**2). This is because the associativity of ** operator is from right to left. Hence the result of the third expression is 512.

## 9. What is the value of the following expression?[Яке значення має наступний вираз?]

```8/4/2, 8/(4/2)```

**a) (1.0, 4.0)**

b) (1.0, 1.0)

c) (4.0. 1.0)

d) (4.0, 4.0)

Explanation: The above expressions are evaluated as: 2/2, 8/2, which is equal to (1.0, 4.0).

## 10. What is the value of the following expression?[Яке значення має наступний вираз?]

`float(22//3+3/3)`

a) 8

**b) 8.0**

c) 8.3

d) 8.33

Explanation: The expression shown above is evaluated as: float( 7+1) = float(8) = 8.0. Hence the result of this expression is 8.0.

## 1. What will be the output of the following Python expression?[Яким буде результат наступного виразу Python?]

`print(4.00/(2.0+2.0))`

a) Error

**b) 1.0**

c) 1.00

d) 1

Explanation: The result of the expression shown above is 1.0 because print rounds off digits.

## 2. What will be the value of X in the following Python expression?[Яким буде значення X у наступному виразі Python?]

`X = 2+9*((3*12)-8)/10`

a) 30.0

b) 30.8

c) 28.4

**d) 27.2**

Explanation: The expression shown above is evaluated as: 2+9*(36-8)/10, which simplifies to give 2+9*(2.8), which is equal to 2+25.2 = 27.2. Hence the result of this expression is 27.2.
 
## 3. Which of the following expressions involves coercion when evaluated in Python?[Який із наведених нижче виразів включає примус при оцінці в Python?]

a) 4.7 – 1.5

b) 7.9 * 6.3

**c) 1.7 % 2**

d) 3.4 + 4.6

Explanation: Coercion is the implicit (automatic) conversion of operands to a common type. Coercion is automatically performed on mixed-type expressions. The expression 1.7 % 2 is evaluated as 1.7 % 2.0 (that is, automatic conversion of int to float).

## 4. What will be the output of the following Python expression?[Яким буде результат наступного виразу Python?]

`24//6%3, 24//4//2`

**a) (1,3)**

b) (0,3)

c) (1,0)

d) (3,1)

Explanation: The expressions are evaluated as: 4%3 and 6//2 respectively. This results in the answer (1,3). This is because the associativity of both of the expressions shown above is left to right.

## 5. Which among the following list of operators has the highest precedence?[Який із наведених нижче операторів має найвищий пріоритет?]

 `+, -, **, %, /, <<, >>, |`

a) <<, >>

**b) ****

c) |

d) %

Explanation: The highest precedence is that of the exponentiation operator, that is of **.

## 6. What will be the value of the following Python expression?[Яким буде значення наступного виразу Python?]

`float(4+int(2.39)%2)`

a) 5.0

b) 5

**c) 4.0**

d) 4

Explanation: The above expression is an example of explicit conversion. It is evaluated as: float(4+int(2.39)%2) = float(4+2%2) = float(4+0) = 4.0. Hence the result of this expression is 4.0.

## 7. Which of the following expressions is an example of type conversion?[Який із наведених виразів є прикладом перетворення типів?]

**a) 4.0 + float(3)**

b) 5.3 + 6.3

c) 5.0 + 3

d) 3 + 7

Explanation: Type conversion is nothing but explicit conversion of operands to a specific type. Options 5.3 + 6.3 and 5.0 + 3 are examples of implicit conversion whereas option 4.0 + float(3) is an example of explicit conversion or type conversion.

## 8. Which of the following expressions results in an error?[Який із наведених виразів призводить до помилки?]

a) float(‘10’)

b) int(‘10’)

c) float(’10.8’)

**d) int(’10.8’)**

Explanation: All of the above examples show explicit conversion. However the expression int(’10.8’) results in an error.

## 9. What will be the value of the following Python expression?[Яким буде значення наступного виразу Python?]

`4+2**5//10`

a) 3

**b) 7**

c) 77

d) 0

Explanation: The order of precedence is: **, //, +. The expression 4+2**5//10 is evaluated as 4+32//10, which is equal to 4+3 = 7. Hence the result of the expression shown above is 7.

## 10. The expression 2**2**3 is evaluates as: (2**2)**3. [Вираз 2**2**3 обчислюється як: (2**2)**3.]

a) True

**b) False**

Explanation: The value of the expression (2**2)**3 = 4**3 = 64. When the expression 2**2**3 is evaluated in python, we get the result as 256, because this expression is evaluated as 2**(2**3). This is because the associativity of exponentiation operator (**) is from right to left and not from left to right.

## 1. What will be the output of the following Python code snippet if x=1?[Яким буде результат наступного фрагмента коду Python, якщо x=1?]

`x<<2`

a) 8

b) 1

c) 2

**d) 4**

Explanation: The binary form of 1 is 0001. The expression x<<2 implies we are performing bitwise left shift on x. This shift yields the value: 0100, which is the binary form of the number 4.

## 2. What will be the output of the following Python expression?[Яким буде результат наступного виразу Python?]

`bin(29)`

a) ‘0b10111’

**b) ‘0b11101’**

c) ‘0b11111’

d) ‘0b11011’

Explanation: The binary form of the number 29 is 11101. Hence the output of this expression is ‘0b11101’.

## 3. What will be the value of x in the following Python expression, if the result of that expression is 2?[Яким буде значення x у наступному виразі Python, якщо результат цього виразу дорівнює 2?]

`x>>2`

**a) 8**

b) 4

c) 2

d) 1

Explanation: When the value of x is equal to 8 (1000), then x>>2 (bitwise right shift) yields the value 0010, which is equal to 2. Hence the value of x is 8.

## 4. What will be the output of the following Python expression?[Яким буде результат наступного виразу Python?]

`int(1011)?`

**a) 1011**

b) 11

c) 13

d) 1101

Explanation: The result of the expression shown will be 1011. This is because we have not specified the base in this expression. Hence it automatically takes the base as 10.

## 5. To find the decimal value of 1111, that is 15, we can use the function:[Щоб знайти десяткове значення 1111, тобто 15, ми можемо скористатися функцією?]

a) int(1111,10)

b) int(‘1111’,10)

c) int(1111,2)

**d) int(‘1111’,2)**

Explanation: The expression int(‘1111’,2) gives the result 15. The expression int(‘1111’, 10) will give the result 1111.

## 6. What will be the output of the following Python expression if x=15 and y=12?[Яким буде результат наступного виразу Python якщо x=15 та y=12?]

`x & y`

a) b1101

b) 0b1101

**c) 12**

d) 1101

Explanation: The symbol ‘&’ represents bitwise AND. This gives 1 if both the bits are equal to 1, else it gives 0. The binary form of 15 is 1111 and that of 12 is 1100. Hence on performing the bitwise AND operation, we get 1100, which is equal to 12.

## 7. Which of the following expressions results in an error?[Який із наведених виразів призводить до помилки?]

a) int(1011)

b) int(‘1011’,23)

**c) int(1011,2)**

d) int(‘1011’)

Explanation: The expression int(1011,2) results in an error. Had we written this expression as int(‘1011’,2), then there would not be an error.

## 8. Which of the following represents the bitwise XOR operator?[Що з наведеного нижче представляє порозрядний оператор XOR?]

a) &

**b) ^**

c) |

d) !

Explanation: The ^ operator represent bitwise XOR operation. &: bitwise AND, | : bitwise OR and ! represents bitwise NOT.

## 9. What is the value of the following Python expression?[Яке значення має наступний вираз Python?]

`bin(0x8)`

a) ‘0bx1000’

b) 8

c) 1000

**d) ‘0b1000’**

Explanation: The prefix 0x specifies that the value is hexadecimal in nature. When we convert this hexadecimal value to binary form, we get the result as: ‘0b1000’.

## 10. What will be the output of the following Python expression?[Яким буде результат наступного виразу Python?]

`0x35 | 0x75`

a) 115

b) 116

**c) 117**

d) 118

Explanation: The binary value of 0x35 is 110101 and that of 0x75 is 1110101. On OR-ing these two values we get the output as: 1110101, which is equal to 117. Hence the result of the above expression is 117.

## 1. It is not possible for the two’s complement value to be equal to the original value in any case.[Ні в якому разі неможливо, щоб значення доповнення до двох було рівним початковому значенню.]

a) True

**b) False**

Explanation: In most cases the value of two’s complement is different from the original value. However, there are cases in which the two’s complement value may be equal to the original value. For example, the two’s complement of 10000000 is also equal to 10000000. Hence the statement is false.

## 2. The one’s complement of 110010101 is:[Доповнення до 110010101 є]

**a) 001101010**

b) 110010101

c) 001101011

d) 110010100

Explanation: The one’s complement of a value is obtained by simply changing all the 1’s to 0’s and all the 0’s to 1’s. Hence the one’s complement of 110010101 is 001101010.

## 3. Bitwise _________ gives 1 if either of the bits is 1 and 0 when both of the bits are 1.[Побітово _________ дає 1, якщо один з бітів дорівнює 1, і 0, коли обидва біти дорівнюють 1]

a) OR

b) AND

**c) XOR**

d) NOT

Explanation: Bitwise XOR gives 1 if either of the bits is 1 and 0 when both of the bits are 1.

## 4. What will be the output of the following Python expression?[Яким буде результат наступного виразу Python?]

`4^12`

a) 2

b) 4

**c) 8**

d) 12

Explanation: ^ is the XOR operator. The binary form of 4 is 0100 and that of 12 is 1100. Therefore, 0100^1100 is 1000, which is equal to 8.

## 5. Any odd number on being AND-ed with ________ always gives 1. Hint: Any even number on being AND-ed with this value always gives 0.[Будь-яке непарне число під час переміщення І з ________ завжди дає 1. Підказка: будь-яке парне число при переміщенні І з цим значенням завжди дає 0.]

a) 10

b) 2

**c) 1**

d) 0

Explanation: Any odd number on being AND-ed with 1 always gives 1. Any even number on being AND-ed with this value always gives 0.

## 6. What will be the value of the following Python expression?[Яким буде значення наступного виразу Python?]

`bin(10-2)+bin(12^4)`

a) 0b10000

b) 0b10001000

c) 0b1000b1000

**d) 0b10000b1000**

Explanation: The output of bin(10-2) = 0b1000 and that of bin(12^4) is ob1000. Hence the output of the above expression is: 0b10000b1000.

## 7. Which of the following expressions can be used to multiply a given number ‘a’ by 4?[Який із наведених виразів можна використати, щоб помножити дане число «а» на 4?]

**a) a<<2**

b) a<<4

c) a>>2

d) a>>4


Explanation: Let us consider an example wherein a=2. The binary form of 2 is 0010. When we left shift this value by 2, we get 1000, the value of which is 8. Hence if we want to multiply a given number ‘a’ by 4, we can use the expression: a<<2.

## 8. What will be the output of the following Python code if a=10 and b =20?[Яким буде результат наступного коду Python, якщо a=10 і b =20]

`a=10 b=20 a=a^b b=a^b a=a^b print(a,b)`

a) 10 20

b) 10 10

**c) 20 10**

d) 20 20

Explanation: The code shown above is used to swap the contents of two memory locations using bitwise X0R operator. Hence the output of the code shown above is: 20 10.


## 9. What is the two’s complement of -44?[Яке доповнення двох до -44]

a) 1011011

**b) 11010100**

c) 11101011

d) 10110011

Explanation: The binary form of -44 is 00101100. The one’s complement of this value is 11010011. On adding one to this we get: 11010100 (two’s complement).

## 10. What will be the output of the following Python expression?[Яким буде результат наступного виразу Python?]

`~100?`

a) 101

**b) -101**

c) 100

d) -100

Explanation: Suppose we have an expression ~A. This is evaluated as: -A – 1. Therefore, the expression ~100 is evaluated as -100 – 1, which is equal to -101.

# Exception Handling – 1

## 1. How many except statements can a try-except block have? [Скільки визначень винятків є у блоці try-except?]

a) zero

b) one

c) more than one

**d) more than zero**

> Explanation: There has to be at least one except statement.

## 2. When will the else part of try-except-else be executed? [Коли буде виконана частина else в try-except-else?]

a) always

b) when an exception occurs

**c) when no exception occurs**

d) when an exception occurs in to except block

> Explanation: The else part is executed when no exception occurs.

## 3. Is the following Python code valid? [Чи правильний даний код Python?]

```
try:
    # Do something
except:
    # Do something
finally:
    # Do something
```

a) no, there is no such thing as finally

**b) no, finally cannot be used with except**

c) no, finally must come before except

d) yes

>Explanation: Refer documentation.

## 4. Is the following Python code valid? [Чи правильний даний код Python?]

```
try:
    # Do something
except:
    # Do something
else:
    # Do something
```

a) no, there is no such thing as else

b) no, else cannot be used with except

c) no, else must come before except

**d) yes**

> Explanation: Refer documentation.

## 5. Can one block of except statements handle multiple exception? [Чи може один блок визначень винятків обробляти кілька винятків?]

**a) yes, like except TypeError, SyntaxError [,…]**

b) yes, like except [TypeError, SyntaxError]

c) no

d) none of the mentioned

> Explanation: Each type of exception can be specified directly. There is no need to put it in a list.

## 6. When is the finally block executed? [Коли виконується блок finally?]

a) when there is no exception

b) when there is an exception

c) only if some condition that has been specified is satisfied

**d) always**

> Explanation: The finally block is always executed.

## 7. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
def foo():
    try:
        return 1
    finally:
        return 2
k = foo()
print(k)
```

a) 1

**b) 2**

c) 3

d) error, there is more than one return statement in a single try-finally block
> Explanation: The finally block is executed even there is a return statement in the try block.

## 8. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
def foo():
    try:
        print(1)
    finally:
        print(2)
foo()
```

**a) 1 2**
b) 1

c) 2

d) none of the mentioned

> Explanation: No error occurs in the try block so 1 is printed. Then the finally block is executed and 2 is printed.

## 9. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
try:
    if '1' != 1:
        raise "someError"
    else:
        print("someError has not occurred")
except "someError":
    print ("someError has occurred")
```


a) someError has occurred

b) someError has not occurred

**c) invalid code**

d) none of the mentioned

> Explanation: A new exception class must inherit from a BaseException. There is no such inheritance here.

## 10. What happens when ‘1’ == 1 is executed? [Що відбувається, якщо виконається '1' == 1?]

a) we get a True

**b) we get a False**

c) an TypeError occurs

d) a ValueError occurs

> Explanation: It simply evaluates to False and does not raise any exception.

# Exception Handling – 2

## 1. The following Python code will result in an error if the input value is entered as -5. [Наступний код Python призведе до помилки, якщо введене значення буде введено як -5.]

```
assert False, 'Spanish'
```

**a) True**

b) False

> Explanation: The code shown above results in an assertion error. The output of the code is:
Traceback (most recent call last):
File “<pyshell#0>”, line 1, in <module>
assert False, ‘Spanish’
AssertionError: Spanish
Hence, this statement is true.

## 2. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
x=10
y=8
assert x>y, 'X too small'
```

a) Assertion Error

b) 10 8

**c) No output**

d) 108

> Explanation: The code shown above results in an error if and only if x<y. However, in the above case, since x>y, there is no error. Since there is no print statement, hence there is no output.

## 3. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
#generator
def f(x):
    yield x+1
g=f(8)
print(next(g))
```

a) 8

**b) 9**

c) 7

d) Error

> Explanation: The code shown above returns the value of the expression x+1, since we have used to keyword yield. The value of x is 8. Hence the output of the code is 9.

## 4. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
def f(x):
    yield x+1
    print("test")
    yield x+2
g=f(9)
```
a) Error

b) test

c)
```
test
10
12
```

**d) No output**

> Explanation: The code shown above will not yield any output. This is because when we try to yield 9, and there is no next(g), the iteration stops. Hence there is no output.4

## 5. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
def f(x):
    yield x+1
    print("test")
    yield x+2
g=f(10)
print(next(g))
print(next(g))
```

a) No output

**b)**
```
11
test
12
```

c)
```
11
test
```

d) 11

> Explanation: The code shown above results in the output:
11
test
12
This is because we have used next(g) twice. Had we not used next, there would be no output.

## 6. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
def a():
    try:
        f(x, 4)
    finally:
        print('after f')
    print('after f?')
a()
```

a) No output

b) after f?

**c) error**

d) after f

> Explanation: This code shown above will result in an error simply because ‘f’ is not defined. ‘try’ and ‘finally’ are keywords used in exception handling.

## 7. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
def f(x):
    for i in range(5):
        yield i
g=f(8)
print(list(g))
```

**a) [0, 1, 2, 3, 4]**

b) [1, 2, 3, 4, 5, 6, 7, 8]

c) [1, 2, 3, 4, 5]

d) [0, 1, 2, 3, 4, 5, 6, 7]

> Explanation: The output of the code shown above is a list containing whole numbers in the range (5). Hence the output of this code is: [0, 1, 2, 3, 4].

## 8. The error displayed in the following Python code is? [У наступному коді Python яка помилка появиться?]

```
import itertools
l1=(1, 2, 3)
l2=[4, 5, 6]
l=itertools.chain(l1, l2)
print(next(l1))
```

a) ‘list’ object is not iterator

**b) ‘tuple’ object is not iterator**

c) ‘list’ object is iterator

d) ‘tuple’ object is iterator

> Explanation: The error raised in the code shown above is that: ‘tuple’ object is not iterator. Had we given l2 as argument to next, the error would have been: ‘list’ object is not iterator.

## 9. Which of the following is not an exception handling keyword in Python? [Що з переліченого не є ключовим словом для обробки винятків у Python?]

a) try

b) except

**c) accept**

d) finally

> Explanation: The keywords ‘try’, ‘except’ and ‘finally’ are exception handling keywords in python whereas the word ‘accept’ is not a keyword at all.

## 10. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
g = (i for i in range(5))
type(g)
```

a) class <’loop’>

b) class <‘iteration’>

c) class <’range’>

**d) class <’generator’>**

> Explanation: Another way of creating a generator is to use parenthesis. Hence the output of the code shown above is: class<’generator’>.

# Exception Handling – 3

## 1. What happens if the file is not found in the following Python code? [Що станеться, якщо файл не буде знайдено в наступному коді Python?]

```
a=False
while not a:
    try:
        f_n = input("Enter file name")
        i_f = open(f_n, 'r')
    except:
        print("Input file not found")
```

**a) No error**

b) Assertion error

c) Input output error

d) Name error

> Explanation: In the code shown above, if the input file in not found, then the statement: “Input file not found” is printed on the screen. The user is then prompted to reenter the file name. Error is not thrown.

## 2. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
lst = [1, 2, 3]
lst[3]
```

a) NameError

b) ValueError

**c) IndexError**

d) TypeError

> Explanation: The snippet of code shown above throws an index error. This is because the index of the list given in the code, that is, 3 is out of range. The maximum index of this list is 2.

## 3. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
t[5]
```

a) IndexError

**b) NameError**

c) TypeError

d) ValeError

> Explanation: The expression shown above results in a name error. This is because the name ‘t’ is not defined.

## 4. What will be the output of the following Python code, if the time module has already been imported? [Яким буде результат даного коду Python, якщо модуль часу вже імпортовано??]

```
4 + '3'
```

a) NameError

b) IndexError

c) ValueError

**d) TypeError**

> Explanation: The line of code shown above will result in a type error. This is because the operand ‘+’ is not supported when we combine the data types ‘int’ and ‘str’. Sine this is exactly what we have done in the code shown above, a type error is thrown.

## 5. What will be the output of the following Python code? [Яким буде результат даного коду Python?]
```
int('65.43')
```

a) ImportError

**b) ValueError**

c) TypeError

d) NameError

> Explanation: The snippet of code shown above results in a value error. This is because there is an invalid literal for int() with base 10: ’65.43’.

## 6. Compare the following two Python codes shown below and state the output if the input entered in each case is -6? [Порівняйте два наступні коди Python, показані нижче, і вкажіть результат, якщо введене значення в кожному випадку дорівнює -6?]

```
CODE 1
import math
num=int(input("Enter a number of whose factorial you want to find"))
print(math.factorial(num))
 
CODE 2
num=int(input("Enter a number of whose factorial you want to find"))
print(math.factorial(num))
```

**a) ValueError, NameError**

b) AttributeError, ValueError

c) NameError, TypeError

d) TypeError, ValueError

> Explanation: The first code results in a ValueError. This is because when we enter the input as -6, we are trying to find the factorial of a negative number, which is not possible. The second code results in a NameError. This is because we have not imported the math module. Hence the name ‘math’ is undefined.

## 7. What will be the output of the following Python code? [Яким буде результат даного коду Python?]

```
def getMonth(m):
    if m<1 or m>12:
        raise ValueError("Invalid")
    print(m)
getMonth(6)
```
a) ValueError

b) Invalid

**c) 6**

d) ValueError(“Invalid”)

> Explanation: In the code shown above, since the value passed as an argument to the function is between 1 and 12 (both included), hence the output is the value itself, that is 6. If the value had been above 12 and less than 1, a ValueError would have been thrown.

## 8. What will be the output of the following Python code if the input entered is 6? [Яким буде результат даного коду Python, якщо вхідне значення буде 6?]

```
valid = False
while not valid:
    try:
        n=int(input("Enter a number"))
        while n%2==0:
            print("Bye")
        valid = True
    except ValueError:
        print("Invalid")
```
a) Bye (printed once)

b) No output

c) Invalid (printed once)

**d) Bye (printed infinite number of times)**

> Explanation: The code shown above results in the word “Bye” being printed infinite number of times. This is because an even number has been given as input. If an odd number had been given as input, then there would have been no output.

## 9. Identify the type of error in the following Python codes? [Визначте тип помилки в наступних кодах Python?]

```
Print(“Good Morning”)
print(“Good night)
```

a) Syntax, Syntax

**b) Semantic, Syntax**

c) Semantic, Semantic

d) Syntax, Semantic

> Explanation: The first code shows an error detected during execution. This might occur occasionally. The second line of code represents a syntax error. When there is deviation from the rules of a language, a syntax error is thrown.

## 10. Which of the following statements is true? [Яке з наведених тверджень вірне?]

**a) The standard exceptions are automatically imported into Python programs**

b) All raised standard exceptions must be handled in Python

c) When there is a deviation from the rules of a programming language, a semantic error is thrown

d) If any exception is thrown in try block, else block is executed

> Explanation: When any exception is thrown in try block, except block is executed. If exception in not thrown in try block, else block is executed. When there is a deviation from the rules of a programming language, a syntax error is thrown. The only true statement above is: The standard exceptions are automatically imported into Python programs.

## 11. Which of the following is not a standard exception in Python? [Що з наведеного нижче не є стандартним винятком у Python?]

a) NameError

b) IOError

**c) AssignmentError**

d) ValueError

> Explanation: NameError, IOError and ValueError are standard exceptions in Python whereas Assignment error is not a standard exception in Python.

## 12. Syntax errors are also known as parsing errors. [Синтаксичні помилки також відомі як помилки аналізу.]

**a) True**

b) False

> Explanation: Syntax errors are known as parsing errors. Syntax errors are raised when there is a deviation from the rules of a language. Hence the statement is true.

## 13. An exception is ____________ [Виняток становить ___________]

**a) an object**

b) a special function

c) a standard module

d) a module

> Explanation: An exception is an object that is raised by a function signaling that an unexpected situation has occurred, that the function itself cannot handle.

## 14. _______________________ exceptions are raised as a result of an error in opening a particular file. [_______________________ винятки виникають у результаті помилки під час відкриття певного файлу.]

a) ValueError

b) TypeError

c) ImportError

**d) IOError**

> Explanation: IOError exceptions are raised as a result of an error in opening or closing a particular file.

## 15. Which of the following blocks will be executed whether an exception is thrown or not? [Який із наведених нижче блоків буде виконано, незалежно від того, виникне виняток чи ні?]

a) except

b) else

**c) finally**

d) assert

> Explanation: The statements in the finally block will always be executed, whether an exception is thrown or not. This clause is used to close the resources used in a code.


# Section 4

# Section 5

# Section 6

# Section 7

## 1. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
class father:
    def __init__(self, param):
        self.o1 = param
 
class child(father):
    def __init__(self, param):
        self.o2 = param
 
>>>obj = child(22)
>>>print "%d %d" % (obj.o1, obj.o2)
```
a) None None

b) None 22

c) 22 None

**d) Error is generated**
>Explanation: self.o1 was never created.

## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
class tester:
    def __init__(self, id):
        self.id = str(id)
        id="224"
 
>>>temp = tester(12)
>>>print(temp.id)
```
a) 224

b) Error

**c) 12**

d) None
>Explanation: Id in this case will be the attribute of the class.

## 3. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]
```
>>>example = "snow world"
>>>print("%s" % example[4:7])
```
**a) wo**

b) world

c) sn

d) rl
>Explanation: Execute in the shell and verify.
## 4. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]
```
>>>example = "snow world"
>>>example[3] = 's'
>>>print example
```
a) snow

b) snow world

**c) Error**

d) snos world
>Explanation: Strings cannot be modified.

## 5. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]
```
>>>max("what are you")
```
a) error

b) u

c) t

**d) y**
>Explanation: Max returns the character with the highest ascii value.

## 6. Given a string example=”hello” what is the output of example.count(‘l’)? [За допомогою рядка example=”hello” що виводить example.count(‘l’)?]
**a) 2**

b) 1

c) None

d) 0
>Explanation: l occurs twice in hello.

## 7. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]
```
>>>example = "helle"
>>>example.find("e")
```
a) Error

b) -1

**c) 1**

d) 0
> >Explanation: Returns lowest index.

##  8. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]
```
>>>example = "helle"
>>>example.rfind("e")
```
a) -1

**b) 4**

c) 3

d) 1
>Explanation: Returns highest index.

## 9. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]
```
>>>example="helloworld"
>>>example[::-1].startswith("d")
```
a) dlrowolleh

**b) True**

c) -1

d) None
>Explanation: Starts with checks if the given string starts with the parameter that is passed.

## 10. To concatenate two strings to a third what statements are applicable? [Які твердження застосовні для з’єднання двох рядків з третім?]
a) s3 = s1 . s2

b) s3 = s1.add(s2)

**c) s3 = s1.\_\_add\_\_(s2)**

d) s3 = s1 * s2
>Explanation: __add__ is another method that can be used for concatenation.

## 1. What will be the output of the following Python statement?[Яким буде результат наступного оператора Python?]
```
>>>chr(ord('A'))
```
**a) A**

b) B

c) a

d) Error
>Explanation: Execute in shell to verify.

## 2. What will be the output of the following Python statement?[Яким буде результат наступного оператора Python?]
```
>>>print(chr(ord('b')+1))
```
a) a

b) b

**c) c**

d) A
>Explanation: Execute in the shell to verify.

## 3. Which of the following statement prints hello\example\test.txt? [Який із наведених нижче операторів друкує hello\example\test.txt?]
a) print(“hello\example\test.txt”)

**b) print(“hello\\\\example\\\\test.txt”)**

c) print(“hello\”example\”test.txt”)

d) print(“hello”\example”\test.txt”)
>Explanation: \is used to indicate that the next \ is not an escape sequence.

## 4. Suppose s is “\t\tWorld\n”, what is s.strip()? [Припустимо, s – це “\t\tWorld\n”, а що таке s.strip()?]

a) \t\tWorld\n

b) \t\tWorld\n

c) \t\tWORLD\n

**d) World**
>Explanation: Execute help(string.strip) to find details.

## 5. The format function, when applied on a string returns [Функція форматування при застосуванні до рядка повертає] ___________
a) Error

b) int

c) bool

**d) str**
>Explanation: Format function returns a string.

## 6. What will be the output of the “hello” +1+2+3?[Яким буде результат “hello” +1+2+3?]
a) hello123

b) hello

**c) Error**

d) hello6
>Explanation: Cannot concatenate str and int objects.

## 7. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
>>>print("D", end = ' ')
>>>print("C", end = ' ')
>>>print("B", end = ' ')
>>>print("A", end = ' ')
```
a) DCBA

b) A, B, C, D

**c) D C B A**

d) D, C, B, A will be displayed on four lines

>Explanation: Execute in the shell.

## 8. What will be the output of the following Python statement?(python 3.xx) [Яким буде результат наступного оператора Python?(python 3.xx)]
```
>>>print(format("Welcome", "10s"), end = '#')
>>>print(format(111, "4d"), end = '#')
>>>print(format(924.656, "3.2f"))
```
a)    Welcome# 111#924.66

b) Welcome#111#924.66

c) Welcome#111#.66

**d) Welcome   # 111#924.66**

>Explanation: Execute in the shell to verify.

## 9. What will be displayed by print(ord(‘b’) – ord(‘a’))? [Що буде відображатися print(ord(‘b’) – ord(‘a’))?]
a) 0

**b) 1**

c) -1

d) 2
>Explanation: ASCII value of b is one more than a. Hence the output of this code is 98-97, which is equal to 1.

## 10. Say s=”hello” what will be the return value of type(s)? [10. Нехай s=”hello”, яке буде значення типу(ів)?]

a) int

b) bool

**c) str**

d) String

>Explanation: str is used to represent strings in python.


## 1. What is “Hello”.replace(“l”, “e”)[Що таке “Hello”.replace(“l”, “e”)]?

**a) Heeeo**

b) Heelo

c) Heleo

d) None

>Explanation: Execute in shell to verify.

## 2. To retrieve the character at index 3 from string s=”Hello” what command do we execute (multiplellowed)[Щоб отримати символ з індексом 3 з рядка s=”Hello”, яку команду ми виконуємо (допускається декілька)]?
a) s[]

b) s.getitem(3)

**c) s.\_\_getitem\_\_(3)**

d) s.getItem(3)

>Explanation: __getitem(..) can be used to get character at index specified as parameter.
## 3. To return the length of string s what command do we execute[Щоб повернути довжину рядка s, яку команду ми виконуємо]?

**a) s.\_\_len\_\_()**

b) len(s)

c) size(s)

d) s.size()

>Explanation: Execute in shell to verify.

## 4. If a class defines the __str__(self) method, for an object obj for the class, you can use which command to invoke the \_\_str\_\_ method.[Якщо клас визначає метод __str__(self), для об’єкта obj для класу можна використовувати команду, щоб викликати метод \_\_str\_\_]
a) obj.\_\_str\_\_()

b) str(obj)

c) print obj

**d) all of the mentioned**

>Explanation: Execute in shell to verify.
## 5. To check whether string s1 contains another string s2, use [Щоб перевірити, чи містить рядок s1 інший рядок s2, використовуйте]________
**a) s1.\_\_contains\_\_(s2)**

b) s2 in s1

c) s1.contains(s2)

d) si.in(s2)

>Explanation: s2 in s1 works in the same way as calling the special function \_\_contains\_\_ .

## 6. Suppose i is 5 and j is 4, i + j is same as [Припустимо, i дорівнює 5, а j дорівнює 4, i + j те саме, що] ________
a) i.\_\_add(j)

**b) i.\_\_add__(j)**

c) i.\_\_Add(j)

d) i.\_\_ADD(j)

>Explanation: Execute in shell to verify.
## 7. What will be the output of the following Python code?[Яким буде результат наступного коду Python]
```
class Count:
    def __init__(self, count = 0):
       self.__count = count
 
c1 = Count(2)
c2 = Count(2)
print(id(c1) == id(c2), end = " ")
 
s1 = "Good"
s2 = "Good"
print(id(s1) == id(s2))
```
a) True False

b) True True

**c) False True**

d) False False

>Explanation: Execute in the shell objects cannot have same id, however in the case of strings its different.

## 8. What will be the output of the following Python code?[Яким буде результат наступного коду Python]
```
class Name:
    def __init__(self, firstName, mi, lastName):
        self.firstName = firstName
        self.mi = mi
        self.lastName = lastName
 
firstName = "John"
name = Name(firstName, 'F', "Smith")
firstName = "Peter"
name.lastName = "Pan"
print(name.firstName, name.lastName)
```
a) Peter Pan

**b) John Pan**

c) Peter Smith

d) John Smith

>Explanation: Execute in the shell to verify.
## 9. What function do you use to read a string?[Яку функцію ви використовуєте для читання рядка?]
**a) input(“Enter a string”)**

b) eval(input(“Enter a string”))

c) enter(“Enter a string”)

d) eval(enter(“Enter a string”))

>Explanation: Execute in shell to verify.
## 10. Suppose x is 345.3546, what is format(x, “10.3f”) (_ indicates space).[Припустимо, x дорівнює 345,3546, що таке format(x, “10.3f”) (_ означає пробіл)]
a) \_\_345.355

**b) \_\_\_345.355**   

c) \_\_\_\_345.355

d) \_\_\_\_\_345.354

>Explanation: Execute in the shell to verify.

## 1. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]
```
print("abc DEF".capitalize())
```
a) abc def

b) ABC DEF

**c) Abc def**

d) Abc Def

>Explanation: The first letter of the string is converted to uppercase and the others are converted to lowercase.
advertisement

## 2. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]
```
print("abc. DEF".capitalize())
```
a) abc. def

b) ABC. DEF

**c) Abc. def**

d) Abc. Def

>Explanation: The first letter of the string is converted to uppercase and the others are converted to lowercase.
## 3. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]
```
print("abcdef".center())
```
a) cd

b) abcdef

**c) error**

d) none of the mentioned

>Explanation: The function center() takes at least one parameter.
## 4. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]
```
print("abcdef".center(0))
```
a) cd

**b) abcdef**

c) error

d) none of the mentioned

>Explanation: The entire string is printed when the argument passed to center() is less than the length of the string.
## 5. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]
```
print('*', "abcdef".center(7), '*')
```
a) * abcdef *

**b) * abcdef \***

c) *abcdef *

d) * abcdef*

>Explanation: Padding is done towards the left-hand-side first when the final string is of odd length. Extra spaces are present since we haven’t overridden the value of sep.
## 6. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]
```
print('*', "abcdef".center(7), '*', sep='')
```
a) * abcdef *

b) * abcdef *

c) *abcdef *

**d) * abcdef\***

>Explanation: Padding is done towards the left-hand-side first when the final string is of odd length.
## 7. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]
```
print('*', "abcde".center(6), '*', sep='')
```
a) * abcde *

b) * abcde *

**c) *abcde \***

d) * abcde*

>Explanation: Padding is done towards the right-hand-side first when the final string is of even length.
## 8. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]
```
print("abcdef".center(7, 1))
```
a) 1abcdef

b) abcdef1

c) abcdef

**d) error**

>Explanation: TypeError, the fill character must be a character, not an int.
## 9. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]
```
print("abcdef".center(7, '1'))
```
**a) 1abcdef**

b) abcdef1

c) abcdef

d) error

>Explanation: The character ‘1’ is used for padding instead of a space.
## 10. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]
```
print("abcdef".center(10, '12'))
```
a) 12abcdef12

b) abcdef1212

c) 1212abcdef

**d) error**

>Explanation: The fill character must be exactly one character long.

# Section 8

## 1. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("xyyzxyzxzxyy".count('yy'))
```
**a) 2**

b) 0

c) error

d) none of the mentioned

>Explanation: Counts the number of times the substring ‘yy’ is present in the given string.
## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("xyyzxyzxzxyy".count('yy', 1))
```
**a) 2**

b) 0

c) 1

d) none of the mentioned

>Explanation: Counts the number of times the substring ‘yy’ is present in the given string, starting from position 1.
## 3. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("xyyzxyzxzxyy".count('yy', 2))
```
a) 2

b) 0

**c) 1**

d) none of the mentioned

>Explanation: Counts the number of times the substring ‘yy’ is present in the given string, starting from position 2.
## 4. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("xyyzxyzxzxyy".count('xyy', 0, 100))
```
**a) 2**

b) 0

c) 1

d) error

>Explanation: An error will not occur if the end value is greater than the length of the string itself.
## 5. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("xyyzxyzxzxyy".count('xyy', 2, 11))
```
a) 2

**b) 0**

c) error

d) none of the mentioned

>Explanation: Counts the number of times the substring ‘xyy’ is present in the given string, starting from position 2 and ending at position 11.
## 6. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("xyyzxyzxzxyy".count('xyy', -10, -1))
```
a) 2

**b) 0**

c) error

d) none of the mentioned

>Explanation: Counts the number of times the substring ‘xyy’ is present in the given string, starting from position 2 and ending at position 11.
## 7. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print('abc'.encode())
```
a) abc

b) ‘abc’

**c) b’abc’**

d) h’abc’

>Explanation: A bytes object is returned by encode.
## 8. What is the default value of encoding in encode()? [Яке значення кодування за замовчуванням у encode()?]
a) ascii

b) qwerty

**c) utf-8**

d) utf-16

>Explanation: The default value of encoding is utf-8.
## 9. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("xyyzxyzxzxyy".endswith("xyy"))
```
a) 1

**b) True**

c) 3

d) 2

>Explanation: The function returns True if the given string ends with the specified substring.
## 10. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("xyyzxyzxzxyy".endswith("xyy", 0, 2))
```
a) 0

b) 1

c) True

**d) False**

>Explanation: The function returns False if the given string does not end with the specified substring.
## 1. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("ab\tcd\tef".expandtabs())
```
**a) ab  cd  ef**

b) abcdef

c) ab\tcd\tef

d) ab cd ef

>Explanation: Each \t is converted to 8 blank spaces by default.
## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("ab\tcd\tef".expandtabs(4))
```
a) ab   cd   ef

b) abcdef

c) ab\tcd\tef

**d) ab cd ef**

>Explanation: Each \t is converted to 4 blank spaces.
## 3. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("ab\tcd\tef".expandtabs('+'))
```
a) ab+cd+ef

b) ab++++++++cd++++++++ef

c) ab cd ef

**d) none of the mentioned**

>Explanation: TypeError, an integer should be passed as an argument.
## 4. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("abcdef".find("cd") == "cd" in "abcdef")
```
a) True

**b) False**

c) Error

d) None of the mentioned

>Explanation: The function find() returns the position of the sunstring in the given string whereas the in keyword returns a value of Boolean type.
## 5. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("abcdef".find("cd"))
```
a) True

**b) 2**

c) 3

d) None of the mentioned

>Explanation: The first position in the given string at which the substring can be found is returned.
## 6. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("ccdcddcd".find("c"))
```
a) 4

**b) 0**

c) Error

d) True

>Explanation: The first position in the given string at which the substring can be found is returned.
## 7. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("Hello {0} and {1}".format('foo', 'bin'))
```
**a) Hello foo and bin**

b) Hello {0} and {1} foo bin

c) Error

d) Hello 0 and 1

>Explanation: The numbers 0 and 1 represent the position at which the strings are present.
## 8. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("Hello {1} and {0}".format('bin', 'foo'))
```
**a) Hello foo and bin**

b) Hello bin and foo

c) Error

d) None of the mentioned

>Explanation: The numbers 0 and 1 represent the position at which the strings are present.
## 9. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("Hello {} and {}".format('foo', 'bin'))
```
**a) Hello foo and bin**

b) Hello {} and {}

c) Error

d) Hello and

>Explanation: It is the same as Hello {0} and {1}.
## 10. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("Hello {name1} and {name2}".format('foo', 'bin'))
```
a) Hello foo and bin

b) Hello {} and {}

**c) Error**

d) Hello and

>Explanation: The arguments passed to the function format aren’t keyword arguments.
## 1. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("Hello {name1} and {name2}".format(name1='foo', name2='bin'))
```
**a) Hello foo and bin**

b) Hello {name1} and {name2}

c) Error

d) Hello and

>Explanation: The arguments are accessed by their names.
## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("Hello {0!r} and {0!s}".format('foo', 'bin'))
```
a) Hello foo and foo

**b) Hello ‘foo’ and foo**

c) Hello foo and ‘bin’

d) Error

>Explanation: !r causes the characters ‘ or ” to be printed as well.
## 3. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("Hello {0} and {1}".format(('foo', 'bin')))
```
a) Hello foo and bin

b) Hello (‘foo’, ‘bin’) and (‘foo’, ‘bin’)

**c) Error**

d) None of the mentioned

>Explanation: IndexError, the tuple index is out of range.
## 4. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print("Hello {0[0]} and {0[1]}".format(('foo', 'bin')))
```
**a) Hello foo and bin**

b) Hello (‘foo’, ‘bin’) and (‘foo’, ‘bin’)

c) Error

d) None of the mentioned

>Explanation: The elements of the tuple are accessed by their indices.
## 5. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('The sum of {0} and {1} is {2}'.format(2, 10, 12))
```
**a) The sum of 2 and 10 is 12**

b) Error

c) The sum of 0 and 1 is 2

d) None of the mentioned

>Explanation: The arguments passed to the function format can be integers also.
## 6. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('The sum of {0:b} and {1:x} is {2:o}'.format(2, 10, 12))
```
a) The sum of 2 and 10 is 12

**b) The sum of 10 and a is 14**

c) The sum of 10 and a is c

d) Error

>Explanation: 2 is converted to binary, 10 to hexadecimal and 12 to octal.
## 7. . What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('{:,}'.format(1112223334))
```
a) 1,112,223,334

b) 111,222,333,4

c) 1112223334

d) Error

>Explanation: A comma is added after every third digit from the right.
## 8. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('{:,}'.format('1112223334'))
```
a) 1,112,223,334

b) 111,222,333,4

c) 1112223334

**d) Error**

>Explanation: An integer is expected.
## 9. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('{:$}'.format(1112223334))
```
a) 1,112,223,334

b) 111,222,333,4

c) 1112223334

**d) Error**

>Explanation: $ is an invalid format code.
## 10. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('{:#}'.format(1112223334))
```
a) 1,112,223,334

b) 111,222,333,4

**c) 1112223334**

d) Error

>Explanation: The number is printed as it is.
## 1. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print('{0:.2}'.format(1/3))
```
a) 0.333333

.**b) 0.33**

c) 0.333333:.2

d) Error

>Explanation: .2 specifies the precision.
## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print('{0:.2%}'.format(1/3))
```
a) 0.33
b) 0.33%
**c) 33.33%**
d) 33%

>Explanation: The symbol % is used to represent the result of an expression as a percentage.
## 3. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print('ab12'.isalnum())
```
**a) True**
b) False
c) None
d) Error

>Explanation: The string has only letters and digits.
## 4. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print('ab,12'.isalnum()
```
a) True
**b) False**
c) None
d) Error

>Explanation: The character , is not a letter or a digit.
## 5. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print('ab'.isalpha())
```
**a) True**

b) False

c) None

d) Error

>Explanation: The string has only letters.
## 6. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]
```
print('a B'.isalpha())
```
a) True

**b) False**

c) None

d) Error

>Explanation: Space is not a letter.
## 7. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('0xa'.isdigit())
```
a) True

**b) False**

c) None

d) Error

>Explanation: Hexadecimal digits aren’t considered as digits (a-f).
## 8. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print(''.isdigit())
```
a) True

**b) False**

c) None

d) Error

>Explanation: If there are no characters then False is returned.
## 9. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('my_string'.isidentifier())
```
**a) True**

b) False

c) None

d) Error

>Explanation: It is a valid identifier.
## 10. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('__foo__'.isidentifier())
```
**a) True**

b) False

c) None

d) Error

>Explanation: It is a valid identifier.


# Section 9

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('for'.isidentifier())`

**a) True**\
b) False \
c) None \
d) Error

>Explanation: Even keywords are considered as valid identifiers.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abc'.islower())`

**a) True**\
b) False\
c) None\
d) Error

>Explanation: There are no uppercase letters.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('a@ 1,'.islower())`

**a) True**\
b) False\
c) None\
d) Error

>Explanation: There are no uppercase letters.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('11'.isnumeric())`

**a) True**\
b) False\
c) None\
d) Error

>Explanation: All the character are numeric.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('1.1'.isnumeric())`

a) True\
**b) False**\
c) None\
d) Error

>Explanation: The character . is not a numeric character.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('1@ a'.isprintable())`

**a) True**\
b) False\
c) None\
d) Error

>Explanation: All those characters are printable.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print(''''''.isspace())`

a) True\
**b) False**\
c) None\
d) Error

>Explanation: None.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('\t'.isspace())`

**a) True**\
b) False\
c) None\
d) Error

>Explanation: Tab Spaces are considered as spaces.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('HelloWorld'.istitle())`

a) True\
**b) False**\
c) None\
d) Error

>Explanation: The letter W is uppercased.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('Hello World'.istitle())`

**a) True**\
b) False\
c) None\
d) Error

>Explanation: It is in title form.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('Hello!2@#World'.istitle())`

**a) True**\
b) False\
c) None\
d) Error

>Explanation: It is in the form of a title.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('1Rn@'.lower())`

a) n\
**b) 1rn@**\
c) rn\
d) r

>Explanation: Uppercase letters are converted to lowercase. The other characters are left unchanged.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
```
print('''
 \tfoo'''.lstrip())
```

a) \tfoo\
**b) foo**\
c)   foo\
d) none of the mentioned

>Explanation: All leading whitespace is removed.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('xyyzxxyxyy'.lstrip('xyy'))`

a) error\
**b) zxxyxyy**\
c) z\
d) zxxy

>Explanation: The leading characters containing xyy are removed.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('xyxxyyzxxy'.lstrip('xyy'))`

**a) zxxy**\
b) xyxxyyzxxy\
c) xyxzxxy\
d) none of the mentioned

>Explanation: All combinations of the characters passed as an argument are removed from the left hand side.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('cba'.maketrans('abc', '123'))`

**a) {97: 49, 98: 50, 99: 51}**\
b) {65: 49, 66: 50, 67: 51}\
c) 321\
d) 123

>Explanation: A translation table is returned by maketrans.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('a'.maketrans('ABC', '123'))`

a) {97: 49, 98: 50, 99: 51}\
**b) {65: 49, 66: 50, 67: 51}**\
c) {97: 49}\
d) 1

>Explanation: maketrans() is a static method so it's behaviour does not depend on the object from which it is being called.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcdef'.partition('cd'))`

a) ('ab', 'ef')\
b) ('abef')\
**c) ('ab', 'cd', 'ef')**\
d) 1

>Explanation: The string is split into three parts by partition.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcdefcdgh'.partition('cd'))`

a) ('ab', 'cd', 'ef', 'cd', 'gh')\
**b) ('ab', 'cd', 'efcdgh')**\
c) ('abcdef', 'cd', 'gh')\
d) error

>Explanation: The string is partitioned at the point where the separator first appears.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcd'.partition('cd'))`

**a) ('ab', 'cd', ”)**\
b) ('ab', 'cd')\
c) error\
d) none of the mentioned

>Explanation: The last item is a null string.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('cd'.partition('cd'))`

a) ('cd')\
b) (”)\
c) ('cd', ”, ”)\
**d) (”, 'cd', ”)**

>Explanation: The entire string has been passed as the separator hence the first and the last item of the tuple returned are null strings.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abef'.partition('cd'))`

a) ('abef')\
b) ('abef', 'cd', ”)\
**c) ('abef', ”, ”)**\
d) error

>Explanation: The separator is not present in the string hence the second and the third elements of the tuple are null strings.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcdef12'.replace('cd', '12'))`

**a) ab12ef12**\
b) abcdef12\
c) ab12efcd\
d) none of the mentioned

>Explanation: All occurrences of the first substring are replaced by the second substring.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abef'.replace('cd', '12'))`

**a) abef**\
b) 12\
c) error\
d) none of the mentioned

>Explanation: The first substring is not present in the given string and hence nothing is replaced.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcefd'.replace('cd', '12'))`

a) ab1ef2\
**b) abcefd**\
c) ab1efd\
d) ab12ed2

>Explanation: The first substring is not present in the given string and hence nothing is replaced.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('xyyxyyxyxyxxy'.replace('xy', '12', 0))`

**a) xyyxyyxyxyxxy**\
b) 12y12y1212x12\
c) 12yxyyxyxyxxy\
d) xyyxyyxyxyx12

>Explanation: The first 0 occurrences of the given substring are replaced.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('xyyxyyxyxyxxy'.replace('xy', '12', 100))`

a) xyyxyyxyxyxxy\
**b) 12y12y1212x12**\
c) none of the mentioned
d) error

>Explanation: The first 100 occurrences of the given substring are replaced.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcdefcdghcd'.split('cd'))`

a) ['ab', 'ef', 'gh']\
**b) ['ab', 'ef', 'gh', ”]**\
c) ('ab', 'ef', 'gh')\
d) ('ab', 'ef', 'gh', ”)

>Explanation: The given string is split and a list of substrings is returned.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcdefcdghcd'.split('cd', 0))`

**a) ['abcdefcdghcd']**\
b) 'abcdefcdghcd'\
c) error\
d) none of the mentioned

>Explanation: The given string is split at 0 occurances of the specified substring.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcdefcdghcd'.split('cd', -1))`

a) ['ab', 'ef', 'gh']\
**b) ['ab', 'ef', 'gh', ”]**\
c) ('ab', 'ef', 'gh')\
d) ('ab', 'ef', 'gh', ”)

>Explanation: Calling the function with a negative value for maxsplit is the same as calling it without any maxsplit specified. The string will be split into as many substring s as possible.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcdefcdghcd'.split('cd', 2))`

**a) ['ab', 'ef', 'ghcd']**\
b) ['ab', 'efcdghcd']\
c) ['abcdef', 'ghcd']\
d) none of the mentioned

>Explanation: The string is split into a maximum of maxsplit+1 substrings.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('ab\ncd\nef'.splitlines())`

**a) ['ab', 'cd', 'ef']**\
b) ['ab\n', 'cd\n', 'ef\n']\
c) ['ab\n', 'cd\n', 'ef']\
d) ['ab', 'cd', 'ef\n']

>Explanation: It is similar to calling split('\n').

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('Ab!2'.swapcase())`

a) AB!@\
b) ab12\
**c) aB!2**\
d) aB1@

>Explanation: Lowercase letters are converted to uppercase and vice-versa.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('ab cd ef'.title())`

a) Ab cd ef\
b) Ab cd eF\
**c) Ab Cd Ef**\
d) None of the mentioned

>Explanation: The first letter of every word is capitalized.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('ab cd-ef'.title())`

a) Ab cd-ef\
b) Ab Cd-ef\
**c) Ab Cd-Ef**\
d) None of the mentioned

>Explanation: The first letter of every word is capitalized. Special symbols terminate a word.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcd'.translate('a'.maketrans('abc', 'bcd')))`

a) bcde\
b) abcd\
c) error\
**d) bcdd**

>Explanation: The output is bcdd since no translation is provided for d.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcd'.translate({97: 98, 98: 99, 99: 100}))`

a) bcde\
b) abcd\
c) error\
**d) none of the mentioned**

>Explanation: The output is bcdd since no translation is provided for d.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('abcd'.translate({'a': '1', 'b': '2', 'c': '3', 'd': '4'}))`

**a) abcd**\
b) 1234\
c) error\
d) none of the mentioned

>Explanation: The function translate expects a dictionary of integers. Use maketrans() instead of doing the above.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('ab'.zfill(5))`

**a) 000ab**\
b) 00ab0\
c) 0ab00\
d) ab000

>Explanation: The string is padded with zeros on the left hand side. It is useful for formatting numbers.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]
`print('+99'.zfill(5))`

a) 00+99\
b) 00099\
**c) +0099**\
d) +++99

>Explanation: zeros are filled in between the first sign and the rest of the string.

# Section 10

# Section 11

# Section 12

# Section 13

# Section 14

# Section 15

# Section 16

# Section 17

# Section 18

# Section 19

# Section 20

# Section 21

# Section 22
 
### Which of the following functions can help us to find the version of python that we are currently working on? [Яка з функцій допоможе знайте версія Python, яку ми зараз використовуємо?]
**a) sys.version**\
b) sys.version()\
c) sys.version(0)\
d) sys.version(1)
>Explanation: The function sys.version can help us to find the version of python that we are currently working on. For example, 3.5.2, 2.7.3 etc. this function also returns the current date, time, bits etc along with the version.

### Which of the following functions is not defined under the sys module? [Яка з функцій не визначена в модулі sys?]
a) sys.platform\
b) sys.path\
**c) sys.readline**\
d) sys.argv
>Explanation: The functions sys.platform, sys.path and sys.argv are defined under the sys module. The function sys.readline is not defined. However, sys.stdin.readline is defined.

### The output of the functions len(“abc”) and sys.getsizeof(“abc”) will be the same. [Вивід функцій len(“abc”) і sys.getsizeof(“abc”) буде однаковий.]
a) True\
**b) False**
>Explanation: The function len returns the length of the string passed, and hence it’s output will be 3. The function getsizeof, present under the sys module returns the size of the object passed. It’s output will be a value much larger than 3. Hence the above statement is false.
 
### What will be the output of the following Python code, if the code is run on Windows operating system? [Який буде вивід, якщо код запустити на ОС Windows?]
```python
import sys
if sys.platform[:2]== 'wi':
	 print("Hello")
```
 
a) Error\
**b) Hello**\
c) No output\
d) Junk value
>Explanation: The output of the function sys.platform[:2] is equal to ‘wi’, when this code is run on windows operating system. Hence the output printed is ‘hello’.
 
### What will be the output of the following Python code, if the sys module has already been imported? [Який буде вивід, якщо модуль sys вже заімпортований?]
`sys.stdout.write("hello world")`
 
a) helloworld\
b) hello world10\
**c) hello world11**\
d) error
>Explanation: The function shown above prints the given string along with the length of the string. Hence the output of the function shown above will be hello world11. (In PyChram output = "hello world", in terminal = "hello world11", think about it :))
 
## What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import sys
sys.stdin.readline()
Sanfoundry
```
 
**a) ‘Sanfoundry\n’**\
b) ‘Sanfoundry’\
c) ‘Sanfoundry10’\
d) Error
>Explanation: The function shown above works just like raw_input. Hence it automatically adds a ‘\n’ character to the input string. Therefore, the output of the function shown above will be: Sanfoundry\n.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import sys
eval(sys.stdin.readline())
"India"
```
 
a) India5\
b) India\
c) ‘India\n’\
**d) ‘India’**
>Explanation: The function shown above evaluates the input into a string. Hence if the input entered is enclosed in double quotes, the output will be enclosed in single quotes. Therefore, the output of this code is ‘India’.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import sys
eval(sys.stdin.readline())
Computer
```
 
**a) Error**\
b) ‘Computer\n’\
c) Computer8\
d) Computer
>Explanation: The code shown above will result in an error. This is because this particular function accepts only strings enclosed in single or double inverted quotes, or numbers. Since the string entered above is not enclosed in single or double inverted quotes, an error will be thrown.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]

```python
import sys
sys.argv[0]
```

a) Junk value\
**b) ‘ ‘**\
c) No output\
d) Error
>Explanation: The output of the function shown above will be a blank space enclosed in single quotes. Hence the output of the code shown above is ‘ ‘.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import sys
sys.stderr.write(“hello”)
```

a) ‘hello’\
b) ‘hello\n’\
c) hello\
**d) hello5**
>Explanation: The code shown above returns the string, followed by the length of the string. Hence the output of the code shown above is hello5.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import sys
sys.argv
```
 
a) ‘ ‘\
b) [ ]\
**c) [‘ ‘]**\
d) Error
>Explanation: The output of the code shown above is a blank space inserted in single quotes, which is enclosed by square brackets. Hence the output will be [‘ ‘].
 
### To obtain a list of all the functions defined under sys module, which of the following functions can be used? [Щоб отримати список усіх функцій, визначених у модулі sys, які з наведених нижче функцій можна використовувати]

a) print(sys)\
b) print(dir.sys)\
c) print(dir[sys])\
**d) print(dir(sys))**
>Explanation: The function print(dir(sys)) helps us to obtain a list of all the functions defined under the sys module. The function can be used to obtain the list of functions under any given module in Python.
 
### The output of the function len(sys.argv) is [Вивід функції len(sys.argv) - це]
 
a) Error\
**b) 1**\
c) 0\
d) Junk value
>Explanation: The output of the function sys.argv is [‘ ‘]. When we execute the function len([‘ ‘]), the output is 1. Hence the output of the function len(sys.argv) is also 1.
 
### What does os.name contain? [Що містить в собі os.name?]
**a) the name of the operating system dependent module imported**\
b) the address of the module os\
c) error, it should’ve been os.name()\
d) none of the mentioned
>Explanation: It contains the name of the operating system dependent module imported such as ‘posix’, ‘java’ etc.
 
### What does print(os.geteuid()) print? [Що виводить функція print(os.geteuid())?]
a) the group id of the current process\
**b) the user id of the current process**\
c) both the group id and the user of the current process\
d) none of the mentione
>Explanation: os.geteuid() gives the user id while the os.getegid() gives the group id.
 
### What does os.getlogin() return? [Що повертає функція os.getlogin()?]
**a) name of the current user logged in**\
b) name of the superuser\
c) gets a form to login as a different user\
d) all of the mentioned
>Explanation: It returns the name of the user who is currently logged in and is running the script.
 
### What does os.close(f) do? [Що робить os.close()?]
a) terminate the process f\
b) terminate the process f if f is not responding\
**c) close the file descriptor f**\
d) return an integer telling how close the file pointer is to the end of file
>Explanation: When a file descriptor is passed as an argument to os.close() it will be closed.
 
### What does os.fchmod(fd, mode) do? [Що робить os.fchmod(fd, mode)?]
**a) change permission bits of the file**\
b) change permission bits of the directory\
c) change permission bits of either the file or the directory\
d) none of the mentioned\
>Explanation: The arguments to the function are a file descriptor and the new mode.
 
### Which of the following functions can be used to read data from a file using a file descriptor? [Яку з наведених нижче функцій можна використовувати для читання даних із файлу за допомогою дескриптора файлу?]
a) os.reader()\
**b) os.read()**\
c) os.quick_read()\
d) os.scan()
>Explanation: None of the other functions exist.
 
### Which of the following returns a string that represents the present working directory? [Що з наведеного нижче повертає рядок, що представляє поточний робочий каталог?]
**a) os.getcwd()**\
b) os.cwd()\
c) os.getpwd()\
d) os.pwd()
>Explanation: The function getcwd() (get current working directory) returns a string that represents the present working directory.
 
### What does os.link() do? [Що робить os.link()?]
a) create a symbolic link\
**b) create a hard link**\
c) create a soft link\
d) none of the mentioned
>Explanation: os.link(source, destination) will create a hard link from source to destination.
 
### Which of the following can be used to create a directory? [Що з наведеного нижче можна використовувати для створення каталогу?]
**a) os.mkdir()**\
b) os.creat_dir()\
c) os.create_dir()\
d) os.make_dir()
>Explanation: The function mkdir() creates a directory in the path specified.
 
### Which of the following can be used to create a symbolic link? [Що з наведеного нижче можна використовувати для створення символічного посилання?]
**a) os.symlink()**\
b) os.symb_link()\
c) os.symblin()\
d) os.ln()
>Explanation: It is the function that allows you to create a symbolic link.
 
### What will be the output shape of the following Python code? [Який буде вигляд виводу наступного коду?]
```python
import turtle
t=turtle.Pen()
for i in range(0,4):
	t.forward(100)
	t.left(120)
```
 
a) square\
b) rectangle\
**c) triangle**\
d) kite
>Explanation: According to the code shown above, 4 lines will be drawn. Three lines will be in the shape of a triangle. The fourth line will trace the base, which is already drawn. Hence the base will be slightly thicker than the rest of the lines. However there will be no change in the shape due to this extra line. Hence the output shape will be a triangle.
 
### The number of lines drawn in each case, assuming that the turtle module has been imported: [Кількість ліній, намальованих у кожному випадку, якщо припустити, що модуль turtle було імпортовано:]
```python
Case 1:
for i in range(0,10):
	turtle.forward(100)
	turtle.left(90)
Case 2:
for i in range(1,10):
	turtle.forward(100)
	turtle.left(90)
```
 
**a) 10, 9**\
b) 9, 10\
c) 9, 9\
d) 10, 10
>Explanation: The number of lines drawn in the first case is 10, while that in the second case is 9.
 
### The command which helps us to reset the pen (turtle): [Команда, яка допомагає нам скинути pen (turtle)]
a) turtle.reset\
b) turtle.penreset\
c) turtle.penreset()\
**d) turtle.reset()**
>Explanation: The command turtle.reset() helps us to reset the pen. After the execution of this command, we get a blank page with an arrow on it. We can then perform any desired operation on this page.
 
### Fill in the blank such that the following Python code results in the formation of an inverted, equilateral triangle. [Заповніть пропуск так, щоб наступний код Python утворив перевернутий рівносторонній трикутник.]
```python
import turtle
t=turtle.Pen()
for i in range(0,3):
	t.forward(150)
	t.right(_____)
```
 
a) -60\
**b) 120**\
c) -120\
d) 60
>Explanation: An angle of -120 will result in the formation of an upright, equilateral triangle. An angle of 120 will result in the formation of an inverted triangle. The angles of 60 and -60 do not result in the formation of a triangle.
 
### What will be the output shape of the following Python code? [Який буде вигляд виводу наступного коду?]
```python
import turtle
t=turtle.Pen()
for i in range(1,4):
	t.forward(60)
	t.left(90)
```

a) Rectangle\
b) Trapezium\
c) Triangle\
**d) Square**
>Explanation: The code shown above will result in the formation of a square, with each of side 60.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
for i in range(0,4):
	t.forward(100)
	t.left(90)
 
t.penup()
t.left(90)
t.forward(200)
for i in range(0,4):
	t.forward(100)
	t.left(90)
```
 
a) Error\
**b) 1 square**\
c) 2 squares, at a separation of100 units, joined by a straight line\
d) 2 squares, at a separation of 100 units, without a line joining them\
>Explanation: The output of the code shown above will be a single square. This is because the function t.penup() is used to lift the pen after the construction of the first square. However, the function t.pendown() has not been used to put the pen back down. Hence, the output shape of this code is one square, of side 100 units.
 
### Which of the following functions does not accept any arguments? [Яка з наведених функцій не приймає жодних аргументів?]
**a) position**\
b) fillcolor\
c) goto\
d) setheading()
>Explanation: The functions fillcolor(), goto() and setheading() accept arguments, whereas the function position() does not accept any arguments. The function position() returns the current position of the turtle.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
t.goto(300,9)
t.position()
```
 
**a) 300.00, 9.00**\
b) 9, 300\
c) 300, 9\
d) 9.00, 300.00
>Explanation: The goto functions takes the arrow to the position specified by the user as arguments. The position function returns the current position of the arrow. Hence the output of the code shown above will be: 300.00, 9.00.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
for i in range(0,5):
        t.left(144)
        t.forward(100)
```
 
a) Trapezium\
b) Parallelepiped\
c) Tetrahedron\
**d) Star**
>Explanation: It is clear from the above code that 5 lines will be drawn on the canvas, at an angle of 144 degrees. The only shape which fits this description is star. Hence the output of the code shown above is star.
 
### What will be the output of the following Python functions? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
for i in range(0,3):
	t.forward(100)
	t.left(120)
 
t.back(100)
for i in range(0,3):
	t.forward(100)
	t.left(120)
```
 
a) Error\
b) Two triangles, joined by a straight line\
**c) Two triangles, joined at one vertex**\
d) Two separate triangles, not connected by a line
>Explanation: The output of the code shown above is two equilateral triangles (of side 100 units), joined at the vertex.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
t.color(0,0,1)
t.begin_fill()
t.circle(15)
t.end_fill()
```
 
a) Error\
b) A circle filled in with the colour red\
**c) A circle filled in with the colour blue**\
d) A circle filled in with the colour green
>Explanation: The function t.colour(0, 0, 1) is used to fill in the colour blue into any given shape. Hence the output of the code shown above will be a circle filled in with the colour blue.
 
### Which of the following functions can be used to make the arrow black? [Яку з наведених нижче функцій можна використати, щоб зробити стрілку чорною?]
a) turtle.color(0,1,0)\
b) turtle.color(1,0,0)\
c) turtle.color(0,0,1)\
**d) turtle.color(0,0,0)**
>Explanation: The function turtle.color(0,0,0) can change the colour of the arrow. The function turtle.color(0,1,0) will make the arrow green. The function turtle.color(1,0,0) will make the arrow red. The function turtle.color(0,0,1) will make the arrow blue. The function turtle.color(0,0,0) will make the arrow black.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
t.color(1,1,1)
t.begin_fill()
for i in range(0,3):
	t.forward(100)
	t.right(120)
              t.end_fill()
```

**a) Blank page**\
b) A triangle filled in with the colour yellow\
c) A triangle which is not filled in with any colour\
d) Error
>Explanation: The code shown above will result in a blank page. This is because the command turtle.color(1,1,1) eliminates the arrow from the page. Hence all the commands after this command are ineffective.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
t.color(0,1,0)
t.begin_fill()
for i in range(0,4):
	t.forward(100)
	t.right(90)
```
 
a) A square filled in with the colour green\
**b) A square outlined with the colour green**\
c) Blank canvas\
d) Error
>Explanation: The output shape of the code shown above is a square, outlined with the colour green, but not filled in with any colour. This is because we have not used the command t.end_fill() at the end.

 
### In which direction is the turtle pointed by default? [У який бік за замовчуванням вказана turtle?]

a) North\
b) South\
**c) East**\
d) West
>Explanation: By default, the turtle is pointed towards the east direction. We can change the direction of the turtle by using certain commands. However, whenever the turtle is reset, it points towards east.
 
### The command used to set only the x coordinate of the turtle at 45 units is: [Команда, яка використовується для встановлення лише координати x turtle на 45 одиниць]
 
a) reset(45)\
**b) setx(45)**\
c) xset(45)\
d) xreset(45)
>Explanation: The command setx(45) is used to set the x coordinate of the turtle. Similarly, the command sety() is used to set the y coordinate of the turtle. The function reset() takes two values as arguments, one for the x-coordinate and the other for the y-coordinate.

 
### Which of the following functions returns a value in degrees, counterclockwise from the horizontal right? [Яка з наведених нижче функцій повертає значення в градусах проти годинникової стрілки від горизонтального праворуч?]
 
**a) heading()**\
b) degrees()\
c) position()\
d) window_height()
>Explanation: The function heading() returns the heading of the turtle, which is a value in degrees counterclockwise from the horizontal right. This measure will be in radians if radians() has been called.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
t.right(90)
t.forward(100)
t.heading()
```
 
a) 0.0\
b) 90.0\
**c) 270.0**\
d) 360.0
>Explanation: The output of the code shown above will be 270.0. The function heading() returns the heading of the turtle, a value in degrees, counterclockwise from the horizontal right. The output shape of this code is a straight line pointing downwards.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
t.clear()
t.isvisible()
```
 
a) Yes\
**b) True**\
c) No\
d) False
>Explanation: The function t.clear() returns a blank canvas, without changing the position of the turtle. Since the turtle is visible on the blank canvas, the output of this code is: Yes.
 
### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```python
import turtle
t=turtle.Pen()
t.forward(100)
t.left(90)
t.clear()
t.position()
```
 
a) 0.00, 90.00\
b) 0.00, 0.00\
c) 100.00, 90.00\
**d) 100.00, 100.00**
>Explanation: (Ну вапще-то (100.00, 0.00)..., но ладна) The output of the code shown above is 100.00, 100.00. The function clear() is used to erase the entire canvas and redraw the turtle. However, the position of the turtle is not changed.


# Section 23

# Section 24

# Section 25

## Python Files – 1

### 1. To open a file c:\scores.txt for reading, we use _____________ [Щоб відкрити файл c:\scores.txt для читання, ми використовуємо...]

a) infile = open(“c:\scores.txt”, “r”)

**b) infile = open(“c:\\scores.txt”, “r”)**

c) infile = open(file = “c:\scores.txt”, “r”)

d) infile = open(file = “c:\\scores.txt”, “r”)

> "r" for reading, \\ is needed after disk name

### 2. To open a file c:\scores.txt for writing, we use ____________ [Щоб відкрити файл c:\scores.txt для запису, ми використовуємо...]

a) outfile = open(“c:\scores.txt”, “w”)

**b) outfile = open(“c:\\scores.txt”, “w”)**

c) outfile = open(file = “c:\scores.txt”, “w”)

d) outfile = open(file = “c:\\scores.txt”, “w”)

> "w" is used to indicate that file is to be written to.

### 3. To open a file c:\scores.txt for appending data, we use ____________ [Щоб відкрити файл c:\scores.txt для запису даних в кінець, ми використовуємо...]

**a) outfile = open(“c:\\scores.txt”, “a”)**

b) outfile = open(“c:\\scores.txt”, “rw”)

c) outfile = open(file = “c:\scores.txt”, “w”)

d) outfile = open(file = “c:\\scores.txt”, “w”)

>a is used to indicate that data is to be appended.

### 4. Which of the following statements are true? [Які твердження є правильними?]

a) When you open a file for reading, if the file does not exist, an error occurs

b) When you open a file for writing, if the file does not exist, a new file is created

c) When you open a file for writing, if the file exists, the existing file is overwritten with the new file

**d) All of the mentioned**

### 5. To read two characters from a file object infile, we use ____________ [Для читання 2 символів з з файлового об'єкту infile ми використовуємо...]

**a) infile.read(2)**

b) infile.read()

c) infile.readline()

d) infile.readlines()

### 6. To read the entire remaining contents of the file as a string from a file object infile, we use ____________ [Для читання всього продовження файлу як рядка з файлового об'єкту infile ми використовуємо...]

a) infile.read(2)

**b) infile.read()**

c) infile.readline()

d) infile.readlines()

> read function is used to read all the lines (that left?) in a file.

### 7. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
```
    f = None

    for i in range (5):

        with open("data.txt", "w") as f:

            if i > 2:

                break

    print(f.closed)
```

**a) True**

b) False

c) None

d) Error

> The WITH statement when used with open file guarantees that the file object is closed when the with block exits.

### 8. To read the next line of the file from a file object infile, we use ____________ [Для читання наступного рядка з файлового об'єкту infile ми використовуємо...]

a) infile.read(2)

b) infile.read()

**c) infile.readline()**

d) infile.readlines()


### 9. To read the remaining lines of the file from a file object infile, we use ____________ [Для читання рядків, що залишилися, з файлового об'єкту infile ми використовуємо...]

a) infile.read(2)

b) infile.read()

c) infile.readline()

**d) infile.readlines()**

> Content of t.txt:
> ```
> eerrrrrrrrrrrrrrrrrrrrrrr
> tttttttt
> ```
> Code:
> ```
> f = open('t.txt','r')
> f.read(2)
> print(f.readlines())
> f.close()
>
> f = open('t.txt', 'r')
> f.read(2)
> print(f.read())
> f.close()
> ```
> Output:
> ```
> ['rrrrrrrrrrrrrrrrrrrrrrr\n', 'tttttttt']
> rrrrrrrrrrrrrrrrrrrrrrr
> tttttttt
> ```
> Apparently in this question they want list of lines and not just string (like in question 6)

### 10. The readlines() method returns ____________ [Метод readlines() повертає ...]

a) str

**b) a list of lines**

c) a list of single characters

d) a list of integers

> see the explanation of previous question


<!-- *************************************************************************************************************************************************************************** -->
## Python Files – 2

### 1. Which are the two built-in functions to read a line of text from standard input, which by default comes from the keyboard? [Що є двома вбудованими функціями для читання рядка зі стандартного вводу, який за замовчу]

**a) Raw_input & Input**

b) Input & Scan

c) Scan & Scanner

d) Scanner

> Python 2 provides two built-in functions to read a line of text from standard input, which by default comes from the keyboard. These functions are:
raw_input and input
>
> In Python 3 raw_input() is just input()

### 2. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
```
    str = raw_input("Enter your input: ");

    print "Received input is : ", str
```

**a)**
```
Enter your input: Hello Python
Received input is :  Hello Python
```

b)
```
Enter your input: Hello Python
Received input is :  Hello 
```

c)
```
Enter your input: Hello Python
Received input is :  Python
```

d) None of the mentioned

> The raw_input([prompt]) function reads one line from standard input and returns it as a string. This would prompt you to enter any string and it would display same string on the screen.
> In python 3 it changed to just input()

### 3. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
```
    str = input("Enter your input: ");

    print "Received input is : ", str
```

**a)**
```
Enter your input: [x*5 for x in range(2,10,2)]
Received input is :  [x*5 for x in range(2,10,2)]
```

b)
```
Enter your input: [x*5 for x in range(2,10,2)]
Received input is :  [10, 30, 20, 40]
```

c)
```
Enter your input: [x*5 for x in range(2,10,2)]
Received input is :  [10, 10, 30, 40]
```

d) None of the mentioned


> tested

### 4. Which one of the following is not attributes of file? [Що не є атрибутом файлу?]

a) closed

b) softspace

**c) rename**

d) mode

> rename is not the attribute of file rest all are files attributes.
>```
>Attribute	Description
>file.closed	Returns true if file is closed, false otherwise.
>file.mode	Returns access mode with which file was opened.
>file.name	Returns name of the file.
>file.softspace	Returns false if space explicitly required with print, true otherwise.
>```

### 5. What is the use of tell() method in python? [Навіщо метод tell() у python?]

**a) tells you the current position within the file**

b) tells you the end position within the file

c) tells you the file is opened or not

d) none of the mentioned

> The tell() method tells you the current position within the file; in other words, the next read or write will occur at that many bytes from the beginning of the file.

### 6. What is the current syntax of rename() a file? [Який наразі синтаксис у rename() файл?]

**a) rename(current_file_name, new_file_name)**

b) rename(new_file_name, current_file_name,)

c) rename(()(current_file_name, new_file_name))

d) none of the mentioned

> This is the correct syntax which has shown below.
>```
>rename(current_file_name, new_file_name)
>```

### 7. What is the current syntax of remove() a file? [Який наразі синтаксис у remove() файл?]

**a) remove(file_name)**

b) remove(new_file_name, current_file_name,)

c) remove(() , file_name))

d) none of the mentioned

> remove(file_name)

### 8. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
```
    fo = open("foo.txt", "rw+")

    print "Name of the file: ", fo.name

     
    # Assuming file has following 5 lines
    # This is 1st line
    # This is 2nd line
    # This is 3rd line
    # This is 4th line
    # This is 5th line

     
    for index in range(5):

       line = fo.next()

       print "Line No %d - %s" % (index, line)

     
    # Close opened file

    fo.close()
```

a) Compilation Error

**technically in Python 3 print should have () so this also b) Syntax Error**

**from site c) Displays Output**

**on Python 3.8 I've got runtime error d) None of the mentioned**


> In python 2 it will work??? but I've run it in Python 3.8 and got error
>```
>ValueError: must have exactly one of create/read/write/append mode
>```
> which is runtime error?

### 9. What is the use of seek() method in files? [Навіщо метод seek() для файлів?]

**a) sets the file’s current position at the offset**

b) sets the file’s previous position at the offset

c) sets the file’s current position within the file

d) none of the mentioned

> Sets the file’s current position at the offset. The method seek() sets the file’s current position at the offset.
>Following is the syntax for seek() method:
>```
>fileObject.seek(offset[, whence])
>```
>Parameters
>
>`offset` — This is the position of the read/write pointer within the file.
>
>whence — This is optional and defaults to 0 which means absolute file positioning, other values are 1 which means seek relative to the current position and 2 means seek relative to the file’s end.

### 10. What is the use of truncate() method in file? [Навіщо метод truncate() для файлів?]

**a) truncates the file size**

b) deletes the content of the file

c) deletes the file size

d) none of the mentioned

> The method truncate() truncates the file size. Following is the syntax for truncate() method:
>```
>fileObject.truncate( [ size ])
>```
>Parameters
>
>`size` — If this optional argument is present, the file is truncated to (at most) that size. 



<!-- *********************************************************************************************************************************** -->
## Python Files – 3

### 1. Which is/are the basic I/O connections in file? [Що є базовими I/O зв'язки у файлі?]

a) Standard Input

b) Standard Output

c) Standard Errors

**d) All of the mentioned**

> Standard input, standard output and standard error. Standard input is the data that goes to the program. The standard input comes from a keyboard. Standard output is where we print our data with the print keyword. Unless redirected, it is the terminal console. The standard error is a stream where programs write their error messages. It is usually the text terminal. 

### 2. What will be the output of the following Python code? (If entered name is sanfoundry) [Яким буде вихід цього Python коду? (якщо введене ім'я sanfoundry)]
```
    import sys

    print 'Enter your name: ',

    name = ''

    while True:

       c = sys.stdin.read(1)

       if c == '\n':

          break

       name = name + c

     

    print 'Your name is:', name
```

**a) sanfoundry**

b) sanfoundry, sanfoundry

c) San

d) None of the mentioned

> In order to work with standard I/O streams, we must import the sys module. The read() method reads one character from the standard input. In our example we get a prompt saying “Enter your name”. We enter our name and press enter. The enter key generates the new line character: \n.
>Output:
> Enter your name: sanfoundry
>Your name is: sanfoundry

### 3. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
```
    import sys

    sys.stdout.write(' Hello\n')

    sys.stdout.write('Python\n')
```

a) Compilation Error

b) Runtime Error

c) Hello Python

**d)**
```
Hello
Python
```

> Explanation: None
>```Output:
>Hello
>Python`
``
 

### 4. Which of the following mode will refer to binary data? [Який з наведених режимів відповідая бінарному?]

a) r

b) w

c) +

**d) b**

> Mode Meaning is as explained below:
>r Reading
>w Writing
>a Appending
>b Binary data
>+ Updating.

### 5. What is the pickling? [Що таке pickling?]

**a) It is used for object serialization**

b) It is used for object deserialization

c) None of the mentioned

d) All of the mentioned

> Pickle is the standard mechanism for object serialization. Pickle uses a simple stack-based virtual machine that records the instructions used to reconstruct the object. This makes pickle vulnerable to security risks by malformed or maliciously constructed data, that may cause the deserializer to import arbitrary modules and instantiate any object.

### 6. What is unpickling? [Що таке unpickling?]

a) It is used for object serialization

**b) It is used for object deserialization**

c) None of the mentioned

d) All of the mentioned

> We have been working with simple textual data. What if we are working with objects rather than simple text? For such situations, we can use the pickle module. This module serializes Python objects. The Python objects are converted into byte streams and written to text files. This process is called pickling. The inverse operation, reading from a file and reconstructing objects is called deserializing or unpickling. 
 
### 7. What is the correct syntax of open() function? [Який правильний синтаксис функції open()?]

a) file = open(file_name [, access_mode][, buffering])

**b) file object = open(file_name [, access_mode][, buffering])**

c) file object = open(file_name)

**for Python 3 d) none of the mentioned**

> Python 3: open(file, mode='r', buffering=-1, encoding=None, errors=None, newline=None, closefd=True, opener=None)

> Open() function correct syntax with the parameter details as shown below:
>```file object = open(file_name [, access_mode][, buffering])```
>Here is parameters’ detail:
>file_name: The file_name argument is a string value that contains the name of the file that you want to access.
>access_mode: The access_mode determines the mode in which the file has to be opened, i.e., read, write, append, etc. A complete list of possible values is given below in the table. This is optional parameter and the default file access mode is read (r).
>buffering: If the buffering value is set to 0, no buffering will take place. If the buffering value is 1, line buffering will be performed while accessing a file. If you specify the buffering value as an integer greater than 1, then buffering action will be performed with the indicated buffer size. If negative, the buffer size is the system default(default behavior). 

### 8. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
```
    fo = open("foo.txt", "wb")

    print "Name of the file: ", fo.name

    fo.flush()

    fo.close()
```

a) Compilation Error

b) Runtime Error

c) No Output

**d) Flushes the file when closing them**


> The method flush() flushes the internal buffer. Python automatically flushes the files when closing them. But you may want to flush the data before closing any file.

### 9. Correct syntax of file.writelines() is? [Який правильний синтаксис функції file.writelines()?]

a) file.writelines(sequence)

b) fileObject.writelines()

**c) fileObject.writelines(sequence)**

d) none of the mentioned

> The method writelines() writes a sequence of strings to the file. The sequence can be any iterable object producing strings, typically a list of strings. There is no return 
value.
>Syntax
>Following is the syntax for writelines() method:
>fileObject.writelines( sequence ).

### 10. Correct syntax of file.readlines() is? [Який правильний синтаксис функції file.readlines()?]

**a) fileObject.readlines( sizehint );**

b) fileObject.readlines();

c) fileObject.readlines(sequence)

d) none of the mentioned

> The method readlines() reads until EOF using readline() and returns a list containing the lines. If the optional sizehint argument is present, instead of reading up to EOF, whole lines totalling approximately sizehint bytes (possibly after rounding up to an internal buffer size) are read.
>Syntax
>Following is the syntax for readlines() method:
>fileObject.readlines( sizehint );
>Parameters
>sizehint — This is the number of bytes to be read from the file. 

<!-- ************************************************************************************************************************************************************************** -->
## Python Files - 4

### 1. In file handling, what does this terms means “r, a”? [У роботі з файлами, що означає “r, a”?]

**a) read, append**

b) append, read

c) write, append

d) none of the mentioned

> r- reading, a-appending.

### 2. What is the use of “w” in file handling? [У роботі з файлами, що означає “w”?]

a) Read

**b) Write**

c) Append

d) None of the mentioned

> This opens the file for writing. It will create the file if it doesn’t exist, and if it does, it will overwrite it.
fh = open(“filename_here”, “w”).

### 3. What is the use of “a” in file handling? [У роботі з файлами, що означає “a?]

a) Read

b) Write

**c) Append**

d) None of the mentioned

> This opens the fhe file in appending mode. That means, it will be open for writing and everything will be written to the end of the file.
fh =open(“filename_here”, “a”).
advertisement

### 4. Which function is used to read all the characters? [Яка функція читає всі символи?]

**a) Read()**

b) Readcharacters()

c) Readall()

d) Readchar()


> The read function reads all characters fh = open(“filename”, “r”)
content = fh.read().

### 5. Which function is used to read single line from file? [Яка функція читає один рядок?]

**a) Readline()**

b) Readlines()

c) Readstatement()

d) Readfullline()

>The readline function reads a single line from the file fh = open(“filename”, “r”)
content = fh.readline().

### 6. Which function is used to write all the characters? [Яка функція пише всі символи?]

**a) write()**

b) writecharacters()

c) writeall()

d) writechar()

> To write a fixed sequence of characters to a file
fh = open(“hello.txt”,”w”)
write(“Hello World”).

### 7. Which function is used to write a list of string in a file? [Яка функція пише список рядків]

a) writeline()

**b) writelines()**

c) writestatement()

d) writefullline()

>With the writeline function you can write a list of strings to a file
>```fh = open(“hello.txt”, “w”)
>lines_of_text = [“a line of text”, “another line of text”, “a third line”] fh.writelines(lines_of_text)
>```

### 8. Which function is used to close a file in python? [Яка функція закриває файл]

**a) Close()**

b) Stop()

c) End()

d) Closefile()

>f.close()to close it and free up any system resources taken up by the open file.

### 9. Is it possible to create a text file in python? [Чи можливо створити у python текстовий файл?]

**a) Yes**

b) No

c) Machine dependent

d) All of the mentioned

>Yes we can create a file in python. Creation of file is as shown below.
>```file = open(“newfile.txt”, “w”)
>file.write(“hello world in the new file\n”)
>file.write(“and another line\n”)
>file.close()
>```

### 10. Which of the following are the modes of both writing and reading in binary format in file? [Який режим використовується і для запису, і для читання бінарного файлу?]

a) wb+

b) w

**c) wb**

d) w+

> Here is the description below
>“w” Opens a file for writing only. Overwrites the file if the file exists. If the file does not exist, creates a new file for writing.
>“wb” Opens a file for writing only in binary format. Overwrites the file if the file exists. If the file does not exist, creates a new file for writing.
>“w+” Opens a file for both writing and reading. Overwrites the existing file if the file exists. If the file does not exist, creates a new file for reading and writing.
>“wb+” Opens a file for both writing and reading in binary format. Overwrites the existing file if the file exists. If the file does not exist, creates a new file for reading and writing.

<!-- ***************************************************************************************************************************************************************** -->
## Python Encapsulation

### 1. Which of these is not a fundamental features of OOP?

a) Encapsulation

b) Inheritance

**c) Instantiation**

d) Polymorphism

>Instantiation simply refers to creation of an instance of class. It is not a fundamental feature of OOP.

### 2. Which of the following is the most suitable definition for encapsulation?

a) Ability of a class to derive members of another class as a part of its own definition

**b) Means of bundling instance variables and methods in order to restrict access to certain class members**

c) Focuses on variables and passing of variables to functions

d) Allows for implementation of elegant software that is well designed and easily modified

> The values assigned by the constructor to the class members is used to create the object.

### 3. What will be the output of the following Python code?
```
class Demo:
    def __init__(self):
        self.a = 1
        self.__b = 1
 
    def display(self):
        return self.__b
obj = Demo()
print(obj.a)
```

a) The program has an error because there isn’t any function to return self.a

b) The program has an error because b is private and display(self) is returning a private member

**c) The program runs fine and 1 is printed**

d) The program has an error as you can’t name a class member using __b

> The program has no error because the class member which is public is printed. 1 is displayed. Execute in python shell to verify.

### 4. What will be the output of the following Python code?
```
class Demo:
    def __init__(self):
        self.a = 1
        self.__b = 1
 
    def display(self):
        return self.__b
 
obj = Demo()
print(obj.__b)
```

a) The program has an error because there isn’t any function to return self.a

b) The program has an error because b is private and display(self) is returning a private member

**c) The program has an error because b is private and hence can’t be printed**

d) The program runs fine and 1 is printed

>Variables beginning with two underscores are said to be private members of the class and they can’t be accessed directly.

### 5. Methods of a class that provide access to private members of the class are called as ______ and ______

**a) getters/setters**

b) `__repr__/__str__`

c) user-defined functions/in-built functions

d) `__init__/__del__`

> The purpose of getters and setters is to get(return) and set(assign) private instance variables of a class.

### 6. Which of these is a private data field?

```
def Demo:
def __init__(self):
    __a = 1
    self.__b = 1
    self.__c__ = 1
    __d__= 1
```

a) __a

**b) __b**

c) `__c__`

d) `__d__`

>Variables such as self.__b are private members of the class.

### 7. What will be the output of the following Python code?
```
class Demo:
     def __init__(self):
         self.a = 1
         self.__b = 1
 
     def get(self):
         return self.__b
 
obj = Demo()
print(obj.get())
```

a) The program has an error because there isn’t any function to return self.a

b) The program has an error because b is private and display(self) is returning a private member

c) The program has an error because b is private and hence can’t be printed

**d) The program runs fine and 1 is printed**

>Here, get(self) is a member of the class. Hence, it can even return a private member of the class. Because of this reason, the program runs fine and 1 is printed.

### 8. What will be the output of the following Python code?
```
class Demo:
     def __init__(self):
         self.a = 1
         self.__b = 1
     def get(self):
         return self.__b
obj = Demo()
obj.a=45
print(obj.a)
```

**a) The program runs properly and prints 45**

b) The program has an error because the value of members of a class can’t be changed from outside the class

c) The program runs properly and prints 1

d) The program has an error because the value of members outside a class can only be changed as self.a=45

>It is possible to change the values of public class members using the object of the class.

### 9. Private members of a class cannot be accessed.

a) True

**b) False**

>Private members of a class are accessible if written as follows: obj._Classname__privatemember. Such renaming of identifiers is called as name mangling.

### 10. The purpose of name mangling is to avoid unintentional access of private class members.

**a) True**

b) False

>Name mangling prevents unintentional access of private members of a class, while still allowing access when needed. Unless the variable is accessed with its mangled name, it will not be found.

### 11. What will be the output of the following Python code?
```
class fruits:
    def __init__(self):
        self.price = 100
        self.__bags = 5
    def display(self):
        print(self.__bags)
obj=fruits()
obj.display()
```

a) The program has an error because display() is trying to print a private class member

b) The program runs fine but nothing is printed

**c) The program runs fine and 5 is printed**

d) The program has an error because display() can’t be accessed

>Private class members can be printed by methods which are members of the class.

### 12. What will be the output of the following Python code?
```
 class student:
    def __init__(self):
        self.marks = 97
        self.__cgpa = 8.7
    def display(self):
        print(self.marks)
obj=student()
print(obj._student__cgpa)
```

**a) The program runs fine and 8.7 is printed**

b) Error because private class members can’t be accessed

c) Error because the proper syntax for name mangling hasn’t been implemented

d) The program runs fine but nothing is printed

>Name mangling has been properly implemented in the code given above and hence the program runs properly.

### 13. Which of the following is false about protected class members?

a) They begin with one underscore

b) They can be accessed by subclasses

**c) They can be accessed by name mangling method**

d) They can be accessed within a class

>Protected class members can’t be accessed by name mangling.

### 14. What will be the output of the following Python code?
```
class objects:
    def __init__(self):
        self.colour = None
        self._shape = "Circle" 
 
    def display(self, s):
        self._shape = s
obj=objects()
print(obj._objects_shape)
```

a) The program runs fine because name mangling has been properly implemented

b) Error because the member shape is a protected member

c) Error because the proper syntax for name mangling hasn’t been implemented

d) Error because the member shape is a private member

>Protected members begin with one underscore and they can only be accessed within a class or by subclasses.

# Section 26
