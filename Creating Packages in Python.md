# Creating Packages in Python

Group of related modules can be placed together as a package. In this tutorial, steps to create a package is provided.

### Step 1:

Create a folder with the same name as the package name and place all the .py files of module within the folder

### Step 2:

Within the created, create an empty file named "\_init\_.py"

### Step 3

Use the below command to import the package

 ```python
 from python_package import module1,module2
 print(module1.add(2,3))
 print(module2.add(3,4))
```

module1 has function named add and module2 also has function named add.

If you have not created the package, you can download the package from here and rename to "python_package"

[Click here to download](https://github.com/pythoncoder100/python_package)


Note that python_package would have to be placed in the Colab for the below program to work  

[Click here to try](https://github.com/pythoncoder100/practice/blob/master/Creating_a_user_defined_package.ipynb)
