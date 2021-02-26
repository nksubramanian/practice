# Sorting through List

.sort() can be used on list containing strings as well as numbers. When used with strings, the elements would be sorted in a dictionary-like fashion
When used on numbers, the numbers would be sorted in an ascending manner. 

.sort(reverse = True) does the same as above except in descending manner. 

Results returned using sort() may go awry when some elements start off with lower case and some with upper case. This problem is overcome with the following command
.sort(key = str.lower)

[Click here for DYI](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Sorting_through_Lists.ipynb)
