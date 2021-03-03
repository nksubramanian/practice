# Including Methods in Class

It's possible to include methods in the class too that binds it with the data in the object created.

Below is the demonstration

```python
class Student:
  def __init__(self, name, major):
    self.name = name
    self.major = major
  
  def description(self):
    print("My name is "+ str(self.name) +" and my major is "+str(self.major))

  def greetings(self):
    print("Good Morning!")
 
John = Student("John","Math")
Lisa = Student("Lisa","Physics")
```
```python
John.description()
```
```python
Lisa.greetings()
```

As seen in the above, self is used to refer to that particular instance of the class. Class contains methods greetings() and description()

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Including%20methods%20in%20class.ipynb#scrollTo=kfhbGot8VO9Z)

