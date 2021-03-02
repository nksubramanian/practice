# Modifying Global Variable within function

To modify global variables within function,the keyword global is used as shown below

### Program

```python
def experiment():
  global x
  x="I am changed"
```
```python
x="I am global"
print(x)
experiment()
print(x)
```

The above program changes the function experiment() changes the value of global variable x and the change is also seen outside the function

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Modifying_Global_Variable_within_functions.ipynb)



