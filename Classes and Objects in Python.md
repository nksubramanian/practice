# Classes and Objects in Python

The first step towards getting a grasp in OOP is to understand Class and objects.

Classes, as some view, are blue print. Classes have functions and its related data grouped together.

Classes are similar to mathematical "sets" like "set of cats".

Each member/cat in the set of cats may differ from each other, but nevertheless there is some common features/attributes that each cat can be grouped together as set.

Objects are particular instance of a class, with all details. 

So, classes are an abstractions of objects and objects are in instance of a class.

First, Classes are created and then objects are created for the class

Below is a program to create a class

The keyword class is used

```python
class MyFirstClass:
x=5
```
Now creating object for a class

```python
object1=MyFirstClass()
object2=MyFirstClass()
```
```python
print(object1.x)
print(object2.x)
```
As seen above, two objects(object1 and object2) are created and variable x in each of the object is accessed using the '.' operator 

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Creating_Classes_and_Objects.ipynb)


In the above example, it is seen that the data variable x is shared by both of the created objects.  

Now, it is possible for objects to share the same data members and yet differ in the value held by the data member

The following program demonstrates it

```python
class Student:
  def __init__(self, name, major):
    self.name = name
    self.major = major
```
```python
Sam=Student("Sam", "Physics")
Lisa=Student("Lisa", "Math")
```
```python
Sam.major
Lisa.major
```

__init__() method would always get executed whenever an object is created. The purpose of \_init\_() method is to initialize data members.

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Creating_Classes_and_Objects_2.ipynb)








