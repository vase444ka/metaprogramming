# Section 0 [Questions from first page]

## 1. Who developed Python Programming Language?

**c) Guido van Rossum**

## 2. Which type of Programming does Python support? [тип програмування]

a) object-oriented programming

b) structured programming

c) functional programming

**d) all of the mentioned**

> Explanation: Python is an interpreted programming language.

## 3. Is Python case sensitive when dealing with identifiers? [чутливий до регістру під час роботи з ідентифікаторами]

**b) yes**

## 4. Which of the following is the correct extension of the Python file?

**c) .py**

## 5. Is Python code compiled or interpreted?

**a) Python code is both compiled and interpreted**

b) Python code is neither compiled nor interpreted

c) Python code is only compiled

d) Python code is only interpreted

> Explanation: Many languages have been implemented using both compilers and interpreters, including C, Pascal, and Python.

## 6. All keywords in Python are in \***\*\_\*\***

a) Capitalized

b) lower case

c) UPPER CASE

**d) None of the mentioned**

> Explanation: True, False and None are capitalized while the others are in lower case.

## 7. What will be the value of the following Python expression?

`4 + 3 % 5`

**a) 7**

## 8. Which of the following is used to define a block of code in Python language?

**a) Indentation**

b) Key

c) Brackets

d) All of the mentioned

> Explanation: In Python, to define a block of code we use indentation. Indentation refers to whitespaces at the beginning of the line.

## 9. Which keyword is used for function in Python language?

**b) Def**

## 10. Which of the following character is used to give single-line comments in Python?

**b) #**

> Explanation: To write single-line comments in Python use the Numero sign (#) at the beginning of the line. To write multi-line comments, close the text between triple quotes.
> Example: “”” comment
> text “””

## 11. What will be the output of the following Python code?

```i = 1
while True:
    if i%3 == 0:
        break
    print(i)

    i + = 1
```

**b) error**

> Explanation: SyntaxError, there shouldn’t be a space between + and = in +=.


## 13. Python supports the creation of anonymous functions at runtime, using a construct called \***\*\_\_\*\*** [анонімні функції]

**c) lambda**

> Explanation: Python supports the creation of anonymous functions (i.e. functions that are not bound to a name) at runtime, using a construct called lambda. Lambda functions are restricted to a single expression. They can be used wherever normal functions can be used.

## 14. What is the order of precedence in python? [порядок пріоритету]

**d) Parentheses, Exponential, Multiplication, Division, Addition, Subtraction**

> Explanation: For order of precedence, just remember this PEMDAS (similar to BODMAS).

## 15. What will be the output of the following Python code snippet if x=1?

`x<<2`

**a) 4**

> Explanation: The binary form of 1 is 0001. The expression x<<2 implies we are performing bitwise left shift on x. This shift yields the value: 0100, which is the binary form of the number 4.

## 16. What does pip stand for python?

**c) Preferred Installer Program**

## 17. Which of the following is true for variable names in Python?

a) underscore and ampersand are the only two special characters allowed

**b) unlimited length**

c) all private members must have leading and trailing underscores

d) none of the mentioned

## 18. What are the values of the following Python expressions?

```
 2**(3**2)
 (2**3)**2
 2**3**2
```

**a) 512, 64, 512**

## 19. Which of the following is the truncation division operator in Python?

**b) //**

> Explanation: // is the operator for truncation division. It is called so because it returns only the integer part of the quotient, truncating the decimal part. For example: 20//3 = 6.

## 20. What will be the output of the following Python code?

```
l=[1, 0, 2, 0, 'hello', '', []]
list(filter(bool, l))
```

a) [1, 0, 2, ‘hello’, ”, []]

b) Error

**c) [1, 2, ‘hello’]**

d) [1, 0, 2, 0, ‘hello’, ”, []]

> Explanation: The code shown above returns a new list containing only those elements of the list l which do not amount to zero. Hence the output is: [1, 2, ‘hello’].

## 21. Which of the following functions is a built-in function in python?

a) factorial()

**b) print()**

c) seed()

d) sqrt()

## 22. Which of the following is the use of id() function in python?

a) Every object doesn’t have a unique id

**b) Id returns the identity of the object**

c) All of the mentioned

d) None of the mentioned

## 23. The following python program can work with \_\_\_\_ parameters.

```
def f(x):
    def f1(*args, **kwargs):
           print("Sanfoundry")
           return x(*args, **kwargs)
    return f1
```

**a) any number of**

> Explanation: The code shown above shows a general decorator which can work with any number of arguments.

## 24. What will be the output of the following Python function?

min(max(False,-3,-4), 2,7)

**d) False**

> Explanation: The function max() is being used to find the maximum value from among -3, -4 and false. Since false amounts to the value zero, hence we are left with min(0, 2, 7) Hence the output is 0 (false).

## 25. Which of the following is not a core data type in Python programming?

a) Tuples

b) Lists

**c) Class**

d) Dictionary

## 26. What will be the output of the following Python expression if x=56.236?

`print("%.2f"%x)`

**d) 56.24**

## 27. Which of these is the definition for packages in Python?

a) A set of main modules

**b) A folder of python modules**

c) A number of files containing Python definitions and statements

d) A set of programs making use of Python modules

## 28. What will be the output of the following Python function?

`len(["hello",2, 4, 6])`

**c) 4**

## 29. What will be the output of the following Python code?

```
x = 'abcd'
for i in x:
    print(i.upper())
```

**d) A B C D**

## 30. What is the order of namespaces in which Python looks for an identifier?

**c) Python first searches the local namespace, then the global namespace and finally the built-in namespace**

## 31. What will be the output of the following Python code snippet?

```
for i in [1, 2, 3, 4][::-1]:
print (i)
```

**a) 4 3 2 1**

## 32. What will be the output of the following Python statement?

```
"a"+"bc"
```

**b) abc**

## 33. Which function is called when the following Python program is executed?

```
f = foo()
format(f)
```

a) str()

b) format()


c) \_ _ str _ \_()

**d) \_ _ format _ \_()**

## 34. Which one of the following is not a keyword in Python language?

a) pass

**b) eval**

c) assert

d) nonlocal

## 35. What will be the output of the following Python code?

```
class tester:
    def __init__(self, id):
        self.id = str(id)
        id="224"

>>>temp = tester(12)
>>>print(temp.id)
```

**a) 12**

> Explanation: Id in this case will be the attribute of the class.

## 36. What will be the output of the following Python program?

```
def foo(x):
    x[0] = ['def']
    x[1] = ['abc']
    return id(x)
q = ['abc', 'def']
print(id(q) == foo(q))
```

**d) True**

> Explanation: The same object is modified in the function.

## 37. Which module in the python standard library parses options received from the command line?

a) getarg

**b) getopt**

c) main

d) os

## 38. What will be the output of the following Python program?

```
z=set('abc')
z.add('san')
z.update(set(['p', 'q']))
z
```

**c) {‘a’, ‘b’, ‘c’, ‘p’, ‘q’, ‘san’}**

> Explanation: The code shown first adds the element ‘san’ to the set z. The set z is then updated and two more elements, namely, ‘p’ and ‘q’ are added to it. Hence the output is: {‘a’, ‘b’, ‘c’, ‘p’, ‘q’, ‘san’}

## 39. What arithmetic operators cannot be used with strings in Python?

**b) –**

## 40. What will be the output of the following Python code?

`print("abc. DEF".capitalize())`

**a) Abc. def**

## 41. Which of the following statements is used to create an empty set in Python?

**d) set()**

> Explanation: { } creates a dictionary not a set. Only set() creates an empty set.

## 42. What will be the value of ‘result’ in following Python program?

```
list1 = [1,2,3,4]
list2 = [2,4,5,6]
list3 = [2,6,7,8]
result = list()
result.extend(i for i in list1 if i not in (list2+list3) and i not in result)
result.extend(i for i in list2 if i not in (list1+list3) and i not in result)
result.extend(i for i in list3 if i not in (list1+list2) and i not in result)
```

**a) [1, 3, 5, 7, 8]**

> Explanation: Here, ‘result’ is a list which is extending three times. When first time ‘extend’ function is called for ‘result’, the inner code generates a generator object, which is further used in ‘extend’ function. This generator object contains the values which are in ‘list1’ only (not in ‘list2’ and ‘list3’).
> Same is happening in second and third call of ‘extend’ function in these generator object contains values only in ‘list2’ and ‘list3’ respectively.
> So, ‘result’ variable will contain elements which are only in one list (not more than 1 list).

## 43. To add a new element to a list we use which Python command?

**c) list1.append(5)**

## 44. What will be the output of the following Python code?

`print('*', "abcde".center(6), '*', sep='')`

b) _abcde _

## 45. What will be the output of the following Python code?

```
list1 = [1, 3]
list2 = list1
list1[0] = 4
print(list2)
```

**c) [4, 3]**

> Explanation: Lists should be copied by executing [:] operation.

## 46. Which one of the following is the use of function in python?

a) Functions don’t provide better modularity for your application

b) you can’t also create your own functions

**c) Functions are reusable pieces of programs**

d) All of the mentioned

> Explanation: Functions are reusable pieces of programs. They allow you to give a name to a block of statements, allowing you to run that block using the specified name anywhere in your program and any number of times.

## 47. Which of the following Python statements will result in the output: 6?

```
A = [[1, 2, 3],
     [4, 5, 6],
     [7, 8, 9]]

```

**b) A[1][2]**

## 48. What is the maximum possible length of an identifier in Python?

**d) Identifiers can be of any length**

## 49. What will be the output of the following Python program?

```
i = 0
while i < 5:
    print(i)
    i += 1
    if i == 3:
        break
else:
    print(0)
```

**c) 0 1 2**

## 50. What will be the output of the following Python code?

```
x = 'abcd'
for i in range(len(x)):
    print(i)
```

**d) 0 1 2 3**

## 51. What are the two main types of functions in Python?

**c) Built-in function & User defined function**

## 52. What will be the output of the following Python program?

```
def addItem(listParam):
    listParam += [1]

mylist = [1, 2, 3, 4]
addItem(mylist)
print(len(mylist))
```

**a) 5**

## 53. Which of the following is a Python tuple?

a) {1, 2, 3}

b) {}

c) [1, 2, 3]

**d) (1, 2, 3)**

## 54. What will be the output of the following Python code snippet?

```
z=set('abc$de')
'a' in z
```

b) True

> Explanation: The code shown above is used to check whether a particular item is a part of a given set or not. Since ‘a’ is a part of the set z, the output is true. Note that this code would result in an error in the absence of the quotes.

## 55. What will be the output of the following Python expression?

`round(4.576)`

**c) 5**

## 56. Which of the following is a feature of Python DocString?

a) In Python all functions should have a docstring

b) Docstrings can be accessed by the \_ _ doc _ \_ attribute on objects

c) It provides a convenient way of associating documentation with Python modules, functions, classes, and methods

**d) All of the mentioned**

## 57. What will be the output of the following Python code?

`print("Hello {0[0]} and {0[1]}".format(('foo', 'bin')))`

**c) Hello foo and bin**

## 58. What is output of print(math.pow(3, 2))?

**a) 9.0**

## 59. Which of the following is the use of id() function in python?

a) Every object in Python doesn’t have a unique id

**b) In Python Id function returns the identity of the object**

c) None of the mentioned

d) All of the mentioned

## 60. What will be the output of the following Python code?

```
x = [[0], [1]]
print((' '.join(list(map(str, x))),))
```

**d) (‘[0] [1]’,)**

> Explanation: (element,) is not the same as element. It is a tuple with one item.

## 61. The process of pickling in Python includes \***\*\_\_\_\_\*\***

**a) conversion of a Python object hierarchy into byte stream**

b) conversion of a datatable into a list

c) conversion of a byte stream into Python object hierarchy

d) conversion of a list into a datatable

## 62. What will be the output of the following Python code?

```
def foo():
    try:
        return 1
    finally:
        return 2
k = foo()
print(k)
```

**c) 2**

# Section 1 

## [Variable Names]

## 1. Is Python case sensitive when dealing with identifiers?
**a) yes**

b) no

c) machine dependent

d) none of the mentioned

> Python is case sensitive overall


## 2. What is the maximum possible length of an identifier?
a) 31 characters

b) 63 characters

c) 79 characters

**d) none of the mentioned**

>Any length

## 3. Which of the following is invalid?
a) _a = 1

b) __a = 1

c) \_\_str\_\_ = 1

**d) none of the mentioned**

>a) is package-private, b) will go through name mangling if inside a class, it’s not a good practice to have a name like c) without a strong reason. Bu all are valid

## 4. Which of the following is an invalid variable?
a) my_string_1

**b) 1st_string**

c) foo

d) _


## 5. Why are local variable names beginning with an underscore discouraged?
**a) they are used to indicate a private variables of a class**

b) they confuse the interpreter

c) they are used to indicate global variables

d) they slow down execution

> As Python has no concept of private variables, leading underscores are used to indicate variables that must not be accessed from outside the class.

## 6. Which of the following is not a keyword?
**a) eval**

b) assert

c) nonlocal

d) pass


## 7. All keywords in Python are in _________
a) lower case

b) UPPER CASE

c) Capitalized

**d) None of the mentioned**

>All lowercase except ```True```, ```False```, ```None```. 

## 8. Which of the following is true for variable names in Python?
**a) unlimited length**

b) all private members must have leading and trailing underscores

c) underscore and ampersand are the only two special characters allowed

d) none of the mentioned


## 9. Which of the following is an invalid statement?
a) abc = 1,000,000

**b) a b c = 1000 2000 3000**

c) a,b,c = 1000, 2000, 3000

d) a_b_c = 1,000,000


## 10. Which of the following cannot be a variable?
a) \_\_init\_\_

**b) in**

c) it

d) on

## [Basic Operators]

## 1. Which is the correct operator for power(xy)?
a) X^y

**b) X\*\*y**

c) X^^y

d) None of the mentioned


## 2. Which one of these is floor division?
a) /

**b) //**

c) %

d) None of the mentioned


## 3. What is the order of precedence in python?
i) Parentheses  
ii) Exponential  
iii) Multiplication  
iv) Division  
v) Addition  
vi) Subtraction  

**a) i,ii,iii,iv,v,vi**

b) ii,i,iii,iv,v,vi

c) ii,i,iv,iii,v,vi

d) i,ii,iii,iv,vi,v


## 4. What is the answer to this expression, 22 % 3 is?
a) 7

**b) 1**

c) 0

d) 5


## 5. Mathematical operations can be performed on a string.
a) True

**b) False**

>Convert to number first

## 6. Operators with the same precedence are evaluated in which manner?
**a) Left to Right**

b) Right to Left

c) Can’t say

d) None of the mentioned


## 7. What is the output of this expression, 3*1**3?
a) 27

b) 9

**c) 3**

d) 1


## 8. Which one of the following has the same precedence level?
**a) Addition and Subtraction**

b) Multiplication, Division and Addition

c) Multiplication, Division, Addition and Subtraction

d) Addition and Multiplication


## 9. The expression Int(x) implies that the variable x is converted to integer.
a) True

**b) False**

>int(x), not Int(x). But original answer was ```True```

## 10. Which one of the following has the highest precedence in the expression?
a) Exponential

b) Addition

c) Multiplication

**d) Parentheses**


## [Core Data Types]

1. Which of these in not a core data type?
a) Lists
b) Dictionary
c) Tuples
d) Class


2. Given a function that does not return any value, What value is thrown by default when executed in shell.
a) int
b) bool
c) void
d) None


3. What will be the output of the following Python code?

advertisement

>>>str="hello"
>>>str[:2]
>>>
a) he
b) lo
c) olleh
d) hello


4. Which of the following will run without errors?
a) round(45.8)
b) round(6352.898,2,5)
c) round()
d) round(7463.123,2,1)


5. What is the return type of function id?
a) int
b) float
c) bool
d) dict


6. In python we do not specify types, it is directly interpreted by the compiler, so consider the following operation to be performed.

>>>x = 13 ? 2
objective is to make sure x has a integer value, select all that apply (python 3.xx)
a) x = 13 // 2
b) x = int(13 / 2)
c) x = 13 % 2
d) All of the mentioned


7. What error occurs when you execute the following Python code snippet?

apple = mango
a) SyntaxError
b) NameError
c) ValueError
d) TypeError


8. What will be the output of the following Python code snippet?

def example(a):
    a = a + '2'
     a = a*2
    return a
>>>example("hello")
a) indentation Error
b) cannot perform mathematical operation on strings
c) hello2
d) hello2hello2


9. What data type is the object below?

L = [1, 23, 'hello', 1]
a) list
b) dictionary
c) array
d) tuple


10. In order to store values in terms of key and value we use what core data type.
a) list
b) tuple
c) class
d) dictionary


11. Which of the following results in a SyntaxError?
a) ‘”Once upon a time…”, she said.’
b) “He said, ‘Yes!'”
c) ‘3\’
d) ”’That’s okay”’


12. The following is displayed by a print function call. Select all of the function calls that result in this output.

tom
dick
harry
a)

print('''tom
\ndick
\nharry''')
b) print(”’tomdickharry”’)
c) print(‘tom\ndick\nharry’)
d)

print('tom
dick
harry')
  
 
13. What is the average value of the following Python code snippet?

>>>grade1 = 80
>>>grade2 = 90
>>>average = (grade1 + grade2) / 2
a) 85.0
b) 85.1
c) 95.0
d) 95.1


14. Select all options that print.

hello-how-are-you
a) print(‘hello’, ‘how’, ‘are’, ‘you’)
b) print(‘hello’, ‘how’, ‘are’, ‘you’ + ‘-‘ * 4)
c) print(‘hello-‘ + ‘how-are-you’)
d) print(‘hello’ + ‘-‘ + ‘how’ + ‘-‘ + ‘are’ + ‘you’)


15. What is the return value of trunc()?
a) int
b) bool
c) float
d) None



## [Numeric Types]


## 1. What is the output of print 0.1 + 0.2 == 0.3?
a) True

b) False

c) Machine dependent

**d) Error**

>Missing parentheses. But orig answer is ```False``` due to round off errors

## 2. Which of the following is not a complex number?
a) k = 2 + 3j

b) k = complex(2, 3)

**c) k = 2 + 3l**

d) k = 2 + 3J

>  l (or L) stands for long

## 3. What is the type of inf?
a) Boolean

b) Integer

**c) Float**

d) Complex

>Infinity is a special case of floating point numbers

## 4. What does ~4 evaluate to?
**a) -5**

b) -4

c) -3

d) +3


## 5. What does ~~~~~~5 evaluate to?
**a) +5**

b) -11

c) +11

d) -5


## 6. Which of the following is incorrect?
a) x = 0b101

b) x = 0x4f5

c) x = 19023

**d) x = 03964**

>Numbers starting with a 0 are octal numbers but 9 isn’t allowed in octal numbers.


## 7. What is the result of cmp(3, 1)?
**a) 1**

b) 0

c) True

d) False

>```cmp(x, y)``` returns ```1 if x > y, 0 if x == y``` and ```-1 if x < y```.

## 8. Which of the following is incorrect?
a) float(‘inf’)

b) float(‘nan’)

c) float(’56’+’78’)

**d) float(’12+34′)**


## 9. What is the result of round(0.5) – round(-0.5)?
a) 1.0

b) 2.0

c) 0.0

**d) Value depends on Python version**

>

## 10. What does 3 ^ 4 evaluate to?
a) 81

b) 12

c) 0.75

**d) 7**


# Section 2

# Section 3

## 1. The value of the expressions 4/(3*(2-1)) and 4/3*(2-1) is the same.[Значення виразів 4/(3*(2-1)) і 4/3*(2-1) однакові?]

**a) True**

b) False

Explanation: Although the presence of parenthesis does affect the order of precedence, in the case shown above, it is not making a difference. The result of both of these expressions is 1.333333333. Hence the statement is true.

## 2. What will be the value of the following Python expression?[Яким буде значення наступного виразу Python?]

`4 + 3 % 5`

a) 4

**b) 7**

c) 2

d) 0

Explanation: The order of precedence is: %, +. Hence the expression above, on simplification results in 4 + 3 = 7. Hence the result is 7.

## 3. Evaluate the expression given below if A = 16 and B = 15.[Оцініть наведений нижче вираз, якщо A = 16 і B = 15?]

`A % B // A`

a) 0.0

**b) 0**

c) 1.0

d) 1

Explanation: The above expression is evaluated as: 16%15//16, which is equal to 1//16, which results in 0.

## 4. Which of the following operators has its associativity from right to left?[Який з наведених операторів має свою асоціативність справа наліво?]

a) +

b) //

c) %

**d) \*\***

Explanation: All of the operators shown above have associativity from left to right, except exponentiation operator (\*\*) which has its associativity from right to left.

## 5. What will be the value of x in the following Python expression?[Яким буде значення x у наступному виразі Python?]

`x = int(43.55+2/2)`

a) 43

**b) 44**

c) 22

d) 23

Explanation: The expression shown above is an example of explicit conversion. It is evaluated as int(43.55+1) = int(44.55) = 44. Hence the result of this expression is 44.

## 6. What is the value of the following expression?[Яке значення має наступний вираз?]

`2+4.00, 2**4.0`

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

`2**(3**2) (2**3)**2 2**3**2 `

a) 64, 512, 64

b) 64, 64, 64

c) 512, 512, 512

**d) 512, 64, 512**

Explanation: Expression 1 is evaluated as: 2**9, which is equal to 512. Expression 2 is evaluated as 8**2, which is equal to 64. The last expression is evaluated as 2**(3**2). This is because the associativity of \*\* operator is from right to left. Hence the result of the third expression is 512.

## 9. What is the value of the following expression?[Яке значення має наступний вираз?]

`8/4/2, 8/(4/2)`

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

b) 7.9 \* 6.3

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

**b) \*\***

c) |

d) %

Explanation: The highest precedence is that of the exponentiation operator, that is of \*\*.

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

## 3. Bitwise \***\*\_\*\*** gives 1 if either of the bits is 1 and 0 when both of the bits are 1.[Побітово _________ дає 1, якщо один з бітів дорівнює 1, і 0, коли обидва біти дорівнюють 1]

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

## 5. Any odd number on being AND-ed with **\_\_\_\_** always gives 1. Hint: Any even number on being AND-ed with this value always gives 0.[Будь-яке непарне число під час переміщення І з ________ завжди дає 1. Підказка: будь-яке парне число при переміщенні І з цим значенням завжди дає 0.]

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

> Explanation: Refer documentation.

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
> Traceback (most recent call last):
> File “<pyshell#0>”, line 1, in <module>
> assert False, ‘Spanish’
> AssertionError: Spanish
> Hence, this statement is true.

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
> 11
> test
> 12
> This is because we have used next(g) twice. Had we not used next, there would be no output.

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

## 13. An exception is \***\*\_\_\_\_\*\*** [Виняток становить ___________]

**a) an object**

b) a special function

c) a standard module

d) a module

> Explanation: An exception is an object that is raised by a function signaling that an unexpected situation has occurred, that the function itself cannot handle.

## 14. \***\*\*\*\*\***\_\_\_\***\*\*\*\*\*** exceptions are raised as a result of an error in opening a particular file. [_______________________ винятки виникають у результаті помилки під час відкриття певного файлу.]

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

## What will be the output of the following Python code? [Який буде вивід наступного коду]

```python
def mk(x):
    def mk1():
        print("Decorated")
        x()
    return mk1
def mk2():
    print("Ordinary")
p = mk(mk2)
p()
```

a)\
 Decorated\
 Decorated

b)\
 Ordinary\
 Ordinary

c)\
 Ordinary\
 Decorated

**d)**\
 **Decorated**\
 **Ordinary**

## In the following Python code, which function is the decorator?

```python
def mk(x):
    def mk1():
        print("Decorated")
        x()
    return mk1
def mk2():
    print("Ordinary")
p = mk(mk2)
p()
```

a) p()\
**b) mk()**\
c) mk1()\
d) mk2()

> Explanation: In the code shown above, the function mk() is the decorator. The function which is getting decorated is mk2(). The return function is given the name p().

## The **\_\_** symbol along with the name of the decorator function can be placed above the definition of the function to be decorated works as an alternate way for decorating a function.

a) #\
b) $\
**c) @**\
d) &

> Explanation: The @ symbol along with the name of the decorator function can be placed above the definition of the function to be decorated works as an alternate way for decorating a function.

## What will be the output of the following Python code?

```python
def ordi():
	print("Ordinary")
ordi
ordi()
```

**a)**\
 **Address**\
 **Ordinary**

b)\
 Error\
 Address

c)\
 Ordinary\
 Ordinary

d)\
 Ordinary\
 Address

> Explanation: The code shown above returns the address on the function ordi first, after which the word “Ordinary” is printed.

## The two snippets of the following Python codes are equivalent.

```python
# CODE 1
@f
def f1():
    print(“Hello”)
# CODE 2
def f1():
    print(“Hello”)
f1 = f(f1)
```

**a) True**\
b) False

> Explanation: The @ symbol can be used as an alternate way to specify a function that needs to be decorated. The output of the codes shown above is the same. Hence they are equivalent. Therefore this statement is true.

## What will be the output of the following Python function?

```python
def f(p, q):
	return p%q
f(0, 2)
f(2, 0)
```

a)\
 0\
 0

b)\
 Zero Division Error\
 Zero Division Error

**c)**\
 **0**\
 **Zero Division Error**

d)\
 Zero Division Error\
 0

> Explanation: The output of f(0, 2) is 0, since o%2 is equal to 0. The output of the f(2, 0) is a Zero Division Error. We can make use of decorators (Ого як притягнуто, шикарні питання, нічо не скажеш 👍🏻) in order to avoid this error.

## What will be the output of the following Python code?

```python
def f(x):
    def f1(a, b):
        print("hello")
        if b==0:
            print("NO")
            return
        return f(a, b)
    return f1
@f
def f(a, b):
    return a%b
f(4,0)
```

**a)**\
 **hello**\
 **NO**

b)\
 hello\
 Zero Division Error

c)\
NO

d)\
hello

> Explanation: In the code shown above, we have used a decorator in order to avoid the Zero Division Error.

## What will be the output of the following Python code?

```python
def f(x):
    def f1(*args, **kwargs):
        print("*"* 5)
        x(*args, **kwargs)
        print("*"* 5)
    return f1
def a(x):
    def f1(*args, **kwargs):
        print("%"* 5)
        x(*args, **kwargs)
        print("%"* 5)
    return f1
@f
@a
def p(m):
    print(m)
p("hello")
```

**a)**\
 **\*\*\*\*\***\
 **%%%%%**\
 **hello**\
 **%%%%%**\
 **\*\*\*\*\***

b)\
Error

c)\
\*\*\*\*\*%%%%%hello%%%%%\*\*\*\*\*

d)\
hello

> Explanation: The code shown above uses multiple decorators.

## The following python code can work with \_\_\_\_ parameters.

```python
def f(x):
    def f1(*args, **kwargs):
           print("Sanfoundry")
           return x(*args, **kwargs)
    return f1
```

a) 2\
b) 1\
**c) any number of**\
d) 0

> Explanation: The code shown above shows a general decorator which can work with any number of arguments.

## What will be the output of the following Python code?

```python
def f(x):
    def f1(*args, **kwargs):
        print("*", 5)
        x(*args, **kwargs)
        print("*", 5)
    return f1
@f
def p(m):
    p(m)
print("hello")
```

a)\
 **\***\
 hello

b)\
 **\***\
 **\***\
 hello

c)\
\*\*\*\*\*

**d)**\
**hello**

> Explanation: In the code shown above, we have not passed any parameter to the function p. Hence the output of this code is: hello.

## A function with parameters cannot be decorated.

a) True\
**b) False**

> Explanation: Any function, irrespective of whether or not it has parameters can be decorated. Hence the statement is false.

## Identify the decorator in the snippet of code shown below.

```python
def sf():
     pass
sf = mk(sf)
@f
def sf():
     return
```

a) @f\
b) f\
c) sf()\
**d) mk**

> Explanation: In the code shown above, @sf is not a decorator but only a decorator line. The ‘@’ symbol represents the application of a decorator. The decorator here is the function mk.

## What will be the output of the following Python code?

```python
class A:
    @staticmethod
    def a(x):
        print(x)
A.a(100)
```

a) Error\
b) Warning\
**c) 100**\
d) No output

> Explanation: The code shown above demonstrates rebinding using a static method. This can be done with or without a decorator. The output of this code will be 100.

## What will be the output of the following Python code?

```python
def d(f):
    def n(*args):
        return '$' + str(f(*args))
    return n
@d
def p(a, t):
    return a + a*t
print(p(100,0))
```

a) 100\
**b) $100**\
c) $0\
d) 0

> Explanation: In the code shown above, the decorator helps us to prefix the dollar sign along with the value. Since the second argument is zero, the output of the code is: $100.

## What will be the output of the following Python code?

```python
def c(f):
    def inner(*args, **kargs):
        inner.co += 1
        return f(*args, **kargs)
    inner.co = 0
    return inner
@c
def fnc():
    pass
if __name__ == '__main__':
    fnc()
    fnc()
    fnc()
    print(fnc.co)
```

a) 4\
**b) 3**\
c) 0\
d) 1

> Explanation: The code shown above returns the number of times a given function has been called. Hence the output of this code is: 3

## What will be the output of the following Python code?

```python
x = ['ab', 'cd']
for i in x:
    i.upper()
print(x)
```

**a) [‘ab’, ‘cd’]**\
b) [‘AB’, ‘CD’]\
c) [None, None]\
d) none of the mentioned

> Explanation: The function upper() does not modify a string in place, it returns a new string which isn’t being stored anywhere.

## What will be the output of the following Python code?

```python
x = ['ab', 'cd']
for i in x:
    x.append(i.upper())
print(x)
```

a) [‘AB’, ‘CD’]\
b) [‘ab’, ‘cd’, ‘AB’, ‘CD’]\
c) [‘ab’, ‘cd’]\
**d) none of the mentioned**

> Explanation: The loop does not terminate as new elements are being added to the list in each iteration.

## What will be the output of the following Python code?

```python
i = 1
while True:
    if i%3 == 0:
        break
    print(i)

    i + = 1
```

a) 1 2\
b) 1 2 3\
**c) error**\
d) none of the mentioned

> Explanation: SyntaxError, there shouldn’t be a space between + and = in +=.

## What will be the output of the following Python code?

```python
i = 1
while True:
    if i%0O7 == 0:
        break
    print(i)
    i += 1
```

**a) 1 2 3 4 5 6**\
b) 1 2 3 4 5 6 7\
c) error\
d) none of the mentioned

> Explanation: Control exits the loop when i becomes 7.

## What will be the output of the following Python code?

```python
i = 5
while True:
    if i%0O11 == 0:
        break
    print(i)
    i += 1
```

a) 5 6 7 8 9 10\
**b) 5 6 7 8**\
c) 5 6\
d) error

> Explanation: 0O11 is an octal number.

## What will be the output of the following Python code?

```python
i = 5
while True:
    if i%0O9 == 0:
        break
    print(i)
    i += 1
```

a) 5 6 7 8\
b) 5 6 7 8 9\
c) 5 6 7 8 9 10 11 12 13 14 15 ….\
**d) error**

> Explanation: 9 isn’t allowed in an octal number.

## What will be the output of the following Python code?

```python
i = 1
while True:
    if i%2 == 0:
        break
    print(i)
    i += 2
```

a) 1\
b) 1 2\
c) 1 2 3 4 5 6 …\
**d) 1 3 5 7 9 11 …**

> Explanation: The loop does not terminate since i is never an even number.

## What will be the output of the following Python code?

```python
i = 2
while True:
    if i%3 == 0:
        break
    print(i)
    i += 2
```

a) 2 4 6 8 10 …\
**b) 2 4**\
c) 2 3\
d) error

> Explanation: The numbers 2 and 4 are printed. The next value of i is 6 which is divisible by 3 and hence control exits the loop.

## What will be the output of the following Python code?

```python
i = 1
while False:
    if i%2 == 0:
        break
    print(i)
    i += 2
```

a) 1\
b) 1 3 5 7 …\
c) 1 2 3 4 …\
**d) none of the mentioned**

> Explanation: Control does not enter the loop because of False.

## What will be the output of the following Python code?

```python
True = False
while True:
    print(True)
    break
```

a) True\
b) False\
c) None\
**d) none of the mentioned**

> Explanation: SyntaxError, True is a keyword and it’s value cannot be changed.

## What will be the output of the following Python code?

```python
i = 0
while i < 5:
    print(i)
    i += 1
    if i == 3:
        break
else:
    print(0)
```

a) 0 1 2 0\
**b) 0 1 2**\
c) error\
d) none of the mentioned

> Explanation: The else part is not executed if control breaks out of the loop.

## What will be the output of the following Python code?

```python
i = 0
while i < 3:
    print(i)
    i += 1
else:
    print(0)
```

a) 0 1 2 3 0\
**b) 0 1 2 0**\
c) 0 1 2\
d) error

> Explanation: The else part is executed when the condition in the while statement is false.

## What will be the output of the following Python code?

```python
x = "abcdef"
while i in x:
    print(i, end=" ")
```

a) a b c d e f\
b) abcdef\
c) i i i i i i …\
**d) error**

> Explanation: NameError, i is not defined.

## What will be the output of the following Python code?

```python
x = "abcdef"
i = "i"
while i in x:
    print(i, end=" ")
```

**a) no output**\
b) i i i i i i …\
c) a a a a a a …\
d) a b c d e f

> Explanation: “i” is not in “abcdef”.

## What will be the output of the following Python code?

```python
x = "abcdef"
i = "a"
while i in x:
    print(i, end = " ")
```

a) no output\
b) i i i i i i …\
**c) a a a a a a …**\
d) a b c d e f

> Explanation: As the value of i or x isn’t changing, the condition will always evaluate to True.

## What will be the output of the following Python code?

```python
x = "abcdef"
i = "a"
while i in x:
    print('i', end = " ")
```

a) no output\
**b) i i i i i i …**\
c) a a a a a a …\
d) a b c d e f

> Explanation: Here i i i i i … printed continuously because as the value of i or x isn’t changing, the condition will always evaluate to True. But also here we use a citation marks on “i”, so, here i treated as a string, not like a variable.

## What will be the output of the following Python code?

```python
x = "abcdef"
i = "a"
while i in x:
    x = x[:-1]
    print(i, end = " ")
```

a) i i i i i i\
**b) a a a a a a**\
c) a a a a a\
d) none of the mentioned

> Explanation: The string x is being shortened by one character in each iteration.

## What will be the output of the following Python code?

```python
x = "abcdef"
i = "a"
while i in x[:-1]:
    print(i, end = " ")
```

a) a a a a a\
b) a a a a a a\
**c) a a a a a a …**\
d) a

> Explanation: String x is not being altered and i is in x[:-1].

## What will be the output of the following Python code?

```python
x = "abcdef"
i = "a"
while i in x:
    x = x[1:]
    print(i, end = " ")
```

a) a a a a a a\
**b) a**\
c) no output\
d) error

> Explanation: The string x is being shortened by one character in each iteration.

## What will be the output of the following Python code?

```python
x = "abcdef"
i = "a"
while i in x[1:]:
    print(i, end = " ")
```

a) a a a a a a\
b) a\
**c) no output**\
d) error

> Explanation: i is not in x[1:].

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in x:
    print(i)
    x.upper()
```

a) a B C D\
**b) a b c d**\
c) A B C D\
d) error

> Explanation: Changes do not happen in-place, rather a new instance of the string is returned.

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in x:
    print(i.upper())
```

a) a b c d\
**b) A B C D**\
c) a B C D\
d) error

> Explanation: The instance of the string returned by upper() is being printed.

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in range(x):
    print(i)
```

a) a b c d\
b) 0 1 2 3\
**c) error**\
d) none of the mentioned

> Explanation: range(str) is not allowed.

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in range(len(x)):
    print(i)
```

a) a b c d\
**b) 0 1 2 3**\
c) error\
d) 1 2 3 4

> Explanation: i takes values 0, 1, 2 and 3.

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in range(len(x)):
    print(i.upper())
```

a) a b c d\
b) 0 1 2 3\
**c) error**\
d) 1 2 3 4

> Explanation: Objects of type int have no attribute upper().

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in range(len(x)):
    i.upper()
print (x)
```

a) a b c d\
b) 0 1 2 3\
**c) error**\
d) none of the mentioned

> Explanation: Objects of type int have no attribute upper().

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in range(len(x)):
    x[i].upper()
print (x)
```

**a) abcd**\
b) ABCD\
c) error\
d) none of the mentioned

> Explanation: Changes do not happen in-place, rather a new instance of the string is returned.

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in range(len(x)):
    i[x].upper()
print (x)
```

a) abcd\
b) ABCD\
**c) error**\
d) none of the mentioned

> Explanation: Objects of type int aren’t subscriptable. However, if the statement was x[i], an error would not have been thrown.

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in range(len(x)):
    x = 'a'
    print(x)
```

a) a\
b) abcd abcd abcd\
**c) a a a a**\
d) none of the mentioned

> Explanation: range() is computed only at the time of entering the loop.

## What will be the output of the following Python code?

```python
x = 'abcd'
for i in range(len(x)):
    print(x)
    x = 'a'
```

a) a\
b) abcd abcd abcd abcd\
c) a a a a\
**d) none of the mentioned**

> Explanation: abcd a a a is the output as x is modified only after ‘abcd’ has been printed once.

## Which of these definitions correctly describes a module? [Яке з цих визначень вірно описує модуль?]

a) Denoted by triple quotes for providing the specification of certain program elements\
**b) Design and implementation of specific functionality to be incorporated into a program**\
c) Defines the specification of how it is to be used\
d) Any program that reuses code

> Explanation: The term “module” refers to the implementation of specific functionality to be incorporated into a program.

## Which of the following is not an advantage of using modules? [Що з перерахованого не є перевагами використання модулів?]

a) Provides a means of reuse of program code\
b) Provides a means of dividing up tasks\
**c) Provides a means of reducing the size of the program**\
d) Provides a means of testing individual parts of the program

> Explanation: The total size of the program remains the same regardless of whether modules are used or not. Modules simply divide the program.

## Program code making use of a given module is called a ______ of the module. [Програмний код, що використовує певний можуль, називається _____ модуля]

**a) Client**\
b) Docstring\
c) Interface\
d) Modularity

> Explanation: Program code making use of a given module is called the client of the module. There may be multiple clients for a module.

## ______ is a string literal denoted by triple quotes for providing the specifications of certain program elements. [_____ - рядковий літерал, обмежений потрійними лапками, для впровадження специфікацій певних програмних елементів]

a) Interface\
b) Modularity\
c) Client\
**d) Docstring**

>Explanation: Docstring used for providing the specifications of program elements.

## Which of the following is true about top-down design process? [Що з наведеного є правдивим про процес дизайнування зверху-вниз]

a) The details of a program design are addressed before the overall design\
b) Only the details of the program are addressed\
**c) The overall design of the program is addressed before the details**\
d) Only the design of the program is addressed

> Explanation: Top-down design is an approach for deriving a modular design in which the overall design.

## In top-down design every module is broken into same number of submodules. [У дизайні зверху-вниз кожен модуль розбитий на однакову кількість підмодулів]

a) True\
**b) False**

>Explanation: In top-down design every module can even be broken down into different number of submodules.

## All modular designs are because of a top-down design process. [Всі модульні дизайни породжені процесом дизайнування зверху-вниз]

a) True\
**b) False**

>Explanation: The details of the program can be addressed before the overall design too. Hence, all modular designs are not because of a top-down design process.

## What will be the output of the following Python code?

```python
#mod1
def change(a):
    b=[x*2 for x in a]
    print(b)
#mod2
def change(a):
    b=[x*x for x in a]
    print(b)
from mod1 import change
from mod2 import change
#main
s=[1,2,3]
change(s)
```

a) [2,4,6]

b) [1,4,9]

c)\
[2,4,6]\
[1,4,9]

**d) There is a name clash**

>Explanation: A name clash is when two different entities with the same identifier become part of the same scope. Since both the modules have the same function name, there is a name clash. (code snippet is idiotic, main should begin with imports, not after)

## Which of the following isn’t true about main modules? [Що з наведеного не є правдивим про модулі]

a) When a python file is directly executed, it is considered main module of a program\
b) Main modules may import any number of modules\
c) Special name given to main modules is: \_\_main\_\_\
**d) Other main modules can import main modules**

> Explanation: Main modules are not meant to be imported into other modules.

## Which of the following is not a valid namespace? [Що з наведеного не є коректним простором імен]

a) Global namespace\
**b) Public namespace**\
c) Built-in namespace\
d) Local namespace

>Explanation: During a Python program execution, there are as many as three namespaces – built-in namespace, global namespace and local namespace.

## Which of the following is false about “import modulename” form of import? [Що з неведеного невірно про форму імпорту “import modulename”]

**a) The namespace of imported module becomes part of importing module**\
b) This form of import prevents name clash\
c) The namespace of imported module becomes available to importing module\
d) The identifiers in module are accessed as: modulename.identifier

> Explanation: In the “import modulename” form of import, the namespace of imported module becomes available to, but not part of, the importing module.

## Which of the following is false about “from-import” form of import? [Що з неведеного невірно про форму імпорту “from-import”]

a) The syntax is: from modulename import identifier\
**b) This form of import prevents name clash**\
c) The namespace of imported module becomes part of importing module\
d) The identifiers in module are accessed directly as: identifier

> Explanation: In the “from-import” form of import, there may be name clashes because names of the imported identifiers aren’t specified along with the module name.

##  Which of the statements about modules is false? [Що з наведеного про модулі невірно]

a) In the “from-import” form of import, identifiers beginning with two underscores are private and aren’t imported\
b) dir() built-in function monitors the items in the namespace of the main module\
**c) In the “from-import” form of import, all identifiers regardless of whether they are private or public are imported**\
d) When a module is loaded, a compiled version of the module with file extension .pyc is automatically produced

> Explanation: In the “from-import” form of import, identifiers beginning with two underscores are private and aren’t imported.

## What will be the output of the following Python code?

```python
from math import factorial
print(math.factorial(5))
```

a) 120\
b) Nothing is printed\
c) Error, method factorial doesn’t exist in math module\
**d) Error, the statement should be: print(factorial(5))**

>Explanation: In the “from-import” form of import, the imported identifiers (in this case factorial()) aren’t specified along with the module name.

## What is the order of namespaces in which Python looks for an identifier?

a) Python first searches the global namespace, then the local namespace and finally the built-in namespace\
**b) Python first searches the local namespace, then the global namespace and finally the built-in namespace**\
c) Python first searches the built-in namespace, then the global namespace and finally the local namespace\
d) Python first searches the built-in namespace, then the local namespace and finally the global namespace

# Section 6

## Topic 18. While and For Loops – 4

### 1. What will be the output of the following Python code?

```python
x = 123
for i in x:
    print(i)
```

- a) 1 2 3
- b) 123
- **c) error**
- d) none of the mentioned

> Objects of type int are not iterable.

### 2. What will be the output of the following Python code?

```python
d = {0: 'a', 1: 'b', 2: 'c'}
for i in d:
    print(i)
```

- **a) 0 1 2**
- b) a b c
- c) 0 a 1 b 2 c
- d) none of the mentioned

> Loops over the keys of the dictionary.

### 3. What will be the output of the following Python code?

```python
d = {0: 'a', 1: 'b', 2: 'c'}
for x, y in d:
    print(x, y)
```

- a) 0 1 2
- b) a b c
- c) 0 a 1 b 2 c
- **d) none of the mentioned**

> Error, objects of type int aren’t iterable.

### 4. What will be the output of the following Python code?

```python
d = {0: 'a', 1: 'b', 2: 'c'}
for x, y in d.items():
    print(x, y)
```

- a) 0 1 2
- b) a b c
- **c) 0 a 1 b 2 c**
- d) none of the mentioned

> Loops over key, value pairs.

### 5. What will be the output of the following Python code?

```python
d = {0: 'a', 1: 'b', 2: 'c'}
for x in d.keys():
    print(d[x])
```

- a) 0 1 2
- **b) a b c**
- c) 0 a 1 b 2 c
- d) none of the mentioned

> Loops over the keys and prints the values.

### 6. What will be the output of the following Python code?

```python
d = {0: 'a', 1: 'b', 2: 'c'}
for x in d.values():
    print(x)
```

- a) 0 1 2
- **b) a b c**
- c) 0 a 1 b 2 c
- d) none of the mentioned

> Loops over the values.

### 7. What will be the output of the following Python code?

```python
d = {0: 'a', 1: 'b', 2: 'c'}
for x in d.values():
    print(d[x])
```

- a) 0 1 2
- b) a b c
- c) 0 a 1 b 2 c
- **d) none of the mentioned**

> Causes a KeyError.

### 8. What will be the output of the following Python code?

```python
d = {0, 1, 2}
for x in d.values():
    print(x)
```

- a) 0 1 2
- b) None None None
- **c) error**
- d) none of the mentioned

> Objects of type set have no attribute values.

### 9. What will be the output of the following Python code?

```python
d = {0, 1, 2}
for x in d:
    print(x)
```

- **a) 0 1 2**
- b) {0, 1, 2} {0, 1, 2} {0, 1, 2}
- c) error
- d) none of the mentioned

> Loops over the elements of the set and prints them.

### 10. What will be the output of the following Python code?

```python
d = {0, 1, 2}
for x in d:
    print(d.add(x))
```

- a) 0 1 2
- b) 0 1 2 0 1 2 0 1 2 …
- **c) None None None**
- d) None of the mentioned

> Variable x takes the values 0, 1 and 2. set.add() returns None which is printed.

### 11. What will be the output of the following Python code?

```python
for i in range(0):
    print(i)
```

- a) 0
- **b) no output**
- c) error
- d) none of the mentioned

> range(0) is empty.

## Topic 19. While and For Loops – 5

### 1. What will be the output of the following Python code?

```python
for i in range(2.0):
    print(i)
```

- a) 0.0 1.0
- b) 0 1
- **c) error**
- d) none of the mentioned

> Object of type float cannot be interpreted as an integer.

### 2. What will be the output of the following Python code?

```python
for i in range(int(2.0)):
    print(i)
```

- a) 0.0 1.0
- **b) 0 1**
- c) error
- d) none of the mentioned

> range(int(2.0)) is the same as range(2).

### 3. What will be the output of the following Python code?

```python
for i in range(float('inf')):
    print (i)
```

- a) 0.0 0.1 0.2 0.3 …
- b) 0 1 2 3 …
- c) 0.0 1.0 2.0 3.0 …
- **d) none of the mentioned**

> Error, objects of type float cannot be interpreted as an integer.

### 4. What will be the output of the following Python code?

```python
for i in range(int(float('inf'))):
    print (i)
```

- a) 0.0 0.1 0.2 0.3 …
- b) 0 1 2 3 …
- c) 0.0 1.0 2.0 3.0 …
- **d) none of the mentioned**

> OverflowError, cannot convert float infinity to integer.

### 5. What will be the output of the following Python code snippet?

```python
for i in [1, 2, 3, 4][::-1]:
    print (i)
```

- a) 1 2 3 4
- **b) 4 3 2 1**
- c) error
- d) none of the mentioned

> [::-1] reverses the list.

### 6. What will be the output of the following Python code snippet?

```python
for i in ''.join(reversed(list('abcd'))):
    print (i)
```

- a) a b c d
- **b) d c b a**
- c) error
- d) none of the mentioned

> ‘‘.join(reversed(list(‘abcd’))) reverses a string.

### 7. What will be the output of the following Python code snippet?

```python
for i in 'abcd'[::-1]:
    print (i)
```

- a) a b c d
- **b) d c b a**
- c) error
- d) none of the mentioned

> [::-1] reverses the string.

### 8. What will be the output of the following Python code snippet?

```python
for i in '':
    print (i)
```

- a) None
- **b) (nothing is printed)**
- c) error
- d) none of the mentioned

> The string does not have any character to loop over.

### 9. What will be the output of the following Python code snippet?

```python
x = 2
for i in range(x):
    x += 1
    print (x)
```

- a) 0 1 2 3 4 …
- b) 0 1
- **c) 3 4**
- d) 0 1 2 3

> Variable x is incremented and printed twice.

### 10. What will be the output of the following Python code snippet?

```python
x = 2
for i in range(x):
    x -= 2
    print (x)
```

- a) 0 1 2 3 4 …
- **b) 0 -2**
- c) 0
- d) error

> The loop is entered twice.

## Topic 20. While and For Loops – 6

### 1. What will be the output of the following Python code?

```python
for i in range(10):
    if i == 5:
        break
    else:
        print(i)
else:
    print("Here")
```

- a) 0 1 2 3 4 Here
- b) 0 1 2 3 4 5 Here
- **c) 0 1 2 3 4**
- d) 1 2 3 4 5

> The else part is executed if control doesn’t break out of the loop.

### 2. What will be the output of the following Python code?

```python
for i in range(5):
    if i == 5:
        break
    else:
        print(i)
else:
    print("Here")
```

- **a) 0 1 2 3 4 Here**
- b) 0 1 2 3 4 5 Here
- c) 0 1 2 3 4
- d) 1 2 3 4 5

> The else part is executed if control doesn’t break out of the loop.

### 3. What will be the output of the following Python code?

```python
x = (i for i in range(3))
for i in x:
    print(i)
```

- **a) 0 1 2**
- b) error
- c) 0 1 2 0 1 2
- d) none of the mentioned

> The first statement creates a generator object.

### 4. What will be the output of the following Python code?

```python
x = (i for i in range(3))
for i in x:
    print(i)
for i in x:
    print(i)
```

- **a) 0 1 2**
- b) error
- c) 0 1 2 0 1 2
- d) none of the mentioned

> We can loop over a generator object only once.

### 5. What will be the output of the following Python code?

```python
string = "my name is x"
for i in string:
    print (i, end=", ")
```

- **a) m, y, , n, a, m, e, , i, s, , x,**
- b) m, y, , n, a, m, e, , i, s, , x
- c) my, name, is, x,
- d) error

> Variable i takes the value of one character at a time.

### 6. What will be the output of the following Python code?

```python
string = "my name is x"
for i in string.split():
    print (i, end=", ")
```

- a) m, y, , n, a, m, e, , i, s, , x,
- b) m, y, , n, a, m, e, , i, s, , x
- **c) my, name, is, x,**
- d) error

> Variable i takes the value of one word at a time.

### 7. What will be the output of the following Python code snippet?

```python
a = [0, 1, 2, 3]
for a[-1] in a:
    print(a[-1])
```

- a) 0 1 2 3
- **b) 0 1 2 2**
- c) 3 3 3 3
- d) error

> The value of a[-1] changes in each iteration.

### 8. What will be the output of the following Python code snippet?

```python
a = [0, 1, 2, 3]
for a[0] in a:
    print(a[0])
```

- **a) 0 1 2 3**
- b) 0 1 2 2
- c) 3 3 3 3
- d) error

> The value of a[0] changes in each iteration. Since the first value that it takes is itself, there is no visible error in the current example.

### 9. What will be the output of the following Python code snippet?

```python
a = [0, 1, 2, 3]
i = -2
for i not in a:
    print(i)
    i += 1
```

- a) -2 -1
- b) 0
- **c) error**
- d) none of the mentioned

> SyntaxError, not in isn’t allowed in for loops.

### 10. What will be the output of the following Python code snippet?

```python
string = "my name is x"
for i in ' '.join(string.split()):
    print (i, end=", ")
```

- **a) m, y, , n, a, m, e, , i, s, , x,**
- b) m, y, , n, a, m, e, , i, s, , x
- c) my, name, is, x,
- d) error

> Variable i takes the value of one character at a time.

### Topic 21. Strings – 1

### 1. What will be the output of the following Python statement?

```
    >>>"a"+"bc"
```

- a) a
- b) bc
- c) bca
- **d) abc**

> - operator is concatenation operator.

### 2. What will be the output of the following Python statement?

    >>>"abcd"[2:]

- a) a
- b) ab
- **c) cd**
- d) dc

> Slice operation is performed on string.

### 3. The output of executing string.ascii_letters can also be achieved by: [Результату виконання string.ascii_letters також можна досягнути за допомогою:]

- a) string.ascii_lowercase_string.digits
- **b) string.ascii_lowercase+string.ascii_uppercase**
- c) string.letters
- d) string.lowercase_string.uppercase

> Explanation: Execute in shell and check.

))))))0)

### 4. What will be the output of the following Python code?

    >>> str1 = 'hello'

    >>> str2 = ','

    >>> str3 = 'world'

    >>> str1[-1:]

- a) olleh
- b) hello
- c) h
- **d) o**

> -1 corresponds to the last index.

### 5. What arithmetic operators cannot be used with strings? [Які арифметичні оператори не можна застосовувати до строк?]

- a) +
- b) \*
- **c) -**
- d) All of the mentioned

> '+' is used to concatenate and \* is used to multiply strings.

### 6. What will be the output of the following Python code?

    >>>print (r"\nhello")

- a) a new line and hello
- **b) \nhello**
- c) the letter r and then hello
- d) error

> When prefixed with the letter ‘r’ or ‘R’ a string literal becomes a raw string and the escape sequences such as \n are not converted.

### 7. What will be the output of the following Python statement?

    >>>print('new' 'line')

- a) Error
- b) Output equivalent to print ‘new\nline’
- **c) newline**
- d) new line

> String literal separated by whitespace are allowed. They are concatenated.

### 8. What will be the output of the following Python statement?

    >>> print('x\97\x98')

- a) Error
- b)
  97
  98
- **c) x\97**
- d) \x97\x98

> \x is an escape sequence that means the following 2 digits are a hexadecimal number encoding a character.

### 9. What will be the output of the following Python code?

    >>>str1="helloworld"

    >>>str1[::-1]

- **a) dlrowolleh**
- b) hello
- c) world
- d) helloworld

> Explanation: Execute in shell to verify.

lol

### 10. What will be the output of the following Python code?

```python
print(0xA + 0xB + 0xC)
```

- a) 0xA0xB0xC
- b) Error
- c) 0x22
- **d) 33**

> 0xA and 0xB and 0xC are hexadecimal integer literals representing the decimal values 10, 11 and 12 respectively. There sum is 33.

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

> Explanation: self.o1 was never created.

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

> Explanation: Id in this case will be the attribute of the class.

## 3. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]

```
>>>example = "snow world"
>>>print("%s" % example[4:7])
```

**a) wo**

b) world

c) sn

d) rl

> Explanation: Execute in the shell and verify.

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

> Explanation: Strings cannot be modified.

## 5. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]

```
>>>max("what are you")
```

a) error

b) u

c) t

**d) y**

> Explanation: Max returns the character with the highest ascii value.

## 6. Given a string example=”hello” what is the output of example.count(‘l’)? [За допомогою рядка example=”hello” що виводить example.count(‘l’)?]

**a) 2**

b) 1

c) None

d) 0

> Explanation: l occurs twice in hello.

## 7. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]

```
>>>example = "helle"
>>>example.find("e")
```

a) Error

b) -1

**c) 1**

d) 0

> > Explanation: Returns lowest index.

## 8. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]

```
>>>example = "helle"
>>>example.rfind("e")
```

a) -1

**b) 4**

c) 3

d) 1

> Explanation: Returns highest index.

## 9. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]

```
>>>example="helloworld"
>>>example[::-1].startswith("d")
```

a) dlrowolleh

**b) True**

c) -1

d) None

> Explanation: Starts with checks if the given string starts with the parameter that is passed.

## 10. To concatenate two strings to a third what statements are applicable? [Які твердження застосовні для з’єднання двох рядків з третім?]

a) s3 = s1 . s2

b) s3 = s1.add(s2)

**c) s3 = s1.\_\_add\_\_(s2)**

d) s3 = s1 \* s2

> Explanation: **add** is another method that can be used for concatenation.

## 1. What will be the output of the following Python statement?[Яким буде результат наступного оператора Python?]

```
>>>chr(ord('A'))
```

**a) A**

b) B

c) a

d) Error

> Explanation: Execute in shell to verify.

## 2. What will be the output of the following Python statement?[Яким буде результат наступного оператора Python?]

```
>>>print(chr(ord('b')+1))
```

a) a

b) b

**c) c**

d) A

> Explanation: Execute in the shell to verify.

## 3. Which of the following statement prints hello\example\test.txt? [Який із наведених нижче операторів друкує hello\example\test.txt?]

a) print(“hello\example\test.txt”)

**b) print(“hello\\\\example\\\\test.txt”)**

c) print(“hello\”example\”test.txt”)

d) print(“hello”\example”\test.txt”)

> Explanation: \is used to indicate that the next \ is not an escape sequence.

## 4. Suppose s is “\t\tWorld\n”, what is s.strip()? [Припустимо, s – це “\t\tWorld\n”, а що таке s.strip()?]

a) \t\tWorld\n

b) \t\tWorld\n

c) \t\tWORLD\n

**d) World**

> Explanation: Execute help(string.strip) to find details.

## 5. The format function, when applied on a string returns [Функція форматування при застосуванні до рядка повертає] \***\*\_\_\_\*\***

a) Error

b) int

c) bool

**d) str**

> Explanation: Format function returns a string.

## 6. What will be the output of the “hello” +1+2+3?[Яким буде результат “hello” +1+2+3?]

a) hello123

b) hello

**c) Error**

d) hello6

> Explanation: Cannot concatenate str and int objects.

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

> Explanation: Execute in the shell.

## 8. What will be the output of the following Python statement?(python 3.xx) [Яким буде результат наступного оператора Python?(python 3.xx)]

```
>>>print(format("Welcome", "10s"), end = '#')
>>>print(format(111, "4d"), end = '#')
>>>print(format(924.656, "3.2f"))
```

a) Welcome# 111#924.66

b) Welcome#111#924.66

c) Welcome#111#.66

**d) Welcome # 111#924.66**

> Explanation: Execute in the shell to verify.

## 9. What will be displayed by print(ord(‘b’) – ord(‘a’))? [Що буде відображатися print(ord(‘b’) – ord(‘a’))?]

a) 0

**b) 1**

c) -1

d) 2

> Explanation: ASCII value of b is one more than a. Hence the output of this code is 98-97, which is equal to 1.

## 10. Say s=”hello” what will be the return value of type(s)? [10. Нехай s=”hello”, яке буде значення типу(ів)?]

a) int

b) bool

**c) str**

d) String

> Explanation: str is used to represent strings in python.

## 1. What is “Hello”.replace(“l”, “e”)[Що таке “Hello”.replace(“l”, “e”)]?

**a) Heeeo**

b) Heelo

c) Heleo

d) None

> Explanation: Execute in shell to verify.

## 2. To retrieve the character at index 3 from string s=”Hello” what command do we execute (multiplellowed)[Щоб отримати символ з індексом 3 з рядка s=”Hello”, яку команду ми виконуємо (допускається декілька)]?

a) s[]

b) s.getitem(3)

**c) s.\_\_getitem\_\_(3)**

d) s.getItem(3)

> Explanation: \_\_getitem(..) can be used to get character at index specified as parameter.

## 3. To return the length of string s what command do we execute[Щоб повернути довжину рядка s, яку команду ми виконуємо]?

**a) s.\_\_len\_\_()**

b) len(s)

c) size(s)

d) s.size()

> Explanation: Execute in shell to verify.

## 4. If a class defines the **str**(self) method, for an object obj for the class, you can use which command to invoke the \_\_str\_\_ method.[Якщо клас визначає метод __str__(self), для об’єкта obj для класу можна використовувати команду, щоб викликати метод \_\_str\_\_]

a) obj.\_\_str\_\_()

b) str(obj)

c) print obj

**d) all of the mentioned**

> Explanation: Execute in shell to verify.

## 5. To check whether string s1 contains another string s2, use [Щоб перевірити, чи містить рядок s1 інший рядок s2, використовуйте]**\_\_\_\_**

**a) s1.\_\_contains\_\_(s2)**

b) s2 in s1

c) s1.contains(s2)

d) si.in(s2)

> Explanation: s2 in s1 works in the same way as calling the special function \_\_contains\_\_ .

## 6. Suppose i is 5 and j is 4, i + j is same as [Припустимо, i дорівнює 5, а j дорівнює 4, i + j те саме, що] **\_\_\_\_**

a) i.\_\_add(j)

**b) i.\_\_add\_\_(j)**

c) i.\_\_Add(j)

d) i.\_\_ADD(j)

> Explanation: Execute in shell to verify.

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

> Explanation: Execute in the shell objects cannot have same id, however in the case of strings its different.

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

> Explanation: Execute in the shell to verify.

## 9. What function do you use to read a string?[Яку функцію ви використовуєте для читання рядка?]

**a) input(“Enter a string”)**

b) eval(input(“Enter a string”))

c) enter(“Enter a string”)

d) eval(enter(“Enter a string”))

> Explanation: Execute in shell to verify.

## 10. Suppose x is 345.3546, what is format(x, “10.3f”) (_ indicates space).[Припустимо, x дорівнює 345,3546, що таке format(x, “10.3f”) (_ означає пробіл)]

a) \_\_345.355

**b) \_\_\_345.355**

c) \_\_\_\_345.355

d) \_\_\_\_\_345.354

> Explanation: Execute in the shell to verify.

## 1. What will be the output of the following Python code? [Що буде результатом наступного коду Python?]

```
print("abc DEF".capitalize())
```

a) abc def

b) ABC DEF

**c) Abc def**

d) Abc Def

> Explanation: The first letter of the string is converted to uppercase and the others are converted to lowercase.
> advertisement

## 2. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]

```
print("abc. DEF".capitalize())
```

a) abc. def

b) ABC. DEF

**c) Abc. def**

d) Abc. Def

> Explanation: The first letter of the string is converted to uppercase and the others are converted to lowercase.

## 3. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]

```
print("abcdef".center())
```

a) cd

b) abcdef

**c) error**

d) none of the mentioned

> Explanation: The function center() takes at least one parameter.

## 4. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]

```
print("abcdef".center(0))
```

a) cd

**b) abcdef**

c) error

d) none of the mentioned

> Explanation: The entire string is printed when the argument passed to center() is less than the length of the string.

## 5. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]

```
print('*', "abcdef".center(7), '*')
```

a) _ abcdef _

**b) \* abcdef \***

c) _abcdef _

d) _ abcdef_

> Explanation: Padding is done towards the left-hand-side first when the final string is of odd length. Extra spaces are present since we haven’t overridden the value of sep.

## 6. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]

```
print('*', "abcdef".center(7), '*', sep='')
```

a) _ abcdef _

b) _ abcdef _

c) _abcdef _

**d) \* abcdef\***

> Explanation: Padding is done towards the left-hand-side first when the final string is of odd length.

## 7. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]

```
print('*', "abcde".center(6), '*', sep='')
```

a) _ abcde _

b) _ abcde _

**c) \*abcde \***

d) _ abcde_

> Explanation: Padding is done towards the right-hand-side first when the final string is of even length.

## 8. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]

```
print("abcdef".center(7, 1))
```

a) 1abcdef

b) abcdef1

c) abcdef

**d) error**

> Explanation: TypeError, the fill character must be a character, not an int.

## 9. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]

```
print("abcdef".center(7, '1'))
```

**a) 1abcdef**

b) abcdef1

c) abcdef

d) error

> Explanation: The character ‘1’ is used for padding instead of a space.

## 10. What will be the output of the following Python code?[Що буде результатом наступного коду Python?]

```
print("abcdef".center(10, '12'))
```

a) 12abcdef12

b) abcdef1212

c) 1212abcdef

**d) error**

> Explanation: The fill character must be exactly one character long.

# Section 8

## 1. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("xyyzxyzxzxyy".count('yy'))
```

**a) 2**

b) 0

c) error

d) none of the mentioned

> Explanation: Counts the number of times the substring ‘yy’ is present in the given string.

## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("xyyzxyzxzxyy".count('yy', 1))
```

**a) 2**

b) 0

c) 1

d) none of the mentioned

> Explanation: Counts the number of times the substring ‘yy’ is present in the given string, starting from position 1.

## 3. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("xyyzxyzxzxyy".count('yy', 2))
```

a) 2

b) 0

**c) 1**

d) none of the mentioned

> Explanation: Counts the number of times the substring ‘yy’ is present in the given string, starting from position 2.

## 4. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("xyyzxyzxzxyy".count('xyy', 0, 100))
```

**a) 2**

b) 0

c) 1

d) error

> Explanation: An error will not occur if the end value is greater than the length of the string itself.

## 5. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("xyyzxyzxzxyy".count('xyy', 2, 11))
```

a) 2

**b) 0**

c) error

d) none of the mentioned

> Explanation: Counts the number of times the substring ‘xyy’ is present in the given string, starting from position 2 and ending at position 11.

## 6. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("xyyzxyzxzxyy".count('xyy', -10, -1))
```

a) 2

**b) 0**

c) error

d) none of the mentioned

> Explanation: Counts the number of times the substring ‘xyy’ is present in the given string, starting from position 2 and ending at position 11.

## 7. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print('abc'.encode())
```

a) abc

b) ‘abc’

**c) b’abc’**

d) h’abc’

> Explanation: A bytes object is returned by encode.

## 8. What is the default value of encoding in encode()? [Яке значення кодування за замовчуванням у encode()?]

a) ascii

b) qwerty

**c) utf-8**

d) utf-16

> Explanation: The default value of encoding is utf-8.

## 9. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("xyyzxyzxzxyy".endswith("xyy"))
```

a) 1

**b) True**

c) 3

d) 2

> Explanation: The function returns True if the given string ends with the specified substring.

## 10. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("xyyzxyzxzxyy".endswith("xyy", 0, 2))
```

a) 0

b) 1

c) True

**d) False**

> Explanation: The function returns False if the given string does not end with the specified substring.

## 1. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("ab\tcd\tef".expandtabs())
```

**a) ab  cd  ef**

b) abcdef

c) ab\tcd\tef

d) ab cd ef

> Explanation: Each \t is converted to 8 blank spaces by default.

## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("ab\tcd\tef".expandtabs(4))
```

a) ab  cd  ef

b) abcdef

c) ab\tcd\tef

**d) ab cd ef**

> Explanation: Each \t is converted to 4 blank spaces.

## 3. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("ab\tcd\tef".expandtabs('+'))
```

a) ab+cd+ef

b) ab++++++++cd++++++++ef

c) ab cd ef

**d) none of the mentioned**

> Explanation: TypeError, an integer should be passed as an argument.

## 4. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("abcdef".find("cd") == "cd" in "abcdef")
```

a) True

**b) False**

c) Error

d) None of the mentioned

> Explanation: The function find() returns the position of the sunstring in the given string whereas the in keyword returns a value of Boolean type.

## 5. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("abcdef".find("cd"))
```

a) True

**b) 2**

c) 3

d) None of the mentioned

> Explanation: The first position in the given string at which the substring can be found is returned.

## 6. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("ccdcddcd".find("c"))
```

a) 4

**b) 0**

c) Error

d) True

> Explanation: The first position in the given string at which the substring can be found is returned.

## 7. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("Hello {0} and {1}".format('foo', 'bin'))
```

**a) Hello foo and bin**

b) Hello {0} and {1} foo bin

c) Error

d) Hello 0 and 1

> Explanation: The numbers 0 and 1 represent the position at which the strings are present.

## 8. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("Hello {1} and {0}".format('bin', 'foo'))
```

**a) Hello foo and bin**

b) Hello bin and foo

c) Error

d) None of the mentioned

> Explanation: The numbers 0 and 1 represent the position at which the strings are present.

## 9. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("Hello {} and {}".format('foo', 'bin'))
```

**a) Hello foo and bin**

b) Hello {} and {}

c) Error

d) Hello and

> Explanation: It is the same as Hello {0} and {1}.

## 10. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("Hello {name1} and {name2}".format('foo', 'bin'))
```

a) Hello foo and bin

b) Hello {} and {}

**c) Error**

d) Hello and

> Explanation: The arguments passed to the function format aren’t keyword arguments.

## 1. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("Hello {name1} and {name2}".format(name1='foo', name2='bin'))
```

**a) Hello foo and bin**

b) Hello {name1} and {name2}

c) Error

d) Hello and

> Explanation: The arguments are accessed by their names.

## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("Hello {0!r} and {0!s}".format('foo', 'bin'))
```

a) Hello foo and foo

**b) Hello ‘foo’ and foo**

c) Hello foo and ‘bin’

d) Error

> Explanation: !r causes the characters ‘ or ” to be printed as well.

## 3. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("Hello {0} and {1}".format(('foo', 'bin')))
```

a) Hello foo and bin

b) Hello (‘foo’, ‘bin’) and (‘foo’, ‘bin’)

**c) Error**

d) None of the mentioned

> Explanation: IndexError, the tuple index is out of range.

## 4. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print("Hello {0[0]} and {0[1]}".format(('foo', 'bin')))
```

**a) Hello foo and bin**

b) Hello (‘foo’, ‘bin’) and (‘foo’, ‘bin’)

c) Error

d) None of the mentioned

> Explanation: The elements of the tuple are accessed by their indices.

## 5. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('The sum of {0} and {1} is {2}'.format(2, 10, 12))
```

**a) The sum of 2 and 10 is 12**

b) Error

c) The sum of 0 and 1 is 2

d) None of the mentioned

> Explanation: The arguments passed to the function format can be integers also.

## 6. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('The sum of {0:b} and {1:x} is {2:o}'.format(2, 10, 12))
```

a) The sum of 2 and 10 is 12

**b) The sum of 10 and a is 14**

c) The sum of 10 and a is c

d) Error

> Explanation: 2 is converted to binary, 10 to hexadecimal and 12 to octal.

## 7. . What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('{:,}'.format(1112223334))
```

a) 1,112,223,334

b) 111,222,333,4

c) 1112223334

d) Error

> Explanation: A comma is added after every third digit from the right.

## 8. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('{:,}'.format('1112223334'))
```

a) 1,112,223,334

b) 111,222,333,4

c) 1112223334

**d) Error**

> Explanation: An integer is expected.

## 9. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('{:$}'.format(1112223334))
```

a) 1,112,223,334

b) 111,222,333,4

c) 1112223334

**d) Error**

> Explanation: $ is an invalid format code.

## 10. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('{:#}'.format(1112223334))
```

a) 1,112,223,334

b) 111,222,333,4

**c) 1112223334**

d) Error

> Explanation: The number is printed as it is.

## 1. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print('{0:.2}'.format(1/3))
```

a) 0.333333

.**b) 0.33**

c) 0.333333:.2

d) Error

> Explanation: .2 specifies the precision.

## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print('{0:.2%}'.format(1/3))
```

a) 0.33
b) 0.33%
**c) 33.33%**
d) 33%

> Explanation: The symbol % is used to represent the result of an expression as a percentage.

## 3. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print('ab12'.isalnum())
```

**a) True**
b) False
c) None
d) Error

> Explanation: The string has only letters and digits.

## 4. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print('ab,12'.isalnum()
```

a) True
**b) False**
c) None
d) Error

> Explanation: The character , is not a letter or a digit.

## 5. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print('ab'.isalpha())
```

**a) True**

b) False

c) None

d) Error

> Explanation: The string has only letters.

## 6. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```
print('a B'.isalpha())
```

a) True

**b) False**

c) None

d) Error

> Explanation: Space is not a letter.

## 7. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('0xa'.isdigit())
```

a) True

**b) False**

c) None

d) Error

> Explanation: Hexadecimal digits aren’t considered as digits (a-f).

## 8. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print(''.isdigit())
```

a) True

**b) False**

c) None

d) Error

> Explanation: If there are no characters then False is returned.

## 9. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('my_string'.isidentifier())
```

**a) True**

b) False

c) None

d) Error

> Explanation: It is a valid identifier.

## 10. What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('__foo__'.isidentifier())
```

**a) True**

b) False

c) None

d) Error

> Explanation: It is a valid identifier.

# Section 9

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('for'.isidentifier())`

**a) True**\
b) False \
c) None \
d) Error

> Explanation: Even keywords are considered as valid identifiers.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abc'.islower())`

**a) True**\
b) False\
c) None\
d) Error

> Explanation: There are no uppercase letters.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('a@ 1,'.islower())`

**a) True**\
b) False\
c) None\
d) Error

> Explanation: There are no uppercase letters.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('11'.isnumeric())`

**a) True**\
b) False\
c) None\
d) Error

> Explanation: All the character are numeric.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('1.1'.isnumeric())`

a) True\
**b) False**\
c) None\
d) Error

> Explanation: The character . is not a numeric character.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('1@ a'.isprintable())`

**a) True**\
b) False\
c) None\
d) Error

> Explanation: All those characters are printable.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print(''''''.isspace())`

a) True\
**b) False**\
c) None\
d) Error

> Explanation: None.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('\t'.isspace())`

**a) True**\
b) False\
c) None\
d) Error

> Explanation: Tab Spaces are considered as spaces.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('HelloWorld'.istitle())`

a) True\
**b) False**\
c) None\
d) Error

> Explanation: The letter W is uppercased.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('Hello World'.istitle())`

**a) True**\
b) False\
c) None\
d) Error

> Explanation: It is in title form.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('Hello!2@#World'.istitle())`

**a) True**\
b) False\
c) None\
d) Error

> Explanation: It is in the form of a title.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('1Rn@'.lower())`

a) n\
**b) 1rn@**\
c) rn\
d) r

> Explanation: Uppercase letters are converted to lowercase. The other characters are left unchanged.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

```
print('''
 \tfoo'''.lstrip())
```

a) \tfoo\
**b) foo**\
c)   foo\
d) none of the mentioned

> Explanation: All leading whitespace is removed.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('xyyzxxyxyy'.lstrip('xyy'))`

a) error\
**b) zxxyxyy**\
c) z\
d) zxxy

> Explanation: The leading characters containing xyy are removed.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('xyxxyyzxxy'.lstrip('xyy'))`

**a) zxxy**\
b) xyxxyyzxxy\
c) xyxzxxy\
d) none of the mentioned

> Explanation: All combinations of the characters passed as an argument are removed from the left hand side.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('cba'.maketrans('abc', '123'))`

**a) {97: 49, 98: 50, 99: 51}**\
b) {65: 49, 66: 50, 67: 51}\
c) 321\
d) 123

> Explanation: A translation table is returned by maketrans.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('a'.maketrans('ABC', '123'))`

a) {97: 49, 98: 50, 99: 51}\
**b) {65: 49, 66: 50, 67: 51}**\
c) {97: 49}\
d) 1

> Explanation: maketrans() is a static method so it's behaviour does not depend on the object from which it is being called.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcdef'.partition('cd'))`

a) ('ab', 'ef')\
b) ('abef')\
**c) ('ab', 'cd', 'ef')**\
d) 1

> Explanation: The string is split into three parts by partition.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcdefcdgh'.partition('cd'))`

a) ('ab', 'cd', 'ef', 'cd', 'gh')\
**b) ('ab', 'cd', 'efcdgh')**\
c) ('abcdef', 'cd', 'gh')\
d) error

> Explanation: The string is partitioned at the point where the separator first appears.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcd'.partition('cd'))`

**a) ('ab', 'cd', ”)**\
b) ('ab', 'cd')\
c) error\
d) none of the mentioned

> Explanation: The last item is a null string.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('cd'.partition('cd'))`

a) ('cd')\
b) (”)\
c) ('cd', ”, ”)\
**d) (”, 'cd', ”)**

> Explanation: The entire string has been passed as the separator hence the first and the last item of the tuple returned are null strings.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abef'.partition('cd'))`

a) ('abef')\
b) ('abef', 'cd', ”)\
**c) ('abef', ”, ”)**\
d) error

> Explanation: The separator is not present in the string hence the second and the third elements of the tuple are null strings.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcdef12'.replace('cd', '12'))`

**a) ab12ef12**\
b) abcdef12\
c) ab12efcd\
d) none of the mentioned

> Explanation: All occurrences of the first substring are replaced by the second substring.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abef'.replace('cd', '12'))`

**a) abef**\
b) 12\
c) error\
d) none of the mentioned

> Explanation: The first substring is not present in the given string and hence nothing is replaced.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcefd'.replace('cd', '12'))`

a) ab1ef2\
**b) abcefd**\
c) ab1efd\
d) ab12ed2

> Explanation: The first substring is not present in the given string and hence nothing is replaced.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('xyyxyyxyxyxxy'.replace('xy', '12', 0))`

**a) xyyxyyxyxyxxy**\
b) 12y12y1212x12\
c) 12yxyyxyxyxxy\
d) xyyxyyxyxyx12

> Explanation: The first 0 occurrences of the given substring are replaced.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('xyyxyyxyxyxxy'.replace('xy', '12', 100))`

a) xyyxyyxyxyxxy\
**b) 12y12y1212x12**\
c) none of the mentioned
d) error

> Explanation: The first 100 occurrences of the given substring are replaced.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcdefcdghcd'.split('cd'))`

a) ['ab', 'ef', 'gh']\
**b) ['ab', 'ef', 'gh', ”]**\
c) ('ab', 'ef', 'gh')\
d) ('ab', 'ef', 'gh', ”)

> Explanation: The given string is split and a list of substrings is returned.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcdefcdghcd'.split('cd', 0))`

**a) ['abcdefcdghcd']**\
b) 'abcdefcdghcd'\
c) error\
d) none of the mentioned

> Explanation: The given string is split at 0 occurances of the specified substring.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcdefcdghcd'.split('cd', -1))`

a) ['ab', 'ef', 'gh']\
**b) ['ab', 'ef', 'gh', ”]**\
c) ('ab', 'ef', 'gh')\
d) ('ab', 'ef', 'gh', ”)

> Explanation: Calling the function with a negative value for maxsplit is the same as calling it without any maxsplit specified. The string will be split into as many substring s as possible.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcdefcdghcd'.split('cd', 2))`

**a) ['ab', 'ef', 'ghcd']**\
b) ['ab', 'efcdghcd']\
c) ['abcdef', 'ghcd']\
d) none of the mentioned

> Explanation: The string is split into a maximum of maxsplit+1 substrings.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('ab\ncd\nef'.splitlines())`

**a) ['ab', 'cd', 'ef']**\
b) ['ab\n', 'cd\n', 'ef\n']\
c) ['ab\n', 'cd\n', 'ef']\
d) ['ab', 'cd', 'ef\n']

> Explanation: It is similar to calling split('\n').

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('Ab!2'.swapcase())`

a) AB!@\
b) ab12\
**c) aB!2**\
d) aB1@

> Explanation: Lowercase letters are converted to uppercase and vice-versa.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('ab cd ef'.title())`

a) Ab cd ef\
b) Ab cd eF\
**c) Ab Cd Ef**\
d) None of the mentioned

> Explanation: The first letter of every word is capitalized.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('ab cd-ef'.title())`

a) Ab cd-ef\
b) Ab Cd-ef\
**c) Ab Cd-Ef**\
d) None of the mentioned

> Explanation: The first letter of every word is capitalized. Special symbols terminate a word.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcd'.translate('a'.maketrans('abc', 'bcd')))`

a) bcde\
b) abcd\
c) error\
**d) bcdd**

> Explanation: The output is bcdd since no translation is provided for d.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcd'.translate({97: 98, 98: 99, 99: 100}))`

a) bcde\
b) abcd\
c) error\
**d) none of the mentioned**

> Explanation: The output is bcdd since no translation is provided for d.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('abcd'.translate({'a': '1', 'b': '2', 'c': '3', 'd': '4'}))`

**a) abcd**\
b) 1234\
c) error\
d) none of the mentioned

> Explanation: The function translate expects a dictionary of integers. Use maketrans() instead of doing the above.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('ab'.zfill(5))`

**a) 000ab**\
b) 00ab0\
c) 0ab00\
d) ab000

> Explanation: The string is padded with zeros on the left hand side. It is useful for formatting numbers.

### What will be the output of the following Python code snippet? [Яким буде результат наступного фрагмента коду Python?]

`print('+99'.zfill(5))`

a) 00+99\
b) 00099\
**c) +0099**\
d) +++99

> Explanation: zeros are filled in between the first sign and the rest of the string.

# Section 10

## 1. Which of the following commands will create a list? [Яка з наступних команд створює список]

a) list1 = list()\
b) list1 = [] \
c) list1 = list([1, 2, 3])\
_**d) all of the mentioned**_

> Explanation: Execute in the shell and verify.

## 2. What is the output when we execute list(“hello”)? [Що виведеться при запуску list("hello")]

_**a) [‘h’, ‘e’, ‘l’, ‘l’, ‘o’]**_\
b) [‘hello’]\
c) [‘llo’]\
d) [‘olleh’]

> Explanation: Execute in the shell and verify.

## 3. Suppose listExample is [‘h’,’e’,’l’,’l’,’o’], what is len(listExample)? [Припустимо що listExample це [‘h’,’e’,’l’,’l’,’o’], чому дорівнюватиме len(listExample)]

_**a) 5**_\
b) 4\
c) None\
d) Error

> Explanation: Execute in the shell and verify.

## 4. Suppose list1 is [2445,133,12454,123], what is max(list1)? [Припустимо що list1 це [2445,133,12454,123], що буде тоді max(list1)?]

a) 2445\
b) 133\
_**c) 12454**_\
d) 123

> Explanation: Max returns the maximum element in the list.

## 5. Suppose list1 is [3, 5, 25, 1, 3], what is min(list1)? [Припустимо що list1 це [3, 5, 25, 1, 3], що буде тоді min(list1)?]

a) 3\
b) 5\
c) 25\
_**d) 1**_

> Explanation: Min returns the minimum element in the list.

## 6. Suppose list1 is [1, 5, 9], what is sum(list1)? [Припустимо що list1 це [1, 5, 9], що буде тоді sum(list1)?]

a) 1\
b) 9\
_**c) 15**_\
d) Error

> Explanation: Sum returns the sum of all elements in the list.

## 7. To shuffle the list(say list1) what function do we use? [Для того щоб перемішати список(наприклад list1) яку функцію ми використовуємо?]

a) list1.shuffle()\
b) shuffle(list1)\
_**c) random.shuffle(list1)**_\
d) random.shuffleList(list1)

> Explanation: Execute in the shell to verify.

## 8. Suppose list1 is [4, 2, 2, 4, 5, 2, 1, 0], Which of the following is correct syntax for slicing operation? [Припустимо, що list1 це [4, 2, 2, 4, 5, 2, 1, 0], який із наступного є правильним синтаксисом для операції slicing?]

a) print(list1[0])\
b) print(list1[:2])\
c) print(list1[:-2])\
_**d) all of the mentioned**_

> Explanation: Slicing is allowed in lists just as in the case of strings.

## 9. Suppose list1 is [2, 33, 222, 14, 25], What is list1[-1]? [Припустимо що list1 це [2, 33, 222, 14, 25], що тоді буде list[-1] ?]

a) Error\
b) None\
_**c) 25**_\
d) 2

> Explanation: -1 corresponds to the last index in the list.

## 10. Suppose list1 is [2, 33, 222, 14, 25], What is list1[:-1]? [Припустимо що list1 це [2, 33, 222, 14, 25], що тоді буде list1[:-1]]

_**a) [2, 33, 222, 14]**_\
b) Error\
c) 25\
d) [25, 14, 222, 33, 2]

> Explanation: Execute in the shell to verify.

## 1. What will be the output of the following Python code? [Що виведеться піісля виконання наступного коду?]

```
names = ['Amir', 'Bear', 'Charlton', 'Daman']
print(names[-1][-1])
```

a) A\
b) Daman\
c) Error\
_**d) n**_

> Explanation: Execute in the shell to verify.

## 2. What will be the output of the following Python code? [Що відбудеться при запуску наступного Python code]

```python
names1 = ['Amir', 'Bear', 'Charlton', 'Daman']
names2 = names1
names3 = names1[:]

names2[0] = 'Alice'
names3[1] = 'Bob'

sum = 0
for ls in (names1, names2, names3):
    if ls[0] == 'Alice':
        sum += 1
    if ls[1] == 'Bob':
        sum += 10

print sum
```

a) 11\
_**b) 12**_\
c) 21\
d) 22

> Explanation: When assigning names1 to names2, we create a second reference to the same list. Changes to names2 affect names1. When assigning the slice of all elements in names1 to names3, we are creating a full copy of names1 which can be modified independently.

> **ПРИМІТКА!!!!** цей код взагалі не запускається через синтаксичну помилку в останній строці `print sum` (і навіть в python 2.7 не запускається), бо функція `print` має викликатись з дужками, тобто має бути `print(sum)`. Але так як варіанту що код не запускається нема будемо вважати що той хто набирав цей код просто забув скобкі і `print` виводить значення, ну і тоді сума буде дорівнювати 12.

## 3. Suppose list1 is [1, 3, 2], What is list1 _ 2? [Дано list1 який дорівнює [1,2,3], чому дорівнюватиме list1 _ 2?]

a) [2, 6, 4]\
b) [1, 3, 2, 1, 3]\
_**c) [1, 3, 2, 1, 3, 2]**_\
d) [1, 3, 2, 3, 2, 1]

> Explanation: Execute in the shell and verify.

## 4. Suppose list1 = [0.5 * x for x in range(0, 4)], list1 is: [Дано list1 = [0.5 * x for x in range(0, 4)], тоді list1 є:]

a) [0, 1, 2, 3]\
b) [0, 1, 2, 3, 4]\
_**c) [0.0, 0.5, 1.0, 1.5]**_\
d) [0.0, 0.5, 1.0, 1.5, 2.0]

> Explanation: Execute in the shell to verify.

## 5. What will be the output of the following Python code? [Що відбудеться при запуску наступного Python code]

```
>>>list1 = [11, 2, 23]
>>>list2 = [11, 2, 2]
>>>list1 < list2
```

a) True
b) False
c) Error
d) None

> Explanation: Elements are compared one by one.

## 6. To add a new element to a list we use which command? [Для того щоб додати новий елемент до списку, яку команду ми використовуємо?]

a) list1.add(5)\
_**b) list1.append(5)**_\
c) list1.addLast(5)\
d) list1.addEnd(5)

> Explanation: We use the function append to add an element to the list.

## 7. To insert 5 to the third position in list1, we use which command?[Яку команду ми використовуємо, щоб вставити 5 на третю позицію в list1?]

a) list1.insert(3, 5)\
_**b) list1.insert(2, 5)**_\
c) list1.add(3, 5)\
d) list1.append(3, 5)

> Explanation: Execute in the shell to verify.

## 8. To remove string “hello” from list1, we use which command? [Яку команду ми використовуємо, щоб видалити рядок «hello» зі list1?]

_**a) list1.remove(“hello”)**_\
b) list1.remove(hello)\
c) list1.removeAll(“hello”)\
d) list1.removeOne(“hello”)

> Explanation: Execute in the shell to verify.

## 9. Suppose list1 is [3, 4, 5, 20, 5], what is list1.index(5)? [Вважаємо що list1 це [3, 4, 5, 20, 5], чому дорівнюватиме list1.index(5) ?]

a) 0\
b) 1\
c) 4\
_**d) 2**_

> Explanation: Execute help(list.index) to get details.

## 10. Suppose list1 is [3, 4, 5, 20, 5, 25, 1, 3], what is list1.count(5)? [Вважаємо що list1 це [3, 4, 5, 20, 5, 25, 1, 3], чому дорівнюватиме list1.count(5) ?]

a) 0\
b) 4\
c) 1\
_**d) 2**_

> Explanation: Execute in the shell to verify.

## 1. Suppose list1 is [3, 4, 5, 20, 5, 25, 1, 3], what is list1 after list1.reverse()? [Вважаємо list1 це [3, 4, 5, 20, 5, 25, 1, 3], тоді чому дорівнює list1 після list1.reverse()?]

a) [3, 4, 5, 20, 5, 25, 1, 3]\
b) [1, 3, 3, 4, 5, 5, 20, 25]\
c) [25, 20, 5, 5, 4, 3, 3, 1]\
_**d) [3, 1, 25, 5, 20, 5, 4, 3]**_

> Explanation: Execute in the shell to verify.

## 2. Suppose listExample is [3, 4, 5, 20, 5, 25, 1, 3], what is list1 after listExample.extend([34, 5])? [Вважаємо що listExample є [3, 4, 5, 20, 5, 25, 1, 3], чому дорівнюватиме list1 після listExample.extend([34, 5])?]

_**a) [3, 4, 5, 20, 5, 25, 1, 3, 34, 5]**_\
b) [1, 3, 3, 4, 5, 5, 20, 25, 34, 5]\
c) [25, 20, 5, 5, 4, 3, 3, 1, 34, 5]\
d) [1, 3, 4, 5, 20, 5, 25, 3, 34, 5]

> Explanation: Execute in the shell to verify.

> **ПРИМІТКА!!!!** Можна докопатись до того що яким вообще боком list1 до listExample??? Но якщо просто додумувать те що list1 це мав би бути listExample то відповідь буде **а)** .

## 3. Suppose listExample is [3, 4, 5, 20, 5, 25, 1, 3], what is list1 after listExample.pop(1)? [Вважаємо що listExample є [3, 4, 5, 20, 5, 25, 1, 3], чому дорівнюватиме list1 після listExample.pop(1)]

a) [3, 4, 5, 20, 5, 25, 1, 3]\
b) [1, 3, 3, 4, 5, 5, 20, 25]\
_**c) [3, 5, 20, 5, 25, 1, 3]**_\
d) [1, 3, 4, 5, 20, 5, 25]

> Explanation: pop() removes the element at the position specified in the parameter.

> **ПРИМІТКА!!!!** Можна докопатись до того, що яким вообще боком list1 може бути до listExample???! Но якщо просто додумувать те що list1 це мав би бути listExample то відповідь буде с)

## 4. Suppose listExample is [3, 4, 5, 20, 5, 25, 1, 3], what is list1 after listExample.pop()? [Вважаємо що listExample є [3, 4, 5, 20, 5, 25, 1, 3], чому дорівнюватиме list1 після listExample.pop()]

_**a) [3, 4, 5, 20, 5, 25, 1]**_\
b) [1, 3, 3, 4, 5, 5, 20, 25]\
c) [3, 5, 20, 5, 25, 1, 3]\
d) [1, 3, 4, 5, 20, 5, 25]

> Explanation: pop() by default will remove the last element.

> **ПРИМІТКА!!!!** Можна докопатись до того, що яким вообще боком list1 може бути до listExample???! Но якщо просто додумувать те що list1 це мав би бути listExample то відповідь буде a)

## 5. What will be the output of the following Python code? [Що відбудеться при запуску наступного Python code]

```
>>>"Welcome to Python".split()
```

_**a) [“Welcome”, “to”, “Python”]**_\
b) (“Welcome”, “to”, “Python”)\
c) {“Welcome”, “to”, “Python”}\
d) “Welcome”, “to”, “Python”

> Explanation: split() function returns the elements in a list.

## 6. What will be the output of the following Python code? [Що відбудеться при запуску наступного Python code?]

```python
>>>list("a#b#c#d".split('#'))
```

_**a) [‘a’, ‘b’, ‘c’, ‘d’]**_\
b) [‘a b c d’]\
c) [‘a#b#c#d’]\
d) [‘abcd’]

> Explanation: Execute in the shell to verify.

## 7. What will be the output of the following Python code? [Що відбудеться при запуску наступного Python code?]

```python
myList = [1, 5, 5, 5, 5, 1]
max = myList[0]
indexOfMax = 0
for i in range(1, len(myList)):
    if myList[i] > max:
        max = myList[i]
        indexOfMax = i

>>>print(indexOfMax)
```

_**a) 1**_\
b) 2\
c) 3\
d) 4

> Explanation: First time the highest number is encountered is at index 1.

## 8. What will be the output of the following Python code? [Що відбудеться при запуску наступного Python code?]

```python
myList = [1, 2, 3, 4, 5, 6]
for i in range(1, 6):
    myList[i - 1] = myList[i]

for i in range(0, 6):
    print(myList[i], end = " ")
```

a) 2 3 4 5 6 1\
b) 6 1 2 3 4 5\
_**c) 2 3 4 5 6 6**_\
d) 1 1 2 3 4 5

> Explanation: Execute in the shell to verify.

## 9. What will be the output of the following Python code? [Що відбудеться при запуску наступного Python code?]

```python
>>>list1 = [1, 3]
>>>list2 = list1
>>>list1[0] = 4
>>>print(list2)
```

a) [1, 3]\
_**b) [4, 3]**_\
c) [1, 4]\
d) [1, 3, 4]

> Explanation: Lists should be copied by executing [:] operation.

## 10. What will be the output of the following Python code? [Що відбудеться при запуску наступного Python code?]

```python
def f(values):
    values[0] = 44

v = [1, 2, 3]
f(v)
print(v)
```

a) [1, 44]\
b) [1, 2, 3, 44]\
_**c) [44, 2, 3]**_\
d) [1, 2, 3]

> Explanation: Execute in the shell to verify.

## 1. What will be the output of the following Python code?

```python
def f(i, values = []):
    values.append(i)
    return values

f(1)
f(2)
v = f(3)
print(v)
```

a) [1] [2] [3]\
b) [1] [1, 2] [1, 2, 3]\
_**c) [1, 2, 3]**_\
d) 1 2 3

> Explanation: Execute in the shell to verify

## 2. What will be the output of the following Python code?

```python
names1 = ['Amir', 'Bala', 'Chales']

if 'amir' in names1:
    print(1)
else:
    print(2)
```

a) None\
b) 1\
_**c) 2**_\
d) Error

> Explanation: Execute in the shell to verify.

## 3. What will be the output of the following Python code?

```python
names1 = ['Amir', 'Bala', 'Charlie']
names2 = [name.lower() for name in names1]

print(names2[2][0])
```

a) None\
b) a\
c) b\
_**d) c**_

> Explanation: List Comprehension are a shorthand for creating new lists.

## 4. What will be the output of the following Python code?

```python
numbers = [1, 2, 3, 4]

numbers.append([5,6,7,8])

print(len(numbers))
```

a) 4\
_**b) 5**_\
c) 8\
d) 12

> Explanation: A list is passed in append so the length is 5.

## 5. To which of the following the “in” operator can be used to check if an item is in it? [До яких наступних структур даних "in" оператор може бути використаним для перевірки чи є елемент в ній?]

a) Lists\
b) Dictionary\
c) Set\
_**d) All of the mentioned**_

> Explanation: In can be used in all data structures.

## 6. What will be the output of the following Python code?

```python
list1 = [1, 2, 3, 4]
list2 = [5, 6, 7, 8]

print(len(list1 + list2))
```

a) 2\
b) 4\
c) 5\
_**d) 8**_

> Explanation: + appends all the elements individually into a new list.

## 7. What will be the output of the following Python code?

```python
def addItem(listParam):
    listParam += [1]

mylist = [1, 2, 3, 4]
addItem(mylist)
print(len(mylist))
```

a) 1\
b) 4\
_**c) 5**_\
d) 8

> Explanation: + will append the element to the list.

## 8. What will be the output of the following Python code?

```python
def increment_items(L, increment):
    i = 0
    while i < len(L):
        L[i] = L[i] + increment
        i = i + 1

values = [1, 2, 3]
print(increment_items(values, 2))
print(values)
```

_**a)**_

```
 None
 [3, 4, 5]
```

b)

```
   None
   [1, 2, 3]
```

c)

```
   [3, 4, 5]
   [1, 2, 3]
```

d)

```
   [3, 4, 5]
   None
```

Answer: a)

> Explanation: Execute in the shell to verify.

## 9. What will be the output of the following Python code?

```python
def example(L):
    ''' (list) -> list
    '''
    i = 0
    result = []
    while i < len(L):
        result.append(L[i])
        i = i + 3
    return result
```

_**a) Return a list containing every third item from L starting at index 0**_\
b) Return an empty list\
c) Return a list containing every third index from L starting at index 0\
d) Return a list containing the items from L starting from index 0, omitting every third item

> Explanation: Run the code to get a better understanding with many arguments.

## 10. What will be the output of the following Python code?

```python
veggies = ['carrot', 'broccoli', 'potato', 'asparagus']
veggies.insert(veggies.index('broccoli'), 'celery')
print(veggies)
```

_**a) [‘carrot’, ‘celery’, ‘broccoli’, ‘potato’, ‘asparagus’] Correct 1.00**_\
b) [‘carrot’, ‘celery’, ‘potato’, ‘asparagus’]\

c) [‘carrot’, ‘broccoli’, ‘celery’, ‘potato’, ‘asparagus’]\

d) [‘celery’, ‘carrot’, ‘broccoli’, ‘potato’, ‘asparagus’]\

> Explanation: Execute in the shell to verify.

> **ПРИМІТКА!!!** Correct 1.00 виглядає максимально странно у варіанті `а)`, але без цього correct 1.00 відповідь а) є правильною

# Section 11

## 1. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
>>>m = [[x, x + 1, x + 2] for x in range(0, 3)]
```

a) `[[1, 2, 3], [4, 5, 6], [7, 8, 9]]`\
**b) `[[0, 1, 2], [1, 2, 3], [2, 3, 4]]`**\
c) `[1, 2, 3, 4, 5, 6, 7, 8, 9]`\
d) `[0, 1, 2, 1, 2, 3, 2, 3, 4]`

## 2. How many elements are in m? [Скільки елементів в m?]

```python
m = [[x, y] for x in range(0, 4) for y in range(0, 4)]
```

a) 8\
b) 12\
**c) 16**\
d) 32

## 3. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
values = [[3, 4, 5, 1], [33, 6, 1, 2]]

v = values[0][0]
for row in range(0, len(values)):
    for column in range(0, len(values[row])):
        if v < values[row][column]:
            v = values[row][column]

print(v)
```

a) 3\
b) 5\
c) 6\
**d) 33**

## 4. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
values = [[3, 4, 5, 1], [33, 6, 1, 2]]

v = values[0][0]
for lst in values:
    for element in lst:
        if v > element:
            v = element

print(v)
```

**a) 1**\
b) 3\
c) 5\
d) 6

## 5. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
values = [[3, 4, 5, 1 ], [33, 6, 1, 2]]

for row in values:
    row.sort()
    for element in row:
        print(element, end = " ")
    print()
```

a) The program prints two rows 3 4 5 1 followed by 33 6 1 2\
b) The program prints on row 3 4 5 1 33 6 1 2\
c) The program prints two rows 3 4 5 1 followed by 33 6 1 2\
**d) The program prints two rows 1 3 4 5 followed by 1 2 6 33**

## 6. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
matrix = [[1, 2, 3, 4],
       [4, 5, 6, 7],
       [8, 9, 10, 11],
       [12, 13, 14, 15]]

for i in range(0, 4):
    print(matrix[i][1], end = " ")
```

a) 1 2 3 4\
b) 4 5 6 7\
c) 1 3 8 12\
**d) 2 5 9 13**

## 7. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
def m(list):
    v = list[0]
    for e in list:
      if v < e: v = e
    return v

values = [[3, 4, 5, 1], [33, 6, 1, 2]]

for row in values:
    print(m(row), end = " ")
```

a) 3 33\
b) 1 1\
c) 5 6\
**d) 5 33**

## 8. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
data = [[[1, 2], [3, 4]], [[5, 6], [7, 8]]]

print(data[1][0][0])
```

a) 1\
b) 2\
c) 4\
**d) 5**

## 9. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
data = [[[1, 2], [3, 4]], [[5, 6], [7, 8]]]

def ttt(m):
    v = m[0][0]

    for row in m:
        for element in row:
           if v < element: v = element

    return v

print(ttt(data[0]))
```

a) 1\
b) 2\
**c) 4**\
d) 5

## 10. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
points = [[1, 2], [3, 1.5], [0.5, 0.5]]
points.sort()
print(points)
```

a) `[[1, 2], [3, 1.5], [0.5, 0.5]]`\
b) `[[3, 1.5], [1, 2], [0.5, 0.5]]`\
**c) `[[0.5, 0.5], [1, 2], [3, 1.5]]`**\
d) `[[0.5, 0.5], [3, 1.5], [1, 2]]`

## 1. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a=[10,23,56,[78]]
b=list(a)
a[3][0]=95
a[1]=34
print(b)
```

a) `[10,34,56,[95]]`\
b) `[10,23,56,[78]]`\
**c) `[10,23,56,[95]]`**\
d) `[10,34,56,[78]]`

## 2. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
print(list(zip((1,2,3),('a'),('xxx','yyy'))))
print(list(zip((2,4),('b','c'),('yy','xx'))))
```

a)

```python
[(1, 2, 3), ('a'), ('xxx', 'yyy')]
[(2, 4), ('b', 'c'), ('yy', 'xx')]
```

b)

```python
[(1, 'a', 'xxx'), (2, ' ', 'yyy'), (3, ' ', ' ')]
[(2, 'b', 'yy'), (4, 'c', 'xx')]
```

c) Syntax error
**d)**

```python
[(1, 'a', 'xxx')]
[(2, 'b', 'yy'), (4, 'c', 'xx')]
```

> The zip function combines the individual attributes of the lists into a list of tuples.

## 3. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
import copy
a=[10,23,56,[78]]
b=copy.deepcopy(a)
a[3][0]=95
a[1]=34
print(b)
```

a) `[10,34,56,[95]]`\
**b) `[10,23,56,[78]]`**\
c) `[10,23,56,[95]]`\
d) `[10,34,56,[78]]`

## 4. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
s="a@b@c@d"
a=list(s.partition("@"))
print(a)
b=list(s.split("@",3))
print(b)
```

a)

```python
['a','b','c','d']
['a','b','c','d']
```

b)

```python
['a','@','b','@','c','@','d']
['a','b','c','d']
```

**c)**

```python
['a','@','b@c@d']
['a','b','c','d']
```

d)

```python
['a','@','b@c@d']
['a','@','b','@','c','@','d']
```

## 5. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a=[1,2,3,4]
b=[sum(a[0:x+1]) for x in range(0,len(a))]
print(b)
```

a) `10`\
b) `[1,3,5,7]`\
c) `4`\
**d) `[1,3,6,10]`**

## 6. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a="hello"
b=list((x.upper(),len(x)) for x in a)
print(b)
```

**a) `[('H', 1), ('E', 1), ('L', 1), ('L', 1), ('O', 1)]`**\
b) `[('HELLO', 5)]`\
c) `[('H', 5), ('E', 5), ('L', 5), ('L', 5), ('O', 5)]`\
d) Syntax error

## 7. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a=[1,2,3,4]
b=[sum(a[0:x+1]) for x in range(0,len(a))]
print(b)
```

a) `10`\
b) `[1,3,5,7]`\
c) `4`\
**d) `[1,3,6,10]`**

## 8. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a=[[]]*3
a[1].append(7)
print(a)
```

a) Syntax error\
**b) `[[7], [7], [7]]`**\
c) `[[7], [], []]`\
d) `[[],7, [], []]`

## 9. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
b=[2,3,4,5]
a=list(filter(lambda x:x%2,b))
print(a)
```

a) `[2,4]`\
b) `[ ]`\
**c) `[3,5]`**\
d) Invalid arguments for filter function

## 10. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
lst=[3,4,6,1,2]
lst[1:2]=[7,8]
print(lst)
```

**a) `[3, 7, 8, 6, 1, 2]`**\
b) Syntax error\
c) `[3,[7,8],6,1,2]`\
d) `[3,4,6,7,8]`

## 1. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a=[1,2,3]
b=a.append(4)
print(a)
print(b)
```

a)

```python
[1,2,3,4]
[1,2,3,4]
```

**b)**

```python
[1, 2, 3, 4]
None
```

c) Syntax error
d)

```python
[1,2,3]
[1,2,3,4]
```

## 2. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
>>> a=[14,52,7]
>>> b=a.copy()
>>> b is a
```

a) True
**b) False**

## 3. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a=[13,56,17]
a.append([87])
a.extend([45,67])
print(a)
```

**a) `[13, 56, 17, [87], 45, 67]`**\
b) `[13, 56, 17, 87, 45, 67]`\
c) `[13, 56, 17, 87,[ 45, 67]]`\
d) `[13, 56, 17, [87], [45, 67]]`

## 4. What is the output of the following piece of code? [Який буде результат виконання наступного уривку коду?]

```python
a=list((45,)*4)
print((45)*4)
print(a)
```

**a)**

```python
180
[(45),(45),(45),(45)]
```

b)

```python
(45,45,45,45)
[45,45,45,45]
```

c)

```python
180
[45,45,45,45]
```

d) Syntax error

## 5. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
lst=[[1,2],[3,4]]
print(sum(lst,[]))
```

a) `[[3],[7]]`\
**b) `[1,2,3,4]`**\
c) Error\
d) `[10]`

## 6. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
word1="Apple"
word2="Apple"
list1=[1,2,3]
list2=[1,2,3]
print(word1 is word2)
print(list1 is list2)
```

a)

```python
True
True
```

b)

```python
False
True
```

c)

```python
False
False
```

**d)**

```python
True
False
```

## 7. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
def unpack(a,b,c,d):
    print(a+d)
x = [1,2,3,4]
unpack(*x)
```

a) Error\
b) `[1,4]`\
c) `[5]`\
**d) `5`**

## 8. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
places = ['Bangalore', 'Mumbai', 'Delhi']
places1 = places
places2 = places[:]
places1[1]="Pune"
places2[2]="Hyderabad"
print(places)
```

a) `['Bangalore', 'Pune', 'Hyderabad']`\
**b) `['Bangalore', 'Pune', 'Delhi']`**\
c) `['Bangalore', 'Mumbai', 'Delhi']`\
d) `['Bangalore', 'Mumbai', 'Hyderabad']`

## 9. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
x=[[1],[2]]
print(" ".join(list(map(str,x))))
```

**a) `[1] [2]`**\
b) `[49] [50]`\
c) Syntax error\
d) `[[1]] [[2]]`

## 10. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a=165
b=sum(list(map(int,str(a))))
print(b)
```

a) 561\
b) 5\
**c) 12**\
d) Syntax error

## 11. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a= [1, 2, 3, 4, 5]
for i in range(1, 5):
    a[i-1] = a[i]
for i in range(0, 5):
    print(a[i],end = " ")
```

a) 5 5 1 2 3\
b) 5 1 2 3 4\
c) 2 3 4 5 1\
**d) 2 3 4 5 5**

## 12. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
def change(var, lst):
    var = 1
    lst[0] = 44
k = 3
a = [1, 2, 3]
change(k, a)
print(k)
print(a)
```

**a)**

```python
3
[44, 2, 3]
```

b)

```python
1
[1,2,3]
```

c)

```python
3
[1,2,3]
```

d)

```python
1
[44,2,3]
```

## 13. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a = [1, 5, 7, 9, 9, 1]
b=a[0]
x= 0
for x in range(1, len(a)):
    if a[x] > b:
        b = a[x]
        b= x
print(b)
```

a) 5\
b) 3\
**c) 4**\
d) 0

## 14. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
a=["Apple","Ball","Cobra"]
a.sort(key=len)
print(a)
```

a) `['Apple', 'Ball', 'Cobra']`\
**b) `['Ball', 'Apple', 'Cobra']`**\
c) `['Cobra', 'Apple', 'Ball']`\
d) Invalid syntax for sort()

## 15. What will be the output of the following Python code? [Який буде результат виконання наступного Python-коду?]

```python
num = ['One', 'Two', 'Three']
for i, x in enumerate(num):
    print('{}: {}'.format(i, x),end=" ")
```

a) 1: 2: 3:\
b) Exception is thrown\
c) One Two Three\
**d) 0: One 1: Two 2: Three**

## 1. What will be the output of the following Python code snippet? [Що буде результатом виконання наступного шматка Python-коду?]

```python
k = [print(i) for i in my_string if i not in "aeiou"]
```

a) prints all the vowels in my_string\
b) prints all the consonants in my_string\
**c) prints all characters of my_string that aren’t vowels**\
d) prints only on executing print(k)

## 2. What is the output of `print(k)` in the following Python code snippet? [Що буде результатом виконання `print(k)` в наступному уривку Python-коду?]

```python
k = [print(i) for i in my_string if i not in "aeiou"]
print(k)
```

a) all characters of my_string that aren’t vowels\
**b) a list of Nones**\
c) list of Trues\
d) list of Falses\

## 3. What will be the output of the following Python code snippet? [Що буде результатом виконання наступного шматка Python-коду?]

```python
my_string = "hello world"
k = [(i.upper(), len(i)) for i in my_string]
print(k)
```

a) `[('HELLO', 5), ('WORLD', 5)]`\
**b) `[('H, 1), ('E, 1), ('L, 1), ('L', 1), ('O', 1), (' ', 1), ('W', 1), ('O', 1), ('R', 1), ('L', 1), ('D', 1)]`**\
c) `[('HELLO WORLD', 11)]`\
d) none of the mentioned

## 4. Which of the following is the correct expansion of `list_1 = [expr(i) for i in list_0 if func(i)]`? [Які з наступних уривків є коректним розкриттям `list_1 = [expr(i) for i in list_0 if func(i)]`?]

a)

```python
list_1 = []
for i in list_0:
    if func(i):
        list_1.append(i)
```

b)

```python
for i in list_0:
    if func(i):
        list_1.append(expr(i))
```

**c)**

```python
list_1 = []
for i in list_0:
    if func(i):
        list_1.append(expr(i))
```

d) none of the mentioned

## 5. What will be the output of the following Python code snippet? [Що буде результатом виконання наступного шматка Python-коду?]

```python
x = [i**+1 for i in range(3)]; print(x);
```

**a) `[0, 1, 2]`**\
b) `[1, 2, 5]`\
c) error, \*\*+ is not a valid operator\
d) error, ‘;’ is not allowed

## 6. What will be the output of the following Python code snippet? [Що буде результатом виконання наступного шматка Python-коду?]

```python
print([i.lower() for i in "HELLO"])
```

**a) `['h', 'e', 'l', 'l', 'o']`**\
b) `'hello'`\
c) `['hello']`\
d) `hello`

## 7. What will be the output of the following Python code snippet? [Що буде результатом виконання наступного шматка Python-коду?]

```python
print([i+j for i in "abc" for j in "def"])
```

a) `[‘da’, ‘ea’, ‘fa’, ‘db’, ‘eb’, ‘fb’, ‘dc’, ‘ec’, ‘fc’]`\
b) `[[‘ad’, ‘bd’, ‘cd’], [‘ae’, ‘be’, ‘ce’], [‘af’, ‘bf’, ‘cf’]]`\
c) `[[‘da’, ‘db’, ‘dc’], [‘ea’, ‘eb’, ‘ec’], [‘fa’, ‘fb’, ‘fc’]]`\
**d) `[‘ad’, ‘ae’, ‘af’, ‘bd’, ‘be’, ‘bf’, ‘cd’, ‘ce’, ‘cf’]`**

## 8. What will be the output of the following Python code snippet? [Що буде результатом виконання наступного шматка Python-коду?]

```python
print([[i+j for i in "abc"] for j in "def"])
```

a) `[‘da’, ‘ea’, ‘fa’, ‘db’, ‘eb’, ‘fb’, ‘dc’, ‘ec’, ‘fc’]`\
**b) `[[‘ad’, ‘bd’, ‘cd’], [‘ae’, ‘be’, ‘ce’], [‘af’, ‘bf’, ‘cf’]]`**\
c) `[[‘da’, ‘db’, ‘dc’], [‘ea’, ‘eb’, ‘ec’], [‘fa’, ‘fb’, ‘fc’]]`\
d) `[‘ad’, ‘ae’, ‘af’, ‘bd’, ‘be’, ‘bf’, ‘cd’, ‘ce’, ‘cf’]`\

## 9. What will be the output of the following Python code snippet? [Що буде результатом виконання наступного шматка Python-коду?]

```python
print([if i%2==0: i; else: i+1; for i in range(4)])
```

a) `[0, 2, 2, 4]`\
b) `[1, 1, 3, 3]`\
**c) error**\
d) none of the mentioned

## 10. Which of the following is the same as `list(map(lambda x: x**-1, [1, 2, 3]))`? [Що з переліченого є еквівалентом `list(map(lambda x: x**-1, [1, 2, 3]))`?]

a) `[x**-1 for x in [(1, 2, 3)]]`\
b) `[1/x for x in [(1, 2, 3)]]`\
**c) `[1/x for x in (1, 2, 3)]`**\
d) error

# Section 12

### Python Questions and Answers – List Comprehension – 1

## 1. What will be the output of the following Python code?
```python
l=[1,2,3,4,5]
[x&1 for x in l]
```

a) [1, 1, 1, 1, 1]

**b) [1, 0, 1, 0, 1]**

c) [1, 0, 0, 0, 0]

d) [0, 1, 0, 1, 0]

<details>
<summary>detailed</summary>
Answer: b
Explanation: In the code shown above, each of the numbers of the list, that is, 1, 2, 3, 4 and 5 are AND-ed with 1 and the result is printed in the form of a list. Hence the output is [1, 0, 1, 0, 1].
</details>

## 2. What will be the output of the following Python code?
```python
l1=[1,2,3]
l2=[4,5,6]
[x*y for x in l1 for y in l2]
```

a) [4, 8, 12, 5, 10, 15, 6, 12, 18]

b) [4, 10, 18]

**c) [4, 5, 6, 8, 10, 12, 12, 15, 18]**

d) [18, 12, 6, 15, 10, 5, 12, 8, 4]

<details>
<summary>detailed</summary>
Answer: c
Explanation: The code shown above returns x*y, where x belongs to the list l1 and y belongs to the list l2. Therefore, the output is: [4, 5, 6, 8, 10, 12, 12, 15, 18].
</details>

## 3. Write the list comprehension to pick out only negative integers from a given list ‘l’.

a) [x<0 in l]

b) [x for x<0 in l]

c) [x in l for x<0]

**d) [x for x in l if x<0]**

<details>
<summary>detailed</summary>
Explanation: To pick out only the negative numbers from a given list ‘l’, the correct list comprehension statement would be: [x for x in l if x<0].

For example if we have a list l=[-65, 2, 7, -99, -4, 3]
>>> [x for x in l if x<0]
The output would be: [-65, -99, -4].
</details>

## 4. What will be the output of the following Python code?
```python
s=["pune", "mumbai", "delhi"]
[(w.upper(), len(w)) for w in s]
```

a) Error

b) [‘PUNE’, 4, ‘MUMBAI’, 6, ‘DELHI’, 5]

c) [PUNE, 4, MUMBAI, 6, DELHI, 5]

**d) [(‘PUNE’, 4), (‘MUMBAI’, 6), (‘DELHI’, 5)]**

<details>
<summary>detailed</summary>
Answer: d
Explanation: If we need to generate two results, we need to put it in the form of a tuple. The code shown above returns each word of list in uppercase, along with the length of the word. Hence the output of the code is: [(‘PUNE’, 4), (‘MUMBAI’, 6), (‘DELHI’, 5)].
</details>

## 5. What will be the output of the following Python code?
```python
l1=[2,4,6]
l2=[-2,-4,-6]
for i in zip(l1, l2):
	print(i)
```

a)
```shell
2, -2
4, -4
6, -6
```

b) [(2, -2), (4, -4), (6, -6)]

**c)**
```shell
(2, -2)
(4, -4)
(6, -6)
```

d) [-4, -16, -36]

<details>
<summary>detailed</summary>
Answer: c
Explanation: The output of the code shown will be:
(2, -2)
(4, -4)
(6, -6)
This format is due to the statement print(i).
</details>

## 6. What will be the output of the following Python code?
```python
l1=[10, 20, 30]
l2=[-10, -20, -30]
l3=[x+y for x, y in zip(l1, l2)]
l3
```

a) Error

b) 0

c) [-20, -60, -80]

**d) [0, 0, 0]**


<details>
<summary>detailed</summary>
Answer: d
Explanation: The code shown above returns x+y, for x belonging to the list l1 and y belonging to the list l2. That is, l3=[10-10, 20-20, 30-20], which is, [0, 0, 0].
</details>

## 7. Write a list comprehension for number and its cube for l=[1, 2, 3, 4, 5, 6, 7, 8, 9].

**a) [x**3 for x in l]**

b) [x^3 for x in l]

c) [x**3 in l]

d) [x^3 in l]


<details>
<summary>detailed</summary>
Answer: a
Explanation: The list comprehension to print a list of cube of the numbers for the given list is: [x**3 for x in l].
</details>

## 8. What will be the output of the following Python code?
```python
l=[[1 ,2, 3], [4, 5, 6], [7, 8, 9]]
[[row[i] for row in l] for i in range(3)]
```

a) Error

**b) [[1, 4, 7], [2, 5, 8], [3, 6, 9]]**

c)
```shell
1 4 7
2 5 8
3 6 9
```

d)
```shell
(1 4 7)
(2 5 8)
(3 6 9)
```


<details>
<summary>detailed</summary>
Answer: b
Explanation: In the code shown above, ‘3’ is the index of the list. Had we used a number greater than 3, it would result in an error. The output of this code is: [[1, 4, 7], [2, 5, 8], [3, 6, 9]].
</details>

## 9. What will be the output of the following Python code?
```python
import math
[str(round(math.pi)) for i in range (1, 6)]
```

a) [‘3’, ‘3’, ‘3’, ‘3’, ‘3’, ‘3’]

b) [‘3.1’, ‘3.14’, ‘3.142’, ‘3.1416’, ‘3.14159’, ‘3.141582’]

**c) [‘3’, ‘3’, ‘3’, ‘3’, ‘3’]**

d) [‘3.1’, ‘3.14’, ‘3.142’, ‘3.1416’, ‘3.14159’]


<details>
<summary>detailed</summary>
Answer: c
Explanation: The list comprehension shown above rounds off pi(3.141) and returns its value, that is 3. This is done 5 times. Hence the output is: [‘3’, ‘3’, ‘3’, ‘3’, ‘3’].
</details>

## 10. What will be the output of the following Python code?
```python
l1=[1,2,3]
l2=[4,5,6]
l3=[7,8,9]
for x, y, z in zip(l1, l2, l3):
	print(x, y, z)
```

**a)**
```shell    
1 4 7
2 5 8
3 6 9
```


b)
```shell
(1 4 7)
(2 5 8)
(3 6 9)
```

c) [(1, 4, 7), (2, 5, 8), (3, 6, 9)]
d) Error


<details>
<summary>detailed</summary>
Answer: a
Explanation: The output of the code shown above is:
1 4 7
2 5 8
3 6 9
This is due to the statement: print(x, y,z).
</details>

### Python Questions and Answers – List Comprehension – 2

## 1. Read the information given below carefully and write a list comprehension such that the output is: [‘e’, ‘o’]
```python
w="hello"
v=('a', 'e', 'i', 'o', 'u')
```

a) [x for w in v if x in v]

**b) [x for x in w if x in v]**

c) [x for x in v if w in v]

d) [x for v in w for x in w]


<details>
<summary>detailed</summary>
Answer: b
Explanation: The tuple ‘v’ is used to generate a list containing only vowels in the string ‘w’. The result is a list containing only vowels present in the string “hello”. Hence the required list comprehension is: [x for x in w if x in v].
</details>

## 2. What will be the output of the following Python code?
```python
[ord(ch) for ch in 'abc']
```

**a) [97, 98, 99]**

b) [‘97’, ‘98’, ‘99’]

c) [65, 66, 67]

d) Error


<details>
<summary>detailed</summary>
Answer: a
Explanation: The list comprehension shown above returns the ASCII value of each alphabet of the string ‘abc’. Hence the output is: [97, 98, 99]. Had the string been ‘ABC’, the output would be: [65, 66, 67].
</details>

## 3. What will be the output of the following Python code?
```python
t=32.00
[round((x-32)*5/9) for x in t]
```

a) [0]

b) 0

c) [0.00]

**d) Error**


<details>
<summary>detailed</summary>
Answer: d
Explanation: The value of t in the code shown above is equal to 32.00, which is a floating point value. ‘Float’ objects are not iterable. Hence the code results in an error.
</details>

## 4. Write a list comprehension for producing a list of numbers between 1 and 1000 that are divisible by 3.

a) [x in range(1, 1000) if x%3==0]

**b) [x for x in range(1000) if x%3==0]**

c) [x%3 for x in range(1, 1000)]

d) [x%3=0 for x in range(1, 1000)]

<details>
<summary>detailed</summary>
Answer: b
Explanation: The list comprehension [x for x in range(1000) if x%3==0] produces a list of numbers between 1 and 1000 that are divisible by 3.
</details>

## 5. Write a list comprehension equivalent for the Python code shown below.
```python
for i in range(1, 101):
	if int(i*0.5)==i*0.5:
		print(i)
```

a) [i for i in range(1, 100) if int(i*0.5)==(i*0.5)]

**b) [i for i in range(1, 101) if int(i*0.5)==(i*0.5)]**

c) [i for i in range(1, 101) if int(i*0.5)=(i*0.5)]

d) [i for i in range(1, 100) if int(i*0.5)=(i*0.5)]

<details>
<summary>detailed</summary>
Answer: b
Explanation: The code shown above prints the value ‘i’ only if it satisfies the condition: int(i*0.5) is equal to (i*0.5). Hence the required list comprehension is: [i for i in range(1, 101) if int(i*0.5)==(i*0.5)].
</details>

## 6. What is the list comprehension equivalent for: list(map(lambda x:x**-1, [1, 2, 3]))?

a) [1|x for x in [1, 2, 3]]

b) [-1**x for x in [1, 2, 3]]

**c) [x**-1 for x in [1, 2, 3]]**

d) [x^-1 for x in range(4)]

<details>
<summary>detailed</summary>
Answer: c
Explanation: The output of the function list(map(lambda x:x**-1, [1, 2, 3])) is [1.0, 0.5, 0.3333333333333333] and that of the list comprehension [x**-1 for x in [1, 2, 3]] is [1.0, 0.5, 0.3333333333333333]. Hence the answer is: [x**-1 for x in [1, 2, 3]].
</details>

## 7. Write a list comprehension to produce the list: [1, 2, 4, 8, 16……212].

**a) [(2**x) for x in range(0, 13)]**

b) [(x**2) for x in range(1, 13)]

c) [(2**x) for x in range(1, 13)]

d) [(x**2) for x in range(0, 13)]

<details>
<summary>detailed</summary>
Answer: a
Explanation: The required list comprehension will print the numbers from 1 to 12, each raised to 2. The required answer is thus, [(2**x) for x in range(0, 13)].
</details>

## 8. What is the list comprehension equivalent for?
```python
{x : x is a whole number less than 20, x is even}    (including zero)
```

a) [x for x in range(1, 20) if (x%2==0)]

b) [x for x in range(0, 20) if (x//2==0)]

c) [x for x in range(1, 20) if (x//2==0)]

**d) [x for x in range(0, 20) if (x%2==0)]**

<details>
<summary>detailed</summary>
Answer: d
Explanation: The required list comprehension will print a whole number, less than 20, provided that the number is even. Since the output list should contain zero as well, the answer to this question is: [x for x in range(0, 20) if (x%2==0)].
</details>

## 9. What will be the output of the following Python list comprehension?
```python
[j for i in range(2,8) for j in range(i*2, 50, i)]
```

a) A list of prime numbers up to 50

b) A list of numbers divisible by 2, up to 50

**c) A list of non prime numbers, up to 50**

d) Error

<details>
<summary>detailed</summary>
Answer: c
Explanation: The list comprehension shown above returns a list of non-prime numbers up to 50. The logic behind this is that the square root of 50 is almost equal to 7. Hence all the multiples of 2-7 are not prime in this range.
</details>

## 10. What will be the output of the following Python code?
```python
l=["good", "oh!", "excellent!", "#450"]
[n for n in l if n.isalpha() or n.isdigit()]
```

a) [‘good’, ‘oh’, ‘excellent’, ‘450’ ]

**b) [‘good’]**

c) [‘good’, ‘#450’]

d) [‘oh!’, ‘excellent!’, ‘#450’]

<details>
<summary>detailed</summary>
Answer: b
Explanation: The code shown above returns a new list containing only strings which do not have any punctuation in them. The only string from the list which does not contain any punctuation is ‘good’. Hence the output of the code shown above is [‘good’].
</details>

### Python Questions and Answers – Matrix List Comprehension

## 1. Which of the following matrices will throw an error in Python?
a)
```python
        A = [[1, 2, 3],
        [4, 5, 6],
        [7, 8, 9]]
```

**b)**
```shell
        B = [[3, 3, 3]
        [4, 4, 4]
        [5, 5, 5]]
```

c)
```shell
        C = [(1, 2, 4),
        (5, 6, 7),
        (8, 9, 10)]
```

d)
```shell
        D = [2, 3, 4,
        3, 3, 3,
        4, 5, 6]
```


<details>
<summary>detailed</summary>
Answer: b
Explanation: In matrix B will result in an error because in the absence of a comma at the end of each row, it behaves like three separate lists. The error thrown states that the list integers must be integers or slices, not tuples.
</details>

## 2. What will be the output of the following Python code?
```python
A = [[1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]]
A[1]
```

**a) [4, 5, 6]**

b) [3, 6, 9]

c) [1, 4, 7]

d) [1, 2, 3]


<details>
<summary>detailed</summary>
Answer: a
Explanation: We can index the rows and columns using normal index operations. The statement A[1] represents the second row, that is, the middle row. Hence the output of the code will be: [4, 5, 6].
</details>

## 3. Which of the following Python statements will result in the output: 6?
```python
A = [[1, 2, 3],
     [4, 5, 6],
     [7, 8, 9]]
```

a) A[2][3]

b) A[2][1]

**c) A[1][2]**

d) A[3][2]


<details>
<summary>detailed</summary>
Answer: c
Explanation: The output that is required is 6, that is, row 2, item 3. This position is represented by the statement: A[1][2].
</details>

## 4. What will be the output of the following Python code?
```shell
A = [[1, 2, 3],
      [4, 5, 6],
      [7, 8, 9]]
[A[row][1] for row in (0, 1, 2)]
```

a) [7, 8, 9]

b) [4, 5, 6]

**c) [2, 5, 8]**

d) [1, 4, 7]

<details>
<summary>detailed</summary>
Answer: c
Explanation: To get a particular column as output, we can simple iterate across the rows and pull out the desired column, or iterate through positions in rows and index as we go. Hence the output of the code shown above is: [2, 5, 8].
</details>

## 5. What will be the output of the following Python code?
```python
A = [[1, 2, 3],
     [4, 5, 6],
     [7, 8, 9]]
[A[i][i] for i in range(len(A))]
```

**a) [1, 5, 9]**

b) [3, 5, 7]

c) [4, 5, 6]

d) [2, 5, 8]

<details>
<summary>detailed</summary>
Answer: a
Explanation: We can also perform tasks like pulling out a diagonal. The expression shown above uses range to generate the list of offsets and the indices with the row and column the same, picking out A[0][0], then A[1][1] and so on. Hence the output of the code is: [1, 5, 9].
</details>

## 6. What will be the output of the following Python code?
```shell
l=[[1, 2, 3], [4, 5, 6]]
for i in range(len(l)):
	for j in range(len(l[i])):
		l[i][j]+=10
l
```

a) No output

b) Error

c) [[1, 2, 3], [4, 5, 6]]

**d) [[11, 12, 13], [14, 15, 16]]**

<details>
<summary>detailed</summary>
Answer: d
Explanation: We use range twice if the shapes differ. Each element of list l is increased by 10. Hence the output is: [[11, 12, 13], [14, 15, 16]]
</details>

## 7. What will be the output of the following Python code?
```shell
A = [[1, 2, 3],
     [4, 5, 6],
     [7, 8, 9]]
 
[[col + 10 for col in row] for row in A]
```

**a) [[11, 12, 13], [14, 15, 16], [17, 18, 19]]**

b) Error

c) [11, 12, 13], [14, 15, 16], [17, 18, 19]

d) [11, 12, 13, 14, 15, 16, 17, 18, 19]

<details>
<summary>detailed</summary>
Answer: a
Explanation: The code shown above shows a list comprehension which adds 10 to each element of the matrix A and prints it row-wise. Hence the output of the code is: [[11, 12, 13], [14, 15, 16], [17, 18, 19]]
</details>

## 8. What will be the output of the following Python code?
```python
A = [[1, 2, 3],
     [4, 5, 6],
     [7, 8, 9]]
[A[i][len(A)-1-i] for i in range(len(A))]
```

a) [1, 5, 9]

b) [4, 5, 6]

**c) [3, 5, 7]**

d) [2, 5, 8]

<details>
<summary>detailed</summary>
Answer: c
Explanation: This expression scales the common index to fetch A[0][2], A[1][1], etc. We assume the matrix has the same number of rows and columns.
</details>

## 9. What will be the output of the following Python code?
```python
A = [[1, 2, 3],
     [4, 5, 6],
     [7, 8, 9]]
B = [[3, 3, 3],
     [4, 4, 4],
     [5, 5, 5]]
[B[row][col]*A[row][col] for row in range(3) for col in range(3)]
```

**a) [3, 6, 9, 16, 20, 24, 35, 40, 45]**

b) Error

c) [0, 30, 60, 120, 160, 200, 300, 350, 400]

d) 0

<details>
<summary>detailed</summary>
Answer: a
Explanation: In the code shown above, we have used list comprehension to combine values of multiple matrices. We have multiplied the elements of the matrix B with that of the matrix A, in the range(3). Hence the output of this code is: [3, 6, 9, 16, 20, 24, 35, 40, 45].
</details>

## 10. What will be the output of the following Python code?
```python
r = [11, 12, 13, 14, 15, 16, 17, 18, 19]
A = [[0, 10, 20],
               [30, 40, 50],
               [60, 70, 80]]
for row in A:
	for col in row:
		r.append(col+10)
r
```

**a) [11, 12, 13, 14, 15, 16, 17, 18, 19, 10, 20, 30, 40, 50, 60, 70, 80, 90]**

b) [10, 20, 30, 40, 50, 60, 70, 80, 90]

c) [11, 12, 13, 14, 15, 16, 17, 18, 19]

d) [0, 10, 20, 30, 40, 50, 60, 70, 80]

<details>
<summary>detailed</summary>
Answer: a
Explanation: The code shown above adds 10 to each element of the matrix and prints the output row-wise. Since the list l already contains some elements, the new elements are appended to it. Hence the output of this code is: [11, 12, 13, 14, 15, 16, 17, 18, 19, 10, 20, 30, 40, 50, 60, 70, 80, 90].
</details>

## 11. What will be the output of the following Python code?
```python
A = [[1, 2, 3],
     [4, 5, 6],
     [7, 8, 9]]
B = [[3, 3, 3],
     [4, 4, 4],
     [5, 5, 5]]
[[col1 * col2 for (col1, col2) in zip(row1, row2)] for (row1, row2) in zip(A, B)]
```

a) [0, 30, 60, 120, 160, 200, 300, 350, 400]

**b) [[3, 6, 9], [16, 20, 24], [35, 40, 45]]**

c) No output

d) Error

<details>
<summary>detailed</summary>
Answer: b
Explanation: The list comprehension shown above results in the output: [[3, 6, 9], [16, 20, 24], [35, 40, 45]].
</details>

## 12. What will be the output of the following Python code?
```python
A = [[1, 2, 3],
     [4, 5, 6],
     [7, 8, 9]]
B = [[3, 3, 3],
     [4, 4, 4],
     [5, 5, 5]]
zip(A, B)
```

**a) Address of the zip object**

b) Address of the matrices A and B

c) No output

d) [3, 6, 9, 16, 20, 24, 35, 40, 45]

<details>
<summary>detailed</summary>
Answer: a
Explanation: The output of the code shown above returns the address of the zip object. If we print it in the form of a list, we get:
>>> list(zip(A, B))
[([1, 2, 3], [3, 3, 3]), ([4, 5, 6], [4, 4, 4]), ([7, 8, 9], [5, 5, 5])]
</details>

### Python Questions and Answers – Tuples – 1

## 1. Which of the following is a Python tuple?

a) [1, 2, 3]

**b) (1, 2, 3)**

c) {1, 2, 3}

d) {}

<details>
<summary>detailed</summary>
Answer: b
Explanation: Tuples are represented with round brackets.
</details>

## 2. Suppose t = (1, 2, 4, 3), which of the following is incorrect?

a) print(t[3])

**b) t[3] = 45**

c) print(max(t))

d) print(len(t))

<details>
<summary>detailed</summary>
Answer: b
Explanation: Values cannot be modified in the case of tuple, that is, tuple is immutable. 
</details>

## 3. What will be the output of the following Python code?
```python
    >>>t=(1,2,4,3)

    >>>t[1:3]
```

a) (1, 2)

b) (1, 2, 4)

**c) (2, 4)**

d) (2, 4, 3)


<details>
<summary>detailed</summary>
Answer: c
Explanation: Slicing in tuples takes place just as it does in strings. 
</details>

## 4. What will be the output of the following Python code?
```shell
    >>>t=(1,2,4,3)

    >>>t[1:-1]
```

a) (1, 2)

b) (1, 2, 4)

**c) (2, 4)**

d) (2, 4, 3)

<details>
<summary>detailed</summary>
Answer: c
Explanation: Slicing in tuples takes place just as it does in strings.
</details>

## 5. What will be the output of the following Python code?
```python
    >>>t = (1, 2, 4, 3, 8, 9)

    >>>[t[i] for i in range(0, len(t), 2)]
```

a) [2, 3, 9]

b) [1, 2, 4, 3, 8, 9]

**c) [1, 4, 8]**

d) (1, 4, 8)

<details>
<summary>detailed</summary>
Answer: c
Explanation: Execute in the shell to verify.
</details>

## 6. What will be the output of the following Python code?
```shell
    d = {"john":40, "peter":45}

    d["john"]
```

**a) 40**

b) 45

c) “john”

d) “peter”

<details>
<summary>detailed</summary>
Answer: a
Explanation: Execute in the shell to verify. 
</details>

## 7. What will be the output of the following Python code?
```shell
    >>>t = (1, 2)

    >>>2 * t
```

**a) (1, 2, 1, 2)**

b) [1, 2, 1, 2]

c) (1, 1, 2, 2)

d) [1, 1, 2, 2]

<details>
<summary>detailed</summary>
Answer: a
Explanation: * operator concatenates tuple.
</details>

## 8. What will be the output of the following Python code?
```python
    >>>t1 = (1, 2, 4, 3)

    >>>t2 = (1, 2, 3, 4)

    >>>t1 < t2
```

a) True

**b) False**

c) Error

d) None

<details>
<summary>detailed</summary>
Answer: b
Explanation: Elements are compared one by one in this case.
</details>

## 9. What will be the output of the following Python code?
```python
    >>>my_tuple = (1, 2, 3, 4)

    >>>my_tuple.append( (5, 6, 7) )

    >>>print len(my_tuple)
```

a) 1

b) 2

c) 5

**d) Error**

<details>
<summary>detailed</summary>
Answer: d
Explanation: Tuples are immutable and don’t have an append method. An exception is thrown in this case.
</details>

## 10. What will be the output of the following Python code?
```python
    numberGames = {}
    numberGames[(1,2,4)] = 8
    numberGames[(4,2,1)] = 10
    numberGames[(1,2)] = 12
    sum = 0
    
    for k in numberGames:
        sum += numberGames[k]
        
    print len(numberGames) + sum
```

a) 30

b) 24

**c) 33**

d) 12

<details>
<summary>detailed</summary>
Answer: c
Explanation: Tuples can be used for keys into dictionary. The tuples can have mixed length and the order of the items in the tuple is considered when comparing the equality of the keys.
</details>

# Section 13

## 1. What is the data type of (1)? [Який тип даних у (1)?]

a) Tuple

**b) Integer**

c) List

d) Both tuple and integer

> Explanation: A tuple of one element must be created as (1,).

## 2. If a=(1,2,3,4), a[1:-1] is \***\*\_\*\*** [Якщо a=(1,2,3,4), a[1:-1] є \***\*\_\*\***]

a) Error, tuple slicing doesn’t exist

b) [2,3]

c) (2,3,4)

**d) (2,3)**

> Explanation: Tuple slicing exists and a[1:-1] returns (2,3).

## 3. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a=(1,2,(4,5))
>
> b=(1,2,(3,4))
>
> a<b

**a) False**

b) True

c) Error, < operator is not valid for tuples

d) Error, < operator is valid for tuples but not if there are sub-tuples

> Explanation: Since the first element in the sub-tuple of a is larger that the first element in the subtuple of b, False is printed.

## 4. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a=("Check")\*3
>
> a

a) (‘Check’,’Check’,’Check’)

b) \* Operator not valid for tuples

**c) (‘CheckCheckCheck’)**

d) Syntax error

> Explanation: Here (“Check”) is a string not a tuple because there is no comma after the element.

## 5. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a=(1,2,3,4)
>
> del(a[2])

a) Now, a=(1,2,4)

b) Now, a=(1,3,4)

c) Now a=(3,4)

**d) Error as tuple is immutable**

> Explanation: ‘tuple’ object doesn’t support item deletion.

## 6. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a=(2,3,4)
>
> sum(a,3)

a) Too many arguments for sum() method

b) The method sum() doesn’t exist for tuples

**c) 12**

d) 9

> Explanation: In the above case, 3 is the starting value to which the sum of the tuple is added to.

## 7. Is the following Python code valid? [Чи правильний цей Python код?]

> a=(1,2,3,4)
>
> del a

a) No because tuple is immutable

b) Yes, first element in the tuple is deleted

**c) Yes, the entire tuple is deleted**

d) No, invalid syntax for del method

> Explanation: The command del a deletes the entire tuple.

## 8. What type of data is: a=[(1,1),(2,4),(3,9)]? [Яким типом даних є a=[(1,1),(2,4),(3,9)]?]

a) Array of tuples

**b) List of tuples**

c) Tuples of lists

d) Invalid type

> Explanation: The variable a has tuples enclosed in a list making it a list of tuples.

## 9. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a=(0,1,2,3,4)
>
> b=slice(0,2)
>
> a[b]

a) Invalid syntax for slicing

b) [0,2]

**c) (0,1)**

d) (0,2)

> Explanation: The method illustrated in the above piece of code is that of naming of slices.

## 10. Is the following Python code valid? [Чи правильний цей Python код?]

> a=(1,2,3)
>
> b=('A','B','C')
>
> c=tuple(zip(a,b))

**a) Yes, c will be ((1, ‘A’), (2, ‘B’), (3, ‘C’))**

b) Yes, c will be ((1,2,3),(‘A’,’B’,’C’))

c) No because tuples are immutable

d) No because the syntax for zip function isn’t valid

> Explanation: Zip function combines individual elements of two iterables into tuples. Execute in Python shell to verify.

## 1. Is the following Python code valid? [Чи правильний цей Python код?]

> a,b,c=1,2,3
>
> a,b,c

a) Yes, [1,2,3] is printed

b) No, invalid syntax

**c) Yes, (1,2,3) is printed**

d) 1 is printed

> Explanation: A tuple needn’t be enclosed in parenthesis.

## 2. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

a = ('check',)
n = 2
for i in range(int(n)):
a = (a,)
print(a)

a) Error, tuples are immutable

**b)**

**(('check',),)**

**((('check',),),)**

c) ((‘check’,)’check’,)

d)

(('check',)’check’,)

((('check',)’check’,)’check’,)

> Explanation: The loop runs two times and each time the loop runs an extra parenthesis along with a comma is added to the tuple (as a=(a’)).

## 3. Is the following Python code valid? [Чи правильний цей Python код?]

> a,b=1,2,3

a) Yes, this is an example of tuple unpacking. a=1 and b=2

b) Yes, this is an example of tuple unpacking. a=(1,2) and b=3

**c) No, too many values to unpack**

d) Yes, this is an example of tuple unpacking. a=1 and b=(2,3)

> Explanation: For unpacking to happen, the number of values of the right hand side must be equal to the number of variables on the left hand side.

## 4. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a=(1,2)
>
> b=(3,4)
>
> c=a+b
>
> c

a) (4,6)

**b) (1,2,3,4)**

c) Error as tuples are immutable

d) None

> Explanation: In the above piece of code, the values of the tuples aren’t being changed. Both the tuples are simply concatenated.

## 5. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a,b=6,7
>
> a,b=b,a
>
> a,b

a) (6,7)

b) Invalid syntax

**c) (7,6)**

d) Nothing is printed

> Explanation: The above piece of code illustrates the unpacking of variables.

## 6. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> import collections
>
> a=collections.namedtuple('a',['i','j'])
>
> obj=a(i=4,j=7)
>
> obj

**a) a(i=4, j=7)**

b) obj(i=4, j=7)

c) (4,7)

d) An exception is thrown

> Explanation: The above piece of code illustrates the concept of named tuples.

## 7. Tuples can’t be made keys of a dictionary. [Чи можуть кортежі бути ключами словника]

a) True

**b) False**

> Explanation: Tuples can be made keys of a dictionary because they are hashable.

## 8. Is the following Python code valid? [Чи правильний цей Python код?]

> a=2,3,4,5
>
> a

a) Yes, 2 is printed

b) Yes, [2,3,4,5] is printed

c) No, too many values to unpack

**d) Yes, (2,3,4,5) is printed**

> Explanation: A tuple needn’t be enclosed in parenthesis.

## 9. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a=(2,3,1,5)
>
> a.sort()
>
> a

a) (1,2,3,5)

b) (2,3,1,5)

c) None

**d) Error, tuple has no attribute sort**

> Explanation: A tuple is immutable thus it doesn’t have a sort attribute.

## 10. Is the following Python code valid? [Чи правильний цей Python код?]

> a=(1,2,3)
>
> b=a.update(4,)

a) Yes, a=(1,2,3,4) and b=(1,2,3,4)

b) Yes, a=(1,2,3) and b=(1,2,3,4)

**c) No because tuples are immutable**

d) No because wrong syntax for update() method

> Explanation: Tuple doesn’t have any update() attribute because it is immutable.

## 11. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a=[(2,4),(1,2),(3,9)]
>
> a.sort()
>
> a

**a) [(1, 2), (2, 4), (3, 9)]**

b) [(2,4),(1,2),(3,9)]

c) Error because tuples are immutable

d) Error, tuple has no sort attribute

> Explanation: A list of tuples is a list itself. Hence items of a list can be sorted.

## 1. Which of these about a set is not true? [Що з цього про сети не є правдою?]

a) Mutable data type

b) Allows duplicate values

c) Data type with unordered values

**d) Immutable data type**

> Explanation: A set is a mutable data type with non-duplicate, unordered values, providing the usual mathematical set operations.

## 2. Which of the following is not the correct syntax for creating a set? [Що з цього це не є правильним синтаксисом створення сету?]

**a) set([[1,2],[3,4]])**

b) set([1,2,2,3,4])

c) set((1,2,3,4))

d) {1,2,3,4}

> Explanation: The argument given for the set must be an iterable.

## 3. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> nums = set([1,1,2,3,3,3,4,4])
>
> print(len(nums))

a) 7

b) Error, invalid syntax for formation of set

**c) 4**

d) 8

> Explanation: A set doesn’t have duplicate items.

## 4. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a = [5,5,6,7,7,7]
>
> b = set(a)
>
> def test(lst):
>
> if lst in b:
>
>       return 1
>
> else:
>
>        return 0
>
> for i in filter(test, a):
>
> print(i,end=" ")

a) 5 5 6

b) 5 6 7

**c) 5 5 6 7 7 7**

d) 5 6 7 7 7

> Explanation: The filter function will return all the values from list a which are true when passed to function test. Since all the members of the set are non-duplicate members of the list, all of the values will return true. Hence all the values in the list are printed.

## 5. Which of the following statements is used to create an empty set? [Що використовується для створення пустого сету?]

a) { }

**b) set()**

c) [ ]

d) ( )

> Explanation: { } creates a dictionary not a set. Only set() creates an empty set.

## 6. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={5,4}
>
> b={1,2,4,5}
>
> a<b

a) {1,2}

**b) True**

c) False

d) Invalid operation

> Explanation: a<b returns True if a is a proper subset of b.

## 7. If a={5,6,7,8}, which of the following statements is false? [Якщо a={5,6,7,8}, що з цього неправда?]

a) print(len(a))

b) print(min(a))

c) a.remove(5)

**d) a[2]=45**

> Explanation: The members of a set can be accessed by their index values since the elements of the set are unordered.

## 8. If a={5,6,7}, what happens when a.add(5) is executed? [Якщо a={5,6,7}, що відбудеться після виконання a.add(5)?]

a) a={5,5,6,7}

**b) a={5,6,7}**

c) Error as there is no add function for set data type

d) Error as 5 already exists in the set

> Explanation: There exists add method for set data type. However 5 isn’t added again as set consists of only non-duplicate elements and 5 already exists in the set. Execute in python shell to verify.

## 9. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={4,5,6}
>
> b={2,8,6}
>
> a+b

a) {4,5,6,2,8}

b) {4,5,6,2,8,6}

**c) Error as unsupported operand type for sets**

d) Error as the duplicate item 6 is present in both sets

> Explanation: Execute in python shell to verify.

# 10. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={4,5,6}
>
> b={2,8,6}
>
> a-b

**a) {4,5}**

b) {6}

c) Error as unsupported operand type for set data type

d) Error as the duplicate item 6 is present in both sets

> Explanation: – operator gives the set of elements in set a but not in set b.

## 11. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={5,6,7,8}
>
> b={7,8,10,11}
>
> a^b

a) {5,6,7,8,10,11}

b) {7,8}

c) Error as unsupported operand type of set data type

**d) {5,6,10,11}**

> Explanation: ^ operator returns a set of elements in set A or set B, but not in both (symmetric difference).

## 12. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> s={5,6}
>
> s\*3

**a) Error as unsupported operand type for set data type**

b) {5,6,5,6,5,6}

c) {5,6}

d) Error as multiplication creates duplicate elements which isn’t allowed

> Explanation: The multiplication operator isn’t valid for the set data type.

## 13. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={5,6,7,8}
>
> b={7,5,6,8}
>
> a==b

**a) True**

b) False

> Explanation: It is possible to compare two sets and the order of elements in both the sets doesn’t matter if the values of the elements are the same.

## 14. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={3,4,5}
>
> b={5,6,7}
>
> a|b

a) Invalid operation

**b) {3, 4, 5, 6, 7}**

c) {5}

d) {3,4,6,7}

> Explanation: The operation in the above piece of code is union operation. This operation produces a set of elements in both set a and set b.

## 15. Is the following Python code valid? [Чи правильний цей Python код?]

> a={3,4,{7,5}}
>
> print(a[2][0])

a) Yes, 7 is printed

b) Error, elements of a set can’t be printed

**c) Error, subsets aren’t allowed**

d) Yes, {7,5} is printed

> Explanation: In python, elements of a set must not be mutable and sets are mutable. Thus, subsets can’t exist.

# 1. Which of these about a frozenset is not true? [Що з цього про frozenset не є правдою?]

**a) Mutable data type**

b) Allows duplicate values

c) Data type with unordered values

d) Immutable data type

> Explanation: A frozenset is an immutable data type.

## 2. What is the syntax of the following Python code? [Що є синтаксисом цього Python коду?]

> a=frozenset(set([5,6,7]))
>
> a

a) {5,6,7}

**b) frozenset({5,6,7})**

c) Error, not possible to convert set into frozenset

d) Syntax error

> Explanation: The above piece of code is the correct syntax for creating a frozenset.

## 3. Is the following Python code valid? [Чи правильний цей Python код?]

> a=frozenset([5,6,7])
>
> a
>
> a.add(5)

a) Yes, now a is {5,5,6,7}

**b) No, frozen set is immutable**

c) No, invalid syntax for add method

d) Yes, now a is {5,6,7}

> Explanation: Since a frozen set is immutable, add method doesn’t exist for frozen method.

## 4. Set members must not be hashable. [Елементи сету не мають бути хешованими]

a) True

**b) False**

> Explanation: Set members must always be hashable.

## 5. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={3,4,5}
>
> a.update([1,2,3])
>
> a

a) Error, no method called update for set data type

**b) {1, 2, 3, 4, 5}**

c) Error, list can’t be added to set

d) Error, duplicate item present in list

> Explanation: The method update adds elements to a set.

## 6. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={1,2,3}
>
> a.intersection_update({2,3,4,5})
>
> a

**a) {2,3}**

b) Error, duplicate item present in list

c) Error, no method called intersection_update for set data type

d) {1,4,5}

> Explanation: The method intersection_update returns a set which is an intersection of both the sets.

# 7. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={1,2,3}
>
> b=a
>
> b.remove(3)
>
> a

a) {1,2,3}

b) Error, copying of sets isn’t allowed

**c) {1,2}**

d) Error, invalid syntax for remove

> Explanation: Any change made in b is reflected in a because b is an alias of a.

# 8. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={1,2,3}
>
> b=a.copy()
>
> b.add(4)
>
> a

**a) {1,2,3}**

b) Error, invalid syntax for add

c) {1,2,3,4}

d) Error, copying of sets isn’t allowed

> Explanation: In the above piece of code, b is barely a copy and not an alias of a. Hence any change made in b isn’t reflected in a.

## 9. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={1,2,3}
>
> b=a.add(4)
>
> b

a) 0

b) {1,2,3,4}

c) {1,2,3}

**d) Nothing is printed**

> Explanation: The method add returns nothing, hence nothing is printed.

## 10. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={1,2,3}
>
> b=frozenset([3,4,5])
>
> a-b

**a) {1,2}**

b) Error as difference between a set and frozenset can’t be found out

c) Error as unsupported operand type for set data type

d) frozenset({1,2})

> Explanation: – operator gives the set of elements in set a but not in set b.

## 11. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={5,6,7}
>
> sum(a,5)

a) 5

**b) 23**

c) 18

d) Invalid syntax for sum method, too many arguments

> Explanation: The second parameter is the start value for the sum of elements in set a. Thus, sum(a,5) = 5+(5+6+7)=23.

## 12. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={1,2,3}
>
> {x\*2 for x in a|{4,5}}

a) {2,4,6}

b) Error, set comprehensions aren’t allowed

**c) {8, 2, 10, 4, 6}**

d) {8,10}

> Explanation: Set comprehensions are allowed.

## 13. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={5,6,7,8}
>
> b={7,8,9,10}
>
> len(a+b)

a) 8

**b) Error, unsupported operand ‘+’ for sets**

c) 6

d) Nothing is displayed

> Explanation: Duplicate elements in a+b is eliminated and the length of a+b is computed.

## 14. What will be the output of the following Python code? [Що буде результатом цього Python коду?]

> a={1,2,3}
>
> b={1,2,3}
>
> c=a.issubset(b)
>
> print(c)

**a) True**

b) Error, no method called issubset() exists

c) Syntax error for issubset() method

d) False

> Explanation: The method issubset() returns True if b is a proper subset of a.

## 15. Is the following Python code valid? [Чи правильний цей Python код?]

> a={1,2,3}
>
> b={1,2,3,4}
>
> c=a.issuperset(b)
>
> print(c)

**a) False**

b) True

c) Syntax error for issuperset() method

d) Error, no method called issuperset() exists

> Explanation: The method issubset() returns True if b is a proper subset of a.

# Section 14

## 1. What will be the output of the following Python code?

```
s=set()
type(s)
```
a) <’set’>
	
**b) <class ‘set’>**
	
c) set
	
d) class set
	
## 2. The following Python code results in an error.

> s={2, 3, 4, [5, 6]}

**a) True**
	
b) False

Explanation: The set data type makes use of a principle known as hashing. This means that each item in the set should be hashable. Hashable in this context means immutable. List is mutable and hence the line of code shown above will result in an error.
	
## 3. Set makes use of __________ Dictionary makes use of ____________

a) keys, keys

b) key values, keys

**c) keys, key values**

d) key values, key values
	
## 4. Which of the following lines of code will result in an error?

a) s={abs}
	
b) s={4, ‘abc’, (1,2)}
	
c) s={2, 2.2, 3, ‘xyz’}
	
**d) s={san}**
	
Explanation: The line: s={san} will result in an error because ‘san’ is not defined. The line s={abs} does not result in an error because abs is a built-in function. The other sets shown do not result in an error because all the items are hashable.
	
## 5. What will be the output of the following Python code?

> s={2, 5, 6, 6, 7}

a) {2, 5, 7}
	
**b) {2, 5, 6, 7}**
	
c) {2, 5, 6, 6, 7}
	
d) Error
	
## 6. Input order is preserved in sets.

a) True
	
**b) False**
	
## 7. Write a list comprehension for number and its cube for:

> l=[1, 2, 3, 4, 5, 6, 7, 8, 9]
	
**a) [x\*\*3 for x in l]**
	
b) [x^3 for x in l]
	
c) [x**3 in l]
	
d) [x^3 in l]
	
## 8. What will be the output of the following Python code?

```
s={1, 2, 3}
s.update(4)
s
```
	
a) {1, 2, 3, 4}
	
b) {1, 2, 4, 3}
	
c) {4, 1, 2, 3}
	
**d) Error**
	
Explanation: The code shown above will result in an error because the argument given to the function update should necessarily be an iterable. Hence if we write this function as: s.update([4]), there will be no error.
	
## 9. Which of the following functions cannot be used on heterogeneous sets?
	
a) pop
	
b) remove
	
c) update
	
**d) sum**
	
Explanation: The functions sum, min and max cannot be used on mixed type (heterogeneous) sets. The functions pop, remove, update etc can be used on homogenous as well as heterogeneous sets. An example of heterogeneous sets is: {‘abc’, 4, (1, 2)}

## 10. What will be the output of the following Python code?

```
s={4>3, 0, 3-3}
all(s)
any(s)
```

a)
```
True
False
```
	
**b)**
```
False
True
```
	
c)	
```
True 
True
```

d)
```
False
False
```
	
## 1. Which of the following functions will return the symmetric difference between two sets, x and y?
	
a) x | y
	
**b) x \^ y** 
	
c) x & y
	
d) x – y
	
Explanation: The function x ^ y returns the symmetric difference between the two sets x and y. This is basically an XOR operation being performed on the two sets.
	
## 2. What will be the output of the following Python code snippet?

```
z=set('abc$de')
'a' in z
```
	
**a) True**
	
b) False
	
c) No output
	
d) Error
	
Explanation: The code shown above is used to check whether a particular item is a part of a given set or not. Since ‘a’ is a part of the set z, the output is true. Note that this code would result in an error in the absence of the quotes.

## 3. What will be the output of the following Python code snippet?

```
z=set('abc')
z.add('san')
z.update(set(['p', 'q']))
z
```
	
a) {‘abc’, ‘p’, ‘q’, ‘san’}
	
b) {‘a’, ‘b’, ‘c’, [‘p’, ‘q’], ‘san}
	
c) {‘a’, ‘c’, ‘c’, ‘p’, ‘q’, ‘s’, ‘a’, ‘n’}
	
**d) {‘a’, ‘b’, ‘c’, ‘p’, ‘q’, ‘san’}**
	
## 4. What will be the output of the following Python code snippet?

```
s=set([1, 2, 3])
s.union([4, 5])
s|([4, 5])
```

a)
```
   {1, 2, 3, 4, 5}
   {1, 2, 3, 4, 5}
```

b)
```
   Error
   {1, 2, 3, 4, 5}
```

**c)**
```
   {1, 2, 3, 4, 5}
   Error
```
	
d)
```
   Error
   Error
```
	
## 5. What will be the output of the following Python code snippet?

```
for x in set('pqr'):
	print(x*2)
```

**a)**
```
pp
qq
rr
```

b)
```
pqr
pqr
```
	
c) ppqqrr
	
d) pqrpqr

## 6. What will be the output of the following Python code snippet?

> {a**2 for a in range(4)}
	
a) {1, 4, 9, 16}
	
b) {0, 1, 4, 9, 16}
	
c) Error
	
**d) {0, 1, 4, 9}**
	
## 7. What will be the output of the following Python function?

```
{x for x in 'abc'}
{x*3 for x in 'abc'}
```

a)
```
    {abc}
    aaa
    bbb
    ccc
```

b)
```
   abc
   abc abc abc
```
	
**c)**
```
   {‘a’, ‘b’, ‘c’}
   {‘aaa’, ‘bbb’, ‘ccc’}
```
	
d)
```
    {‘a’, ‘b’, ‘c’}
    abc
    abc
    abc
```

## 8. The output of the following code is: class<’set’>.

> type({})
	
a) True
	
**b) False**
	
## 9. What will be the output of the following Python code snippet?

```
a=[1, 4, 3, 5, 2]
b=[3, 1, 5, 2, 4]
a==b
set(a)==set(b)
```
	
a)
```
   True
   False
```
	
b)
```
   False
   False
```
	
**c)**
```
   False
   True
```

d)
```
   True
   True
```
	
## 10. What will be the output of the following Python code snippet?

```
l=[1, 2, 4, 5, 2, 'xy', 4]
set(l)
l
```
	
a)
```
{1, 2, 4, 5, 2, ‘xy’, 4}
[1, 2, 4, 5, 2, ‘xy’, 4]
```

**b)**
```
{1, 2, 4, 5, ‘xy’}
[1, 2, 4, 5, 2, ‘xy’, 4]
```
	
c)
```
{1, 5, ‘xy’}
[1, 5, ‘xy’]
```
	
d)
```
{1, 2, 4, 5, ‘xy’}
[1, 2, 4, 5, ‘xy’]
```

## 1. What will be the output of the following Python code?

```
s1={3, 4}
s2={1, 2}
s3=set()
i=0
j=0
for i in s1:
    for j in s2:
        s3.add((i,j))
        i+=1
        j+=1
print(s3)
```
	
a) {(3, 4), (1, 2)}
	
b) Error
	
**c) {(4, 2), (3, 1), (4, 1), (5, 2)}**
	
d) {(3, 1), (4, 2)}
	
Explanation: The code shown above finds the Cartesian product of the two sets, s1 and s2. The Cartesian product of these two sets is stored in a third set, that is, s3. Hence the output of this code is: {(4, 2), (3, 1), (4, 1), (5, 2)}.
	
## 2. The ____________ function removes the first element of a set and the last element of a list.

a) remove
	
**b) pop**
	
c) discard
	
d) dispose
	
Explanation: The function pop removes the first element when used on a set and the last element when used to a list.
	
## 3. The difference between the functions discard and remove is that:
	
a) Discard removes the last element of the set whereas remove removes the first element of the set
	
b) Discard throws an error if the specified element is not present in the set whereas remove does not throw an error in case of absence of the specified element
	
c) Remove removes the last element of the set whereas discard removes the first element of the set
	
**d) Remove throws an error if the specified element is not present in the set whereas discard does not throw an error in case of absence of the specified element**
	
Explanation: The function remove removes the element if it is present in the set. If the element is not present, it throws an error. The function discard removes the element if it is present in the set. If the element is not present, no action is performed (Error is not thrown).
	
## 4. What will be the output of the following Python code?

```
s1={1, 2, 3}
s2={3, 4, 5, 6}
s1.difference(s2)
s2.difference(s1)
```
	
**a)**
```
{1, 2}
{4, 5, 6}
```
b)
```
{1, 2}
{1, 2}
```
c)
```
{4, 5, 6}
{1, 2}
```
d)
```
{4, 5, 6}
{4, 5, 6}
```

Explanation: The function s1.difference(s2) returns a set containing the elements which are present in the set s1 but not in the set s2. Similarly, the function s2.difference(s1) returns a set containing elements which are present in the set s2 but not in the set s1. Hence the output of the code shown above will be:
{1, 2}
{4, 5, 6}.
	
## 5. What will be the output of the following Python code?

```
s1={1, 2, 3}
s2={4, 5, 6}
s1.isdisjoint(s2)
s2.isdisjoint(s1)
```
	
a)
```
True
False
```
b)
```
False 
True
```
**c)**
```
True
True
```
d)
```
False
False
```
	
## 6. If we have two sets, s1 and s2, and we want to check if all the elements of s1 are present in s2 or not, we can use the function:
	
a) s2.issubset(s1)
	
**b) s2.issuperset(s1)**
	
c) s1.issuperset(s2)
	
d) s1.isset(s2)
	
## 7. What will be the output of the following Python code?

```
s1={1, 2, 3, 8}
s2={3, 4, 5, 6}
s1|s2
s1.union(s2)
```
a)
```
{3}
{1, 2, 3, 4, 5, 6, 8}
```
b)
```
{1, 2, 4, 5, 6, 8}
{1, 2, 4, 5, 6, 8}
```
c)
```
{3}
{3}
```
**d)**
```
{1, 2, 3, 4, 5, 6, 8}
{1, 2, 3, 4, 5, 6, 8}
```
	
Explanation: The function s1|s2 as well as the function s1.union(s2) returns a union of the two sets s1 and s2. Hence the output of both of these functions is: {1, 2, 3, 4, 5, 6, 8}.
	
## 8. What will be the output of the following Python code?

```
a=set('abc')
b=set('def')
b.intersection_update(a)
a
b
```
	
a)
```
set()
(‘e’, ‘d’, ‘f’}
```
b)
```
{}
{}
```
**c)**
```
{‘b’, ‘c’, ‘a’}
set()
```
d)
```
set()
set()
```
	
## 9. What will be the output of the following Python code, if s1= {1, 2, 3}?

> s1.issubset(s1)
	
**a) True**
	
b) Error
	
c) No output
	
d) False
	
## 10. What will be the output of the following Python code?

```
x=set('abcde')
y=set('xyzbd')
x.difference_update(y)
x
y
```
	
a)
```
   {‘a’, ‘b’, ‘c’, ‘d’, ‘e’}
   {‘x’, ‘y’, ‘z’}
```
**b)**
```
   {‘a’, ‘c’, ‘e’}
   {‘x’, ‘y’, ‘z’, ‘b’, ‘d’}
```
c)
```
   {‘b’, ‘d’}
   {‘b’, ‘d’}
```
d)
```
   {‘a’, ‘c’, ‘e’}
   {‘x’, ‘y’, ‘z’}
```
	
Explanation: The function x.difference_update(y) removes all the elements of the set y from the set x. Hence the output of the code is:
{‘a’, ‘c’, ‘e’}
{‘x’, ‘y’, ‘z’, ‘b’, ‘d’}.
	
## 1. Which of the following statements create a dictionary?
	
a) d = {}
	
b) d = {“john”:40, “peter”:45}
	
c) d = {40:”john”, 45:”peter”}
	
**d) All of the mentioned**
	
Explanation: Dictionaries are created by specifying keys and values.
	
## 2. What will be the output of the following Python code snippet?

> d = {"john":40, "peter":45}
	
a) “john”, 40, 45, and “peter”
	
**b) “john” and “peter”** 
	
c) 40 and 45
	
d) d = (40:”john”, 45:”peter”)
	
Answer: b
Explanation: Dictionaries appear in the form of keys and values.

Если делать print, будет {'john': 40, 'peter': 45}, но тут нет такого варианта ответа (может d?)
	
## 3. What will be the output of the following Python code snippet?

```
d = {"john":40, "peter":45}
"john" in d
```
	
**a) True**
	
b) False
	
c) None
	
d) Error
	
## 4. What will be the output of the following Python code snippet?

```
d1 = {"john":40, "peter":45}
d2 = {"john":466, "peter":45}
d1 == d2
```
	
a) True
	
**b) False**
	
c) None
	
d) Error
	
## 5. What will be the output of the following Python code snippet?

```
d1 = {"john":40, "peter":45}
d2 = {"john":466, "peter":45}
d1 > d2
```
	
a) True
	
b) False
	
**c) Error**
	
d) None

## 6. What will be the output of the following Python code snippet?

```
d = {"john":40, "peter":45}
d["john"]
```
	
**a) 40**
	
b) 45
	
c) “john”
	
d) “peter”
	
## 7. Suppose d = {“john”:40, “peter”:45}, to delete the entry for “john” what command do we use?
	
a) d.delete(“john”:40)
	
b) d.delete(“john”)
	
**c) del d[“john”]**
	
d) del d(“john”:40)
	
## 8. Suppose d = {“john”:40, “peter”:45}. To obtain the number of entries in dictionary which command do we use?

a) d.size()
	
**b) len(d)**
	
c) size(d)
	
d) d.len()
	
## 9. What will be the output of the following Python code snippet?

```
d = {"john":40, "peter":45}
print(list(d.keys()))
```
	
**a) [“john”, “peter”]**
	
b) [“john”:40, “peter”:45]
	
c) (“john”, “peter”)
	
d) (“john”:40, “peter”:45)
	
## 10. Suppose d = {“john”:40, “peter”:45}, what happens when we try to retrieve a value using the expression d[“susan”]?
	
a) Since “susan” is not a value in the set, Python raises a KeyError exception
	
b) It is executed fine and no exception is raised, and it returns None
	
**c) Since “susan” is not a key in the set, Python raises a KeyError exception**
	
d) Since “susan” is not a key in the set, Python raises a syntax error

# Section 15

## 1. Which of these about a dictionary is false?[Що з наведеного вище неправильно]

a) The values of a dictionary can be accessed using keys

**b) The keys of a dictionary can be accessed using values**

c) Dictionaries aren’t ordered

d) Dictionaries are mutable

Explanation: The values of a dictionary can be accessed using keys but the keys of a dictionary can’t be accessed using values.

## 2. Which of the following is not a declaration of the dictionary?[Що не є визначенням словника]

a) {1: ‘A’, 2: ‘B’}

b) dict([[1,”A”],[2,”B”]])

**c) {1,”A”,2”B”}**

d) { }

Explanation: Option c is a set, not a dictionary.

## 3. What will be the output of the following Python code snippet?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> for i,j in a.items():
>
> print(i,j,end=" ")

**a) 1 A 2 B 3 C**

b) 1 2 3

c) A B C

d) 1:”A” 2:”B” 3:”C”

Explanation: In the above code, variables i and j iterate over the keys and values of the dictionary respectively.\*\*

## 4. What will be the output of the following Python code snippet?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> print(a.get(1,4))

a) 1

**b) A**

c) 4

d) Invalid syntax for get method

Explanation: The get() method returns the value of the key if the key is present in the dictionary and the default value(second parameter) if the key isn’t present in the dictionary.

## 5. What will be the output of the following Python code snippet?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> print(a.get(5,4))

a) Error, invalid syntax

b) A

c) 5

**d) 4**

Explanation: The get() method returns the default value(second parameter) if the key isn’t present in the dictionary.

## 6. What will be the output of the following Python code snippet?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> print(a.setdefault(3))

a) {1: ‘A’, 2: ‘B’, 3: ‘C’}

**b) C**

c) {1: 3, 2: 3, 3: 3}

d) No method called setdefault() exists for dictionary

Explanation: setdefault() is similar to get() but will set dict[key]=default if key is not already in the dictionary.

## 7. What will be the output of the following Python code snippet?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> a.setdefault(4,"D")
>
> print(a)

**a) {1: ‘A’, 2: ‘B’, 3: ‘C’, 4: ‘D’}**

b) None

c) Error

d) [1,3,6,10]

Explanation: setdefault() will set dict[key]=default if key is not already in the dictionary.

## 8. What will be the output of the following Python code?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> b={4:"D",5:"E"}
>
> a.update(b)
>
> print(a)

a) {1: ‘A’, 2: ‘B’, 3: ‘C’}

b) Method update() doesn’t exist for dictionaries

**c) {1: ‘A’, 2: ‘B’, 3: ‘C’, 4: ‘D’, 5: ‘E’}**

d) {4: ‘D’, 5: ‘E’}

Explanation: update() method adds dictionary b’s key-value pairs to dictionary a. Execute in python shell to verify.

## 9. What will be the output of the following Python code?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> b=a.copy()
>
> b[2]="D"
>
> print(a)

a) Error, copy() method doesn’t exist for dictionaries

**b) {1: ‘A’, 2: ‘B’, 3: ‘C’}**

c) {1: ‘A’, 2: ‘D’, 3: ‘C’}

d) “None” is printed

Explanation: Changes made in the copy of the dictionary isn’t reflected in the original one.

## 10. What will be the output of the following Python code?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> a.clear()
>
> print(a)

a) None

b) { None:None, None:None, None:None}

c) {1:None, 2:None, 3:None}

**d) { }**

Explanation: The clear() method clears all the key-value pairs in the dictionary.

## 11. Which of the following isn’t true about dictionary keys?[Що з наведеного не правдиво для ключів словника]

a) More than one key isn’t allowed

b) Keys must be immutable

**c) Keys must be integers**

d) When duplicate keys encountered, the last assignment wins

Explanation: Keys of a dictionary may be any data type that is immutable.

## 12. What will be the output of the following Python code?[Яким буде вивід]

> a={1:5,2:3,3:4}
>
> a.pop(3)
>
> print(a)

a) {1: 5}

**b) {1: 5, 2: 3}**

c) Error, syntax error for pop() method

d) {1: 5, 3: 4}

Explanation: pop() method removes the key-value pair for the key mentioned in the pop() method.

## 13. What will be the output of the following Python code?[Яким буде вивід]

> a={1:5,2:3,3:4}
>
> print(a.pop(4,9))

**a) 9**

b) 3

c) Too many arguments for pop() method

d) 4

Explanation: pop() method returns the value when the key is passed as an argument and otherwise returns the default value(second argument) if the key isn’t present in the dictionary.

## 14. What will be the output of the following Python code?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> for i in a:
>
> print(i,end=" ")

**a) 1 2 3**

b) ‘A’ ‘B’ ‘C’

c) 1 ‘A’ 2 ‘B’ 3 ‘C’

d) Error, it should be: for i in a.items():

Explanation: The variable i iterates over the keys of the dictionary and hence the keys are printed.

## 15. What will be the output of the following Python code?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> a.items()

a) Syntax error

b) dict_items([(‘A’), (‘B’), (‘C’)])

c) dict_items([(1,2,3)])

**d) dict_items([(1, ‘A’), (2, ‘B’), (3, ‘C’)])**

Explanation: The method items() returns list of tuples with each tuple having a key-value pair.

## 1. Which of the statements about dictionary values if false?[Що з наведеного вище неправильно для значень словника]

a) More than one key can have the same value

b) The values of the dictionary can be accessed as dict[key]

**c) Values of a dictionary must be unique**

d) Values of a dictionary can be a mixture of letters and numbers

Explanation: More than one key can have the same value.

## 2. What will be the output of the following Python code snippet?[Яким буде вивід]

> a={1:"A",2:"B",3:"C"}
>
> del a

a) method del doesn’t exist for the dictionary

b) del deletes the values in the dictionary

**c) del deletes the entire dictionary**

d) del deletes the keys in the dictionary

Explanation: del deletes the entire dictionary and any further attempt to access it will throw an error.
advertisement

## 3. If a is a dictionary with some key-value pairs, what does a.popitem() do?[Якщо a це словник, що a.popitem() робить?]

**a) Removes an arbitrary element**

b) Removes all the key-value pairs

c) Removes the key-value pair for the key given as an argument

d) Invalid method for dictionary

Explanation: The method popitem() removes a random key-value pair.

## 4. What will be the output of the following Python code snippet?[Яким буде вивід]

> total={}
>
> def insert(items):
>
> if items in total:
>
>       total[items] += 1
>
> else:
>
>        total[items] = 1
>
> insert('Apple')
>
> insert('Ball')
>
> insert('Apple')
>
> print (len(total))

a) 3

b) 1

**c) 2**

d) 0

Explanation: The insert() function counts the number of occurrences of the item being inserted into the dictionary. There are only 2 keys present since the key ‘Apple’ is repeated. Thus, the length of the dictionary is 2.

## 5. What will be the output of the following Python code snippet?[Яким буде вивід]

> a = {}
>
> a[1] = 1
>
> a['1'] = 2
>
> a[1]=a[1]+1
>
> count = 0
>
> for i in a:
>
> count += a[i]
>
> print(count)

a) 1

b) 2

**c) 4**

d) Error, the keys can’t be a mixture of letters and numbers

Explanation: The above piece of code basically finds the sum of the values of keys.

## 6. What will be the output of the following Python code snippet?[Яким буде вивід]

> numbers = {}
>
> letters = {}
>
> comb = {}
>
> numbers[1] = 56
>
> numbers[3] = 7
>
> letters[4] = 'B'
>
> comb['Numbers'] = numbers
>
> comb['Letters'] = letters
>
> print(comb)

a) Error, dictionary in a dictionary can’t exist

b) ‘Numbers’: {1: 56, 3: 7}

c) {‘Numbers’: {1: 56}, ‘Letters’: {4: ‘B’}}

**d) {‘Numbers’: {1: 56, 3: 7}, ‘Letters’: {4: ‘B’}}**

Explanation: Dictionary in a dictionary can exist.

## 7. What will be the output of the following Python code snippet?[Яким буде вивід]

> test = {1:'A', 2:'B', 3:'C'}
>
> test = {}
>
> print(len(test))

**a) 0**

b) None

c) 3

d) An exception is thrown

Explanation: In the second line of code, the dictionary becomes an empty dictionary. Thus, length=0.

## 8. What will be the output of the following Python code snippet?[Яким буде вивід]

> test = {1:'A', 2:'B', 3:'C'}
>
> del test[1]
>
> test[1] = 'D'
>
> del test[2]
>
> print(len(test))

a) 0

**b) 2**

c) Error as the key-value pair of 1:’A’ is already deleted

d) 1

Explanation: After the key-value pair of 1:’A’ is deleted, the key-value pair of 1:’D’ is added.

## 9. What will be the output of the following Python code snippet?[Яким буде вивід]

> a = {}
>
> a[1] = 1
>
> a['1'] = 2
>
> a[1.0]=4
>
> count = 0
>
> for i in a:
>
> count += a[i]
>
> print(count)

a) An exception is thrown

b) 3

**c) 6**

d) 2

Explanation: The value of key 1 is 4 since 1 and 1.0 are the same. Then, the function count() gives the sum of all the values of the keys (2+4).

## 10. What will be the output of the following Python code snippet?[Яким буде вивід]

> a={}
>
> a['a']=1
>
> a['b']=[2,3,4]
>
> print(a)

a) Exception is thrown

b) {‘b’: [2], ‘a’: 1}

c) {‘b’: [2], ‘a’: [3]}

**d) {‘b’: [2, 3, 4], ‘a’: 1}**

Explanation: Mutable members can be used as the values of the dictionary but they cannot be used as the keys of the dictionary.

## 11. What will be the output of the following Python code snippet?[Яким буде вивід]

> import collections
>
> a=collections.Counter([1,1,2,3,3,4,4,4])
>
> a

a) {1,2,3,4}

b) Counter({4, 1, 3, 2})

**c) Counter({4: 3, 1: 2, 3: 2, 2: 1})**

d) {4: 3, 1: 2, 3: 2, 2: 1}

Explanation: The statement a=collections.OrderedDict() generates a dictionary with the number as the key and the count of times the number appears as the value.

## 12. What will be the output of the following Python code snippet?[Яким буде вивід]

> import collections
>
> b=collections.Counter([2,2,3,4,4,4])
>
> b.most_common(1)

a) Counter({4: 3, 2: 2, 3: 1})

b) {3:1}

c) {4:3}

**d) [(4, 3)]**

Explanation: The most_common() method returns the n number key-value pairs where the value is the most recurring.

## 13. What will be the output of the following Python code snippet?[Яким буде вивід]

> import collections
>
> b=collections.Counter([2,2,3,4,4,4])
>
> b.most_common(1)

a) Counter({4: 3, 2: 2, 3: 1})

b) {3:1}

c) {4:3}

**d) [(4, 3)]**

Explanation: The most_common() method returns the n number key-value pairs where the value is the most recurring.

## 14. What will be the output of the following Python code snippet?[Яким буде вивід]

> import collections
>
> a=collections.Counter([2,2,3,3,3,4])
>
> b=collections.Counter([2,2,3,4,4])
>
> a|b

**a) Counter({3: 3, 2: 2, 4: 2})**

b) Counter({2: 2, 3: 1, 4: 1})

c) Counter({3: 2})

d) Counter({4: 1})

Explanation: a|b returns the pair of keys and the highest recurring value.

## 15. What will be the output of the following Python code snippet?[Яким буде вивід]

> import collections
>
> a=collections.Counter([3,3,4,5])
>
> b=collections.Counter([3,4,4,5,5,5])
>
> a&b

a) Counter({3: 12, 4: 1, 5: 1})

**b) Counter({3: 1, 4: 1, 5: 1})**

c) Counter({4: 2})

d) Counter({5: 1})

Explanation: a&b returns the pair of keys and the lowest recurring value.

## 1. The following Python code is invalid.[Чи правильний наведений код?]

> class demo(dict):
>
> def **test**(self,key):
>
> return []
>
> a = demo()
>
> a['test'] = 7
>
> print(a)

a) True

**b) False**

Explanation: The output of the code is: {‘test’:7}.

## 2. What will be the output of the following Python code ?[Яким буде вивід]

> count={}
>
> count[(1,2,4)] = 5
>
> count[(4,2,1)] = 7
>
> count[(1,2)] = 6
>
> count[(4,2,1)] = 2
>
> tot = 0
>
> for i in count:
>
>     tot=tot+count[i]
>
> print(len(count)+tot)

a) 25

b) 17

**c) 16**

d) Tuples can’t be made keys of a dictionary

Explanation: Tuples can be made keys of a dictionary. Length of the dictionary is 3 as the value of the key (4,2,1) is modified to 2. The value of the variable tot is 5+6+2=13.

## 3. What will be the output of the following Python code ?[Яким буде вивід]

> a={}
>
> a[2]=1
>
> a[1]=[2,3,4]
>
> print(a[1][1])

a) [2,3,4]

**b) 3**

c) 2

d) An exception is thrown

Explanation: Now, a={1:[2,3,4],2:1} . a[1][1] refers to second element having key 1.

## 4. What will be the output of the following Python code ?[Яким буде вивід]

> a={'B':5,'A':9,'C':7}
>
> sorted(a)

**a) [‘A’,’B’,’C’]**

b) [‘B’,’C’,’A’]

c) [5,7,9]

d) [9,5,7]

Explanation: Return a new sorted list of keys in the dictionary.

## 5. What will be the output of the following Python code ?[Яким буде вивід]

> a={i: i\*i for i in range(6)}
>
> a

a) Dictionary comprehension doesn’t exist

b) {0: 0, 1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6:36}

c) {0: 0, 1: 1, 4: 4, 9: 9, 16: 16, 25: 25}

**d) {0: 0, 1: 1, 2: 4, 3: 9, 4: 16, 5: 25}**

Explanation: Dictionary comprehension is implemented in the above piece of code.

## 6. What will be the output of the following Python code ?[Яким буде вивід]

> a={}
>
> a.fromkeys([1,2,3],"check")

a) Syntax error

**b) {1:”check”,2:”check”,3:”check”}**

c) “check”

d) {1:None,2:None,3:None}

Explanation: The dictionary takes values of keys from the list and initializes it to the default value (value given in the second parameter). Execute in Python shell to verify.

## 7. What will be the output of the following Python code?[Яким буде вивід]

> b={}
>
> all(b)

a) { }

b) False

**c) True**

d) An exception is thrown

Explanation: Function all() returns True if all keys of the dictionary are true or if the dictionary is empty.

## 8. If b is a dictionary, what does any(b) do?[Якщо b це словник, що any(b) робить?]

**a) Returns True if any key of the dictionary is true**

b) Returns False if dictionary is empty

c) Returns True if all keys of the dictionary are true

d) Method any() doesn’t exist for dictionary

Explanation: Method any() returns True if any key of the dictionary is true and False if the dictionary is empty.

## 9. What will be the output of the following Python code?[Яким буде вивід]

> a={"a":1,"b":2,"c":3}
>
> b=dict(zip(a.values(),a.keys()))
>
> b

a) {‘a’: 1, ‘b’: 2, ‘c’: 3}

b) An exception is thrown

c) {‘a’: ‘b’: ‘c’: }

**d) {1: ‘a’, 2: ‘b’, 3: ‘c’}**

Explanation: The above piece of code inverts the key-value pairs in the dictionary.

## 10. What will be the output of the following Python code?[Яким буде вивід]

> a={i: 'A' + str(i) for i in range(5)}
>
> a

a) An exception is thrown

**b) {0: ‘A0’, 1: ‘A1’, 2: ‘A2’, 3: ‘A3’, 4: ‘A4’}**

c) {0: ‘A’, 1: ‘A’, 2: ‘A’, 3: ‘A’, 4: ‘A’}

d) {0: ‘0’, 1: ‘1’, 2: ‘2’, 3: ‘3’, 4: ‘4’}

Explanation: Dictionary comprehension and string concatenation is implemented in the above piece of code.

## 11. What will be the output of the following Python code?[Яким буде вивід]

> a=dict()
>
> a[1]

**a) An exception is thrown since the dictionary is empty**

b) ‘ ‘

c) 1

d) 0

Explanation: The values of a dictionary can be accessed through the keys only if the keys exist in the dictionary.

## 12. What will be the output of the following Python code?[Яким буде вивід]

> import collections
>
> a=dict()
>
> a=collections.defaultdict(int)
>
> a[1]

a) 1

**b) 0**

c) An exception is thrown

d) ‘ ‘

Explanation: The statement a=collections.defaultdict(int) gives the default value of 0
(since int data type is given within the parenthesis) even if the keys don’t exist in the dictionary.

## 13. What will be the output of the following Python code?[Яким буде вивід]

> import collections
>
> a=dict()
>
> a=collections.defaultdict(str)
>
> a['A']

a) An exception is thrown since the dictionary is empty

**b) ‘ ‘**

c) ‘A’

d) 0

Explanation: The statement a=collections.defaultdict(str) gives the default value of ‘ ‘ even if the keys don’t exist in the dictionary.

## 14. What will be the output of the following Python code?[Яким буде вивід]

> import collections
>
> b=dict()
>
> b=collections.defaultdict(lambda: 7)
>
> b[4]

a) 4

b) 0

c) An exception is thrown

**d) 7**

Explanation: The statement a=collections.defaultdict(lambda: x) gives the default value of x even if the keys don’t exist in the dictionary.

## 15. What will be the output of the following Python code?[Яким буде вивід]

> import collections
>
> a=collections.OrderedDict((str(x),x) for x in range(3))
>
> a

a) {‘2’:2, ‘0’:0, ‘1’:1}

**b) OrderedDict([(‘0’, 0), (‘1’, 1), (‘2’, 2)])**

c) An exception is thrown

d) ‘ ‘

Explanation: The line of code a=collections.OrderedDict() generates a dictionary satisfying the conditions given within the parenthesis and in an ascending order of the keys.

## 1. Which of the following functions is a built-in function in python?[Яка з функцій вбудована в пітон?]

a) seed()

b) sqrt()

c) factorial()

**d) print()**

Explanation: The function seed is a function which is present in the random module. The functions sqrt and factorial are a part of the math module. The print function is a built-in function which prints a value directly to the system output.

## 2. What will be the output of the following Python expression?[Яким буде результат функції]

> round(4.576)

a) 4.5

**b) 5**

c) 4

d) 4.6

Explanation: This is a built-in function which rounds a number to give precision in decimal digits. In the above case, since the number of decimal places has not been specified, the decimal number is rounded off to a whole number. Hence the output will be 5.

## 3. The function pow(x,y,z) is evaluated as:[Фугкція pow(x,y,z) обчислюється як:]

a) (x**y) ** z

b) (x\*\*y) / z

**c) (x ** y) % z\*\*

d) (x\**y)*z

Explanation: The built-in function pow() can accept two or three arguments. When it takes in two arguments, they are evaluated as x ** y. When it takes in three arguments, they are evaluated as (x ** y)%z.

## 4. What will be the output of the following Python function?[Яким буде результат даної функції]

> all([2,4,0,6])

a) Error

b) True

**c) False**

d) 0

Explanation: The function all returns false if any one of the elements of the iterable is zero and true if all the elements of the iterable are non zero. Hence the output of this function will be false.

## 5. What will be the output of the following Python expression?[Яким буде результат виразу]

> round(4.5676,2)?

a) 4.5

b) 4.6

**c) 4.57**

d) 4.56

Explanation: The function round is used to round off the given decimal number to the specified decimal places. In this case, the number should be rounded off to two decimal places. Hence the output will be 4.57.

## 6. What will be the output of the following Python function?[Яким буде результат функції]

> any([2>8, 4>2, 1>2])

a) Error

**b) True**

c) False

d) 4>2

Explanation: The built-in function any() returns true if any or more of the elements of the iterable is true (non zero), If all the elements are zero, it returns false.

## 7. What will be the output of the following Python function?[Яким буде результат функції]

> import math
>
> abs(math.sqrt(25))

a) Error

b) -5

c) 5

**d) 5.0**

Explanation: The abs() function prints the absolute value of the argument passed. For example: abs(-5)=5. Hence, in this case we get abs(5.0)=5.0.

## 8. What will be the output of the following Python function?[Яким буде результат функції]

> sum(2,4,6)
>
> sum([1,2,3])

**a) Error, 6**

b) 12, Error

c) 12, 6

d) Error, Error

Explanation: The first function will result in an error because the function sum() is used to find the sum of iterable numbers. Hence the outcomes will be Error and 6 respectively.

## 9. What will be the output of the following Python function?[Яким буде результат функції]

> all(3,0,4.2)

a) True

b) False

**c) Error**

d) 0

Explanation: The function all() returns ‘True’ if any one or more of the elements of the iterable are non zero. In the above case, the values are not iterable, hence an error is thrown.

## 10. What will be the output of the following Python function?[Яким буде результат функції]

> min(max(False,-3,-4), 2,7)

a) 2

**b) False**

c) -3

d) -4

Explanation: The function max() is being used to find the maximum value from among -3, -4 and false. Since false amounts to the value zero, hence we are left with min(0, 2, 7) Hence the output is 0 (false).

# Section 16

# Section 17

## Function – 3

### 1. Python supports the creation of anonymous functions at runtime, using a construct called __________ [Python підтримує створення анонімних функцій під час виконання, використовуючи конструкцію __________]
**a) lambda**\
b) pi\
c) anonymous\
d) none of the mentioned

> Explanation: Python supports the creation of anonymous functions (i.e. functions that are not bound to a name) at runtime, using a construct called lambda. Lambda functions are restricted to a single expression. They can be used wherever normal functions can be used.

### 2. What will be the output of the following Python code?
```python
y = 6
z = lambda x: x * y
print z(8)
```

**a) 48**\
b) 14\
c) 64\
d) None of the mentioned

> Explanation: The lambda keyword creates an anonymous function. The x is a parameter, that is passed to the lambda function. The parameter is followed by a colon character. The code next to the colon is the expression that is executed, when the lambda function is called. The lambda function is assigned to the z variable. The lambda function is executed. The number 8 is passed to the anonymous function and it returns 48 as the result. Note that z is not a name for this function. It is only a variable to which the anonymous function was assigned.

### 3. What will be the output of the following Python code?
```python
lamb = lambda x: x ** 3
print(lamb(5))
```

a) 15\
b) 555\
**c) 125**\
d) None of the mentioned

### 4. Does Lambda contains return statements?
a) True\
**b) False**

> Explanation: lambda definition does not include a return statement. it always contains an expression which is returned. Also note that we can put a lambda definition anywhere a function is expected. We don’t have to assign it to a variable at all.

### 5. Lambda is a statement.
a) True\
**b) False**

> Explanation: lambda is an anonymous function in Python. Hence this statement is false.

### 6. Lambda contains block of statements.
a) True\
**b) False**

### 7. What will be the output of the following Python code?
```python
def f(x, y, z): return x + y + z
f(2, 30, 400)
```

**a) 432**\
b) 24000\
c) 430\
d) No output

### 8. What will be the output of the following Python code?
```python
def writer():
	title = 'Sir'
	name = (lambda x:title + ' ' + x)
	return name
 
who = writer()
who('Arthur')
```

a) Arthur Sir\
**b) Sir Arthur**\
c) Arthur\
d) None of the mentioned

### 9. What will be the output of the following Python code?
```python
L = [lambda x: x ** 2,
         lambda x: x ** 3,
         lambda x: x ** 4]
 
for f in L:
	print(f(3))
```

a)
```python
27
81
343
```
b)
```python
6
9
12
```
**c)**
```python
9
27
81
```
d) None of the mentioned

### 10. What will be the output of the following Python code?
```python
min = (lambda x, y: x if x < y else y)
min(101*99, 102*98)
```

a) 9997\
b) 9999\
**c) 9996**\
d) None of the mentioned

## Function – 4

### 1. What is a variable defined outside a function referred to as?
a) A static variable\
**b) A global variable**\
c) A local variable\
d) An automatic variable

> Explanation: The value of a variable defined outside all function definitions is referred to as a global variable and can be used by multiple functions of the program.

### 2. What is a variable defined inside a function referred to as?
a) A global variable\
b) A volatile variable\
**c) A local variable**\
d) An automatic variable

> Explanation: The variable inside a function is called as local variable and the variable definition is confined only to that function.

### 3. What will be the output of the following Python code?
```python
i=0
def change(i):
   i=i+1
   return i
change(1)
print(i)
```

a) 1\
b) Nothing is displayed\
**c) 0**\
d) An exception is thrown

> Explanation: Any change made in to an immutable data type in a function isn’t reflected outside the function.

### 4. [broken] What will be the output of the following Python code?
```python
def a(b):
    b = b + [5]
 
c = [1, 2, 3, 4]
a(c)
print(len(c))
```

**a) 4**\
b) 5\
c) 1\
d) An exception is thrown

> Site Explanation ~~b)~~: Since a list is mutable, any change made in the list in the function is reflected outside the function.\
> Note: It's correct but we've changed the reference to list, so it doesn't work
 
### 5. What will be the output of the following Python code?
```python
a=10
b=20
def change():
    global b
    a=45
    b=56
change()
print(a)
print(b)
```

**a)**
```python
10
56
```
b)
```python
45
56
```
c)
```python
10
20
```
d) Syntax Error

> Explanation: The statement “global b” allows the global value of b to be accessed and changed. Whereas the variable a is local and hence the change isn’t reflected outside the function.

### 6. What will be the output of the following Python code?
```python
def change(i = 1, j = 2):
    i = i + j
    j = j + 1
    print(i, j)
change(j = 1, i = 2)
```

a) An exception is thrown because of conflicting values\
b) 1 2\
c) 3 3\
**d) 3 2**

> Explanation: The values given during function call is taken into consideration, that is, i=2 and j=1.

### 7. What will be the output of the following Python code?
```python
def change(one, *two):
   print(type(two))
change(1,2,3,4)
```

a) Integer\
**b) Tuple**\
c) Dictionary\
d) An exception is thrown

> Explanation: The parameter two is a variable parameter and consists of (2,3,4). Hence the data type is tuple.

### 8. If a function doesn’t have a return statement, which of the following does the function return?
a) int\
b) null\
**c) None**\
d) An exception is thrown without the return statement

> Explanation: A function can exist without a return statement and returns None if the function doesn’t have a return statement.

### 9. What will be the output of the following Python code?
```python
def display(b, n):
    while n > 0:
        print(b,end="")
        n=n-1
display('z',3)
```

**a) zzz**\
b) zz\
c) An exception is executed\
d) Infinite loop

> Explanation: The loop runs three times and ‘z’ is printed each time.

### 10. What will be the output of the following Python code?
```python
def find(a, **b):
   print(type(b))
find('letters',A='1',B='2')
```
a) String\
b) Tuple\
**c) Dictionary**\
d) An exception is thrown

> Explanation: b combines the remaining parameters into a dictionary.

## Argument Parsing 1

### 1. What is the type of each element in sys.argv?
a) set\
b) list\
c) tuple\
**d) string**

> Explanation: It is a list of strings.

### 2. What is the length of sys.argv?
a) number of arguments\
**b) number of arguments + 1**\
c) number of arguments – 1\
d) none of the mentioned

> Explanation: The first argument is the name of the program itself. Therefore the length of sys.argv is one more than the number arguments.

### 3. What will be the output of the following Python code?
```python
def foo(k):
    k[0] = 1
q = [0]
foo(q)
print(q)
```

a) [0]\
**b) [1]**\
c) [1, 0]\
d) [0, 1]

> Explanation: Lists are mutable.

### 4. How are keyword arguments specified in the function heading?
a) one-star followed by a valid identifier\
b) one underscore followed by a valid identifier\
**c) two stars followed by a valid identifier**\
d) two underscores followed by a valid identifier

> Explanation: Refer documentation.

### 5. How many keyword arguments can be passed to a function in a single function call?
a) zero\
b) one\
**c) zero or more**\
d) one or more

> Explanation: Zero keyword arguments may be passed if all the arguments have default values.

### 6. What will be the output of the following Python code?
```python
def foo(fname, val):
    print(fname(val))
foo(max, [1, 2, 3])
foo(min, [1, 2, 3])
```

**a) 3 1**\
b) 1 3\
c) error\
d) none of the mentioned

> Explanation: It is possible to pass function names as arguments to other functions.

### 7. What will be the output of the following Python code?
```python
def foo():
    return total + 1
total = 0
print(foo())
```

a) 0\
**b) 1**\
c) error\
d) none of the mentioned

> Explanation: It is possible to read the value of a global variable directly.

### 8. What will be the output of the following Python code?
```python
def foo():
    total += 1
    return total
total = 0
print(foo())
```

a) 0\
b) 1\
**c) error**\
d) none of the mentioned

> Explanation: It is not possible to change the value of a global variable without explicitly specifying it.

### 9. What will be the output of the following Python code?
```python
def foo(x):
    x = ['def', 'abc']
    return id(x)
q = ['abc', 'def']
print(id(q) == foo(q))
```

a) True\
**b) False**\
c) None\
d) Error

> Explanation: A new object is created in the function.

### 10. What will be the output of the following Python code?
```python
def foo(i, x=[]):
    x.append(i)
    return x
for i in range(3):
    print(foo(i))
```

a) [0] [1] [2]\
**b) [0] [0, 1] [0, 1, 2]**\
c) [1] [2] [3]\
d) [1] [1, 2] [1, 2, 3]

> Explanation: When a list is a default value, the same list will be reused.

## Argument Parsing 2

### 1. What will be the output of the following Python code?
```python
def foo(k):
    k = [1]
q = [0]
foo(q)
print(q)
```

**a) [0]**\
b) [1]\
c) [1, 0]\
d) [0, 1]

> Explanation: A new list object is created in the function and the reference is lost. This can be checked by comparing the id of k before and after k = [1].

### 2. How are variable length arguments specified in the function heading?
**a) one star followed by a valid identifier**\
b) one underscore followed by a valid identifier\
c) two stars followed by a valid identifier\
d) two underscores followed by a valid identifier

> Explanation: Refer documentation.

### 3. Which module in the python standard library parses options received from the command line?
**a) getopt**\
b) os\
c) getarg\
d) main

> Explanation: getopt parses options received from the command line.

### 4. What is the type of sys.argv?
a) set\
**b) list**\
c) tuple\
d) string

> Explanation: It is a list of elements.

### 5. What is the value stored in sys.argv[0]?
a) null\
b) you cannot access it\
**c) the program’s name**\
d) the first argument

> Explanation: Refer documentation.

### 6. How are default arguments specified in the function heading?
**a) identifier followed by an equal to sign and the default value**\
b) identifier followed by the default value within backticks (“)\
c) identifier followed by the default value within square brackets ([])\
d) identifier

> Explanation: Refer documentation.

### 7. How are required arguments specified in the function heading?
a) identifier followed by an equal to sign and the default value\
b) identifier followed by the default value within backticks (“)\
c) identifier followed by the default value within square brackets ([])\
**d) identifier**

> Explanation: Refer documentation.

### 8. What will be the output of the following Python code?
```python
def foo(x):
    x[0] = ['def']
    x[1] = ['abc']
    return id(x)
q = ['abc', 'def']
print(id(q) == foo(q))
```

**a) True**\
b) False\
c) None\
d) Error

> Explanation: The same object is modified in the function.

### 9. Where are the arguments received from the command line stored?
**a) sys.argv**\
b) os.argv\
c) argv\
d) none of the mentioned

> Explanation: Refer documentation.

### 10. What will be the output of the following Python code?
```python
def foo(i, x=[]):
    x.append(x.append(i))
    return x
for i in range(3):
    y = foo(i)
print(y)
```

a) [[[0]], [[[0]], [1]], [[[0]], [[[0]], [1]], [2]]]\
b) [[0], [[0], 1], [[0], [[0], 1], 2]]\
**c) [0, None, 1, None, 2, None]**\
d) [[[0]], [[[0]], [1]], [[[0]], [[[0]], [1]], [2]]]

> Explanation: append() returns None.

# Section 18

### 1. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
def f1():
    x=15
    print(x)
x=12
f1()
```

a) Error

b) 12

**c) 15**

d) 1512

> Explanation: In the code shown above, x=15 is a local variable whereas x=12 is a global variable. Preference is given to local variable over global variable. Hence the output of the code shown above is 15.

### 2. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
def f1():
    x=100
    print(x)
x=+1
f1()
```

a) Error

**b) 100**

c) 101

d) 99

> Explanation: The variable x is a local variable. It is first printed and then modified. Hence the output of this code is 100.

### 3. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
def san(x):
    print(x+1)
x=-2
x=4
san(12)
```

**a) 13**

b) 10

c) 2

d) 5

> Explanation: The value passed to the function san() is 12. This value is incremented by one and printed. Hence the output of the code shown above is 13.

### 4. What will be the output of the following Python code?

```
def f1():
    global x
    x+=1
    print(x)
x=12
print("x")
```

a) Error

b) 13

c)
13
x

**d) x**

> Explanation: In the code shown above, the variable ‘x’ is declared as global within the function. Hence the output is ‘x’. Had the variable ‘x’ been a local variable, the output would have been:

### 5. What will be the output of the following Python code?

```
def f1(x):
    global x
    x+=1
    print(x)
f1(15)
print("hello")
```

**a) error**

b) hello

c) 16

d)

16
hello

> Explanation: The code shown above will result in an error because ‘x’ is a global variable. Had it been a local variable, the output would be: 16
> hello

### 6. What will be the output of the following Python code?

```
def f1(x):
    global x
    x+=1
    print(x)
f1(15)
print("hello")
```

a) Error

b) 12 4

**c) 4 12**

d) 4 15

> Explanation: At the time of leader processing, the value of ‘x’ is 12. It is not modified later. The value passed to the function f1 is 4. Hence the output of the code shown above is 4 12.

### 7. What will be the output of the following Python code?

```
def f():
    global a
    print(a)
    a = "hello"
    print(a)
a = "world"
f()
print(a)
```

a)

    hello
    hello
    world

**b)**

    world
    hello
    hello

c)

    hello
    world
    world

d)

    world
    hello
    world

> Explanation: Since the variable ‘a’ has been explicitly specified as a global variable, the value of a passed to the function is ‘world’. Hence the output of this code is:
> world
> hello
> hello

### 8. What will be the output of the following Python code?

```
def f1(a,b=[]):
    b.append(a)
    return b
print(f1(2,[3,4]))
```

a) [3,2,4]

b) [2,3,4]

c) Error

**d) [3,4,2]**

> Explanation: In the code shown above, the integer 2 is appended to the list [3,4]. Hence the output of the code is [3,4,2]. Both the variables a and b are local variables.

### 9. What will be the output of the following Python code?

```
def f(p, q, r):
    global s
    p = 10
    q = 20
    r = 30
    s = 40
    print(p,q,r,s)
p,q,r,s = 1,2,3,4
f(5,10,15)
```

a) 1 2 3 4

b) 5 10 15 4

**c) 10 20 30 40**

d) 5 10 15 40

> Explanation: The above code shows a combination of local and global variables. The output of this code is: 10 20 30 40

### 10. What will be the output of the following Python code?

```
def f(x):
    print("outer")
    def f1(a):
        print("inner")
        print(a,x)
f(3)
f1(1)
```

**a)**

outer
error

b)

inner
error

c)

outer
inner

d) error

> Explanation: The error will be caused due to the statement f1(1) because the function is nested. If f1(1) had been called inside the function, the output would have been different and there would be no error.

### 11. What will be the output of the following Python code?

```
x = 5
def f1():
    global x
    x = 4
def f2(a,b):
    global x
    return a+b+x
f1()
total = f2(1,2)
print(total)
```

a) Error

**b) 7**

c) 8

d) 15

> Explanation: In the code shown above, the variable ‘x’ has been declared as a global variable under both the functions f1 and f2. The value returned is a+b+x = 1+2+4 = 7.

### 12. What will be the output of the following Python code?

```
x=100
def f1():
    global x
    x=90
def f2():
    global x
    x=80
print(x)
```

**a) 100**

b) 90

c) 80

d) Error

> Explanation: The output of the code shown above is 100. This is because the variable ‘x’ has been declared as global within the functions f1 and f2.

### 13. Read the following Python code carefully and point out the global variables?

```
y, z = 1, 2
def f():
    global x
    x = y+z
```

a) x

b) y and z

**c) x, y and z**

d) Neither x, nor y, nor z

> Explanation: In the code shown above, x, y and z are global variables inside the function f. y and z are global because they are not assigned in the function. x is a global variable because it is explicitly specified so in the code. Hence, x, y and z are global variables.

### 1. Which of the following data structures is returned by the functions globals() and locals()?

a) list

b) set

**c) dictionary**

d) tuple

> Explanation: Both the functions, that is, globals() and locals() return value of the data structure dictionary.

### 2. What will be the output of the following Python code?

```
x=1
def cg():
    global x
    x=x+1
cg()
x
```

**a) 2**

b) 1

c) 0

d) Error

> Explanation: Since ‘x’ has been declared a global variable, it can be modified very easily within the function. Hence the output is 2.

### 3. On assigning a value to a variable inside a function, it automatically becomes a global variable.

a) True

**b) False**

> Explanation: On assigning a value to a variable inside a function, t automatically becomes a local variable. Hence the above statement is false.

### 4. What will be the output of the following Python code?

```
e="butter"
def f(a): print(a)+e
f("bitter")
```

a) error

b)

    butter
    error

**c)**

    bitter
    error

d) bitterbutter

> Explanation: The output of the code shown above will be ‘bitter’, followed by an error. The error is because the operand ‘+’ is unsupported on the types used above.

### 5. What happens if a local variable exists with the same name as the global variable you want to access?

a) Error

b) The local variable is shadowed

c) Undefined behavior

**d) The global variable is shadowed**

> Explanation: If a local variable exists with the same name as the local variable that you want to access, then the global variable is shadowed. That is, preference is given to the local variable.

### 6. What will be the output of the following Python code?

```
a=10
globals()['a']=25
print(a)
```

a) 10

**b) 25**

c) Junk value

d) Error

> Explanation: In the code shown above, the value of ‘a’ can be changed by using globals() function. The dictionary returned is accessed using key of the variable ‘a’ and modified to 25.

### 7. What will be the output of the following Python code?

```
def f(): x=4
x=1
f()
x
```

a) Error

b) 4

c) Junk value

**d) 1**

> Explanation: In the code shown above, when we call the function f, a new namespace is created. The assignment x=4 is performed in the local namespace and does not affect the global namespace. Hence the output is 1.

### 8. **\*\***\_\_**\*\*** returns a dictionary of the module namespace.

**\*\***\_\_\_\_**\*\*** returns a dictionary of the current namespace.

a)

locals()
globals()

**b)**

locals()
locals()

c)

globals()
locals()

d)

globals()
globals()

> Explanation: The function globals() returns a dictionary of the module namespace, whereas the function locals() returns a dictionary of the current namespace.

### 1. Which is the most appropriate definition for recursion?

a) A function that calls itself

**b) A function execution instance that calls another execution instance of the same function**

c) A class method that calls another class method

d) An in-built method that is automatically called

> Explanation: The appropriate definition for a recursive function is a function execution instance that calls another execution instance of the same function either directly or indirectly.

### 2. Only problems that are recursively defined can be solved using recursion.

a) True

**b) False**

> Explanation: There are many other problems can also be solved using recursion.

### 3. Which of these is false about recursion?

a) Recursive function can be replaced by a non-recursive function

b) Recursive functions usually take more memory space than non-recursive function

**c) Recursive functions run faster than non-recursive function**

d) Recursion makes programs easier to understand

> Explanation: The speed of a program using recursion is slower than the speed of its non-recursive equivalent.

### 4. Fill in the line of the following Python code for calculating the factorial of a number.

```
def fact(num):
    if num == 0:
        return 1
    else:
        return _____________________
```

**a) num\*fact(num-1)**

b) (num-1)\*(num-2)

c) num\*(num-1)

d) fact(num)\*fact(num-1)

> Explanation: Suppose n=5 then, 5*4*3*2*1 is returned which is the factorial of 5.

### 5. What will be the output of the following Python code?

```
def test(i,j):
    if(i==0):
        return j
    else:
        return test(i-1,i+j)
print(test(4,7))
```

a) 13

b) 7

c) Infinite loop

**d) 17**

> Explanation: The test(i-1,i+j) part of the function keeps calling the function until the base condition of the function is satisfied.

### 6. What will be the output of the following Python code?

```
l=[]
def convert(b):
    if(b==0):
        return l
    dig=b%2
    l.append(dig)
    convert(b//2)
convert(6)
l.reverse()
for i in l:
    print(i,end="")
```

a) 011

**b) 110**

c) 3

d) Infinite loop

> Explanation: The above code gives the binary equivalent of the number.

### 7. What is tail recursion?

a) A recursive function that has two base cases

b) A function where the recursive functions leads to an infinite loop

c) A recursive function where the function doesn’t return anything and just prints the values

**d) A function where the recursive call is the last thing executed by the function**

> Explanation: A recursive function is tail recursive when recursive call is executed by the function in the last.

### 8. Observe the following Python code?

```
def a(n):
    if n == 0:
        return 0
    else:
        return n*a(n - 1)
def b(n, tot):
    if n == 0:
        return tot
    else:
        return b(n-2, tot-2)
```

a) Both a() and b() aren’t tail recursive

b) Both a() and b() are tail recursive

**c) b() is tail recursive but a() isn’t**

d) a() is tail recursive but b() isn’t

> Explanation: A recursive function is tail recursive when recursive call is executed by the function in the last.

### 9. Which of the following statements is false about recursion?

a) Every recursive function must have a base case

b) Infinite recursion can occur if the base case isn’t properly mentioned

c) A recursive function makes the code easier to understand

**d) Every recursive function must have a return value**

> Explanation: A recursive function needn’t have a return value.

### 10. What will be the output of the following Python code?

```
def fun(n):
    if (n > 100):
        return n - 5
    return fun(fun(n+11));

print(fun(45))
```

a) 50

**b) 100**

c) 74

d) Infinite loop

> Explanation: The fun(fun(n+11)) part of the code keeps executing until the value of n becomes greater than 100, after which n-5 is returned and printed.

### 11. Recursion and iteration are the same programming approach.

a) True

**b) False**

> Explanation: In recursion, the function calls itself till the base condition is reached whereas iteration means repetition of process for example in for-loops.

### 12. What happens if the base condition isn’t defined in recursive programs?

**a) Program gets into an infinite loop**

b) Program runs once

c) Program runs n number of times where n is the argument given to the function

d) An exception is thrown

> Explanation: The program will run until the system gets out of memory.

### 13. Which of these is not true about recursion?

a) Making the code look clean

b) A complex task can be broken into sub-problems

**c) Recursive calls take up less memory**

d) Sequence generation is easier than a nested iteration

> Explanation: Recursive calls take up a lot of memory and time as memory is taken up each time the function is called.

### 14. Which of these is not true about recursion?

a) It’s easier to code some real-world problems using recursion than non-recursive equivalent

**b) Recursive functions are easy to debug**

c) Recursive calls take up a lot of memory

d) Programs using recursion take longer time than their non-recursive equivalent

> Explanation: Recursive functions may be hard to debug as the logic behind recursion may be hard to follow.

### 15. What will be the output of the following Python code?


```
def a(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        return a(n-1)+a(n-2)
for i in range(0,4):
    print(a(i),end=" ")
```

a) 0 1 2 3

b) An exception is thrown

c) 0 1 1 2 3

**d) 0 1 1 2**

> Explanation: The above piece of code prints the Fibonacci series.

### 1. Which type of copy is shown in the following python code?

```
l1=[[10, 20], [30, 40], [50, 60]]
ls=list(l1)
ls
[[10, 20], [30, 40], [50, 60]]
```

**a) Shallow copy**

b) Deep copy

c) memberwise

d) All of the mentioned

> Explanation: The code shown above depicts shallow copy. For deep copy, the command given is: l2 = l1.copy().

### 2. What will be the output of the following Python code?

```
l=[2, 3, [4, 5]]
l2=l.copy()
l2[0]=88
l
l2
```

a)

[88, 2, 3, [4, 5]]
[88, 2, 3, [4, 5]]

**b)**

[2, 3, [4, 5]]
[88, 2, 3, [4, 5]]

c)

[88, 2, 3, [4, 5]]
[2, 3, [4, 5]]

d)

[2, 3, [4, 5]]
[2, 3, [4, 5]]

> Explanation: The code shown above depicts deep copy. In deep copy, the base address of the objects is not copied. Hence the modification done on one list does not affect the other list.

### 3. In **\*\***\_\_\_**\*\*** copy, the base address of the objects are copied. In **\*\***\_\_\_**\*\*** copy, the base address of the objects are not copied.

a) deep. shallow

b) memberwise, shallow

**c) shallow, deep**

d) deep, memberwise

> Explanation: In shallow copy, the base address of the objects are copied.
> In deep copy, the base address of the objects are not copied.
> Note that memberwise copy is another name for shallow copy.

### 4. The nested list undergoes shallow copy even when the list as a whole undergoes deep copy.

**a) True**

b) False

> Explanation: A nested list undergoes shallow copy even when the list as a whole undergoes deep copy. Hence, this statement is true.

### 5. What will be the output of the following Python code and state the type of copy that is depicted?

```
l1=[2, 4, 6, 8]
l2=[1, 2, 3]
l1=l2
l2
```

a) [2, 4, 6, 8], shallow copy

b) [2, 4, 6, 8], deep copy

**c) [1, 2, 3], shallow copy**

d) [1, 2, 3], deep copy

> Explanation: The code shown above depicts shallow copy and the output of the code is: [1, 2, 3].

### 6. What will be the output of the following Python code?

```
l1=[10, 20, 30]
l2=l1
id(l1)==id(l2)

l2=l1.copy()
id(l1)==id(l2)
```

a) False, False

b) False, True

c) True, True

**d) True, False**

> Explanation: The first code shown above represents shallow copy. Hence the output of the expression id(l1)==id(l2) is True. The second code depicts deep copy. Hence the output of the expression id(l1)==id(l2) in the second case is False.

### 7. What will be the output of the following Python code?

```
l1=[1, 2, 3, [4]]
l2=list(l1)
id(l1)==id(l2)
```

a) True

**b) False**

c) Error

d) Address of l1

> Explanation: The code shown above shows a nested list. A nested list will undergo shallow copy when the list as a whole undergoes deep copy. Hence the output of this code is False.

### 8. What will be the output of the following Python code?

```
l1=[10, 20, 30, [40]]
l2=copy.deepcopy(l1)
l1[3][0]=90
l1
l2
```

a)

[10, 20, 30, [40]]
[10, 20, 30, 90]

b) Error

**c)**

[10, 20, 30 [90]]
[10, 20, 30, [40]]

d)

[10, 20, 30, [40]]
[10, 20, 30, [90]]

> Explanation: The code shown above depicts deep copy. Hence at the end of the code, l1=[10, 20, 30, [90]] and l2=[10, 20, 30, [40]].

### 9. In **\*\*\*\***\_\_\_\_**\*\*\*\*** copy, the modification done on one list affects the other list. In **\*\*\*\***\_\_\_\_**\*\*\*\*** copy, the modification done on one list does not affect the other list.

**a) shallow, deep**
b) memberwise, shallow
c) deep, shallow
d) deep, memberwise

> Explanation: In shallow copy, the modification done on one list affects the other list. In deep copy, the modification done on one list does not affect the other list.

### 10. What will be the output of the following Python code?

```
l1=[1, 2, 3, (4)]
l2=l1.copy()
l2
l1
```

a)

[1, 2, 3, (4)]
[1, 2, 3, 4]

b)

[1, 2, 3, 4]
[1, 2, 3, (4)]

**c)**

[1, 2, 3, 4]
[1, 2, 3, 4]

d)

[1, 2, 3, (4)]
[1, 2, 3, (4)]

> Explanation: In the code shown above, the list l1 is enclosed in a tuple. When we print this list, it is printed as [1, 2, 3, 4]. Note the absence of the tuple. The code shown depicts deep copy. Hence the output of this program is: l1=[1, 2, 3, 4] and l2=[1, 2, 3, 4].

### 11. What will be the output of the following Python code?

```
def check(n):
    if n < 2:
        return n % 2 == 0
    return check(n - 2)
print(check(11))
```

**a) False**

b) True

c) 1

d) An exception is thrown

> Explanation: The above piece of code checks recursively whether a number is even or odd.

### 12. What is the base case in the Merge Sort algorithm when it is solved recursively?

a) n=0

b) n=1

**c) A list of length one**

d) An empty list

> Explanation: Merge Sort algorithm implements the recursive algorithm and when the recursive function receives a list of length 1 which is the base case, the list is returned.

### 13. What will be the output of the following Python code?

```
a = [1, 2, 3, 4, 5]
b = lambda x: (b (x[1:]) + x[:1] if x else [])
print(b (a))
```

a) 1 2 3 4 5

b) [5,4,3,2,1]

**c) []**

d) Error, lambda functions can’t be called recursively

> Explanation: The above piece of code appends the first element of the list to a reversed sublist and reverses the list using recursion.

# Section 19

### 1. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
odd=lambda x: bool(x%2)
numbers=[n for n in range(10)]
print(numbers)
n=list()
for i in numbers:
    if odd(i):
        continue
    else:
        break
```

a) [0, 2, 4, 6, 8, 10]\
**b) [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]**\
c) [1, 3, 5, 7, 9]\
d) Error

> Explanation: The code shown above returns a new list containing whole numbers up to 10 (excluding 10). Hence the output of the code is: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9].

### 2. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
f=lambda x:bool(x%2)
print(f(20), f(21))
```

**a) False True**\
b) False False\
c) True True\
d) True False

> Explanation: The code shown above will return true if the given argument is an odd number, and false if the given argument is an even number. Since the arguments are 20 and 21 respectively, the output of this code is: False True.

### 3. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
import functools
l=[1,2,3,4]
print(functools.reduce(lambda x,y:x*y,l))
```

a) Error\
b) 10\
**c) 24**\
d) No output

> Explanation: The code shown above returns the product of all the elements of the list. Hence the output is 1*2*3\*4 = 24.

### 4. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
l=[1, -2, -3, 4, 5]
def f1(x):
    return x<2
m1=filter(f1, l)
print(list(m1))
```

a) [1, 4, 5 ]\
b) Error\
c) [-2, -3]\
**d) [1, -2, -3]**

> Explanation: The code shown above returns only those elements from the list, which are less than 2. The functional programming tool used to achieve this operation is filter. Hence the output of the code is:[1, -2, -3].

### 5. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
l=[-2, 4]
m=map(lambda x:x*2, l)
print(m)
```

a) [-4, 16]\
**b) Address of m**\
c) Error\
d)

```
-4
   16
```

> Explanation: The code shown above returns the address of m. Had we used the statement: print(list(m)), the output would have been: [-4, 16].

### 6. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
l=[1, -2, -3, 4, 5]
def f1(x):
    return x<-1
m1=map(f1, l)
print(list(m1))
```

a) [False, False, False, False, False]\
**b) [False, True, True, False, False]**\
c) [True, False, False, True, True]\
d) [True, True, True, True, True]

> Explanation: This code shown returns a list which contains True if the corresponding element of the list is less than -1, and false if the corresponding element is greater than -1. Hence the output of the code shown above: [False, True, True, False, False].

### 7. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
l=[1, 2, 3, 4, 5]
m=map(lambda x:2**x, l)
print(list(m))
```

a) [1, 4, 9, 16, 25 ]\
**b) [2, 4, 8, 16, 32 ]**\
c) [1, 0, 1, 0, 1]\
d) Error

> Explanation: The code shown above prints a list containing each element of the list as the power of two. That is, the output is: [2, 4, 8, 16, 32].

### 8. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
import functools
l=[1, 2, 3, 4, 5]
m=functools.reduce(lambda x, y:x if x>y else y, l)
print(m)
```

a) Error\
b) Address of m\
c) 1\
**d) 5**

> Explanation: The code shown above can be used to find the maximum of the elements from the given list. In the above code, this operation is achieved by using the programming tool reduce. Hence the output of the code shown above is 5.

### 9. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
l=[n for n in range(5)]
f=lambda x:bool(x%2)
print(f(3), f(1))
for i in range(len(l)):
    if f(l[i]):
        del l[i]
        print(i)
```

**a)**

```
  True True
  1
  2
  Error
```

b)

```
  False False
  1
  2
```

c)

```
  True False
  1
  2
  Error
```

d)

```
  False True
  1
  2
```

> Explanation: The code shown above prints true if the value entered as an argument is odd, else false is printed. Hence the output: True True. The error is due to the list index being out of range.

### 10. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
m=reduce(lambda x: x-3 in range(4, 10))
print(list(m))
```

a) [1, 2, 3, 4, 5, 6, 7]\
b) No output\
c) [1, 2, 3, 4, 5, 6]\
**d) Error**

> Explanation: The code shown above will result in an error. This is because e have not imported functools. Further, ‘reduce’, as such is not defined. We should use functools.reduce to remove the error.

### 11. Which of the following numbers will not be a part of the output list of the following Python code? [Яке з наступних чисел не буде частиною результуючого списку наступного фрагмента коду Python?]

```
def sf(a):
    return a%3!=0 and a%5!=0
m=filter(sf, range(1, 31))
print(list(m)))
```

a) 1\
b) 29\
c) 6\
**d) 10**

> Explanation: The output list of the code shown above will not contain any element that is divisible by 3 or 5. Hence the number which is not present in the output list is 10. The output list: [1, 2, 4, 7, 8, 11, 13, 14, 16, 17, 19, 22, 23, 26, 28, 29]

### 12. The single line equivalent of the following Python code? [Який рядок еквівалентний наступному фрагменту коду Python?]

```
l=[1, 2, 3, 4, 5]
def f1(x):
    return x<0
m1=filter(f1, l)
print(list(m1))
```

**a) filter(lambda x:x<0, l)**\
b) filter(lambda x, y: x<0, l)\
c) filter(reduce x<0, l)\
d) reduce(x: x<0, l)

> Explanation: The code shown above returns a new list containing only those elements from list l, which are less than 0. Since there are no such elements in the list l, the output of this code is: []. The single line equivalent of this code is filter(lambda x:x<0, l).

### 13. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
list(map((lambda x:x^2), range(10)))
```

a) [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]\
b) 29\
**c) [2, 3, 0, 1, 6, 7, 4, 5, 10, 11]**\
d) No output

> Explanation: The line of code shown above returns a list of each number from 1 to 10, after an XOR operation is performed on each of these numbers with 2. Hence the output of this code is: [2, 3, 0, 1, 6, 7, 4, 5, 10, 11]

### 14. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
list(map((lambda x:x**2), filter((lambda x:x%2==0), range(10))))
```

a) [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]\
**b) [0, 4, 16, 36, 64]**\
c) Error\
d) No output

> Explanation: The output list will contain each number up to 10 raised to 2, except odd numbers, that is, 1, 3, 5, 9. Hence the output of the code is: [0, 4, 16, 36, 64].

### 15.The output of the following codes are the same. [Результати наступних рядків коду однакові. ]

```
[x**2 for x in range(10)]
list(map((lambda x:x**2), range(10)))
```

a) True\
b) False

> Explanation: Both of the codes shown above print each whole number up to 10, raised to the power 2. Hence the output of both of these codes is: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]. Therefore, the statement is true.

### 1. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
elements = [0, 1, 2]
def incr(x):
    return x+1
print(list(map(elements, incr)))
```

a) [1, 2, 3]\
b) [0, 1, 2]\
**c) error**\
d) none of the mentioned

> Explanation: The list should be the second parameter to the mapping function.

### 2. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
elements = [0, 1, 2]
def incr(x):
    return x+1
print(list(map(incr, elements)))
```

**a) [1, 2, 3]**\
b) [0, 1, 2]\
c) error\
d) none of the mentioned

> Explanation: Each element of the list is incremented.

### 3. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = ['ab', 'cd']
print(list(map(upper, x)))
```

a) [‘AB’, ‘CD’]\
b) [‘ab’, ‘cd’]\
**c) error**\
d) none of the mentioned

> Explanation: A NameError occurs because upper is a class method.

### 4. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
def to_upper(k):
    return k.upper()
x = ['ab', 'cd']
print(list(map(upper, x)))
```

a) [‘AB’, ‘CD’]\
b) [‘ab’, ‘cd’]\
**c) error**\
d) none of the mentioned

> Explanation: A NameError occurs because upper is a class method.

### 5. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
def to_upper(k):
    return k.upper()
x = ['ab', 'cd']
print(list(map(to_upper, x)))
```

**a) [‘AB’, ‘CD’]**\
b) [‘ab’, ‘cd’]\
c) error\
d) none of the mentioned

> Explanation: Each element of the list is converted to uppercase.

### 6. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
def to_upper(k):
    k.upper()
x = ['ab', 'cd']
print(list(map(to_upper, x)))
```

a) [‘AB’, ‘CD’]\
b) [‘ab’, ‘cd’]\
**c) none of the mentioned**\
d) error

> Explanation: A list of Nones is printed as to_upper() returns None.

### 7. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = ['ab', 'cd']
print(map(len, x))
```

a) [‘ab’, ‘cd’]\
b) [2, 2]\
c) [‘2’, ‘2’]\
**d) none of the mentioned**

> Explanation: A map object is generated by map(). We must convert this to a list to be able to print it in a human readable form.

### 8. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = ['ab', 'cd']
print(list(map(len, x)))
```

a) [‘ab’, ‘cd’]\
**b) [2, 2]**\
c) [‘2’, ‘2’]\
d) none of the mentioned

> Explanation: The length of each string is 2.

### 9. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = ['ab', 'cd']
print(len(map(list, x)))
```

a) [2, 2]\
b) 2\
c) 4\
**d) none of the mentioned**

> Explanation: A TypeError occurs as map has no len().

### 10. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = ['ab', 'cd']
print(len(list(map(list, x))))
```

a) [2, 2]\
**b) 2**\
c) 4\
d) none of the mentioned

> Explanation: The outer list has two lists in it. So it’s length is 2.

### 1. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = ['ab', 'cd']
print(len(list(map(list, x))))))
```

a) 2\
b) 4\
**c) error**\
d) none of the mentioned

> Explanation: SyntaxError, unbalanced parenthesis.

### 2. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = ['ab', 'cd']
print(list(map(list, x)))
```

a) [‘a’, ‘b’, ‘c’, ‘d’]\
b) [[‘ab’], [‘cd’]]\
**c) [[‘a’, ‘b’], [‘c’, ‘d’]]**\
d) none of the mentioned

> Explanation: Each element of x is converted into a list.

### 3. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [12, 34]
print(len(list(map(len, x))))
```

a) 2\
b) 1\
**c) error**\
d) none of the mentioned

> Explanation: SyntaxError, unbalanced parenthesis.

### 4. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [12, 34]
print(len(list(map(int, x))))
```

**a) 2**\
b) 1\
c) error\
d) none of the mentioned

> Explanation: list(map()) returns a list of two items in this example.

### 5. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [12, 34]
print(len(''.join(list(map(int, x)))))
```

a) 4\
b) 2\
**c) error**\
d) none of the mentioned

> Explanation: SyntaxError, unbalanced parenthesis.

### 6. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [12, 34]
print(len(''.join(list(map(str, x)))))
```

**a) 4**\
b) 5\
c) 6\
d) error

> Explanation: Each number is mapped into a string of length 2.

### 7. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [12, 34]
print(len(' '.join(list(map(int, x)))))
```

a) 4\
b) 5\
c) 6\
**d) error**

> Explanation: TypeError. Execute in shell to verify.

### 8. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [12.1, 34.0]
print(len(' '.join(list(map(str, x)))))
```

a) 6\
b) 8\
**c) 9**\
d) error

> Explanation: The floating point numbers are converted to strings and joined with a space between them.

### 9. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [12.1, 34.0]
print(' '.join(list(map(str, x))))
```

a) 12 1 34 0\
b) 12.1 34\
c) 121 340\
**d) 12.1 34.0**

> Explanation: str(ab.c) is ‘ab.c’.

### 10. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [[0], [1]]
print(len(' '.join(list(map(str, x)))))
```

a) 2\
b) 3\
**c) 7**\
d) 8

> Explanation: map() is applied to the elements of the outer loop.

### 1. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [[0], [1]]
print((' '.join(list(map(str, x)))))
```

a) (‘[0] [1]’,)\
b) (’01’,)\
**c) [0] [1]**\
d) 01

> Explanation: (element) is the same as element. It is not a tuple with one item.

### 2. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [[0], [1]]
print((' '.join(list(map(str, x))),))
```

**a) (‘[0] [1]’,)**\
b) (’01’)\
c) [0] [1]\
d) 01

> Explanation: (element,) is not the same as element. It is a tuple with one item.

### 3. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [34, 56]
print((''.join(list(map(str, x))),))
```

a) 3456\
b) (3456)\
c) (‘3456’)\
**d) (‘3456’,)**

> Explanation: We have created a tuple with one string in it.

### 4. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [34, 56]
print((''.join(list(map(str, x)))),)
```

**a) 3456**\
b) (3456)\
c) (‘3456’)\
d) (‘3456’,)

> Explanation: We have just created a string.

### 5. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = [34, 56]
print(len(map(str, x)))
```

a) [34, 56]\
b) [’34’, ’56’]\
c) 34 56\
**d) error**

> Explanation: TypeError, map has no len.

### 6. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = 'abcd'
print(list(map(list, x)))
```

a) [‘a’, ‘b’, ‘c’, ‘d’]\
b) [‘abcd’]\
**c) [[‘a’], [‘b’], [‘c’], [‘d’]]**\
d) none of the mentioned

> Explanation: list() is performed on each character in x.

### 7. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = abcd
print(list(map(list, x)))
```

a) [‘a’, ‘b’, ‘c’, ‘d’]\
b) [‘abcd’]\
c) [[‘a’], [‘b’], [‘c’], [‘d’]]\
**d) none of the mentioned**

> Explanation: NameError, we have not defined abcd.

### 8. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = 1234
print(list(map(list, x)))
```

a) [1, 2, 3, 4]\
b) [1234]\
c) [[1], [2], [3], [4]]\
**d) none of the mentioned**

> Explanation: TypeError, int is not iterable.

### 9. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = 1234
print(list(map(list, [x])))
```

a) [1, 2, 3, 4]\
b) [1234]\
c) [[1], [2], [3], [4]]\
**d) none of the mentioned**

> Explanation: TypeError, int is not iterable.

### 10. What will be the output of the following Python code? [Яким буде результат наступного фрагмента коду Python?]

```
x = 'abcd'
print(list(map([], x)))
```

a) [‘a’, ‘b’, ‘c’, ‘d’]\
b) [‘abcd’]\
c) [[‘a’], [‘b’], [‘c’], [‘d’]]\
**d) none of the mentioned**

> Explanation: TypeError, list object is not callable.

### 11. Is Python code compiled or interpreted? [Python код компілюємий чи інтерпретуємий?]

a) Python code is only compiled\
**b) Python code is both compiled and interpreted**\
c) Python code is only interpreted\
d) Python code is neither compiled nor interpreted

> Explanation: Many languages have been implemented using both compilers and interpreters, including C, Pascal, and Python.

### 12. Which of these is the definition for packages in Python? [Що з цього є визначенням пакету у Python?]

**a) A folder of python modules**\
b) A set of programs making use of Python modules\
c) A set of main modules\
d) A number of files containing Python definitions and statements

> Explanation: A folder of python programs is called as a package of modules.

### 13. Which of these is false about a package? [Що з цього неправда про Python?]

```
x = [[0], [1]]
print(len(' '.join(list(map(str, x)))))
```

a) A package can have subfolders and modules\
**b) Each import package need not introduce a namespace**\
c) import folder.subfolder.mod1 imports packages\
d) from folder.subfolder.mod1 import objects imports packages

> Explanation: Packages provide a way of structuring Python namespace. Each import package introduces a namespace.

# Section 20

####This set of Python Objective Questions & Answers focuses on “Math – 1”.

### 1. What is returned by math.ceil(3.4)? [Що повертає math.ceil(3.4)?]
   a) 3

   **b) 4**

   c) 4.0

   d) 3.0

Explanation: The ceil function returns the smallest integer that is bigger than or equal to the number itself.
### 2. What is the value returned by math.floor(3.4)? [Яке значення повертає math.floor(3.4)?]
   **a) 3**

   b) 4

   c) 4.0

   d) 3.0

Explanation: The floor function returns the biggest number that is smaller than or equal to the number itself.
### 3. What will be the output of print(math.copysign(3, -1))? [Яким буде результат print(math.copysign(3, -1))?]
   a) 1

   b) 1.0

   c) -3

   **d) -3.0**

Explanation: The copysign function returns a float whose absolute value is that of the first argument and the sign is that of the second argument.

### 4. What is displayed on executing print(math.fabs(-3.4))? [Що відображається під час виконання print(math.fabs(-3.4))?]
   a) -3.4

   **b) 3.4**

   c) 3

   d) -3

Explanation: A negative floating point number is returned as a positive floating point number.
### 5. Is the output of the function abs() the same as that of the function math.fabs()? [Чи є результат функції abs() таким же, як і для функції math.fabs()]
   **a) sometimes**

   b) always

   c) never

   d) none of the mentioned
   

Explanation: math.fabs() always returns a float and does not work with complex numbers whereas the return type of abs() is determined by the type of value that is passed to it.
### 6. What is the value returned by math.fact(6)? [Яке значення повертає math.fact(6)]
   a) 720

   b) 6

   c) [1, 2, 3, 6]

   **d) error**

Explanation: NameError, fact() is not defined.
### 7. What is the value of x if x = math.factorial(0)? [Яке значення x, якщо x = math.factorial(0)]
   a) 0

   **b) 1**

   c) error

   d) none of the mentioned

Explanation: Factorial of 0 is 1.
### 8. What is math.factorial(4.0)? [Чому дорівнює math.factorial(4.0)]
   **a) 24**

   b) 1

   c) error

   d) none of the mentioned


### 9. What will be the output of print(math.factorial(4.5))? [Яким буде результат від print(math.factorial(4.5)]
   a) 24 

   b) 120

   **c) error**

   d) 24.0

Explanation: Factorial is only defined for non-negative integers.
### 10. What is math.floor(0o10)? [Чому дорівнює math.floor(0o10)?]
**a) 8**

Explanation: 0o10 is 8 and floor(8) is 8.


####Python Questions and Answers – Math – 2


###1. What does the function math.frexp(x) return? [Що повертає функція math.freexp(x)?]
   **a) a tuple containing the mantissa and the exponent of x**

   b) a list containing the mantissa and the exponent of x

   c) a tuple containing the mantissa of x

   d) a list containing the exponent of x


Explanation: It returns a tuple with two elements. The first element is the mantissa and the second element is the exponent.
###2. What is the result of math.fsum([.1 for i in range(20)])? [Який результат math.fsum([.1 for i in range(20)])?]
   **a) 2.0**
   
b) 20
   
c) 2
   
d) 2.0000000000000004

Explanation: The function fsum returns an accurate floating point sum of the elements of its argument.
###3. What is the result of sum([.1 for i in range(20)])? [Який результат sum([.1 for i in range(20)])?]
   
a) 2.0
   
b) 20
   
c) 2
   
**d) 2.0000000000000004**

Explanation: There is some loss of accuracy when we use sum with floating point numbers. Hence the function fsum is preferable.
###4. What is returned by math.isfinite(float(‘inf’))? [Що повертає math.isfinite(float(‘inf’))?]
   
a) True
   
**b) False**
   
c) None
   
d) error

Explanation: float(‘inf’) is not a finite number.

###5. What is returned by math.isfinite(float(‘nan’))? [Що повертає math.isfinite(float(‘nan’))?]
   
a) True
   
**b) False**
   
c) None
   
d) error

Explanation: float(‘nan’) is not a finite number.
###6. What is x if x = math.isfinite(float(‘0.0’))? [Що таке x, якщо x = math.isfinite(float(‘0.0’))?]
   
**a) True**
   
b) False
   
c) None
   
d) error

Explanation: float(‘0.0’) is a finite number.
###7. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```python 
>>> -float('inf') + float('inf')
```

a) inf

**b) nan**

c) 0

d) 0.0

Explanation: The result of float(‘inf’)-float(‘inf’) is undefined.
###8. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

```python
 print(math.isinf(float('-inf')))
```

a) error, the minus sign shouldn’t have been inside the brackets

b) error, there is no function called isinf

**c) True**

d) False

Explanation: -float(‘inf’) is the same as float(‘-inf’).
###9. What is the value of x if x = math.ldexp(0.5, 1)? [Яке значення x, якщо x = math.ldexp(0,5, 1)?]
   
a) 1
   
b) 2.0
   
c) 0.5
   
**d) none of the mentioned**

Explanation: The value returned by ldexp(x, y) is x * (2 ** y). In the current case x is 1.0.
###10. What is returned by math.modf(1.0)? [Що повертає math.modf(1.0)?]
    
**a) (0.0, 1.0)**
    
b) (1.0, 0.0)
    
c) (0.5, 1)
    
d) (0.5, 1.0)

Explanation: The first element is the fractional part and the second element is the integral part of the argument.

####Python Questions and Answers – Math – 3

###1. What is the result of math.trunc(3.1)? [Який результат math.trunc(3.1)?]
   
a) 3.0
   
**b) 3**
   
c) 0.1
   
d) 1

Explanation: The integral part of the floating point number is returned.
###2. What is the output of print(math.trunc(‘3.1’))? [Який результат буде print(math.trunc(‘3.1’))?]
   
a) 3
   
b) 3.0
   
**c) error**
   
d) none of the mentioned

Explanation: TypeError, a string does not have __trunc__ method.
###3. Which of the following is the same as math.exp(p)? [Що з наведеного нижче відповідає math.exp(p)?]
   
a) e ** p
   
**b) math.e ** p**
   
c) p ** e
   
d) p ** math.e

Explanation: math.e is the constant defined in the math module.

###4. What is returned by math.expm1(p)? [Що повертає math.expm1(p)?]
   
**a) (math.e ** p) – 1**
   
b) math.e ** (p – 1)
   
c) error
   
d) none of the mentioned

Explanation: One is subtracted from the result of math.exp(p) and returned.
###5. What is the default base used when math.log(x) is found? [Яка база за замовчуванням використовується, коли знайдено math.log(x)?]
   
**a) e**
   
b) 10
   
c) 2
   
d) none of the mentioned

Explanation: The natural log of x is returned by default.
###6. Which of the following aren’t defined in the math module? [Що з наведеного нижче не визначено в математичному модулі?]
   
a) log2()
   
b) log10()
   
**c) logx()**
   
d) none of the mentioned

Explanation: log2() and log10() are defined in the math module.
###7. What is returned by int(math.pow(3, 2))? [Що повертає int(math.pow(3, 2))?]
   
a) 6
   
**b) 9**
   
c) error, third argument required
   
d) error, too many arguments

Explanation: math.pow(a, b) returns a ** b.
###8. What is output of print(math.pow(3, 2))? [Який вивід print(math.pow(3, 2))?]
   
a) 9
   
**b) 9.0**
   
c) None
   
d) None of the mentioned

Explanation: math.pow() returns a floating point number.
###9. What is the value of x if x = math.sqrt(4)? [Яке значення x, якщо x = math.sqrt(4)?]
   
a) 2
   
**b) 2.0**
   
c) (2, -2)
   
d) (2.0, -2.0)

Explanation: The function returns one floating point number.
###10. What does math.sqrt(X, Y) do? [Що робить math.sqrt(X, Y)?]
    
a) calculate the Xth root of Y
    
b) calculate the Yth root of X
    
**c) error**
    
d) return a tuple with the square root of X and Y

Explanation: The function takes only one argument.

# Section 21

Python Question and Answers – Datetime Module – 1

## 1. [broken] What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

import datetime
d=datetime.date(2016,7,24) тут переплутали рік
print(d)
a) Error
**b) 2017-07-24**
c) 2017-7-24
d) 24-7-2017

> In the snippet of code shown above, we are simply printing the date entered by us. We enter the date in the format: yyyy,m,dd. The date is then printed in the format: yyyy-mm-dd. Hence the output is: 2017-07-24.

## 2. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

import datetime
d=datetime.date(2017,06,18)
print(d)
**a) Error**
b) 2017-06-18
c) 18-06-2017
d) 06-18-2017

> The code shown above will result in an error because of the format of the date entered. Had the date been entered as: d=datetime.date(2017,6,18), no error would have been thrown.

## 3. [broken] What will be the output of the following Python code if the system date is 18th August, 2016? [Яким буде результат наступного коду Python, якщо системна дата – 18 серпня 2016 р.?]

Ну мабуть тут має бути import datetime
tday=datetime.date.today()
print(tday.month()) а тут треба писати tday.month

Якщо виконати всі зауваження то відповідь підсвічена нижче, інашке Error
a) August
b) Aug
c) 08
**d) 8**

> The code shown above prints the month number from the system date. Therefor the output will be 8 if the system date is 18th August, 2016.

## 4. What will be the output of the following Python code if the system date is 18th June, 2017? [Яким буде вихід наступного коду Python, якщо системна дата – 18 червня 2017 р.?]

import datetime
tday=datetime.date.today()
print(tday)

a) 18-06-2017
b) 06-18-2017
**c) 2017-06-18**
d) Error

> The code shown above prints the system date in the format yyyy-mm-dd. Hence the output of this code is: 2017-06-18.

## 5. [broken] What will be the output of the following Python code if the system date is 18th June, 2017 (Sunday)? [Яким буде результат наступного коду Python, якщо системна дата – 18 червня 2017 року (неділя)?]

Ну мабуть тут має бути `import datetime`
tday=datetime.date.today()
print(tday.weekday())

**a) 6**
b) 1
c) 0
d) 7

> The code shown above prints an integer depending on which day of the week it is. Monday-0, Tuesday-1, Wednesday-2, Thursday-3, Friday-4, Saturday-5, Sunday-6. Hence the output is 6 in the case shown above.

## 6. [broken] What will be the output of the following Python code if the system date is 21st June, 2017 (Wednesday)? [Яким буде результат наступного коду Python, якщо системна дата – 21 червня 2017 року (середа)?]

Ну мабуть тут має бути `import datetime`
tday=datetime.date.today()
print(tday.isoweekday())

a) Wed
b) Wednesday
c) 2
**d) 3**

> This code prints an integer depending on which day of the week it is. Monday-1, Tuesday-2, Wednesday-3, Thursday-4, Friday-5, Saturday-6, Sunday-7. Hence the output of the code shown above is 3.

## 7. [broken] Point out the error (if any) in the code shown below if the system date is 18th June, 2017? [Вкажіть на помилку (якщо є) у коді, показаному нижче, якщо системна дата – 18 червня 2017 р.?]

Ну мабуть тут має бути import datetime
tday=datetime.date.today()
bday=datetime.date(2017,9,18)
till_bday=bday-tday
print(till_bday)

a) 3 months, 0:00:00
b) 90 days, 0:00:00
c) 3 months 2 days, 0:00:00
**d) 92 days, 0:00:00**

> The code shown above can be used to find the number of days between two given dates. The output of the code shown above will thus be 92.

## 8. The value returned when we use the function isoweekday() is **\_\_** and that for the function weekday() is **\_\_\_\_** if the system date is 19th June, 2017 (Monday)? [Значення, яке повертається, коли ми використовуємо функцію isoweekday(), дорівнює ______, а для функції weekday() — ________, якщо системна дата — 19 червня 2017 року (понеділок)?]

a) 0,0
b) 0,1
**c) 1,0**
d) 1,1

> The value returned when we use the function isoweekday() is 1 and that for the function weekday() is 0 if the system date is 19th June, 2017 (Monday).

## 9. [broken] Which of the following will throw an error if used after the following Python code? [Що з наведеного нижче призведе до помилки, якщо використовується після наступного коду Python?]

Ну мабуть тут має бути import datetime
tday=datetime.date.today()
bday=datetime.date(2017,9,18)
t_day=bday-tday

a) print(t_day.seconds)
**b) print(t_day.months)**
c) print(t_day.max)
d) print(t_day.resolution)

> The statement: print(t_day.months) will throw an error because there is no function such as t_day.months, whereas t_day.seconds, t_day.max and t_day.resolution are valid, provided that t_day is defined.

## 10. [broken] What will be the output of the following Python code if the system date is: 6/19/2017? [Яким буде вихід наступного коду Python, якщо системна дата: 19.06.2017?]

Ну мабуть тут має бути import datetime
tday=datetime.date.today()
tdelta=datetime.timedelta(days=10)
print(tday+tdelta)

a) 2017-16-19
b) 2017-06-9
**c) 2017-06-29**
d) Error

> The code shown above will add the specified number of days to the current date and print the new date. On adding ten days to 6/19/2017, we get 6/29/2017. Hence the output is: 2017-06-29.

Python Question and Answers – Datetime Module – 2

## 1. [broken] The output of both of the print statements is the same. [Висновок обох операторів друку однаковий.]

import datetime
dt_1 = datetime.datetime.today()
dt_2 = datetime.datetime.now()
print(dt_1)
print(dt_2)
У відповідях було написано що правильно False бо - див. Explanation, але якщо в питанні малось на увазі чи виводить воно одне і те саме - то відповідь True + я скомпілив і різниці у часі не було помітно.

**a) True**
b) False

> The output of the two print statements is not the same because of the difference in time between the execution of the two print statements. There is a difference in the order of milliseconds between the two statements and this is reflected in the output.

## 2. Which of the following functions can be used to find the coordinated universal time, assuming that the datetime module has already been imported? [Яку з наведених нижче функцій можна використовувати, щоб знайти скоординований універсальний час, якщо припустити, що модуль datetime вже імпортовано?]

a) datetime.utc()
b) datetime.datetime.utc()
c) datetime.utcnow()
**d) datetime.datetime.utcnow()**

> The function datetime.datetime.utcnow() can be used to find the UTC (Coordinated Universal Time), assuming that the datetime module has already been imported. The other function s shown above are invalid.

## 3. [broken] What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

import time
time.time()
a) The number of hours passed since 1st January, 1970
b) The number of days passed since 1st January, 1970
**c) The number of seconds passed since 1st January, 1970**
d) The number of minutes passed since 1st January, 1970
Якщо дописати print(time.time()) то відповідь c.

> The code shown above will return the number of seconds passed since 1st January, 1970.

## 4. [broken] What will be the output of the following Python code, if the time module has already been imported? [Яким буде результат наступного коду Python, якщо модуль часу вже імпортовано?]

def num(m):
t1 = time.time()
for i in range(0,m):
print(i)
t2 = time.time()
print(str(t2-t1))

    num(3)

**a) 1**
** 2**
** 3**
** The time taken for the execution of the code**
b) 3
The time taken for the execution of the code
c) 1
2
3
UTC time
d) 3
UTC time
Якась діч, бо воно має виводити з 0 а не з 1 як у відповідях. У мене після запуску вивело 0 1 2 0.0

> The code shown above will return the numbers 1, 2, 3, followed by the time taken in the execution of the code.
> Output:
> 1
> 2
> 3
> The time taken for the execution of the code

## 5. [broken] What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

import time
time.asctime()
a) Current date only
b) UTC time
**c) Current date and time**
d) Current time only
Якщо дописати print(time.asctime()) то відповідь c.

> The function time.asctime(), present if the time module can be used to return the current date and time. It can also accept a parameter and return the date and time in a particular format. However in the above code, since we have not passed any parameters in the above code, the current date and time is returned.

## 6. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

import time
t=(2010, 9, 20, 8, 15, 12, 6)
time.asctime(t)
a) ‘20 Sep 2010 8:15:12 Sun’
b) ‘2010 20 Sept 08:15:12 Sun’
c) ‘Sun Sept 20 8:15:12 2010’
**d) Error**

> The code shown above results in an error because this function accepts exactly 9 arguments (including day of the year and DST), but only 7 are given. Hence an error is thrown.

## 7. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

import time
t=(2010, 9, 20, 8, 45, 12, 6, 0, 0)
time.asctime(t)
a) ‘Sep 20 2010 08:45:12 Sun’
**b) ‘Sun Sep 20 08:45:12 2010’**
c) ’20 Sep 08:45:12 Sun 2010’
d) ‘2010 20 Sep 08:45:12 Sun’

> The code shown above returns the given date and time in a particular format. Hence the output of the code shown above will be: ‘Sun Sep 20 08:45:12 2010’.

## 8. The sleep function (under the time module) is used to \***\*\_\_\_\*\*** [Функція сну (під модулем часу) використовується для ___________]

**a) Pause the code for the specified number of seconds**
b) Return the specified number of seconds, in terms of milliseconds
c) Stop the execution of the code
d) Return the output of the code had it been executed earlier by the specified number of seconds

> The sleep function (under the time module) is used to pause the code for the specified number of seconds. The number of seconds is taken as an argument by this function.

## 9. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

import time
for i in range(0,5):
print(i)
time.sleep(2)
a) After an interval of 2 seconds, the numbers 1, 2, 3, 4, 5 are printed all together
b) After an interval of 2 seconds, the numbers 0, 1, 2, 3, 4 are printed all together
c) Prints the numbers 1, 2, 3, 4, 5 at an interval of 2 seconds between each number
**d) Prints the numbers 0, 1, 2, 3, 4 at an interval of 2 seconds between each number**

> The output of the code shown above will be the numbers 0, 1, 2, 3, 4 at an interval of 2 seconds each.

## 10. What will be the output if we try to extract only the year from the following Python code? (time.struct_time(tm_year=2017, tm_mon=6, tm_mday=25, tm_hour=18, tm_min=26, tm_sec=6, tm_wday=6, tm_yday=176, tm_isdst=0))? [Яким буде результат, якщо ми спробуємо витягти лише рік із наступного коду Python? (time.struct_time(tm_year=2017, tm_mon=6, tm_mday=25, tm_hour=18, tm_min=26, tm_sec=6, tm_wday=6, tm_yday=176, tm_isdst=0))?]

import time
t=time.localtime()
print(t)
a) t[1]
b) tm_year
**c) t[0]**
d) t_year

> To extract the year from the code shown above, we use the command t[0]. The command t[1] will return the month number (6 in the above case). The commands tm_year and t_year will result in errors.

Python Question and Answers – Random module – 1

## 1. To include the use of functions which are present in the random library, we must use the option: [Щоб включити використання функцій, які присутні у випадковій бібліотеці, ми повинні використовувати параметр:]

**a) import random**
b) random.h
c) import.random
d) random.random

> The command import random is used to import the random module, which enables us to use the functions which are present in the random library.

## 2. The output of the following Python code is either 1 or 2 [Результатом наступного коду Python є 1 або 2]

import random
random.randint(1,2)
**a) True**
b) False

> The function random.randint(a,b) helps us to generate an integer between ‘a’ and ‘b’, including ‘a’ and ‘b’. In this case, since there are no integers between 1 and 2, the output will necessarily be either 1 or 2’.

## 3. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

import random
random.choice(2,3,4)
a) An integer other than 2, 3 and 4
b) Either 2, 3 or 4
**c) Error**
d) 3 only

> The code shown above displays the incorrect syntax of the function random.choice(). This functions takes its numeric parameter in the form of a list. Hence the correct syntax world be: random.choice([2,3,4]).

## 4. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

import random
random.choice([10.4, 56.99, 76])
a) Error
**b) Either 10.4, 56.99 or 76**
c) Any number other than 10.4, 56.99 and 76
d) 56.99 only

> The function random.choice(a,b,c,d) returns a random number which is selected from a, b, c and d. The output can be either a, b, c or d. Hence the output of the snippet of code shown above can be either 10.4, 56.99 or 76.

## 5. What will be the output of the following Python function (random module has already been imported)? [Яким буде результат наступної функції Python (довільний модуль вже імпортовано)?]

random.choice('sun')
a) sun
b) u
**c) either s, u or n**
d) error

> The above function works with alphabets just as it does with numbers. The output of this expression will be either s, u or n.

## 6. What will be the output of the following Python function, assuming that the random module has already been imported? [Яким буде результат наступної функції Python, якщо припустити, що випадковий модуль вже імпортовано?]

random.uniform(3,4)
a) Error
b) Either 3 or 4
c) Any integer other than 3 and 4
**d) Any decimal value between 3 and 4**

> This question depicts the basic difference between the functions random.randint(a, b) and random.uniform(a, b). While random.randint(a,b) generates an integer between ‘a’ and ‘b’, including ‘a’ and ‘b’, the function random.uniform(a,b) generates a decimal value between ‘a’ and ‘b’.

## 7. What will be the output of the following Python function if the random module has already been imported? [Яким буде результат наступної функції Python, якщо випадковий модуль вже імпортовано?]

random.randint(3.5,7)
**a) Error**
b) Any integer between 3.5 and 7, including 7
c) Any integer between 3.5 and 7, excluding 7
d) The integer closest to the mean of 3.5 and 7

> The function random.randint() does not accept a decimal value as a parameter. Hence the function shown above will throw an error.

## 8. Which of the following functions helps us to randomize the items of a list? [Яка з наведених нижче функцій допомагає нам рандомізувати елементи списку?]

a) seed
b) randomise
**c) shuffle**
d) uniform

> The function shuffle, which is included in the random module, helps us to randomize the items of a list. This function takes the list as a parameter.

## 9. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

random.seed(3)
random.randint(1,5)
2
random.seed(3)
random.randint(1,5)
a) 3
**b) 2**
c) Any integer between 1 and 5, including 1 and 5
d) Any integer between 1 and 5, excluding 1 and 5

> We use the seed function when we want to use the same random number once again in our program. Hence the output of the code shown above will be 2, since 2 was generated previously following which we used the seed function.

## 10. What is the interval of the value generated by the function random.random(), assuming that the random module has already been imported? [Який інтервал значення генерується функцією random.random(), якщо припустити, що модуль random вже імпортовано?]

a) (0,1)
b) (0,1]
c) [0,1]
**d) [0,1)**

> The function random.random() generates a random value in the interval [0,1), that is, including zero but excluding one.

## 11. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

random.randrange(0,91,5)
**a) 10**
b) 18
c) 79
d) 95

> The function shown above will generate an output which is a multiple of 5 and is between 0 and 91. The only option which satisfies these criteria is 10. Hence the only possible output of this function is 10.

## 12. Both the functions randint and uniform accept \***\*\_\_\_\_\*\*** parameters. [Обидві функції randint і uniform приймають ____________ параметри.]

a) 0
b) 1
c) 3
**d) 2**

> Both of these functions, that is, randint and uniform are included in the random module and both of these functions accept 2 parameters. For example: random.uniform(a,b) where ‘a’ and ‘b’ specify the range.

## 13. The randrange function returns only an integer value. [Функція randrange повертає лише ціле значення.]

**a) True**
b) False

> The function randrange returns only an integer value. Hence this statement is true.

## 14. What will be the output of the following Python code? [Яким буде результат наступного коду Python?]

random.randrange(1,100,10)
a) 32
b) 67
**c) 91**
d) 80

> The output of this function can be any value which is a multiple of 10, plus 1. Hence a value like 11, 21, 31, 41…91 can be the output. Also, the value should necessarily be between 1 and 100. The only option which satisfies this criteria is 91.

## 15. What will be the output of the following Python function, assuming that the random library has already been included? [Яким буде результат наступної функції Python, якщо припустити, що випадкова бібліотека вже включена?]

random.shuffle[1,2,24]
a) Randomized list containing the same numbers in any order
b) The same list, that is [1,2,24]
c) A list containing any random numbers between 1 and 24
**d) Error**

> The function shown above will result in an error because this is the incorrect syntax for the usage of the function shuffle(). The list should be previously declared and then passed to this function to get an output.
> An example of the correct syntax:
>
> > > l=['a','b','c','d']
> > > random.shuffle(l)
> > > print(l)

Python Questions and Answers – Random Module – 2

## 1. What the does random.seed(3) return? [Що повертає random.seed(3)?]

a) True
**b) None**
c) 3
d) 1

> The function random.seed() always returns a None.

## 2. Which of the following cannot be returned by random.randrange(4)? [Що з наведеного нижче не може бути повернуто random.randrange(4)?]

a) 0
b) 3
**c) 2.3**
d) none of the mentioned

> Only integers can be returned.

## 3. Which of the following is equivalent to random.randrange(3)? [Що з наведеного нижче є еквівалентним random.randrange(3)?]

a) range(3)
**b) random.choice(range(0, 3))**
c) random.shuffle(range(3))
d) random.select(range(3))

> It returns one number from the given range.

## 4. The function random.randint(4) can return only one of the following values. Which? [Функція random.randint(4) може повертати лише одне з наступних значень. Котрий?]

a) 4
b) 3.4
**c) error**
d) 5

> Error, the function takes two arguments.

## 5. Which of the following is equivalent to random.randint(3, 6)? [Що з наведеного нижче є еквівалентним random.randint(3, 6)?]

a) random.choice([3, 6])
b) random.randrange(3, 6)
c) 3 + random.randrange(3)
**d) 3 + random.randrange(4)**

> Random.randint(3, 6) can return any one of 3, 4, 5 and 6.

## 6. Which of the following will not be returned by random.choice(“1 ,”)? [Що з наведеного нижче не буде повернуто random.choice(“1 ,”)?]

a) 1
b) (space)
c) ,
**d) none of the mentioned**

> Any of the characters present in the string may be returned.

## 7. Which of the following will never be displayed on executing print(random.choice({0: 1, 2: 3}))? [Що з наведеного нижче ніколи не відображатиметься під час виконання print(random.choice({0: 1, 2: 3}))?]

**a) 0**
b) 1
c) KeyError: 1
d) none of the mentioned

> It will not print 0 but dict[0] i.e. 1 may be printed.

## 8. What does random.shuffle(x) do when x = [1, 2, 3]? [Що робить random.shuffle(x), коли x = [1, 2, 3]?]

a) error
b) do nothing, it is a placeholder for a function that is yet to be implemented
**c) shuffle the elements of the list in-place**
d) none of the mentioned

> The elements of the list passed to it are shuffled in-place.

## 9. Which type of elements are accepted by random.shuffle()? [Який тип елементів приймає random.shuffle()?]

a) strings
**b) lists**
c) tuples
d) integers

> Strings and tuples are immutable and an integer has no len().

## 10. What is the range of values that random.random() can return? [Який діапазон значень може повернути random.random()?]

a) [0.0, 1.0]
b) (0.0, 1.0]
c) (0.0, 1.0)
**d) [0.0, 1.0)**

> Any number that is greater than or equal to 0.0 and lesser than 1.0 can be returned.

# Section 22

### Which of the following functions can help us to find the version of python that we are currently working on? [Яка з функцій допоможе знайте версія Python, яку ми зараз використовуємо?]

**a) sys.version**\
b) sys.version()\
c) sys.version(0)\
d) sys.version(1)

> Explanation: The function sys.version can help us to find the version of python that we are currently working on. For example, 3.5.2, 2.7.3 etc. this function also returns the current date, time, bits etc along with the version.

### Which of the following functions is not defined under the sys module? [Яка з функцій не визначена в модулі sys?]

a) sys.platform\
b) sys.path\
**c) sys.readline**\
d) sys.argv

> Explanation: The functions sys.platform, sys.path and sys.argv are defined under the sys module. The function sys.readline is not defined. However, sys.stdin.readline is defined.

### The output of the functions len(“abc”) and sys.getsizeof(“abc”) will be the same. [Вивід функцій len(“abc”) і sys.getsizeof(“abc”) буде однаковий.]

a) True\
**b) False**

> Explanation: The function len returns the length of the string passed, and hence it’s output will be 3. The function getsizeof, present under the sys module returns the size of the object passed. It’s output will be a value much larger than 3. Hence the above statement is false.

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

> Explanation: The output of the function sys.platform[:2] is equal to ‘wi’, when this code is run on windows operating system. Hence the output printed is ‘hello’.

### What will be the output of the following Python code, if the sys module has already been imported? [Який буде вивід, якщо модуль sys вже заімпортований?]

`sys.stdout.write("hello world")`

a) helloworld\
b) hello world10\
**c) hello world11**\
d) error

> Explanation: The function shown above prints the given string along with the length of the string. Hence the output of the function shown above will be hello world11. (In PyChram output = "hello world", in terminal = "hello world11", think about it :))

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

> Explanation: The function shown above works just like raw_input. Hence it automatically adds a ‘\n’ character to the input string. Therefore, the output of the function shown above will be: Sanfoundry\n.

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

> Explanation: The function shown above evaluates the input into a string. Hence if the input entered is enclosed in double quotes, the output will be enclosed in single quotes. Therefore, the output of this code is ‘India’.

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

> Explanation: The code shown above will result in an error. This is because this particular function accepts only strings enclosed in single or double inverted quotes, or numbers. Since the string entered above is not enclosed in single or double inverted quotes, an error will be thrown.

### What will be the output of the following Python code? [Який буде вивід наступного коду?]

```python
import sys
sys.argv[0]
```

a) Junk value\
**b) ‘ ‘**\
c) No output\
d) Error

> Explanation: The output of the function shown above will be a blank space enclosed in single quotes. Hence the output of the code shown above is ‘ ‘.

### What will be the output of the following Python code? [Який буде вивід наступного коду?]

```python
import sys
sys.stderr.write(“hello”)
```

a) ‘hello’\
b) ‘hello\n’\
c) hello\
**d) hello5**

> Explanation: The code shown above returns the string, followed by the length of the string. Hence the output of the code shown above is hello5.

### What will be the output of the following Python code? [Який буде вивід наступного коду?]

```python
import sys
sys.argv
```

a) ‘ ‘\
b) [ ]\
**c) [‘ ‘]**\
d) Error

> Explanation: The output of the code shown above is a blank space inserted in single quotes, which is enclosed by square brackets. Hence the output will be [‘ ‘].

### To obtain a list of all the functions defined under sys module, which of the following functions can be used? [Щоб отримати список усіх функцій, визначених у модулі sys, які з наведених нижче функцій можна використовувати]

a) print(sys)\
b) print(dir.sys)\
c) print(dir[sys])\
**d) print(dir(sys))**

> Explanation: The function print(dir(sys)) helps us to obtain a list of all the functions defined under the sys module. The function can be used to obtain the list of functions under any given module in Python.

### The output of the function len(sys.argv) is [Вивід функції len(sys.argv) - це]

a) Error\
**b) 1**\
c) 0\
d) Junk value

> Explanation: The output of the function sys.argv is [‘ ‘]. When we execute the function len([‘ ‘]), the output is 1. Hence the output of the function len(sys.argv) is also 1.

### What does os.name contain? [Що містить в собі os.name?]

**a) the name of the operating system dependent module imported**\
b) the address of the module os\
c) error, it should’ve been os.name()\
d) none of the mentioned

> Explanation: It contains the name of the operating system dependent module imported such as ‘posix’, ‘java’ etc.

### What does print(os.geteuid()) print? [Що виводить функція print(os.geteuid())?]

a) the group id of the current process\
**b) the user id of the current process**\
c) both the group id and the user of the current process\
d) none of the mentione

> Explanation: os.geteuid() gives the user id while the os.getegid() gives the group id.

### What does os.getlogin() return? [Що повертає функція os.getlogin()?]

**a) name of the current user logged in**\
b) name of the superuser\
c) gets a form to login as a different user\
d) all of the mentioned

> Explanation: It returns the name of the user who is currently logged in and is running the script.

### What does os.close(f) do? [Що робить os.close()?]

a) terminate the process f\
b) terminate the process f if f is not responding\
**c) close the file descriptor f**\
d) return an integer telling how close the file pointer is to the end of file

> Explanation: When a file descriptor is passed as an argument to os.close() it will be closed.

### What does os.fchmod(fd, mode) do? [Що робить os.fchmod(fd, mode)?]

**a) change permission bits of the file**\
b) change permission bits of the directory\
c) change permission bits of either the file or the directory\
d) none of the mentioned\

> Explanation: The arguments to the function are a file descriptor and the new mode.

### Which of the following functions can be used to read data from a file using a file descriptor? [Яку з наведених нижче функцій можна використовувати для читання даних із файлу за допомогою дескриптора файлу?]

a) os.reader()\
**b) os.read()**\
c) os.quick_read()\
d) os.scan()

> Explanation: None of the other functions exist.

### Which of the following returns a string that represents the present working directory? [Що з наведеного нижче повертає рядок, що представляє поточний робочий каталог?]

**a) os.getcwd()**\
b) os.cwd()\
c) os.getpwd()\
d) os.pwd()

> Explanation: The function getcwd() (get current working directory) returns a string that represents the present working directory.

### What does os.link() do? [Що робить os.link()?]

a) create a symbolic link\
**b) create a hard link**\
c) create a soft link\
d) none of the mentioned

> Explanation: os.link(source, destination) will create a hard link from source to destination.

### Which of the following can be used to create a directory? [Що з наведеного нижче можна використовувати для створення каталогу?]

**a) os.mkdir()**\
b) os.creat_dir()\
c) os.create_dir()\
d) os.make_dir()

> Explanation: The function mkdir() creates a directory in the path specified.

### Which of the following can be used to create a symbolic link? [Що з наведеного нижче можна використовувати для створення символічного посилання?]

**a) os.symlink()**\
b) os.symb_link()\
c) os.symblin()\
d) os.ln()

> Explanation: It is the function that allows you to create a symbolic link.

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

> Explanation: According to the code shown above, 4 lines will be drawn. Three lines will be in the shape of a triangle. The fourth line will trace the base, which is already drawn. Hence the base will be slightly thicker than the rest of the lines. However there will be no change in the shape due to this extra line. Hence the output shape will be a triangle.

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

> Explanation: The number of lines drawn in the first case is 10, while that in the second case is 9.

### The command which helps us to reset the pen (turtle): [Команда, яка допомагає нам скинути pen (turtle)]

a) turtle.reset\
b) turtle.penreset\
c) turtle.penreset()\
**d) turtle.reset()**

> Explanation: The command turtle.reset() helps us to reset the pen. After the execution of this command, we get a blank page with an arrow on it. We can then perform any desired operation on this page.

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

> Explanation: An angle of -120 will result in the formation of an upright, equilateral triangle. An angle of 120 will result in the formation of an inverted triangle. The angles of 60 and -60 do not result in the formation of a triangle.

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

> Explanation: The code shown above will result in the formation of a square, with each of side 60.

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

> Explanation: The output of the code shown above will be a single square. This is because the function t.penup() is used to lift the pen after the construction of the first square. However, the function t.pendown() has not been used to put the pen back down. Hence, the output shape of this code is one square, of side 100 units.

### Which of the following functions does not accept any arguments? [Яка з наведених функцій не приймає жодних аргументів?]

**a) position**\
b) fillcolor\
c) goto\
d) setheading()

> Explanation: The functions fillcolor(), goto() and setheading() accept arguments, whereas the function position() does not accept any arguments. The function position() returns the current position of the turtle.

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

> Explanation: The goto functions takes the arrow to the position specified by the user as arguments. The position function returns the current position of the arrow. Hence the output of the code shown above will be: 300.00, 9.00.

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

> Explanation: It is clear from the above code that 5 lines will be drawn on the canvas, at an angle of 144 degrees. The only shape which fits this description is star. Hence the output of the code shown above is star.

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

> Explanation: The output of the code shown above is two equilateral triangles (of side 100 units), joined at the vertex.

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

> Explanation: The function t.colour(0, 0, 1) is used to fill in the colour blue into any given shape. Hence the output of the code shown above will be a circle filled in with the colour blue.

### Which of the following functions can be used to make the arrow black? [Яку з наведених нижче функцій можна використати, щоб зробити стрілку чорною?]

a) turtle.color(0,1,0)\
b) turtle.color(1,0,0)\
c) turtle.color(0,0,1)\
**d) turtle.color(0,0,0)**

> Explanation: The function turtle.color(0,0,0) can change the colour of the arrow. The function turtle.color(0,1,0) will make the arrow green. The function turtle.color(1,0,0) will make the arrow red. The function turtle.color(0,0,1) will make the arrow blue. The function turtle.color(0,0,0) will make the arrow black.

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

> Explanation: The code shown above will result in a blank page. This is because the command turtle.color(1,1,1) eliminates the arrow from the page. Hence all the commands after this command are ineffective.

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

> Explanation: The output shape of the code shown above is a square, outlined with the colour green, but not filled in with any colour. This is because we have not used the command t.end_fill() at the end.

### In which direction is the turtle pointed by default? [У який бік за замовчуванням вказана turtle?]

a) North\
b) South\
**c) East**\
d) West

> Explanation: By default, the turtle is pointed towards the east direction. We can change the direction of the turtle by using certain commands. However, whenever the turtle is reset, it points towards east.

### The command used to set only the x coordinate of the turtle at 45 units is: [Команда, яка використовується для встановлення лише координати x turtle на 45 одиниць]

a) reset(45)\
**b) setx(45)**\
c) xset(45)\
d) xreset(45)

> Explanation: The command setx(45) is used to set the x coordinate of the turtle. Similarly, the command sety() is used to set the y coordinate of the turtle. The function reset() takes two values as arguments, one for the x-coordinate and the other for the y-coordinate.

### Which of the following functions returns a value in degrees, counterclockwise from the horizontal right? [Яка з наведених нижче функцій повертає значення в градусах проти годинникової стрілки від горизонтального праворуч?]

**a) heading()**\
b) degrees()\
c) position()\
d) window_height()

> Explanation: The function heading() returns the heading of the turtle, which is a value in degrees counterclockwise from the horizontal right. This measure will be in radians if radians() has been called.

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

> Explanation: The output of the code shown above will be 270.0. The function heading() returns the heading of the turtle, a value in degrees, counterclockwise from the horizontal right. The output shape of this code is a straight line pointing downwards.

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

> Explanation: The function t.clear() returns a blank canvas, without changing the position of the turtle. Since the turtle is visible on the blank canvas, the output of this code is: Yes.

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

> Explanation: (Ну вапще-то (100.00, 0.00)..., но ладна) The output of the code shown above is 100.00, 100.00. The function clear() is used to erase the entire canvas and redraw the turtle. However, the position of the turtle is not changed.

# Section 23

# Section 24

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.compile('hello', re.X)```

a) [‘h’, ‘e’, ‘l’, ‘l’, ‘o’]\
**b) re.compile(‘hello’, re.VERBOSE)**\
c) Error\
d) Junk value\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.split('[a-c]', '0a3B6', re.I)```

a) Error\
b) [‘a’, ‘B’]\
**c) [‘0’, ‘3B6’]**\
d) [‘a’]\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.sub('morning', 'evening', 'good morning')```

**a) ‘good evening’**\
b) ‘good’\
c) ‘morning’\
d) ‘evening’\

### The function re.error raises an exception if a particular string contains no match for the given pattern [Функція re.error викликає помилку, якщо рядок не відповідає заданому шаблону]

a) True\
**b) False**\
>The function re.error raises an exception when a string passed to one of its functions here is not a valid regular expression. It does not raise an exception if a particular string does not contain a match for the given pattern.

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.escape('new**world')```

a) ‘new world’\
**b) ‘new\\*\\*world’**\
c) ‘**’\
d) ‘new’, ‘*’, ‘*’, ‘world’\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.fullmatch('hello', 'hello world')```

**a) No output**\
b) []\
c) <_sre.SRE_Match object; span=(0, 5), match='hello'>\
d) Error\

### Choose the option wherein the two choices do not refer to the same option [Виберіть варіант, у якому ці два варіанти не стосуються одного параметра]

a) re.I  re.IGNORECASE\
b) re.M  re.MULTILINE\
c) re.X  re.VERBOSE\
**d) re.L  re.LOWERCASE**\
>The function re.L is also written as re.LOCALE. There is no function such as re.LOWERCASE in the re module of Python.

### The difference between the functions re.sub and re.subn is that re.sub returns a ___ whereas re.subn returns a __ [Різниця між функціями re.sub і re.subn полягає в тому, що re.sub повертає __, тоді як re.subn повертає __]

a) string, list\
b) list, tuple\
**c) string, tuple**\
d) tuple, list\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.split('mum', 'mumbai*', 1)```

a) Error\
**b) [”, ‘bai*’]*\
c) [”, ‘bai’]\
d) [‘bai*’]\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.findall('good', 'good is good') ```
```re.findall('good', 'bad is good')```

**a) ```[‘good’, ‘good’]**
**[‘good’]```**\
b) ```(‘good’, ‘good’)
(good)```\
c) ```(‘good’)
(‘good’)```\
d) ```[‘good’]
[‘good’]```\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.split(r'(n\d)=', 'n1=3.1, n2=5, n3=4.565')```

a) Error\
**b) [”, ‘n1’, ‘3.1, ‘, ‘n2’, ‘5, ‘, ‘n3’, ‘4.565’]**\
c) [‘n1’, ‘3.1, ‘, ‘n2’, ‘5, ‘, ‘n3’, ‘4.565’]\
d) [‘3.1, ‘, ‘5, ‘, ‘4.565’]\

### The function of re.search is ___ [Функція re.search це __]

a) Matches a pattern at the start of the string\
b) Matches a pattern at the end of the string\
**c) Matches a pattern from any part of a string**\
d) Such a function does not exist\

### Which of the following functions creates a Python object? [Яка з наведених нижче функцій створює об’єкт Python?]

**a) re.compile(str)**\
b) re.assemble(str)\
c) re.regex(str)\
d) re.create(str)\

### Which of the following pattern matching modifiers permits whitespace and comments inside the regular expression? [Які з наведених нижче модифікаторів відповідності шаблону допускають пробіли та коментарі всередині регулярного виразу?]

a) re.L\
b) re.S\
c) re.U\
**d) re.X**\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```s = 'welcome home'
m = re.match(r'(.*)(.*?)', s)
print(m.group())
```

a) (‘welcome’, ‘home’)\
b) [‘welcome’, ‘home’]\
**c) welcome home**\
d) [‘welcome’ // ‘home’ ]\

### The function of re.match is __ [Функція re.match це __]

a) Error\
b) Matches a pattern anywhere in the string\
c) Matches a pattern at the end of the string\
**d) Matches a pattern at the start of the string**\

### The special character \B matches the empty string, but only when it is __ [Спеціальний символ \B відповідає порожньому рядку, але лише тоді, коли це __]

a) at the beginning or end of a word\
**b) not at the beginning or end of a word**\
c) at the beginning of the word\
d) at the end of the word\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```import re
s = "A new day"
m = re.match(r'(.*)(.*?)', s)
print(m.group(2))
print(m.group(0))
```

**a)No output**
**A new day**\
b)No output
No output\
c)[‘A’, ‘new’, ‘day’]
(‘A’, ‘new’, ‘day’)\
d)Error
[‘A’, ‘new’, ‘day’]\

### Which of the following special characters matches a pattern only at the end of the string? [Який із наступних спеціальних символів відповідає шаблону лише в кінці рядка?]

a) \B\
b) \X\
**c) \Z**\
d) \A\

### The output of the following two Python codes are the same [Вихідні дані двох наступних кодів Python однакові]
```p = re.compile('hello')
r = p.match('hello everyone')
print(r.group(0))
 
r = re.match('hello', 'hello everyone')
print(r.group(0))
```

**a) True**\
b) False\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.match('sp(.*)am', 'spam')```

a) <_sre.SRE_Match object; span=(1, 4), match=’spam’>\
**b) <_sre.SRE_Match object; span=(0, 4), match=’spam’>**\
c) No output\
d) Error\

### Which of the following special characters represents a comment (that is, the contents of the parenthesis are simply ignores)? [Який із наступних спеціальних символів позначає коментар (тобто вміст дужок просто ігнорується)?]

a) (?:…)\
b) (?=…)\
c) (?!…)\
**d) (?#…)**\

### Which of the codes shown below results in a match? [Який із кодів, показаних нижче, збігається?]

a) re.match(‘George(?=Washington)’, ‘George Washington’)\
b) re.match(‘George(?=Washington)’, ‘George’)\
**c) re.match(‘George(?=Washington)’, ‘GeorgeWashington’)**\
d) re.match(‘George(?=Washington)’, ‘Georgewashington’)\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.split(r'(a)(t)', 'Maths is a difficult subject')```

a) [‘M a t h s i s a d i f f i c u l t s u b j e c t’]\
b) [‘Maths’, ‘is’, ‘a’, ‘difficult’, ‘subject’]\
c) ‘Maths is a difficult subject’\
**d) [‘M’, ‘a’, ‘t’, ‘hs is a difficult subject’]**\

### The output of the following two Python codes are the same. [Вихідні дані двох наступних кодів Python однакові]
```CODE 1
>>> re.split(r'(a)(t)', 'The night sky')
CODE 2
>>> re.split(r'\s+', 'The night sky')
```

a) True\
**b) False**\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```import re
s = 'abc123 xyz666 lmn-11 def77'
re.sub(r'\b([a-z]+)(\d+)', r'\2\1:', s)
```

**a) ‘123abc: 666xyz: lmn-11 77def:’**\
b) ‘77def: lmn-11: 666xyz: 123abc’\
c) ‘abc123:’, ‘xyz666:’, ‘lmn-11:’, ‘def77:’\
d) ‘abc123: xyz666: lmn-11: def77’\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.subn('A', 'X', 'AAAAAA', count=4)```

a) ‘XXXXAA, 4’\
b) (‘AAAAAA’, 4)\
**c) (‘XXXXAA’, 4)**\
d) ‘AAAAAA, 4’]\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```n = re.sub(r'\w+', 'Hello', 'Cats and dogs')```

a) Hello Hello Hello\
**b) ‘Hello Hello Hello**\
c) [‘Hello’, ‘Hello’, ‘Hello’]\
d) (‘Hello’, ‘Hello’, ‘Hello’)\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```w = re.compile('[A-Za-z]+')
w.findall('It will rain today')
```

a) ‘It will rain today’\
b) (‘It will rain today’)\
c) [‘It will rain today’]\
**d) [‘It’, ‘will’, ‘rain’, ‘today’]**\

### In the functions re.search.start(group) and re.search.end(group), if the argument groups not specified, it defaults to __ [У функціях re.search.start(group) і re.search.end(group), якщо групи аргументів не вказані, за замовчуванням це __]

**a) Zero**\
b) None\
c) One\
d) Error\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.split(r'\s+', 'Chrome is better than explorer', maxspilt=3)```

a) [‘Chrome’, ‘is’, ‘better’, ‘than’, ‘explorer’]\
**b) [‘Chrome’, ‘is’, ‘better’, ‘than explorer’]**\
c) (‘Chrome’, ‘is’, ‘better’, ‘than explorer’)\
d) ‘Chrome is better’ ‘than explorer’\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```a=re.compile('[0-9]+')
a.findall('7 apples and 3 mangoes')
```

a) [‘apples’ ‘and’ ‘mangoes’]\
b) (7, 4)\
**c) [‘7’, ‘4’]**\
d) Error\

### Which of the following functions returns a dictionary mapping group names to group numbers? [Яка з наведених нижче функцій повертає словник зіставлення назв груп із номерами груп?]

a) re.compile.group\
**b) re.compile.groupindex**\
c) re.compile.index\
d) re.compile.indexgroup\

### Which of the following statements regarding the output of the function re.match is incorrect? [Яке з наведених нижче тверджень щодо виведення функції re.match є неправильним?]

a) ‘pq*’ will match ‘pq’\
b) ‘pq?’ matches ‘p’\
c) ‘p{4}, q’ does not match ‘pppq’\
**d) ‘pq+’ matches ‘p’**\

### The following Python code snippet results in an error [Наступний фрагмент коду Python призводить до помилки]
```c=re.compile(r'(\d+)(\[A-Z]+)([a-z]+)')
c.groupindex
```

a) True\
**b) False**\

### Which of the following functions does not accept any argument? [Яка з наведених функцій не приймає жодного аргументу?]

**a) re.purge**\
b) re.compile\
c) re.findall\
d) re.match\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```a = re.compile('0-9')
a.findall('3 trees')
```

**a) []**\
b) [‘3’]\
c) Error\
d) [‘trees’]\

### Which of the following lines of code will not show a match? [Який із наведених нижче рядків коду не покаже збіг?]

a) >>> re.match(‘ab*’, ‘a’)\
b) >>> re.match(‘ab*’, ‘ab’)\
c) >>> re.match(‘ab*’, ‘abb’)\
**d) >>> re.match(‘ab*’, ‘ba’)**\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```m = re.search('a', 'The blue umbrella')
m.re.pattern
```

a) {}\
b) ‘The blue umbrella’\
**c) ‘a’**\
d) No output\

### What will be the output of the following Python code? [Який буде вивід наступного коду?]
```re.sub('Y', 'X', 'AAAAAA', count=2)```

a) ‘YXAAAA’\
b) (‘YXAAAA’)\
c) (‘AAAAAA’)\
**d) ‘AAAAAA’**\


# Section 25

## Python Files – 1

### 1. To open a file c:\scores.txt for reading, we use **\*\***\_**\*\*** [Щоб відкрити файл c:\scores.txt для читання, ми використовуємо...]

a) infile = open(“c:\scores.txt”, “r”)

**b) infile = open(“c:\\scores.txt”, “r”)**

c) infile = open(file = “c:\scores.txt”, “r”)

d) infile = open(file = “c:\\scores.txt”, “r”)

> "r" for reading, \\ is needed after disk name

### 2. To open a file c:\scores.txt for writing, we use \***\*\_\_\_\_\*\*** [Щоб відкрити файл c:\scores.txt для запису, ми використовуємо...]

a) outfile = open(“c:\scores.txt”, “w”)

**b) outfile = open(“c:\\scores.txt”, “w”)**

c) outfile = open(file = “c:\scores.txt”, “w”)

d) outfile = open(file = “c:\\scores.txt”, “w”)

> "w" is used to indicate that file is to be written to.

### 3. To open a file c:\scores.txt for appending data, we use \***\*\_\_\_\_\*\*** [Щоб відкрити файл c:\scores.txt для запису даних в кінець, ми використовуємо...]

**a) outfile = open(“c:\\scores.txt”, “a”)**

b) outfile = open(“c:\\scores.txt”, “rw”)

c) outfile = open(file = “c:\scores.txt”, “w”)

d) outfile = open(file = “c:\\scores.txt”, “w”)

> a is used to indicate that data is to be appended.

### 4. Which of the following statements are true? [Які твердження є правильними?]

a) When you open a file for reading, if the file does not exist, an error occurs

b) When you open a file for writing, if the file does not exist, a new file is created

c) When you open a file for writing, if the file exists, the existing file is overwritten with the new file

**d) All of the mentioned**

### 5. To read two characters from a file object infile, we use \***\*\_\_\_\_\*\*** [Для читання 2 символів з з файлового об'єкту infile ми використовуємо...]

**a) infile.read(2)**

b) infile.read()

c) infile.readline()

d) infile.readlines()

### 6. To read the entire remaining contents of the file as a string from a file object infile, we use \***\*\_\_\_\_\*\*** [Для читання всього продовження файлу як рядка з файлового об'єкту infile ми використовуємо...]

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

### 8. To read the next line of the file from a file object infile, we use \***\*\_\_\_\_\*\*** [Для читання наступного рядка з файлового об'єкту infile ми використовуємо...]

a) infile.read(2)

b) infile.read()

**c) infile.readline()**

d) infile.readlines()

### 9. To read the remaining lines of the file from a file object infile, we use \***\*\_\_\_\_\*\*** [Для читання рядків, що залишилися, з файлового об'єкту infile ми використовуємо...]

a) infile.read(2)

b) infile.read()

c) infile.readline()

**d) infile.readlines()**

> Content of t.txt:
>
> ```
> eerrrrrrrrrrrrrrrrrrrrrrr
> tttttttt
> ```
>
> Code:
>
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
>
> Output:
>
> ```
> ['rrrrrrrrrrrrrrrrrrrrrrr\n', 'tttttttt']
> rrrrrrrrrrrrrrrrrrrrrrr
> tttttttt
> ```
>
> Apparently in this question they want list of lines and not just string (like in question 6)

### 10. The readlines() method returns \***\*\_\_\_\_\*\*** [Метод readlines() повертає ...]

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
> raw_input and input
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
>
> ```
> Attribute	Description
> file.closed	Returns true if file is closed, false otherwise.
> file.mode	Returns access mode with which file was opened.
> file.name	Returns name of the file.
> file.softspace	Returns false if space explicitly required with print, true otherwise.
> ```

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
>
> ```
> rename(current_file_name, new_file_name)
> ```

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
>
> ```
> ValueError: must have exactly one of create/read/write/append mode
> ```
>
> which is runtime error?

### 9. What is the use of seek() method in files? [Навіщо метод seek() для файлів?]

**a) sets the file’s current position at the offset**

b) sets the file’s previous position at the offset

c) sets the file’s current position within the file

d) none of the mentioned

> Sets the file’s current position at the offset. The method seek() sets the file’s current position at the offset.
> Following is the syntax for seek() method:
>
> ```
> fileObject.seek(offset[, whence])
> ```
>
> Parameters
>
> `offset` — This is the position of the read/write pointer within the file.
>
> whence — This is optional and defaults to 0 which means absolute file positioning, other values are 1 which means seek relative to the current position and 2 means seek relative to the file’s end.

### 10. What is the use of truncate() method in file? [Навіщо метод truncate() для файлів?]

**a) truncates the file size**

b) deletes the content of the file

c) deletes the file size

d) none of the mentioned

> The method truncate() truncates the file size. Following is the syntax for truncate() method:
>
> ```
> fileObject.truncate( [ size ])
> ```
>
> Parameters
>
> `size` — If this optional argument is present, the file is truncated to (at most) that size.

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
> Output:
> Enter your name: sanfoundry
> Your name is: sanfoundry

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
>
> ```Output:
> Hello
> Python`
> ``
> ```

### 4. Which of the following mode will refer to binary data? [Який з наведених режимів відповідая бінарному?]

a) r

b) w

c) +

**d) b**

> Mode Meaning is as explained below:
> r Reading
> w Writing
> a Appending
> b Binary data
>
> - Updating.

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
> `file object = open(file_name [, access_mode][, buffering])`
> Here is parameters’ detail:
> file_name: The file_name argument is a string value that contains the name of the file that you want to access.
> access_mode: The access_mode determines the mode in which the file has to be opened, i.e., read, write, append, etc. A complete list of possible values is given below in the table. This is optional parameter and the default file access mode is read (r).
> buffering: If the buffering value is set to 0, no buffering will take place. If the buffering value is 1, line buffering will be performed while accessing a file. If you specify the buffering value as an integer greater than 1, then buffering action will be performed with the indicated buffer size. If negative, the buffer size is the system default(default behavior).

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
> value.
> Syntax
> Following is the syntax for writelines() method:
> fileObject.writelines( sequence ).

### 10. Correct syntax of file.readlines() is? [Який правильний синтаксис функції file.readlines()?]

**a) fileObject.readlines( sizehint );**

b) fileObject.readlines();

c) fileObject.readlines(sequence)

d) none of the mentioned

> The method readlines() reads until EOF using readline() and returns a list containing the lines. If the optional sizehint argument is present, instead of reading up to EOF, whole lines totalling approximately sizehint bytes (possibly after rounding up to an internal buffer size) are read.
> Syntax
> Following is the syntax for readlines() method:
> fileObject.readlines( sizehint );
> Parameters
> sizehint — This is the number of bytes to be read from the file.

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
> fh = open(“filename_here”, “w”).

### 3. What is the use of “a” in file handling? [У роботі з файлами, що означає “a?]

a) Read

b) Write

**c) Append**

d) None of the mentioned

> This opens the fhe file in appending mode. That means, it will be open for writing and everything will be written to the end of the file.
> fh =open(“filename_here”, “a”).
> advertisement

### 4. Which function is used to read all the characters? [Яка функція читає всі символи?]

**a) Read()**

b) Readcharacters()

c) Readall()

d) Readchar()

> The read function reads all characters fh = open(“filename”, “r”)
> content = fh.read().

### 5. Which function is used to read single line from file? [Яка функція читає один рядок?]

**a) Readline()**

b) Readlines()

c) Readstatement()

d) Readfullline()

> The readline function reads a single line from the file fh = open(“filename”, “r”)
> content = fh.readline().

### 6. Which function is used to write all the characters? [Яка функція пише всі символи?]

**a) write()**

b) writecharacters()

c) writeall()

d) writechar()

> To write a fixed sequence of characters to a file
> fh = open(“hello.txt”,”w”)
> write(“Hello World”).

### 7. Which function is used to write a list of string in a file? [Яка функція пише список рядків]

a) writeline()

**b) writelines()**

c) writestatement()

d) writefullline()

> With the writeline function you can write a list of strings to a file
>
> ```fh = open(“hello.txt”, “w”)
> lines_of_text = [“a line of text”, “another line of text”, “a third line”] fh.writelines(lines_of_text)
> ```

### 8. Which function is used to close a file in python? [Яка функція закриває файл]

**a) Close()**

b) Stop()

c) End()

d) Closefile()

> f.close()to close it and free up any system resources taken up by the open file.

### 9. Is it possible to create a text file in python? [Чи можливо створити у python текстовий файл?]

**a) Yes**

b) No

c) Machine dependent

d) All of the mentioned

> Yes we can create a file in python. Creation of file is as shown below.
>
> ```file = open(“newfile.txt”, “w”)
> file.write(“hello world in the new file\n”)
> file.write(“and another line\n”)
> file.close()
> ```

### 10. Which of the following are the modes of both writing and reading in binary format in file? [Який режим використовується і для запису, і для читання бінарного файлу?]

a) wb+

b) w

**c) wb**

d) w+

> Here is the description below
> “w” Opens a file for writing only. Overwrites the file if the file exists. If the file does not exist, creates a new file for writing.
> “wb” Opens a file for writing only in binary format. Overwrites the file if the file exists. If the file does not exist, creates a new file for writing.
> “w+” Opens a file for both writing and reading. Overwrites the existing file if the file exists. If the file does not exist, creates a new file for reading and writing.
> “wb+” Opens a file for both writing and reading in binary format. Overwrites the existing file if the file exists. If the file does not exist, creates a new file for reading and writing.

<!-- ***************************************************************************************************************************************************************** -->

## Python Encapsulation

### 1. Which of these is not a fundamental features of OOP?

a) Encapsulation

b) Inheritance

**c) Instantiation**

d) Polymorphism

> Instantiation simply refers to creation of an instance of class. It is not a fundamental feature of OOP.

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

d) The program has an error as you can’t name a class member using \_\_b

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

> Variables beginning with two underscores are said to be private members of the class and they can’t be accessed directly.

### 5. Methods of a class that provide access to private members of the class are called as **\_\_** and **\_\_**

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

a) \_\_a

**b) \_\_b**

c) `__c__`

d) `__d__`

> Variables such as self.\_\_b are private members of the class.

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

> Here, get(self) is a member of the class. Hence, it can even return a private member of the class. Because of this reason, the program runs fine and 1 is printed.

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

> It is possible to change the values of public class members using the object of the class.

### 9. Private members of a class cannot be accessed.

a) True

**b) False**

> Private members of a class are accessible if written as follows: obj.\_Classname\_\_privatemember. Such renaming of identifiers is called as name mangling.

### 10. The purpose of name mangling is to avoid unintentional access of private class members.

**a) True**

b) False

> Name mangling prevents unintentional access of private members of a class, while still allowing access when needed. Unless the variable is accessed with its mangled name, it will not be found.

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

> Private class members can be printed by methods which are members of the class.

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

> Name mangling has been properly implemented in the code given above and hence the program runs properly.

### 13. Which of the following is false about protected class members?

a) They begin with one underscore

b) They can be accessed by subclasses

**c) They can be accessed by name mangling method**

d) They can be accessed within a class

> Protected class members can’t be accessed by name mangling.

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

> Protected members begin with one underscore and they can only be accessed within a class or by subclasses.

# Section 26

## Files - 5

## 1. Which of the following is not a valid mode to open a file?

a) ab

_**b) rw**_

c) r+

d) w+

> Need to choose either r or w


## 2. What is the difference between r+ and w+ modes?

_**a) no difference**_

b) in r+ the pointer is initially placed at the beginning of the file and the pointer is at the end for w+

c) in w+ the pointer is initially placed at the beginning of the file and the pointer is at the end for r+

d) depends on the operating system

> Difference exists, for example r+ will get an error on a file that doesn't exist, and w+ creates it. But all those things are out of the scope of this question.


## 3. How do you get the name of a file from a file object (fp)?

_**a) fp.name**_

b) fp.file(name)

c) self.\_\_name\_\_(fp)

d) fp.\_\_name\_\_()

> Name is an attribute


## 4. Which of the following is not a valid attribute of a file object (fp)?

a) fp.name

b) fp.closed

c) fp.mode

_**d) fp.size**_


## 5. How do you close a file object (fp)?

a) close(fp)

b) fclose(fp)

_**c) fp.close()**_

d) fp.__close__()


## 6. How do you get the current position within the file?

a) fp.seek()

_**b) fp.tell()**_

c) fp.loc

d) fp.pos


## 7. How do you rename a file?

a) fp.name = ‘new_name.txt’

_**b) os.rename(existing_name, new_name)**_

c) os.rename(fp, new_name)

d) os.set_name(existing_name, new_name)


## 8. How do you delete a file?

a) del(fp)

b) fp.delete()

_**c) os.remove(‘file’)**_

d) os.delete(‘file’)


## 9. How do you change the file position to an offset value from the start?

_**a) fp.seek(offset, 0)**_

b) fp.seek(offset, 1)

c) fp.seek(offset, 2)

d) none of the mentioned


## 10. What happens if no arguments are passed to the seek function?

a) file position is set to the start of file

b) file position is set to the end of file

c) file position remains unchanged

_**d) error**_

> Need to set offset


## Operators overload

## 1. Which function is called when the following Python code is executed?

```
f = foo()
format(f)
```

a) format()

b) \_\_format\_\_()

c) str()

_**d) \_\_str\_\_()**_


## 2. Which of the following Python code will print True?

```
a = foo(2) 
b = foo(3) 
print(a < b)
```

a)

```
class foo:
    def __init__(self, x):    
        self.x = x        
    def __lt__(self, other):    
        if self.x < other.x:        
            return False           
        else:       
            return True
```

b)

```
class foo:
    def __init__(self, x):   
        self.x = x        
    def __less__(self, other):    
        if self.x > other.x:
            return False            
        else:
            return True
```
            
_**c)**_

```
class foo:
    def __init__(self, x):
        self.x = x
    def __lt__(self, other):
        if self.x < other.x:
            return True
        else:
            return False
 
```
d)

```

class foo:
    def __init__(self, x):
        self.x = x
    def __less__(self, other):
        if self.x < other.x:
            return False
        else:
            return True
```

> \_\_lt\_\_ overloads the < operator>.


## 3. Which function overloads the + operator?

_**a) \_\_add\_\_()**_

b) \_\_plus\_\_()

c) \_\_sum\_\_()

d) none of the mentioned


## 4. Which operator is overloaded by \_\_invert\_\_()?

a) !

**b) ~ **

c) ^

d) –


## 5. Which function overloads the == operator?

_**a) \_\_eq\_\_()**_

b) \_\_equ\_\_()

c) \_\_isequal\_\_()

d) none of the mentioned


## 6. Which operator is overloaded by \_\_lg\_\_()?

a) <

b) >

c) !=

_**d) none of the mentioned**_


> \_\_lg\_\_() is invalid


## 7. Which function overloads the >> operator?

a) \_\_more\_\_()

b) \_\_gt\_\_()

c) \_\_ge\_\_()

_**d) none of the mentioned**_

> \_\_rshift\_\_


## 8. Let A and B be objects of class Foo. Which functions are called when print(A + B) is executed?

_**a) \_\_add\_\_(), \_\_str\_\_()**_

b) \_\_str\_\_(), \_\_add\_\_()

c) \_\_sum\_\_(), \_\_str\_\_()

d) \_\_str\_\_(), \_\_sum\_\_()


## 9. Which operator is overloaded by the \_\_or\_\_() function?

a) ||

**b) |**

c) //

d) /

## 10. Which function overloads the // operator?

a) \_\_div\_\_()

b) \_\_ceildiv\_\_()

_**c) \_\_floordiv\_\_()**_

d) \_\_truediv\_\_()


## Class and objects - 1


## 1. _____ represents an entity in the real world with its identity and behaviour.

a) A method

_**b) An object**_

c) A class

d) An operator


## 2. _____ is used to create an object.

a) class

_**b) constructor**_

c) User-defined functions

d) In-built functions



## **3. What will be the output of the following Python code?**

```
class test:
     def __init__(self,a="Hello World"):
         self.a=a
 
     def display(self):
         print(self.a)
obj=test()
obj.display()
```

a) The program has an error because constructor can’t have default arguments

b) Nothing is displayed

_**c) “Hello World” is displayed**_

d) The program has an error display function doesn’t have parameters


## 4. What is setattr() used for?

a) To access the attribute of the object

_**b) To set an attribute**_

c) To check if an attribute exists or not

d) To delete an attribute


## 5. What is getattr() used for?

_**a) To access the attribute of the object**_

b) To delete an attribute

c) To check if an attribute exists or not

d) To set an attribute


## 6. What will be the output of the following Python code?
```
class change:
    def __init__(self, x, y, z):
        self.a = x + y + z
 
x = change(1,2,3)
y = getattr(x, 'a')
setattr(x, 'a', y+1)
print(x.a)
```

a) 6

**b) 7**

c) Error

d) 0First, a=1+2+3=6. Then, after setattr() is invoked, x.a=6+1=7.

> First, a=1+2+3=6. Then, after setattr() is invoked, x.a=6+1=7.


## 7. What will be the output of the following Python code?
```
 class test:
     def __init__(self,a):
         self.a=a
 
     def display(self):
         print(self.a)
obj=test()
obj.display()
```

a) Runs normally, doesn’t display anything

b) Displays 0, which is the automatic default value

_**c) Error as one argument is required while creating the object**_

d) Error as display function requires additional argument


##  8. Is the following Python code correct?
```
>>> class A:
	def __init__(self,b):
		self.b=b
	def display(self):
		print(self.b)
>>> obj=A("Hello")
>>> del obj
```

_**a) True**_

b) False


## 9. What will be the output of the following Python code?
```
class test:
    def __init__(self):
        self.variable = 'Old'
        self.Change(self.variable)
    def Change(self, var):
        var = 'New'
obj=test()
print(obj.variable)
```

a) Error because function change can’t be called in the __init__ function

b) ‘New’ is printed

_**c) ‘Old’ is printed**_

d) Nothing is printed


## 10. What is Instantiation in terms of OOP terminology?

a) Deleting an instance of class

b) Modifying an instance of class

c) Copying an instance of class

_**d) Creating an instance of class**_


## 11. What will be the output of the following Python code?

a) 12

b) 52

_**c) 13**_

d) 60


## 12. What will be the output of the following Python code?
```
 class Demo:
    def __init__(self):
        pass
 
    def test(self):
        print(__name__)
 
obj = Demo()
obj.test()
```

a) Exception is thrown

_**b) __main__**_

c) Demo

d) test


## Class and Objects - 2

## 1. The assignment of more than one function to a particular operator is _______

a) Operator over-assignment

b) Operator overriding

_**c) Operator overloading**_

d) Operator instance


## 2. Which of the following is not a class method?

_**a) Non-static**_

b) Static

c) Bounded

d) Unbounded



## 3. What will be the output of the following Python code?

```
def add(c,k):
    c.test=c.test+1
    k=k+1
class A:
    def __init__(self):
        self.test = 0
def main():
    Count=A()
    k=0
 
    for i in range(0,25):
        add(Count,k)
    print("Count.test=", Count.test)
    print("k =", k)
main()
```

a) Exception is thrown

b)
```
Count.test=25
k=25
```

_**c)**_

```
Count.test=25
k=0
```

d)
```
Count.test=0
k=0
```


## 4. Which of the following Python code creates an empty class?

a)
```
class A:
    return
```

_**b)**_
```
class A:
    pass
```

c)
```
class A:
```

d) It is not possible to create an empty class



## 5. Is the following Python code valid?

```
class B(object):
  def first(self):
    print("First method called")
  def second():
    print("Second method called")
ob = B()
B.first(ob)
```

a) It isn’t as the object declaration isn’t right

b) It isn’t as there isn’t any \_\_init\_\_ method for initializing class members

_**c) Yes, this method of calling is called unbounded method call**_

d) Yes, this method of calling is called bounded method call


## 6. What are the methods which begin and end with two underscore characters called?

_**a) Special methods**_

b) In-built methods

c) User-defined methods

d) Additional methods


## 7. Special methods need to be explicitly called during object creation.

a) True

_**b) False**_


> They are called automaticly


## 8. What will be the output of the following Python code?

```
>>> class demo():
	def __repr__(self):
		return '__repr__ built-in function called'
	def __str__(self):
		return '__str__ built-in function called'
>>> s=demo()
>>> print(s)
```

a) Error

b) Nothing is printed

_**c) \_\_str\_\_ called**_

d) \_\_repr\_\_ called


## 9. What is hasattr(obj,name) used for?

a) To access the attribute of the object

b) To delete an attribute

_**c) To check if an attribute exists or not**_

d) To set an attribute


## 10. What will be the output of the following Python code?

```
class stud:
   def __init__(self, roll_no, grade):
      self.roll_no = roll_no
      self.grade = grade
   def display (self):
      print("Roll no : ", self.roll_no,  ", Grade: ", self.grade)
stud1 = stud(34, 'S')
stud1.age=7
print(hasattr(stud1, 'age'))
```

a) Error as age isn’t defined

_**b) True**_

c) False

d) 7


## 11. What is delattr(obj,name) used for?

a) To print deleted attribute

_**b) To delete an attribute**_

c) To check if an attribute is deleted or not

d) To set an attribute



## 12. \_\_del\_\_ method is used to destroy instances of a class.

_**a) True**_

b) False


## 13. What will be the output of the following Python code?

```
class stud:
   ‘Base class for all students’
   def __init__(self, roll_no, grade):
      self.roll_no = roll_no
      self.grade = grade
   def display (self):
      print("Roll no : ", self.roll_no,  ", Grade: ", self.grade)
print(student.__doc__)
```

a) Exception is thrown

b) \_\_main\_\_

c) Nothing is displayed

_**d) Base class for all students**_


## 14. What does print(Test.\_\_name\_\_) display (assuming Test is the name of the class)?

a) ()

b) Exception is thrown

_**c) Test**_

d) \_\_main\_\_


# Additional topics

## Topic 102. Inheritance – 1

### 1. Which of the following best describes inheritance? [Що з цього найкраще описує поняття успадкування]
* **a) Ability of a class to derive members of another class as a part of its own definition**
* b) Means of bundling instance variables and methods in order to restrict access to certain class members
* c) Focuses on variables and passing of variables to functions
* d) Allows for implementation of elegant software that is well designed and easily modified

> If the class definition is class B(A): then class B inherits the methods of class A. This is called inheritance.


### 2. Which of the following statements is wrong about inheritance? [Яке з нижче наведених тверджень щодо успадкування невірне?]
* a) Protected members of a class can be inherited
* b) The inheriting class is called a subclass
* **c) Private members of a class can be inherited and accessed**
* d) Inheritance is one of the features of OOP

> Any changes made to the private members of the class in the subclass aren’t reflected in the original members.


### 3. What will be the output of the following Python code?

```python
class Demo:
    def __new__(self):
        self.__init__(self)
        print("Demo's __new__() invoked")
    def __init__(self):
        print("Demo's __init__() invoked")
class Derived_Demo(Demo):
    def __new__(self):
        print("Derived_Demo's __new__() invoked")
    def __init__(self):
        print("Derived_Demo's __init__() invoked")
def main():
    obj1 = Derived_Demo()
    obj2 = Demo()
main()
```

* a)

```
Derived_Demo’s __init__() invoked
Derived_Demo's __new__() invoked
Demo's __init__() invoked
Demo's __new__() invoked
```

* **b)**

```
Derived_Demo's __new__() invoked
Demo's __init__() invoked
Demo's __new__() invoked
```

* c)

```
Derived_Demo's __new__() invoked
Demo's __new__() invoked
```

* d)

```
Derived_Demo’s __init__() invoked
Demo's __init__() invoked
```

Answer: b

Since the object for the derived class is declared first, \_\_new__() method of the derived class is invoked first, followed by the constructor and the \_\_new__() method of main class.


### 4. What will be the output of the following Python code?

```python
class Test:
    def __init__(self):
        self.x = 0
class Derived_Test(Test):
    def __init__(self):
        self.y = 1
def main():
    b = Derived_Test()
    print(b.x,b.y)
main()
```

* a) 0 1
* b) 0 0
* **c) Error because class B inherits A but variable x isn’t inherited**
* d) Error because when object is created, argument must be passed like Derived_Test(1)

Since the invoking method, Test.\_\_init\_\_(self), isn’t present in the derived class, variable x can’t be inherited.


### 5. What will be the output of the following Python code?

```python
class A():
    def disp(self):
        print("A disp()")
class B(A):
    pass
obj = B()
obj.disp()
```

* a) Invalid syntax for inheritance
* b) Error because when object is created, argument must be passed
* c) Nothing is printed
* **d) A disp()**

> Class B inherits class A hence the function disp() becomes part of class B’s definition. Hence disp() method is properly executed and the line is printed.


### 6. All subclasses are a subtype in object-oriented programming. [Всі підкласи є підтипами в ООП]
* a) True
* **b) False**

> A subtype is something that be substituted for and behave as its parent type. A subclass may not be a subtype in object-oriented programming.

https://softwareengineering.stackexchange.com/questions/362316/whats-the-difference-between-a-subclass-and-a-subtype


### 7. When defining a subclass in Python that is meant to serve as a subtype, the subtype Python keyword is used. [Щоб визначити підклас Python, який вестиме себе як підтип, використовується ключове слово Python subtype.]
* a) True
* **b) False**

> B is a subtype of B if instances of type B can substitute for instances of type A without affecting semantics.


### 8. Suppose B is a subclass of A, to invoke the `__init__` method in A from B, what is the line of code you should write? [Припустимо, що B є підкласом A, щоб викликати метод `__init__` A в класі B, яку лінію коду ви маєте написати?]
* **a) A.__init__(self)**
* b) B.__init__(self)
* c) A.__init__(B)
* d) B.__init__(A)

> To invoke the `__init__` method in A from B, either of the following should be written: `A.__init__(self)` or `super().__init__(self)`.


### 9. What will be the output of the following Python code?

```python
class Test:
    def __init__(self):
        self.x = 0
class Derived_Test(Test):
    def __init__(self):
        Test.__init__(self)
        self.y = 1
def main():
    b = Derived_Test()
    print(b.x,b.y)
main()
```

* a) Error because class B inherits A but variable x isn’t inherited
* b) 0 0
* **c) 0 1**
* d) Error, the syntax of the invoking method is wrong

> Since the invoking method has been properly invoked, variable x from the main class has been properly inherited and it can also be accessed.


### 10. What will be the output of the following Python code?

```python
class A:
    def __init__(self, x= 1):
        self.x = x
class der(A):
    def __init__(self,y = 2):
        super().__init__()
        self.y = y
def main():
    obj = der()
    print(obj.x, obj.y)
main()
```

* a) Error, the syntax of the invoking method is wrong
* b) The program runs fine but nothing is printed
* c) 1 0
* **d) 1 2**

> In the above piece of code, the invoking method has been properly implemented and hence x=1 and y=2. 


### 11. What does built-in function type do in context of classes? [Що робить вбудована функція type в контексті класів?]
* a) Determines the object name of any value
* **b) Determines the class name of any value**
* c) Determines class description of any value
* d) Determines the file name of any value

> For example: >>> type((1,)) gives <class ‘tuple’>.


### 12. Which of the following is not a type of inheritance? [Що з нижчу наведеного не є типом наслідування?]
* **a) Double-level**
* b) Multi-level
* c) Single-level
* d) Multiple

> Multiple, multi-level, single-level and hierarchical inheritance are all types of inheritance.


### 13. What does built-in function help do in context of classes? [Що робить вбудована функція help в контексті класів?]
* a) Determines the object name of any value
* b) Determines the class identifiers of any value
* **c) Determines class description of any built-in type**
* d) Determines class description of any user-defined built-in type

> help() usually gives information of the class on any built-in type or function.

(як тип може бути 'user-defined built-in'???)


### 14. What will be the output of the following Python code?

```python
class A:
    def one(self):
        return self.two()
 
    def two(self):
        return 'A'
 
class B(A):
    def two(self):
        return 'B'
obj1=A()
obj2=B()
print(obj1.two(),obj2.two())
```

* a) A A
* **b) A B**
* c) B B
* d) An exception is thrown

> obj1.two() invokes the method two() in class A which returns ‘A’ and obj2.two() invokes the method two() in class B which returns ‘B’.


### 15. What type of inheritance is illustrated in the following Python code? [Який тип успадкування ілюструє наведений код Python?]

```python
class A():
    pass
class B():
    pass
class C(A,B):
    pass
```

* a) Multi-level inheritance
* **b) Multiple inheritance**
* c) Hierarchical inheritance
* d) Single-level inheritance

> In multiple inheritance, two or more subclasses are derived from the superclass as shown in the above piece of code.


## Topic 103. Inheritance – 2

### 1. What type of inheritance is illustrated in the following Python code? [Який тип успадкування ілюструє наведений код Python?]

```python
class A():
    pass
class B(A):
    pass
class C(B):
    pass
```

* **a) Multi-level inheritance**
* b) Multiple inheritance
* c) Hierarchical inheritance
* d) Single-level inheritance

> In multi-level inheritance, a subclass derives from another class which itself is derived from another class.


### 2. What does single-level inheritance mean? [Що значить просте успадкування?]

* a) A subclass derives from a class which in turn derives from another class
* b) A single superclass inherits from multiple subclasses
* **c) A single subclass derives from a single superclass**
* d) Multiple base classes inherit a single derived class

> In single-level inheritance, there is a single subclass which inherits from a single superclass. So the class definition of the subclass will be: class B(A): where A is the superclass.


### 3. What will be the output of the following Python code?

```python
class A:
     def __init__(self):
         self.__i = 1
         self.j = 5
 
     def display(self):
         print(self.__i, self.j)
class B(A):
     def __init__(self):
         super().__init__()
         self.__i = 2
         self.j = 7  
c = B()
c.display()
```

* a) 2 7
* b) 1 5
* **c) 1 7**
* d) 2 5

> Any change made in variable i isn’t reflected as it is the private member of the superclass.


### 4. Which of the following statements isn’t true? [Яке з нижче наведених тверджень є хибним?]
* a) A non-private method in a superclass can be overridden
* b) A derived class is a subset of superclass
* **c) The value of a private variable in the superclass can be changed in the subclass**
* d) When invoking the constructor from a subclass, the constructor of superclass is automatically invoked

> If the value of a private variable in a superclass is changed in the subclass, the change isn’t reflected.

d) ніби теж неправильно, бо в пітоні для цього треба викликати `super.__init__(self)`, але хз. b) трохи нехрозуміле.


### 5. What will be the output of the following Python code?

```python
class A:
    def __init__(self,x):
        self.x = x
    def count(self,x):
        self.x = self.x+1
class B(A):
    def __init__(self, y=0):
        A.__init__(self, 3)
        self.y = y
    def count(self):
        self.y += 1     
def main():
    obj = B()
    obj.count()
    print(obj.x, obj.y)
main()
```

* a) 3 0
* **b) 3 1**
* c) 0 1
* d) An exception in thrown

> Initially x=3 and y=0. When obj.count() is called, y=1.


### 6. What will be the output of the following Python code?

```
>>> class A:
	pass
>>> class B(A):
	pass
>>> obj=B()
>>> isinstance(obj,A)
```

* **a) True**
* b) False
* c) Wrong syntax for isinstance() method
* d) Invalid method for classes

> isinstance(obj,class) returns True if obj is an object class.


### 7. Which of the following statements is true? [Яке з нижче наведених тверджень є правдивим?]
* a) `The __new__() method automatically invokes the __init__ method`
* b) `The __init__ method is defined in the object class`
* **c) The \_\_eq(other) method is defined in the object class**
* d) `The __repr__() method is defined in the object class`

The \_\_eq(other) method is called if any comparison takes place and it is defined in the object class.

тільки він називається \_\_eq\_\_ а не \_\_eq ну да ладно


### 8. Method issubclass() checks if a class is a subclass of another class. [Метод issubclass() перевіряє чи клас є клас підкласом іншого класу.]
* **a) True**
* b) False

> Method issubclass() returns True if a class is a subclass of another class and False otherwise.


### 9. What will be the output of the following Python code?

```python
class A:
    def __init__(self):
        self.__x = 1
class B(A):
    def display(self):
        print(self.__x)
def main():
    obj = B()
    obj.display()
main()
```

* a) 1
* b) 0
* c) Error, invalid syntax for object declaration
* **d) Error, private class member can’t be accessed in a subclass**

> Private class members in the superclass can’t be accessed in the subclass.


### 10. What will be the output of the following Python code?

```python
class A:
    def __init__(self):
        self._x = 5       
class B(A):
    def display(self):
        print(self._x)
def main():
    obj = B()
    obj.display()
main()
```

* a) Error, invalid syntax for object declaration
* b) Nothing is printed
* **c) 5**
* d) Error, private class member can’t be accessed in a subclass

> The class member x is protected, not private and hence can be accessed by subclasses.


### 11. What will be the output of the following Python code?

```python
class A:
    def __init__(self,x=3):
        self._x = x        
class B(A):
    def __init__(self):
        super().__init__(5)
    def display(self):
        print(self._x)
def main():
    obj = B()
    obj.display()
 
main()
```

* **a) 5**
* b) Error, class member x has two values
* c) 3
* d) Error, protected class member can’t be accessed in a subclass

> The super() method re-assigns the variable x with value 5. Hence 5 is printed.


### 12. What will be the output of the following Python code?

```python
class A:
    def test1(self):
        print(" test of A called ")
class B(A):
    def test(self):
        print(" test of B called ")
class C(A):
    def test(self):
        print(" test of C called ")
class D(B,C):
    def test2(self):
        print(" test of D called ")        
obj=D()
obj.test()
```

* a)

```
test of B called
test of C called
```

* b)

```
test of C called
test of B called
```

* **c) test of B called**
* d) Error, both the classes from which D derives has same method test()

> Execute in Python shell to verify. If class D(B,C): is switched is class D(C,B): test of C is called.


### 13. What will be the output of the following Python code?

```python
class A:
    def test(self):
        print("test of A called")
class B(A):
    def test(self):
        print("test of B called")
        super().test()  
class C(A):
    def test(self):
        print("test of C called")
        super().test()
class D(B,C):
    def test2(self):
        print("test of D called")      
obj=D()
obj.test()
```

* **a)**

```
test of B called
test of C called
test of A called
```

* b)

```
test of C called
test of B called
```

* c)

```
test of B called
test of C called
```

* d) Error, all the three classes from which D derives has same method test()

Answer: a
> Since the invoking method, super().test() is called in the subclasses, all the three methods of test() in three different classes is called.


## Topic 104. Polymorphism

### 1. Which of the following best describes polymorphism? [Що з цього найкраще описує поліморфізм?]
* a) Ability of a class to derive members of another class as a part of its own definition
* b) Means of bundling instance variables and methods in order to restrict access to certain class members
* c) Focuses on variables and passing of variables to functions
* **d) Allows for objects of different types and behaviour to be treated as the same general type**

> Polymorphism is a feature of object-oriented programming languages. It allows for the implementation of elegant software that is well designed and easily modified.


### 2. What is the biggest reason for the use of polymorphism? [Яка найголовніша причина використання поліморфізму?]
* a) It allows the programmer to think at a more abstract level
* b) There is less program code to write
* **c) The program will have a more elegant design and will be easier to maintain and update**
* d) Program code takes up less space

> Explanation: Polymorphism allows for the implementation of elegant software.

🤡🤡🤡


### 3. What is the use of duck typing? [Навіщо застосовується duck typing (качина типізація)?]
- [ ] a) More restriction on the type values that can be passed to a given method
- [ ] b) No restriction on the type values that can be passed to a given method
- [x] **c) Less restriction on the type values that can be passed to a given method**
- [ ] d) Makes the program code smaller

> In Python, any set of classes with a common set of methods can be treated similarly. This is called duck typing. Hence duck typing imposes less restrictions.

https://uk.wikipedia.org/wiki/%D0%9A%D0%B0%D1%87%D0%B8%D0%BD%D0%B0_%D1%82%D0%B8%D0%BF%D1%96%D0%B7%D0%B0%D1%86%D1%96%D1%8F
🦆🦆🦆🇺🇦🇺🇦🇺🇦


### 4. What will be the output of the following Python code?

```python
class A:
    def __str__(self):
        return '1'
class B(A):
    def __init__(self):
        super().__init__()
class C(B):
    def __init__(self):
        super().__init__()
def main():
    obj1 = B()
    obj2 = A()
    obj3 = C()
    print(obj1, obj2,obj3)
main()
```

- [x] **a) 1 1 1**
- [ ] b) 1 2 3
- [ ] c) ‘1’ ‘1’ ‘1’
- [ ] d) An exception is thrown

    The super().__init__() in the subclasses has been properly invoked and none of other subclasses return any other value. Hence 1 is returned each time the object is created and printed.


### 5. What will be the output of the following Python code?

```python
class Demo:
    def __init__(self):
        self.x = 1
    def change(self):
        self.x = 10
class Demo_derived(Demo):
    def change(self):
        self.x=self.x+1
        return self.x
def main():
    obj = Demo_derived()
    print(obj.change())
 
main()
```

- [ ] a) 11
- [x] **b) 2**
- [ ] c) 1
- [ ] d) An exception is thrown

> The derived class method change() overrides the base class method.


### 6. A class in which one or more methods are only implemented to raise an exception is called an abstract class. [Клас, у якому імплементація одного чи більше методів лише видає exception, називається абстрактним класом.]
- [x] **a) True**
- [ ] b) False

> A class in which one or more methods are unimplemented or implemented for the methods throw an exception is called an abstract class.


### 7. Overriding means changing behaviour of methods of derived class methods in the base class. [Заміщення - зміна поведінки методів дочірніх класів у базовому класі]
- [ ] a) True
- [x] **b) False**

> Overriding means if there are two same methods present in the superclass and the subclass, the contents of the subclass method are executed.


### 8. What will be the output of the following Python code?

```python
class A:
    def __repr__(self):
        return "1"
class B(A):
    def __repr__(self):
        return "2"
class C(B):
    def __repr__(self):
        return "3"
o1 = A()
o2 = B()
o3 = C()
print(obj1, obj2, obj3)
```

- [ ] a) 1 1 1
- [x] **b) 1 2 3**
- [ ] c) ‘1’ ‘1’ ‘1’
- [ ] d) An exception is thrown

> When different objects are invoked, each of the individual classes return their individual values and hence it is printed.

Насправді програма скрашнеться, бо автор дебіл (name 'obj1' is not defined)


### 9. What will be the output of the following Python code?

```python
class A:
    def __init__(self):
        self.multiply(15)
        print(self.i)
 
    def multiply(self, i):
        self.i = 4 * i;
class B(A):
    def __init__(self):
        super().__init__()
 
    def multiply(self, i):
        self.i = 2 * i;
obj = B()
```

- [ ] a) 15
- [ ] b) 60
- [ ] c) An exception is thrown
- [x] **d) 30**

> The derived class B overrides base class A.


### 10. What will be the output of the following Python code?

```python
class Demo:
    def check(self):
        return " Demo's check "  
    def display(self):
        print(self.check())
class Demo_Derived(Demo):
    def check(self):
        return " Derived's check "
Demo().display()
Demo_Derived().display()
```

- [x] **a) Demo’s check Derived’s check**
- [ ] b) Demo’s check Demo’s check
- [ ] c) Derived’s check Demo’s check
- [ ] d) Syntax error

> Demo().display() invokes the display() method in class Demo and Demo_Derived().display() invokes the display() method in class Demo_Derived. 


### 11. What will be the output of the following Python code?

```python
class A:
    def __init__(self):
        self.multiply(15)
    def multiply(self, i):
        self.i = 4 * i;
class B(A):
    def __init__(self):
        super().__init__()
        print(self.i)
 
    def multiply(self, i):
        self.i = 2 * i;
obj = B()
```

- [ ] a) 15
- [x] **b) 30**
- [ ] c) An exception is thrown
- [ ] d) 60

> The derived class B overrides base class A.


### 12. What will be the output of the following Python code?

```python
class Demo:
    def __check(self):
        return " Demo's check "
    def display(self):
        print(self.check())
class Demo_Derived(Demo):
    def __check(self):
        return " Derived's check "
Demo().display()
Demo_Derived().display()
```

- [ ] a) Demo’s check Derived’s check
- [x] **b) Demo’s check Demo’s check**
- [ ] c) Derived’s check Demo’s check
- [ ] d) Syntax error

> The method check is private so it can’t be accessed by the derived class. Execute the code in the Python shell. 

(только надо поменять self.check() на self.\_\_check())


### 13. What will be the output of the following Python code?

```python
class A:
    def __init__(self, x, y):
        self.x = x
        self.y = y
    def __str__(self):
        return 1
    def __eq__(self, other):
        return self.x * self.y == other.x * other.y
obj1 = A(5, 2)
obj2 = A(2, 5)
print(obj1 == obj2)
```

- [ ] a) False
- [ ] b) 1
- [x] **c) True**
- [ ] d) An exception is thrown

> Since 5\*2==2\*5, True is printed. Execute it in the Python shell to verify.


### 14. What will be the output of the following Python code?

```python
class A:
    def one(self):
        return self.two()    	
    def two(self):
        return 'A'   
class B(A):
    def two(self):
        return 'B'
obj2=B()
print(obj2.two())
```

- [ ] a) A
- [ ] b) An exception is thrown
- [ ] c) A B
- [x] **d) B**

> The derived class method two() overrides the method two() in the base class A. 


### 15. Which of the following statements is true? [Яке з цих тверджень є вірним?]
- [x] **a) A non-private method in a superclass can be overridden**
- [ ] b) A subclass method can be overridden by the superclass
- [ ] c) A private method in a superclass can be overridden
- [ ] d) Overriding isn’t possible in Python

> A public method in the base class can be overridden by the same named method in the subclass.

