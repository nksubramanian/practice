# Recursive Function

Recursive functions are functions that call itself

Typical example of recursive function is the factorial

n!=n*(n-1)!

n factorial is here written as the product of n and (n-1) factorial. This goes on and on


### Sample

```python
def factorial(n):
  if n>0:
    return factorial(n-1)*n
  else:
    return 1
```
```python
factorial(4)
```

In recursive function, it is necessary to write the base case. The base case is when the function returns something concrete.
0 is the base case here

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Recursive_Function.ipynb)






