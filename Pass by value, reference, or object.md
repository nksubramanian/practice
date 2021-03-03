# Pass by value, reference, object

In python, when a function call is made, parameters are passed. 

The question is if any modification in the parameters is done inside the functions, will it reflect in the variable outside the function?

If changes are reflected outside, then it is pass by reference. If not, it is pass by value. 

Python implements neither, python has pass by object. Essentially, it is pass by value for some data types while pass by reference for other data types

It's pass by value for immutable objects such as int, float, complex, string, tuple,
```python
def func(b):
  return 2*b
```
```python
a=5
temp=func(a)
print(a)
```
Since int is an immutable object,note the value of 'a' has not changed

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Pass_by_Object_1.ipynb)


For mutable objects such as list, dict, set, byte array, it is pass by reference

So, changes made in such object inside the function would reflect outside as well

```python
def func(list1):
  return list1.append(5)
```
```python
a=[5,6]
temp=func(a)
print(a)
```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/pass_by_object2.ipynb)
