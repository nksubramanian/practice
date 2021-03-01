# for loop

The for loop is slightly different in python. 

The programmer here can decide the number of times a block of code is to be looped around. 

Unlike other langauges such as Java, C++, there are no conditions in the for loop that are to be checked before executing the block. 

The range is an inbuilt function used to generate a sequence.

### Here is a program to iterate from 0 upto 5 

```python

for iter in range(0,5):
  print(iter)

```
[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/for_loop.ipynb)



for loop can also be used to iterate over elements of a list/tuple.

### Here is a program that iterates over the elements in an array and finds its sum

```python

sample_list=list([10,2,3,4])
summation=0
for iter in sample_list:
  summation+=iter
print("The sum of elements in the list is "+str(summation))

```
[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/for_loop_list.ipynb#scrollTo=zRDLP2jbvKTT)


for loop can also be used to iterate over elements in a string. 

### Here is a program to reverse the elements of a string

```python
string="Here is a python string"
reversed_string=" "
for iter in range(0,len(string)):
  reversed_string=reversed_string+string[len(string)-1-iter]
print(reversed_string)

```

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/for_loop_reversing_the_string.ipynb)



