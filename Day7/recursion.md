## Recursion:
Recursion is a programming technique where a function calls itself either directly or indirectly to solve a problem by breaking it into smaller, simpler subproblems.
In Python, recursion is especially useful for problems that can be divided into identical smaller tasks, such as mathematical calculations, tree traversals or divide-and-conquer algorithms.
A recursive function is just like any other Python function except that it calls itself in its body.
```py
def recursive_function(parameters):
    if base_case_condition:
        return base_result
    else:
        return recursive_function(modified_parameters)
```
Recursive function contains two key parts:
- Base Case: The stopping condition that prevents infinite recursion.
- Recursive Case: The part of the function where it calls itself with modified parameters.

For eg:
1. Factorial :
```py
def factorial(n):
    if n == 0:  # Base case
        return 1
    else:       # Recursive case
        return n * factorial(n - 1)

print(factorial(4))
```
2. Fibonacci Sequence :
```py
def fibonacci(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibonacci(n-1) + fibonacci(n-2)

print(fibonacci(5))
```
