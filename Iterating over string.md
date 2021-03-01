# Iterating Over String

Using for loop, string can also be iterated character by character

### Here is a program to remove '$' from the string


```python

new_string=''
for x in "sam$ple String$":
  if x=='$':
    continue
  new_string+=x
print(new_string)

```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Iterating_over_the_string.ipynb)
