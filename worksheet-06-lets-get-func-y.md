# Lesson 2 - Let's get Func-y
We are going to learn about functions.  Functions are helpful when you want something to do it for you.

## Section 1 - Start Python Terminal
Follow the directions from the previous lesson and start the Python command prompt.

## Section 2 - Move Around
1. We found out how to make shapes, now we are going to add some colors.
```python
import turtle
def turn
turtle.reset()
turtle.forward(100)
turtle.right(90)
turtle.forward(100)
turtle.right(90)
turtle.forward(100)
turtle.right(90)
turtle.forward(100)
```

But what if we want to make a shape with 10, 20 or 100 sides?  You would have to type them all! 

Let's have the computer do the work for us using loops!

Try typing this out:
```python
for i in range(4):
    turtle.forward(75)
    turtle.right(90)
```

Ahhh....much less typing.  What does it do?

2. Hmmmm.....now show me how you would make a shape with 10 sides using loops.  Hint: Here's some of the code....you just need to replace `A`:
```python
turtle.reset()
for i in range(10):
    turtle.forward(75)
    turtle.right(36)
```

## Section 3 - Exit the Terminal
1. Enter the following command: `exit()` and press `Enter`.

## Section 4 - Mastery Checkup
- What does the `i` in the command `for i in range(100)` do?
- What does the `range(9999)` in the the command `for i in range(9999)` do?
