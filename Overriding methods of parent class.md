# Overriding methods of parent class

It's possible for the derived class to inherit all the methods of the base and also replace the methods of parent class.

Below is program that shows the derived class overriding the description() method of base class and also base class using other method voter()
```python
class Adult:
  def __init__(self, name, height,weight):
    self.name = name
    self.weight = weight
    self.height = height

  def voter(self):
    print("I am allowed to vote")

  def description(self):
    print("I am an Adult")
```
```python
class Cricketer(Adult):
    def description(self):
      print("I am a Cricketer")
```
```python
object1 = Cricketer("Tom",168, 65)
object1.voter()
object1.description()
```

 Note that for description method "I am a Cricketer" gets printed.
 
 [Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Overriding_methods_of_parent_class.ipynb)
