# Use modules by importing from Github

The first step in using modules is to create .py file containing the functions with the name of the file same as that of module

If the .py file is in the Github, then it is possible to access the .py from Colab directly instead of manually downloading and then uploading

Below is the command to download 

```python
!git clone https://github.com/pythoncoder100/practice.git
 ```
 
 Since the tester.py is not in the working directory, the working directory is changed with the following command
 
 ```python
cd /content/practice
```

You can now check the working directory by the following command

```python
pwd()
```

After the working directory is changed to the directory containing the .py file, you can import as follows

```python
import tester
tester.add(4,3)
```
tester is the module name and .py file name. tester has the user defined function "add(a,b)"

[Click here to try](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Creating_Module_with_py_file_in_Github.ipynb)



