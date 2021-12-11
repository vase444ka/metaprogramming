# Section 1

# Section 2

# Section 3

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

## 1. To open a file c:\scores.txt for reading, we use _____________ [Щоб відкрити файл c:\scores.txt для читання, ми використовуємо...]

a) infile = open(“c:\scores.txt”, “r”)

**b) infile = open(“c:\\scores.txt”, “r”)**

c) infile = open(file = “c:\scores.txt”, “r”)

d) infile = open(file = “c:\\scores.txt”, “r”)

> "r" for reading, \\ is needed after disk name

## 2. To open a file c:\scores.txt for writing, we use ____________ [Щоб відкрити файл c:\scores.txt для запису, ми використовуємо...]

a) outfile = open(“c:\scores.txt”, “w”)

**b) outfile = open(“c:\\scores.txt”, “w”)**

c) outfile = open(file = “c:\scores.txt”, “w”)

d) outfile = open(file = “c:\\scores.txt”, “w”)

> "w" is used to indicate that file is to be written to.

## 3. To open a file c:\scores.txt for appending data, we use ____________ [Щоб відкрити файл c:\scores.txt для запису даних в кінець, ми використовуємо...]

**a) outfile = open(“c:\\scores.txt”, “a”)**

b) outfile = open(“c:\\scores.txt”, “rw”)

c) outfile = open(file = “c:\scores.txt”, “w”)

d) outfile = open(file = “c:\\scores.txt”, “w”)

>a is used to indicate that data is to be appended.

## 4. Which of the following statements are true? [Які твердження є правильними?]

a) When you open a file for reading, if the file does not exist, an error occurs

b) When you open a file for writing, if the file does not exist, a new file is created

c) When you open a file for writing, if the file exists, the existing file is overwritten with the new file

**d) All of the mentioned**

## 5. To read two characters from a file object infile, we use ____________ [Для читання 2 символів з з файлового об'єкту infile ми використовуємо...]

**a) infile.read(2)**

b) infile.read()

c) infile.readline()

d) infile.readlines()

## 6. To read the entire remaining contents of the file as a string from a file object infile, we use ____________ [Для читання всього продовження файлу як рядка з файлового об'єкту infile ми використовуємо...]

a) infile.read(2)

**b) infile.read()**

c) infile.readline()

d) infile.readlines()

> read function is used to read all the lines (that left?) in a file.

## 7. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
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

## 8. To read the next line of the file from a file object infile, we use ____________ [Для читання наступного рядка з файлового об'єкту infile ми використовуємо...]

a) infile.read(2)

b) infile.read()

**c) infile.readline()**

d) infile.readlines()


## 9. To read the remaining lines of the file from a file object infile, we use ____________ [Для читання рядків, що залишилися, з файлового об'єкту infile ми використовуємо...]

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

## 10. The readlines() method returns ____________ [Метод readlines() повертає ...]

a) str

**b) a list of lines**

c) a list of single characters

d) a list of integers

> see the explanation of previous question


<!-- *************************************************************************************************************************************************************************** -->
## 1. Which are the two built-in functions to read a line of text from standard input, which by default comes from the keyboard? [Що є двома вбудованими функціями для читання рядка зі стандартного вводу, який за замовчу]

**a) Raw_input & Input**

b) Input & Scan

c) Scan & Scanner

d) Scanner

> Python 2 provides two built-in functions to read a line of text from standard input, which by default comes from the keyboard. These functions are:
raw_input and input
>
> In Python 3 raw_input() is just input()

## 2. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
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

## 3. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
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

## 4. Which one of the following is not attributes of file? [Що не є атрибутом файлу?]

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

## 5. What is the use of tell() method in python? [Навіщо метод tell() у python?]

**a) tells you the current position within the file**

b) tells you the end position within the file

c) tells you the file is opened or not

d) none of the mentioned

> The tell() method tells you the current position within the file; in other words, the next read or write will occur at that many bytes from the beginning of the file.

## 6. What is the current syntax of rename() a file? [Який наразі синтаксис у rename() файл?]

**a) rename(current_file_name, new_file_name)**

b) rename(new_file_name, current_file_name,)

c) rename(()(current_file_name, new_file_name))

d) none of the mentioned

> This is the correct syntax which has shown below.
>```
>rename(current_file_name, new_file_name)
>```

## 7. What is the current syntax of remove() a file? [Який наразі синтаксис у remove() файл?]

**a) remove(file_name)**

b) remove(new_file_name, current_file_name,)

c) remove(() , file_name))

d) none of the mentioned

> remove(file_name)

## 8. What will be the output of the following Python code? [Яким буде вихід цього Python коду?]
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

b) Syntax Error

**from site c) Displays Output**

**on Python 3.8 I've got runtime error d) None of the mentioned**


> In python 2 it will work??? but I've run it in Python 3.8 and got error
>```
>ValueError: must have exactly one of create/read/write/append mode
>```
> which is runtime error?

## 9. What is the use of seek() method in files? [Навіщо метод seek() для файлів?]

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

## 10. What is the use of truncate() method in file? [Навіщо метод truncate() для файлів?]

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

# Section 26