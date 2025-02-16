link to lesson:

https://www.codecademy.com/paths/code-foundations/tracks/learn-how-to-code/modules/bop-iii/lessons/bop-lists/exercises/bop-lists-removing-items


Lists
Removing Items from a List
1 min
We’re also able to remove items from a list.

Similar to adding items, we can modify lists by taking off the last item, or we can use indexing to select a specific item and remove it from the list.

```
myList = ['apple', 'banana', 'pear']

// removes 'pear' from myList and returns 'pear'
myList.pop() 

// now, myList == ['apple', 'banana']

```

This line of code will take away the last item from our list, keeping our sequence intact. But we can also remove items from the middle of our list:

```
myList = ['apple', 'banana', 'pear']

myList.splice(1, 1) // removes 'banana' from myList and returns 'banana'

// now, myList == ['apple', 'pear']



```
