# CS50 - Python
My solutions to Harvard's CS50 Python course

Course Description: Learn about functions, arguments, and return values (oh my!); variables and types; conditionals and Boolean expressions; and loops. Learn how to handle exceptions, find and fix bugs, and write unit tests; use third-party libraries; validate and extract data with regular expressions; model real-world entities with classes, objects, methods, and properties; and read and write files. Hands-on opportunities for lots of practice. Exercises inspired by real-world programming problems.

## Week 0 - Functions, Variables
- [Indoor Voice](https://github.com/JohnZolton/CS50-Python/blob/main/Week%200%20-%20Functions%20and%20Variables/indoor.py) - convert input to lowercase
- [Playback Speed](https://github.com/JohnZolton/CS50-Python/blob/main/Week%200%20-%20Functions%20and%20Variables/playback.py) - replace ' ' with '...'
- [Making Faces](https://github.com/JohnZolton/CS50-Python/blob/main/Week%200%20-%20Functions%20and%20Variables/faces.py) - replace :) and :( with emojis
- [Einstein](https://github.com/JohnZolton/CS50-Python/blob/main/Week%200%20-%20Functions%20and%20Variables/einstein.py) - calculates e = mc^2
- [Tip Calculator](https://github.com/JohnZolton/CS50-Python/blob/main/Week%200%20-%20Functions%20and%20Variables/tip.py) - calulates a tip given % tip and total bill
 
## Week 1 - Conditionals

- [Deep Thought](https://github.com/JohnZolton/CS50-Python/blob/main/Week%201%20-%20Conditionals/deep.py) - matches a response to certain user input
- [Home Federal Savings Bank](https://github.com/JohnZolton/CS50-Python/blob/main/Week%201%20-%20Conditionals/bank.py) - returns different answers depending on user input
- [File Extensions](https://github.com/JohnZolton/CS50-Python/blob/main/Week%201%20-%20Conditionals/extensions.py) - determines filetype of a user input
- [Math Interpreter](https://github.com/JohnZolton/CS50-Python/blob/main/Week%201%20-%20Conditionals/interpreter.py) - solves a user input math equation
- [Meal Time](https://github.com/JohnZolton/CS50-Python/blob/main/Week%201%20-%20Conditionals/meal.py) - splits user input to determine if its mealtime


## Week  2 - Loops
- [camelCase](https://github.com/JohnZolton/CS50-Python/blob/main/Week%202%20-%20Loops/camel.py) - contverts camelCase str to camel_case str
- [Coke Machine](https://github.com/JohnZolton/CS50-Python/blob/main/Week%202%20-%20Loops/coke.py) - adds valid coin inputs to buy a 50 cent bottle of coke
- [Just setting up my twttr](https://github.com/JohnZolton/CS50-Python/blob/main/Week%202%20-%20Loops/twttr.py) - removes vowels from user input string
- [Vanity Plates](https://github.com/JohnZolton/CS50-Python/blob/main/Week%202%20-%20Loops/plates.py) - checks if desired vanity plate is valid given a variety of conditions
- [Nutrition Facts](https://github.com/JohnZolton/CS50-Python/blob/main/Week%202%20-%20Loops/nutrition.py) - returns calorie content of a fruit from user input

## Week  3 - Exceptions
- [Fuel Gauge](https://github.com/JohnZolton/CS50-Python/blob/main/Week%203%20-%20%20Exceptions/fuel.py) - Determines % gas tank fullness, checks input for ValueError and ZeroDivisionError
- [Felipe's Taqueria](https://github.com/JohnZolton/CS50-Python/blob/main/Week%203%20-%20%20Exceptions/taqueria.py) - Creates a running tally of a menu order, terminates on ctl+D, ignores invalid menu entries
- [Grocery List](https://github.com/JohnZolton/CS50-Python/blob/main/Week%203%20-%20%20Exceptions/grocery.py) - creates a gocery list from user input, terminates on ctl+D, catches any KeyErrors
- [Outdates](https://github.com/JohnZolton/CS50-Python/blob/main/Week%203%20-%20%20Exceptions/outdated.py) - converts MM/DD/YYYY and Month Day, Year to YYYY-MM-DD, continually asks for proper input

## Week 4 - Libraries
- [Emojize](https://github.com/JohnZolton/CS50-Python/blob/main/Week%204%20-%20Libraries/emojize.py) - uses emoji library to return input as emoji
- [Frank, Ian and Glen's Letters](https://github.com/JohnZolton/CS50-Python/blob/main/Week%204%20-%20Libraries/figlet.py) - Renders text in figlet fonts chosen by user's command line arg
- [Adieu, Adieu](https://github.com/JohnZolton/CS50-Python/blob/main/Week%204%20-%20Libraries/adieu.py) - uses inflect library to print a list of names as "name, name, ... and name"
- [Guessing Game](https://github.com/JohnZolton/CS50-Python/blob/main/Week%204%20-%20Libraries/game.py) - uses random library to make a number guessing game
- [Little Professor](https://github.com/JohnZolton/CS50-Python/blob/main/Week%204%20-%20Libraries/professor.py) - generates addition problems of varying difficulty based on user input
- [Bitcoin Price Index](https://github.com/JohnZolton/CS50-Python/blob/main/Week%204%20-%20Libraries/bitcoin.py) - uses requests and json libraries to pull BTC price from site

## Week 5 - Unit Tests
- [Testing my  twittr](https://github.com/JohnZolton/CS50-Python/tree/main/Week%205%20-%20Unit%20Tests/test_twttr) - tests prior function under various cases
- [Back to the Bank](https://github.com/JohnZolton/CS50-Python/tree/main/Week%205%20-%20Unit%20Tests/test_bank) - tests prior function under various cases
- [Re-requesting a vanity plate](https://github.com/JohnZolton/CS50-Python/tree/main/Week%205%20-%20Unit%20Tests/test_plates) - tests prior function under various cases
- [Refueling](https://github.com/JohnZolton/CS50-Python/tree/main/Week%205%20-%20Unit%20Tests/test_fuel) - uses pytest to check for ZeroDivisionErrors and ValueErrors

## Week 6 - File I/O
- [Lines of Code](https://github.com/JohnZolton/CS50-Python/tree/main/Week%206%20-%20File%20IO/lines) - calculates lines of code in a python file, ignoring comments and blank lines, only accepts python files
- [Pizza Py](https://github.com/JohnZolton/CS50-Python/tree/main/Week%206%20-%20File%20IO/pizza) - makes ascii art menu from a csv menu file, exits if file not entered, not found or not a csv file
- [Scourgify](https://github.com/JohnZolton/CS50-Python/tree/main/Week%206%20-%20File%20IO/scourgify) - accepts a csv with ["Lastname, Firstname", House] and outputs a csv with [Firstname, Lastname, House]
- [CS50 P-Shirt](https://github.com/JohnZolton/CS50-Python/tree/main/Week%206%20-%20File%20IO/shirt) - accepts an original image file and output image file, pastes an image over the original and saves to the output image file

## Week 7 - Regular Expressions
- [Numb3rs](https://github.com/JohnZolton/CS50-Python/tree/main/Week%207%20-%20Regular%20Expressions/numb3rs)
- [Watch on Youtube](https://github.com/JohnZolton/CS50-Python/tree/main/Week%207%20-%20Regular%20Expressions/watch)
- [Working 9 to 5](https://github.com/JohnZolton/CS50-Python/tree/main/Week%207%20-%20Regular%20Expressions/working)
- [Regular, um, expressions](https://github.com/JohnZolton/CS50-Python/tree/main/Week%207%20-%20Regular%20Expressions/um)
- [Response Validation](https://github.com/JohnZolton/CS50-Python/blob/main/Week%207%20-%20Regular%20Expressions/response.py)

## Week 8 - Object-Oriented Programming
- [Seasons of Love](https://github.com/JohnZolton/CS50-Python/tree/main/Week%208%20-%20OOP/seasons)
- [Cookie Jar](https://github.com/JohnZolton/CS50-Python/tree/main/Week%208%20-%20OOP/jar)
- [CS50 Shirtificate](https://github.com/JohnZolton/CS50-Python/tree/main/Week%208%20-%20OOP/shirtificate)
