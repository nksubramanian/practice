# Shallow Copy

Consider the list as shown below

```python
list1=[1,2,3]
```
The following assignment would not create a new object(list) called list2, but would only create a new reference/alias called list2 for list1

```python
list2=list1
```

Both list1 and list2 refer to the same object as shown below. Thus changes made in one would reflect in the other

```python
id(list2)
id(list1)
```
Both, list1 and list2 refer to the same object and have the same id(memory location)

```python
list1[o]='a'
print(list2)
```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/assignment_for_objects.ipynb)

Is it possible to copy one object to another such that when changes made in one does not reflect in the other? YES! 

We have two ways viz shallow copy and deep copy

There is a difference between the two and both are explained below

First, shallow copy is explained

```python
import copy 
list1=[0,1,2]
list2=copy.copy(list1)
```
```python
id(list1)==id(list2)
```
The location of two objects are different as checked above.

Let's modify list1 to see if those changes are reflected in list2

```python
list1.append(10)
print(list1)
print(list2)
```
[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/soft_copy.ipynb)


Now, let's modify elements shared between list1 and list2 and see if it is reflected in list2

```python
import copy 
list1=[0,1,2]
list2=copy.copy(list1)
```
```python
list1[0]='a'
```
```python
print(list2)
print(list1)
```

If you try, you would see that changes made in list1 in the shared elements is reflected in list2

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/soft_copy1.ipynb)


Now, let's make changes in list2 and see if it is reflected in list1


```python
import copy 
list1=[0,1,2]
list2=copy.copy(list1)
```
```python
list1[0]='a'
```
```python
print(list2)
print(list1)
```

We see that changes made in the copied/clone variable does not reflect in the original variable

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/soft_copy2.ipynb)




