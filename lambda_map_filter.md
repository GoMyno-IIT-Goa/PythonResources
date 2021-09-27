# Lambda
A lambda function is a small anonymous function that can take any number of arguments, but can only have one expression which is its return value.

Example:

    square = lambda x : x ** 2
    print(square(8))
    
Output:

    64
    
# Map
The map() function takes two parameters:
function - a function that perform some action to each element of an iterable
iterable - an iterable like sets, lists, tuples, etc.

Example continued:

            scores = [12, 7, 15, 8]<br>
            squared_scores = list(map(square, scores))<br>
            print(squared_scores)<br>
   
Output:

    [144, 49, 225, 64]
    
# Filter
Python’s filter() is a built-in function that allows you to process an iterable and extract those items that satisfy a given condition. 
It takes two parameters:
function -  a function that tests each element in the sequence to be true or not.
sequence -  sequence which needs to be filtered, it can be sets, lists, tuples, or containers of any iterators.
        
Example continued:

        filtered = [lambda x : x >= 100, squared_scores]<br>
        print(filtered)<br>
        
Output:

    [144, 225]
