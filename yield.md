# Yield Expression

Yield is a keyword in Python that is used to return from a function without destroying the states of its local variable and when the function is called, the execution starts from the last yield statement. Instead of a returning value, the yield expression gives back a generator object to the caller.

Each yield temporarily suspends processing, remembering the location execution state (including local variables and pending try-statements). When the generator iterator resumes, it picks up where it left off (in contrast to functions which start fresh on every invocation).

Generators are functions that return an iterable generator object. The values from the generator object are fetched one at a time instead of the full list together and hence to get the actual values you can use a for-loop, using next() or list() method.
      

    def get_fibonacci2():
      a, b = 0, 1
      yield a
      while b < 35:
        yield b
        a, b = b, a + b
        

    for j in get_fibonacci2():
      print(j)


Output:<br>
      0<br>
      1<br>
      1<br>
      2<br>
      3<br>
      5<br>
      8<br>
      13<br>
      21<br>
      34<br>
    


