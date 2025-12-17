## Python Indentation
Indentation means nothing but a space at beginning of code in line. The indentation in Python is very important. It is used to indicate block of code in Python.
For eg: 

```py
if 10 > 5 :
  print("Ten is greater than five!")
```
Here in above example after initialising if loop, on next line there is a space before code of line, that's indentation it's necessary. Now if there was no indentation it would show a syntax error like:
```py
if 10 > 5:
print("Ten is greater than five!")
```
It will show you error!!!!

## Variables
In Python, variables are created when you assigned a value to it. There is no command in Python. Variables means containers storing a value.
```py
a = 4
b = "Hello"
print(a)
print(b)
```
Output:
```
4
Hello
```

They do not have to declared with particular type. The type even can change after they have been set. If you want to specify the data type, this can be done by casting.
```py
a = str(5)  # It will be '5'
b = int(5)   # It will be 5
c = float(5)  #It will be 5.0
```
Variable names are case sensitive like
```py
a = 2
A = "Vaibhavee"
# A will not overwrite on a
```
