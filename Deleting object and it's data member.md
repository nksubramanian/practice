# Deleting object and it's data member

It's possible to delete data member in an object and also delete the entire object

```python
class Student:
  def __init__(self, name, major):
    self.name = name
    self.major = major
```
```python
John = Student("John","Math")
del John.name
del John
```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Deleting_object_and_it's_data_member.ipynb)

