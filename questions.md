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
# Section 8

# Section 9

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

# Section 23

# Section 24

# Section 25

# Section 26