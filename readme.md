# Collection of class exercises from DigitalCrafts starting from the second day of class

Hello. Thank you for showing interest in my first learning steps into Python. Many highly-functional beginner-level Python programs are available for viewing and/or use here.

## Contents

  * What It Is
  * What We Used
  * Challenges
  * Most Interesting Available Working Files
  * Screenshots
  * Github Link
  * Code Examples

## What It Is

This is a running log of all the work I accomplished in class while attending DigitalCrafts, which was my first true experience in coding/technology. The first part of the bootcamp consisted of solely Python, which is evident in the files that are present currently.

*Note: Not all files are functional when run in terminal because they were just practice files and were altered several times without fixing for learning purposes.

## What We Used

  * Python3
  * Turtle

## Challenges

The greatest challenge was simply successfully debugging nearly-functional code. This provided great practice in learning how to review and catch small errors.

## Most Interesting Available Working Files

*Note not all files directly follow given exercises intructions when run due to learning purposes.

1. [dictexercises.py](https://github.com/ekim1707/secondclasspython/blob/master/dictexercises.py)

Grade: N/A
View Grade Information. Opens a dialogue
Exercise 1
Given the following dictionary, representing a mapping from names to phone numbers:
```
phonebook_dict = { 
  'Alice': '703-493-1834', 
  'Bob': '857-384-1234', 
  'Elizabeth': '484-584-2923'
}
```
Write code to do the following:

Print Elizabeth's phone number.
Add a entry to the dictionary: Kareem's number is 938-489-1234.
Delete Alice's phone entry.
Change Bob's phone number to '968-345-2345'.
Print all the phone entries.

Exercise 2: Nested Dictionaries
```
ramit = { 
  'name': 'Ramit', 
  'email': 'ramit@gmail.com', 
  'interests': ['movies', 'tennis'], 
  'friends': [ 
     { 
       'name': 'Jasmine', 
       'email': 'jasmine@yahoo.com', 
       'interests': ['photography', 'tennis']
     }, 
     { 
        'name': 'Jan', 
        'email': 'jan@hotmail.com', 
        'interests': ['movies', 'tv'] 
     } 
    ] 
}
```
Write a python expression that gets the email address of Ramit.
Write a python expression that gets the first of Ramit's interests.
Write a python expression that gets the email address of Jasmine.
Write a python expression that gets the second of Jan's two interests.

Letter Summary
Write a letter_histogram function that takes a word as its input, and returns a dictionary containing the tally of how many times each letter in the alphabet was used in the word. For example:
```
letter_histogram('banana') 
{'a': 3, 'b': 1, 'n': 2}
```
Word Summary
Write a word_histogram function that takes a paragraph of text as its input, and returns a dictionary containing the tally of how many times each word in the alphabet was used in the text. For example:
```
word_histogram('To be or not to be') 
{'to': 2, 'be': 2, 'or': 1, 'not': 1}
```

2. [guessnumber.py](https://github.com/ekim1707/secondclasspython/blob/master/guessnumber.py)

Step 1
You will implement a guess-the-number game where the player has to try guessing a secret number until he gets it right. For now, you will "hard code" the secret number to 5 (just set it to five like secret_number = 5). You will prompt the player to enter a number again and again, each time comparing his input to the secret number. To to that, you will need to write a while loop. If he guesses correctly, you will print "You win!", otherwise, you will prompt for a number again.

3. [phonebook.py](https://github.com/ekim1707/secondclasspython/blob/master/phonebook.py)

Electronic Phone Book:

Look up an entry 
Set an entry 
Delete an entry 
List all entries 
Quit
What do you want to do (1-5)?

If they choose to look up an entry, you will ask them for the person's name, and then look up the person's phone number by the given name and print it to the screen.
If they choose to set an entry, you will prompt them for the person's name and the person's phone number,
If they choose to delete an entry, you will prompt them for the person's name and delete the given person's entry.
If they choose to list all entries, you will go through all entries in the dictionary and print each out to the terminal.
If they choose to quit, end the program.

4. [shapes.py](https://github.com/ekim1707/secondclasspython/blob/master/shapes.py)

Draw these simple shapes (each in its own .py file):

an equilateral triangle
a square
a pentagon
a hexagon
an octagon
a star
a circle

Extract all the code for the shapes in exercise 1 into functions. Move them all into a single file called shapes.py. Write a new .py program that imports the shapes module and use its functions to draw all the available shapes onto the screen.

5. [shapeparameters.py](https://github.com/ekim1707/secondclasspython/blob/master/shapeparameters.py)

*Cont. from above

Add parameters into the various functions of your shapes module. Include:

size - the size of the shape
fill - a bool specifying whether to fill or outline the shape
color - the color of the shape. *Hint: you can use the color function to set both the pen color and the fill color.
Make a new .py program that imports the shapes module and uses its functions to draw different shapes of various colors, fills, and sizes.

##Screenshots
---
![alt text](https://github.com/ekim1707/secondclasspython/blob/master/screenshots/turtlestar.png 'turtlestar.png')
![alt text](https://github.com/ekim1707/secondclasspython/blob/master/screenshots/turtlestar1.png 'turtlestar1.png')

We completed the turtlestar.py file (which produced the first image) before we came across the solution code (turtlestar2.py, which produced the second image), and we noted the interesting differences that resulted from the different methods of completing the instructions of the exercise.

##Github Link
---
[Github](https://github.com/ekim1707/secondclasspython)

##Code Examples
---
Included is the code for both star-drawing programs.

* turtlestar.py:

```
python
from turtle import *

rt(72)
fd(100)
lt(72)
fd(100)
rt(144)
fd(100)
lt(72)
fd(100)
rt(144)
fd(100)
lt(72)
fd(100)
rt(144)
fd(100)
lt(72)
fd(100)
rt(144)
fd(100)
lt(72)
fd(100)

mainloop()
```

* turtlestar1.py:

```
python
from turtle import *
for i in range(5):
    forward(100)
    right(144)
mainloop()
```
