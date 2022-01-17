## CodeClub intro

### Intro round

### Course basics

- goals, methods, topics
  - 2 sessions per week (Mon-Wed)
  - homework (posted on Slack)
  - discussions on Slack  
- guest lecturers
- suggested reading, suggested prep time

- not a bootcamp, no obligations, no guarantees
- can promise to teach the basics of Python
- read a lot of realpython.com


### Python

What is a program?
topics: code, whitespace, comments, errors in Python

A program is a collection of instructions - we instruct the computer what to do, and it does exactly that. It does **exactly** what we tell it.
A program is executed line by line, one afer another, starting from the first line of a file. The "syntax" of a program follows a strict set of rules that the computer can understand
Python is one of many programming languages. It's very popular in many areas: 
- web development, 
- scientific computing, 
- bioinformatics (a straind of DNA as a sequence of characters)
- finance (financial analysis, stock trading)
- machine learning (image recognition)
- data science
- recommendation engines
- natural language processing (sentiment analysis, etc)
- gaming

A special program, called the interpreter, reads and executes our Python code.
Python code is written into files ending with .py.

```
"""
This text you are reading now is valid Python code (although it is a comment, or more specifically a docstring)
"""
```

Code looks like this:

```
cat = 'Jones'

def meow():
    # indentation is the usage of spaces or tabs to create a function "body"
    print('Meow!!!')

meow()

# Lines starting with # are comments
# These are not evaluated
# cica2 = "Mircike"
# asdasda zxcasda. 1q23123asda

def woof():  # Comments can be written inline, next to the code
    pass


def multiply_by_two(number):
    return number * 2

result = multiply_by_two(6)

"""
Lines between three quotation marks (") are comments too
These can be multi-line

Like this
"""

# Data types
# type()
# int, float, boolean, string... etc

# Variable
## naming style and capitalisation
## Assignment ("legyen egyenlő")

dog = "Wolfie"

variable_name = "value"

dog_2 = 'Mr Dog'

number_of_students = 10  # no accents in variable names

number_of_students = number_of_students + 1 
number_of_students += 1

max_student_count = 15


"""
## Equality, comparison

dog == dog_2 

1 == 2

1 == 1

2 > 1

comparison operators: ==, <, >, <=, >=
"""
```
