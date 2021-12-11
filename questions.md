# Section 1

# Section 2

# Section 3

# Section 4

# Section 5

# Section 6

# Section 7

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

## Files - 5

## 1. Which of the following is not a valid mode to open a file?
a) ab
**b) rw**
c) r+
d) w+

> Need to choose either r or w

## 2. What is the difference between r+ and w+ modes?
**a) no difference**
b) in r+ the pointer is initially placed at the beginning of the file and the pointer is at the end for w+
c) in w+ the pointer is initially placed at the beginning of the file and the pointer is at the end for r+
d) depends on the operating system

> Difference exists, for example r+ will get an error on a file that doesn't exist, and w+ creates it. But all those things are out of the scope of this question.

## 3. How do you get the name of a file from a file object (fp)?
**a) fp.name**
b) fp.file(name)
c) self.__name__(fp)
d) fp.__name__()

> Name is an attribute

## 4. Which of the following is not a valid attribute of a file object (fp)?
a) fp.name
b) fp.closed
c) fp.mode
**d) fp.size**

## 5. How do you close a file object (fp)?
a) close(fp)
b) fclose(fp)
**c) fp.close()**
d) fp.__close__()

## 6. How do you get the current position within the file?
a) fp.seek()
**b) fp.tell()**
c) fp.loc
d) fp.pos

## 7. How do you rename a file?
a) fp.name = ‘new_name.txt’
**b) os.rename(existing_name, new_name)**
c) os.rename(fp, new_name)
d) os.set_name(existing_name, new_name)

## 8. How do you delete a file?
a) del(fp)
b) fp.delete()
**c) os.remove(‘file’)**
d) os.delete(‘file’)

## 9. How do you change the file position to an offset value from the start?
**a) fp.seek(offset, 0)**
b) fp.seek(offset, 1)
c) fp.seek(offset, 2)
d) none of the mentioned

## 10. What happens if no arguments are passed to the seek function?
a) file position is set to the start of file
b) file position is set to the end of file
c) file position remains unchanged
**d) error**

> Need to set offset
