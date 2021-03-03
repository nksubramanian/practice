# Modifying Derived class using Super()

Suppose you would want to make use of init method of the parent class in the child and also assign new data attributes to child class, you can use the following method

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
   Super.__init__(self, name, height,weight)
   self.age=age
```
```python
object1 = Cricketer("Tom",168, 65,22)
object1.age
```
