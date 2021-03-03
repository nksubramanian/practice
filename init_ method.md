# \_init_ method

The \_init_ method can be used to initialize the data members of a class as shown below

\_init_method is a constructor that always gets executed when objects are created.


```python
class Student:
  def __init__(self, name, major):
    self.name = name
    self.major = major
```
```python
John = Student("John","Math")
```

Note that Self refers to the particular instance of the object. One can have any other name as one pleases. 
For now, it can viewed as procedure to initialize the data members of an object  


[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/_init_.ipynb)
