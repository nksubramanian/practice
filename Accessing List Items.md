# Acessing List Items

Much like Strings, elements in a list could be accessed as below

list1=[1,2,3,4,'a','ab']
list1[n1:n2] is used to access elements from n1th position up to n2th position
list[n1:] when last index is omitted, elements from n1th position till the end of the list are accessed
list[:n2] when the first index is omitted, all the element from the beginning of the list up to n2th position is accessed.


It's permitted to access the elements of list using negative numbers too. For example, list1[-1] would return the last element

list1[n1,n2,step size]-this would return elements starting from n1th element up to n2th element, every step size
Example list[3,9,2]-this would return every 2nd element from 3th position to 9th position.

[Click here for DYI](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Acessing_List_Items.ipynb)


