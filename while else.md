# while else

while else has the same syntax as while except that else block is included at the end of while block. 

else block would get executed whenever the condition mentioned in while block is false

So, it is impossible to have only the while block executed

### Syntax

```python
while condition:
  statement
else:
  statment
```


### Here is demonstration program
```python

iter=1
n=5
while(iter<n):
  print(iter)
  iter+=1
else:
  print("Try getting only while block get executed. I bet you cannot!")
  
```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/while%20else.ipynb)
