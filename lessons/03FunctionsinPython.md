# Functions in Python

## Overview

Understand the concept of functions and how to write them in Python

## Learning Objectives

- Create and call Python functions

## Topics Covered

- Function Definition
- Function Call
- Parameters

## Status

pending

## Subsections

### Introduction to Functions

Functions in Python are blocks of code that only run when it is called. They help in dividing the program into smaller and modular chunks. Instead of writing the same code again and again, you can call the function when needed, which reduces redundancy and simplifies code maintenance.

**Video URL:** http://video.com/introductionToFunctions

**Code Examples:**

```
def hello_world():
    print('Hello, World!')

hello_world()
```

**External Links:**

- [https://realpython.com/defining-your-own-python-function/](https://realpython.com/defining-your-own-python-function/)

**Quizzes:**

**What is a function in Python used for?**

- To divide the program into smaller parts
- To store large amounts of data
- To speed up the program

**Answer:** To divide the program into smaller parts

### Defining and Calling Functions

To define a function, you use the 'def' keyword, followed by the function name, parentheses, and a colon. Within the parentheses, you can include parameters (optional) that are inputs to the function. A defined function does not execute until it is called by its name followed by parentheses.

**Video URL:** http://video.com/definingAndCallingFunctions

**Code Examples:**

```
def greet(name):
    return 'Hello ' + name

print(greet('Alice'))
```

**External Links:**

- [https://www.tutorialspoint.com/python/python_functions.htm](https://www.tutorialspoint.com/python/python_functions.htm)

**Quizzes:**

**How do you define a function in Python?**

- Using 'function' keyword
- Using 'def' keyword
- Using 'method' keyword

**Answer:** Using 'def' keyword

### Function Parameters and Arguments

Parameters are variables listed inside the parentheses in the function definition. You can use more than one parameter by separating them with commas. Arguments are the data you pass into the function's parameters when you call it, allowing you to pass different data at runtime.

**Video URL:** http://video.com/parametersAndArguments

**Code Examples:**

```
def greet(firstName, lastName):
    return 'Hello ' + firstName + ' ' + lastName

print(greet('Alice', 'Smith'))
```

**External Links:**

- [https://www.w3schools.com/python/python_functions.asp](https://www.w3schools.com/python/python_functions.asp)

**Quizzes:**

**What are parameters in a Python function?**

- Inputs to the function
- Outputs from the function
- Variables that store results

**Answer:** Inputs to the function

### Return Statement

The return statement is used to exit a function and return a value. It is particularly useful for getting output from your functions that you can use elsewhere in your code. If no return statement is provided, the function returns 'None'.

**Video URL:** http://video.com/returnStatement

**Code Examples:**

```
def add(a, b):
    return a + b

result = add(3, 5)
print(result)
```

**External Links:**

- [https://www.geeksforgeeks.org/python-return-statement/](https://www.geeksforgeeks.org/python-return-statement/)

**Quizzes:**

**What is the role of the return statement?**

- To finish a function call and exit the function
- To define the function
- To call the function

**Answer:** To finish a function call and exit the function

## Supplemental Videos

- [http://video.com/advancedFunctionTopics](http://video.com/advancedFunctionTopics)

## References

- [https://docs.python.org/3/tutorial/controlflow.html](https://docs.python.org/3/tutorial/controlflow.html)
- [https://www.learnpython.org/en/Functions](https://www.learnpython.org/en/Functions)

## Podcast URL

No podcast available