# Deep Copy

By Deep copying one object to another, changes made in one object does not at all reflect in the other. 

In soft copy, changes made in the orginal variable in the shared elements are reflected in the copied variable as well. 

In deep copy, it is not the case as demonstrated below

```python
import copy
list1=[0,1,2,3]
```
```python
list2=copy.deepcopy(list1)
```
```python
list1[0]=99
```
```python
print(list1)
print(list2)
```


[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Deep_Copy.ipynb)
