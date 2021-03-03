# Modifying Object properties

It's possible to change/modify the values of data members in the object 

Below shows the way to modify


```python
class Student:
  def __init__(self, name, major):
    self.name = name
    self.major = major
 
John = Student("John","Math")
 ```
 ```python
 print(John.major)
 John.major="Physics"
 ```
 ```python
 print(John.major)
 ```
 

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Modifying_Object_properties.ipynb)
