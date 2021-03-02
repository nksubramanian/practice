# User Defined Function

It's possible in python as with many other langauges to have a user defined function. 

Functions, in programming context, is a piece of code that does certain operations. 

The purpose of functions is reusability. Functions could be written in one part of the program and called/used in other part(s) of the program

### Syntax

```python
def function_name(argument1, argument2, ...) :
      statement_1
      statement_2
      ....
      
```

Functions are defined/declared using the keyword "def" followed by the name of the function. 

Enclosed withing brackets are arguments/parameters that functions acts on. Of course, it is not necessary for functions to have parameters.

Below are the various statements that make the functions


### Program

Here is function that returns twice the number

```python
def myfirstfunction(number):
  twicethenumber =2*number
  return twicethenumber
```


After calling the function, one need to call functions. Calling user defined is no different from calling already defined function.

### Program for demonstrating calling a function

```python
two_a=myfirstfunction(5)
```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Functions_Declaration_and_Calling.ipynb)

