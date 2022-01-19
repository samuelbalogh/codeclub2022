## CodeClub intro

### Intro round

### Course basics

- goals, methods, topics
  - 2 sessions per week (Mon-Wed)
  - homework (posted on Slack)
  - discussions on Slack  
- there will be guest lecturers
- not a bootcamp, no obligations, no guarantees
- can promise to teach the basics of Python
- read a lot of [realpython.com](realpython.com)


### Programmin

What is a program?
topics: code, whitespace, comments, errors in Python

A program is a collection of instructions - we instruct the computer what to do, and it does exactly that. It does **exactly** what we tell it.
A program is executed line by line, one afer another, starting from the first line of a file. The "syntax" of a program follows a strict set of rules that the computer can understand

### Python

Python is one of many programming languages. It's very popular in many areas: 
- web development, 
- scientific computing, 
- bioinformatics (a strand of DNA as a sequence of characters)
- finance (financial analysis, stock trading)
- machine learning (image recognition)
- data science
- recommendation engines
- natural language processing (sentiment analysis, etc)
- gaming

A special program, called the interpreter, reads and executes our Python code.

```
"""
This text you are reading now is valid Python code (although it is a comment, or more specifically a docstring)
"""
```

Code looks like this:

```
cat = 'Jones'
```

In the above line, we've **assigned** a **value** to a **variable name**. A **variable** holds some value, so that we can re-use it later.

```
# Lines starting with # are comments
# These are not evaluated, these are meaningless to the computer
```

## Data types


### Numeric types

- integers: `1, 2, 42`  
- floats: `3.0, 1.232, .01`

(There is a data type for complex numbers, but their usage is very rare)

### Strings


Strings represent **text**. They are between single or double quotes.

```
food = 'spaghetti'
```

```
other_food = "lasagne"
```

[Python docs](https://docs.python.org/3/tutorial/introduction.html?fbclid=IwAR3knUj3nO0-f2fYMS5Yb5MbGplB93buRymiE_07F06rufql14v5bKrzErk#strings)


### Booleans

Values representing "Boolean logic": True/False. 

`True` and `False` are the only boolean values.

This is a [good article about booleans](https://thomas-cokelaer.info/tutorials/python/boolean.html?fbclid=IwAR0mg4nzR6uQ4JvneWMGzLH6yiYzeb4Lo_C83ddo5vwXAcy_-lRdH61Q-Gw#notes-about-booleans-and-logical-operators).
