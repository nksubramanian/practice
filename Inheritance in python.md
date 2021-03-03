# Inheritance in Python

The feature of Inheritance is provided in many langauge including python. 

The purpose of inheritance is reusability of code. 

Say that you want a different class with only slight modification to the original class, you go for inheritance.

The original class is called base class or parent class while class inheriting is called child class or derived class.


```python
class Adult:
  def __init__(self, name, height,weight):
    self.name = name
    self.weight = weight
    self.height = height

  def description(self):
    print("I am an Adult")
```
Above base class is created

The Child class and object is created as shown below

```python
class Cricketer(Adult):
  pass
```

Since only pass is used in child class, child class inherits all data members and methods of the parent class as shown below

object1= Cricketer(Tom,168,65)
print(object1.name)
object1.description()

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Inheritance_in_python.ipynb)


  
