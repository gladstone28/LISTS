link to lesson

https://www.codecademy.com/paths/code-foundations/tracks/learn-how-to-code/modules/bop-iii/lessons/bop-lists/exercises/bop-lists-adding-items

Lists
Adding Items to a List
3 min
After a list is created, we’re able to add things to it.

When we add things to the end of an existing list, we say that we’re appending them to the end. Imagine we’re trying out different endings for our comic strip. We can try adding different frames to our current narrative and see which one we like the best.


```
myList = ['apple', 'banana', 'pear']

myList.push('orange') // the .push command is JavaScript's implementation for appending an item to the end of a list

// now, myList == ['apple', 'banana', 'pear', 'orange']

```

In addition to adding things to the end of a list, we can also insert items in the existing list. We do so by using the 
Preview: Docs Loading link description
index
 number for where we want to position our new value.

```

myList = ['apple', 'banana', 'pear']

myList.splice(1, 0, 'mango') // make 'mango' the second item in the list

// now, myList = ['apple', 'mango', 'banana', 'pear']


```
In this line of code, we inserted the 
Preview: Docs Loading link description
string
 'mango' at the index 1 position. But it’s important to be careful - adding something in the middle of a pre-existing list, or adding it to the beginning of a list, will alter the indices for all the following items. Notice that ‘banana’ was in the second position and is now in the third.

In JavaScript, we can edit lists with commands like .splice and .pop. You don’t need to memorize these commands – the important part is that you understand the ways in which lists can be edited!


