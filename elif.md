# elif

In elif(else if), there is a hierarachy of "if" statements. Firstly, the condition in the first if block is checked. 

If the condition turns out to be true, the first block gets executed and then remaining elif blocks are skipped, not checked.

If the condition in the first block turns out to false, then next elif block is checked and so on.

# syntax

```python

if condition:
  statements
elif condition:
  statement
elif condition:
  statement

```

An else block can be included and is optional.


### Here is program to check if the number is even or zero.

```python

num=0
if num==0:
  print("Number is zero")
elif num>0:
  print("Number is greater than 0")

```

[Click here for DIY](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/elif.ipynb)




