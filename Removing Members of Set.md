#Removing Members of Set

Any member of the set could be removed using remove() or discard()

set1={0,1,2,3}
set1.remove(0)
set1.discard(3)

Even though both methods remove the members, remove() would throw up an error when trying to remove an item that does not exist whereas discard() would not

Members could also be removed using pop(). But, using pop() method, one cannot know which member would be removed.

"del" command can be used to delete an entire set. 

set1={1,2,3}
del set1

.clear() is used to remove all the elements of a set as shown below

[Click here for DYI](https://colab.research.google.com/github/pythoncoder100/practice/blob/master/Removing_members_of_Set.ipynb)


