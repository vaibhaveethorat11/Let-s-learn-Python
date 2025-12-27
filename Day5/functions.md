## Python Functions:
Function is a block of reusable code that performs a specific task. Functions help make your code modular, readable, and easier to debug. There are two main types of functions in Python:
1. Built-in functions like: print(), len(), type()
2. User-defined functions created using the def keyword

Example: This example shows a simple user-defined function that checks whether a number is even or odd using a conditional statement.
```py
def evenOdd(x):
    if x % 2 == 0:
        print("even")
    else:
        print("odd")
​
evenOdd(4)
evenOdd(3)
```
The above func checks the number is odd or even if number is divisible by 2. If it is prints "even" and if it is noth then prints "odd".
