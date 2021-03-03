# Lambda in python

In python, it is possible to construct anonymous functions. Anonymous functions are functions without a name

Lambda functions are used when its usage is confined to some part of the program

```python
lambda argument(s):expression
```
```python
lambda a,b: a+b
_(2,3)
```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/lambda%20function1.ipynb)

You could also use lambda in the following manner

```python
summation=lambda a,b: a+b
summation(2,3)
```
[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Lambda_functions_2.ipynb)


Lambdas are particularly useful when one wants to implement various functions that differ from each other only slightly
For example, all quadratic functions have the form a(x^2)+b(x)+c, or power functions a^n

```python
def tempfunction(n):
  return lambda a : a ** n
```
```python
square_function = tempfunction(2)
square_function(3)
```
```python
powerto5 = tempfunction(5)
powerto5(3)
```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Lambda_function_abstraction.ipynb)

