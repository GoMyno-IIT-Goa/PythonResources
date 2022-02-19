## Python Datatypes

Number Data Type in Python
Python supports integers, floating-point numbers and complex numbers. They are defined as int, float, and complex classes in Python. <br>

Integers and floating points are separated by the presence or absence of a decimal point. For instance, 5 is an integer whereas 5.0 is a floating-point number. <br>

Complex numbers are written in the form, x + yj, where x is the real part and y is the imaginary part. <br>

We can use the type() function to know which class a variable or a value belongs to and isinstance() function to check if it belongs to a particular class. <br>

```py
a = 5

print(type(a))
print(type(5.0))

c = 5 + 3j
print(c + 3)
```

Output is:
```py
<class 'int'>
<class 'float'>
(8+3j)
True
```
