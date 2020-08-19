# Exploring New Programming Languages

We've explored server-side programming with JavaScript, but there are many other options out there. In this assignment, we're going to take a look at working in Python.

There won't be a lot of information here on exactly what you should do. There are some pointers here to get you started, but you'll need to do a lot research on your own. 

> You should work through this assignment yourself, but check in with your group as you go to share what you are learning, useful resources, and ask questions.

## Objectives

- install tools required to work with a new language
- explore basic syntax (variables, types, data structures, loops, conditionals, functions) of new language
- solve a whiteboard logic problem in a new language
- document and share what you've learned in a GitHub readme


## Install

Working with a new language means you'll need some new tools. Start by figuring out what you need to install to get started. When doing development on a Mac, Homebrew is a good starting point. 

Search the web for how to get setup with your assigned language __using Homebrew.__

> Note: Homebrew is nice because it allows you to keep the version of languages you use for development separate from what might be installed by your OS. Many languages, including python, also provide tools that help you manage the version of the language used across different projects. (Check-out `pyenv` for python).

Source:
https://code.visualstudio.com/docs/python/python-tutorial#_prerequisites
- Enable python in vsCode settings
- Use command `brew install python3`
- Use command `python3 --version` to verify python installation

https://code.visualstudio.com/docs/python/environments
- Use `cmd+shift+p` to open Command Palette
- Type `>python: Select Interpreter` to select environment
- Select `Python 3.8.5 64-bit`


## Hello World

A great place to get started with a new language is by making a Hello World program. 

Search the web for a basic Hello World tutorial for your assigned language to get things started. 

Source:
https://code.visualstudio.com/docs/python/python-tutorial#_prerequisites
- Use `.py` for python file type
https://www.w3schools.com/python/python_syntax.asp
- Variables such as `let` or `const` aren't needed in python
- `print` is the equivalent to `console.log()` in js

## Basic syntax

Hello World is a great starting point, but you'll need to sort out more language features to get a bigger application up and running. Find a language guide to help you with basic syntax for functions, conditionals, and loops.

Take some time to look into how to buff it up a bit by writing a function. Can you get it to say hello to a person by name using a function parameter? 

Source:
https://www.w3schools.com/python/python_functions.asp
- `#` is used to signify a comment
- `def` is used to define a function
https://www.w3schools.com/python/python_conditions.asp
- `if` is used to define a conditional
    - a = 33
    - b = 200
    - if b > a:
    - print("b is greater than a")
    - notice a colon is used instead of a curly brace
- `elif` is the equivalent of `else if` in js
- `else` is the same as js
- Equals: a == b
- Not Equals: a != b
- Less than: a < b
- Less than or equal to: a <= b
- Greater than: a > b
- Greater than or equal to: a >= b
https://www.w3schools.com/python/python_for_loops.asp
-3


## Programming

After you are a bit familiar with the basic syntax, solve one of our "whiteboard" problems (FizzBuzz, reverse a string or array, LeapYear, etc.) in your new language! Do this on your computer, not on a whiteboard!

Here is a list of things you should focus on: 

1. Variables & types :
    - how to make a variable (do variables have types?)
    - write to the console

2. Data structures and loops:
    - arrays or lists of things
    - objects

3. Functions and conditionals:
    - write a function that takes arguments and returns a value (sum 2 numbers)
    - operators - math, logical (and/or/not)

4. Pull things all together in one problem. Solve a whiteboard problem! (FizzBuzz, reverse a string or array, LeapYear, etc.) You can find our old whiteboard challenges in the syllabus repository!


### GitHub Repo

Setup a new GitHub repo with a README file that has instruction for installing the new language tools & resources your group found useful. Then add some notes with an example of each of the items listed above. Think of this Readme as a way to highlight your new language learning journey. This is a great way to show potential employers that you can tackle a challenge and learn a new language quickly! 

When you are done, complete the assignment on the portal with your GitHub repo link. 
