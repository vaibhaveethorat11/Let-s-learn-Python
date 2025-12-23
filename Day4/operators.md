## Python Operators:
Operators in Python are symbols used to perform operations on values and variables, such as calculations, comparisons, and logical checks.
1. Arithmetic Operators: These are used to perform basic mathematical operations like addition, subtraction, multiplication, and division. Types of arithmetic operators: +, -, *, /, //, %, **​.
```py
a = 2
b = 4
add = a + b 
sub = a - b 
mul = a * b 
mod = a % b 
exp = a ** b 

print(add) 
print(sub) 
print(mul) 
print(mod) 
print(exp)
```
2. Comparison Operators: These are used to compare two values. They return a Boolean value either True or False depending on whether the comparison is correct.
```py
a = 15
b = 25
​
print(a == b)   # False, because 15 is not equal to 25
print(a != b)   # True, because 15 is not equal to 25
print(a > b)    # False, 15 is not greater than 25
print(a < b)    # True, 15 is less than 25
print(a >= b)   # False, 15 is not greater than or equal to 25
print(a <= b)   # True, 15 is less than or equal to 25
```
3. Logical Operators: It perform Logical AND, Logical OR and Logical NOT operations. It is used to combine conditional statements. Types of logical operators are: AND, OR, NOT​.
```py
a = True
b = False
print(a and b) 
print(a or b) 
print(not a)
```
4. Bitwise Operators: This act on bits and perform bit-by-bit operations. These are used to operate on binary numbers. Types of bitwise operators are: &, |, ^, ~, <<, >>​
```py
a = 10
b = 5
print(a & b) 
print(a | b) 
print(~a) 
print(a ^ b) 
print(a >> 2) 
print(a << 2)
```
5. Assignment Operators: These are used to assign values to the variables. Types of assignment operators: =, +=, -=, *=, /=, %=, **=, //=, &=, |=, ^=, >>=, <<=​.
```py
a = 5
b = a 
print(b) 
b += a 
print(b) 
b -= a 
print(b) 
b *= a 
print(b) 
b <<= a 
print(b)
```
