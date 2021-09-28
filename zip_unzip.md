# Zip Function

The purpose of Python zip() method is to map the similar index of multiple containers so that they can be used just using as single entity. 

Example:
```py
a = ("Riya", "Tina", "Tom")
b = ("John", "Monica", "Jerry", "Rachel")

x = zip(a, b)
    
for i in x:
    print(i)
```

Output:
```py
('Riya', 'John')
('Tina', 'Monica')
('Tom', 'Jerry')
```

# Unzip Function

Unzipping means converting the zipped values back to the individual self as they were. This is done with the help of “*” operator.

Example continued:
```py
y = zip(*x)
for i in y:
    print(i)
```
Output:
```py
('Riya', 'Tina', 'Tom')
('John', 'Monica', 'Jerry')
```
