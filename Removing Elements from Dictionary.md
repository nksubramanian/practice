# Removing Elements from Dictionary

Here are different ways to remove items in Dictionary

Sheela = {
"Major": "Chemistry",
"Age": 21,
"Gender": "Female",
"Qualification":"Bachelor"
}


1) Using the pop() method as shown below

Sheela.pop("Gender")

The pop method returns the value of the attibute in the method too

2)popitem() method is used when the last item is to be removed

Sheela.popitem()

popitem() returns the key-value pair too

[Click here for DYI](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Removing_items_from_Dictionary.ipynb)


3)del method can also be used to remove items from Dicitonary

del Sheela["Age"]

Entire dictionary could also be deleted using the del method

del Sheela

4) clear method can also be used to clear the contents of dictionary

[Click here for DYI](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Clearing_dictionary_using_clear().ipynb)

[Click here for DYI](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Removing_items_using_del_method.ipynb)

