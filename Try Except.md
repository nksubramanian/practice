# Try Except

The purpose of Try Except is to check a piece of code and locate where there is an error. 

When an error is thrown in the try block, the except block gets executed. 

Since variable x is not declared anywhere, there is an error. So, the except block gets executed

try:
  print(x)
except:
  print("An exception occurred")
  
  [Click here for DYI](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Try_except.ipynb)
  

As there are different types of errors, it is possible to have separate blocks for each type

Below the number is divided by zero which would result in ZeroDivisionError, so the corresponding except block would only get executed

try:
  5/0
except ZeroDivisionError:
  print("Number is being divided by zero here")
except:
  print("Something else went wrong")
  
  
[Click here for DYI](https://github.com/pythoncoder100/practice/blob/master/Specific_exception_handling.ipynb)
  
  
Except block gets executed when there is an error in the try block, it is possible to have another block executed only when there is no error in the Try block

try:
  print("Hello")
except:
  print("I would get executed when there is something wrong")
else:
  print("I would get executed when there is nothing wrong in the Try block")
  
[Click here for DYI](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/except%20else.ipynb)  
  
  
  
  

