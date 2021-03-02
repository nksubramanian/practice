# Scope of variables 

Scope of variables refers to accessibility or availability of variable in a program.

For example, is a variable defined within a function accessible in the main program? 

similarly, is variable defined in the main fucntion accessible in the function defined?

Scope of variable deals with these aspects of program. 

There are two variables in the program viz local variable and global variable

### Global Variable

Global variables are accessible anywhere in the program

Below is a demonstration

```python
x=15
def experiment():
  print(x)
```
```python
experiment()
```
In the above example, x is defined outside the program and yet, is accessible within the function experiment

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Global_Variable.ipynb)


It'S possible to have another local variable within a function that has the same name as the global variable outside .

When the control is within the function, the variable when used would refer/point to the local varaible

In essence, local variable with same name as global variable would take precedence when control is inside function. 

### Program

```python
x="I am global"
def experiment():  
  x="I am local"
  print(x)
```
```python
experiment()
```
```python
print(x)
```

Here when inside in the function experiment(), x would point variable "I am local" and when outside the function, x would point to "I am local"

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Local_variable_with_same_name_as_global_variable.ipynb)

