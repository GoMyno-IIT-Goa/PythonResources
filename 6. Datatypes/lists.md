# Lists in Python

In Python, a list is created by placing elements inside square brackets [], separated by commas.

### List of integers
```py
my_list = [1, 2, 3]
```
A list can have any number of items and they may be of different types (integer, float, string, etc.).

### Empty list
An Empty list is defined using:
```py
my_list = []
```

### List with mixed data types
```py
my_list = [1, "Hello", 3.4]
```
A list can also have another list as an item. This is called a nested list.

### Nested list
```py
my_list = ["mouse", [8, 4, 6], ['a']]
```


## Access List Elements
There are various ways in which we can access the elements of a list.

### List Index
We can use the index operator [] to access an item in a list. In Python, indices start at 0. So, a list having 5 elements will have an index from 0 to 4.

Trying to access indexes other than these will raise an IndexError. The index must be an integer. We can't use float or other types, this will result in TypeError.

Nested lists are accessed using nested indexing.
```py
my_list = ['p', 'r', 'o', 'b', 'e']
# First item
print(my_list[0])  # p
# Third item
print(my_list[2])  # o
# Nested List
n_list = ["Happy", [2, 0, 1, 5]]
# Nested indexing
print(n_list[0][1])
print(n_list[1][3])
# Error! Only integer can be used for indexing
print(my_list[4.0])
```

Output:
```py
p
o
e
a
5
Traceback (most recent call last):
  File "<string>", line 21, in <module>
TypeError: list indices must be integers or slices, not float
Negative indexing
Python allows negative indexing for its sequences. The index of -1 refers to the last item, -2 to the second last item and so on.
```

### Negative indexing in lists
```py
my_list = ['p','r','o','b','e']

# last item
print(my_list[-1])

# fifth last item
print(my_list[-5])
```

Output
```py
e
p
```
