# Lesson 1 - Getting In and Out
The purpose of this lesson is to be able to open the terminal on the computer and start the PythonTurtle command line interface.  After this, the objective is to run  a few simple commands in PythonTurtle and move the turtle.

## Section 1 - Start Python Terminal
### Mac
1. Hit `Command` + `Spacebar` then type in `Terminal`.  Press `Enter`.
1. Type the following commands in the terminal:
```bash
cd development/python-turtle
source .venv/bin/activate
python3
```
### Windows
1. Press the `Windows` key and then select `Python 3.12`.

## Section 2 - Moving the Turtle for the First Time
1. Open the PythonTurtle window with the following commands (press `Enter` after each command):
```bash
import turtle
turtle.reset()
turtle.forward(100)
turtle.reset()
turtle.forward(10)
```

## Section 3 - Exit the Terminal
1. Enter the following command: `exit()` and press `Enter`.

## Section 4 - Mastery Checkup
- What does the command `exit()` do?
- What happens if you enter the command `turtle.forward(10000000000)` instead of `turtle.forward(100)`?
- What does the command `turtle.reset()` do?
