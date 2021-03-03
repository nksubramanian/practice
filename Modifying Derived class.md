# Modifying Derived class

Suppose you would want your child class to have all the attributes of parent class and also new attributes, you could use the below code

Here Child class Cricketer has another attribute "age"

```python
class Adult:
  def __init__(self, name, height,weight):
    self.name = name
    self.weight = weight
    self.height = height

  def description(self):
    print("I am an Adult")
 ```
 ```python
 class Cricketer(Adult):
  def __init__(self, name, height,weight,age):
    Adult.__init__(self, name, height,weight)
    self.age=age
 ```
 ```python
object1 = Cricketer("Tom",168, 65,22)
object1.age
```

Here the __init__ method of child class overrides the __init__ method of the parent class. 

To make use of __init__ method of parent class, the __init__ method of parent class is called and even the extra attribute of age is assigned in the child class 
 
 
 [Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Including_more_data_attributes_to_Child_class.ipynb)
