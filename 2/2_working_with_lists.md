# Accessing lists

If we run `2.0_list_index.py` we can see how to get a single item from a list of numbers.

You can see a demonstration of "slicing" in `2.1_list_slice.py`. Slices allow us to take a bunch of values from a list.

`print(a)` is a function that takes variable `a` and prints it out for a *human* to read.

In `2.2_assign_item_to_var.py` we perform some operations on the list and assign the *output* to a new variable.

## List Methods

Lists have a bunch of built in *methods* that we can use to change or analyse the list.

```
mylist.append()  mylist.count()   mylist.insert()  mylist.reverse()
mylist.clear()   mylist.extend()  mylist.pop()     mylist.sort()   
mylist.copy()    mylist.index()   mylist.remove() 
```
the `list.count()` method allows us to count the number of times something appears in the list. Here we can see that 1 appears twice.
```
>>> mylist = [1,2,3,4,3,4,1]
>>> mylist.count(1)
2
```

With `list.append()` we can add something to the end of the list.
```
>>> mylist.append(10)
>>> mylist
[1, 2, 3, 4, 3, 4, 1, 10]
```
Notice how `list.count()