# Zip Function

The purpose of Python zip() method is to map the similar index of multiple containers so that they can be used just using as single entity. 

Example:

    a = ("Riya", "Tina", "Tom")
    b = ("John", "Monica", "Jerry", "Rachel")

    x = zip(a, b)
    
    for i in x:
      print(i)
    
Output:<br>

('Riya', 'John')<br>
('Tina', 'Monica')<br>
('Tom', 'Jerry')<br>

# Unzip Function

Unzipping means converting the zipped values back to the individual self as they were. This is done with the help of “*” operator.

Example continued:

    y = zip(*x)
    for i in y:
      print(i)

Output:<br>

('Riya', 'Tina', 'Tom')<br>
('John', 'Monica', 'Jerry')<br>
