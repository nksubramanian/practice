# break

The break statement is used in loops. When the break statement is encountered, the control is broken away from the loop. 

### Here is a simple program, 

The condition mentioned in the while loop is always True. But, the loop would be broken away when n=4

```python

n=0
while True:
  print(n)
  n+=1
  if n==4:
    print("The break statement is encountered")
    break

```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/break_in_while_loop.ipynb)

break statement can also be used with for loop

```python

for iter in range(0,10):
  print(iter)
  if iter==3:
    print("I am going to break away from the loop")
    break

```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/break_in_for_loop.ipynb)

