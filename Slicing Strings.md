# Slicing Strings

Python has ways of slicing a portion of the string 

For example, string[n1:n2] would return the string from n1th element upto n2th element. This is exclusive of n2th element.

Either n1 or n2 can be omitted. When n1 is omitted, the command string[:n2] would return the string from 0th up to n2th element. 
When n2 is omitted, the command string[n1:] would return the portion of the string starting from n1th element to the end of the string.

It is also possible in python to refer to numbers using negative numbers. string[-1] would return the last element.

It's also possible to return a substring with elements skipped between them.
The command string[n1:n2:step size] can be used.

For example, string[n1:n2:2] would return a portion of string from n1the element up to n2th element with 2 elements skipped between them. 

[Click here for DIY](https://github.com/pythoncoder100/practice/blob/master/slicing_the_string.ipynb) 
