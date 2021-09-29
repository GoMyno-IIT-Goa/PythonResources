# Bisect
The purpose of Bisect is to find a position in list where an element needs to be inserted to keep the list sorted.

bisect module has a functions named bisect and bisect_left in it.

bisect(list, num, beg, end) :- This function returns the position in the sorted list, where the number passed in argument can be placed so as to maintain the resultant list in sorted order. If the element is already present in the list, the right most position where element has to be inserted is returned. This function takes 4 arguments, list which has to be worked with, number to insert, starting position in list to consider, ending position which has to be considered.


Example:
```py
import bisect
    
a = [1, 2, 2, 2, 4, 4, 9]
print(bisect.bisect(a, 4))
```
    
Output:

    6


bisect_left(list, num, beg, end) :- This function returns the position in the sorted list, where the number passed in argument can be placed so as to maintain the resultant list in sorted order. If the element is already present in the list, the left most position where element has to be inserted is returned. This function takes 4 arguments, list which has to be worked with, number to insert, starting position in list to consider, ending position which has to be considered.

Example:
```py
import bisect
    
a = [1, 2, 2, 2, 4, 4, 9]
print(bisect.bisect_left(a, 4))
```

Output:

    4

