# Numbers
Python supports three types of numbers – ```int```, ```float```, and ```complex```. Integers do not have a decimal point, while floats do. Complex is mostly used in geometry and scientific calculations (so ignore them for now). You can also convert numbers into strings, which Python will treat as text (so no more multiplications afterwards).

*Integer and float*<br>
`a = 4
b = 4.0
print(a+b)`{{execute}}

*Float printed out as an integer*<br>
`a = 4.2
print(a)
print(int(a))`{{execute}}

*Integer printed out as a float*<br>
`a = 4
print(a)
print(float(a))`{{execute}}

If you want a user to enter a number that you can then manipulate in Python (for example, multiplying the user's age by 5) you'll want to make sure that Python understands it's a number instead of a string. After all, you can't do maths on text/string.

```input()``` will return what Python "thinks" is best, but you can tell Python exactly what variable type you want by doing the following:

```
number = int(input("Enter a number"))
```

# Text
You already know the variable type for text - it's ```string```.

# Other Data Types
There are many more data types that you'll learn about in future lessons, many of which will take the knowledge from this session and find practical day to day uses for them.

# Quick Exercise
- Turn on your camera
- Come on, it's awkward here when I'm the only one with my camera on :P

# Practical Uses
Floating-point real numbers can't be represented with exact precision due to hardware limitations, so ```print(0.1 + 0.2)``` gives ```0.30000000000000004```, which is obviously not entirely correct. That's where integers or number rounding can come in handy in certain scenarios.