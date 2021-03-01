# Continue statement

The continue statement is used either with for loop or while loop. 

When the continue statement is encountered, the remaining portion of the loop gets skipped for that iteration. 

The control gets to the start of the loop. 

### Here is a program for illustration

When iter is 3, reamining portion(print statement) is skipped

```python

for iter in range(0,7):
  if iter ==3:
    continue
  print(iter)

```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/continue.ipynb)
