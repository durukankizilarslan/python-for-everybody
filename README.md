# Contents of the course:
What is programming?  
What is Python?  
Hardware Architecture  
How To Install Python  
Python Interpreter and Executing Python Files  

## Python Language  (Chapter 1)
Syntax Errors  
Reserved Words  
Program Flow - Sequential Steps
Conditional Steps (if)  
Repeated Steps (while)  

## Variables, Expressions and Statements (Chapter 2)
Constants  
Variables  
Reserved Words  
Variable Naming Rules  
Mnemonic Variable Names  
Assignment Statement  
Numeric Expressions - Operators  
Order of Evaluation - Operator Presedence  
Data types , type() function  
Types of numbers (int, float)  
Type conversion int() float()  
Integer division (puts out a floating point result in Python 3)  
String conversion using int()) and float()  
Use rinput using input()  
Converting user input int(input)  
Comments

## Conditional Execution (Chapter 3)
Conditional steps (if)  
Comparison operators  
One-way Decisions (if only)  
Indentation  
Nested decisions (if inside another if or while etc..)  
Two-way decisions (with else)  
More Conditional Structures  
Multi-way decisions with else if (elif)  
try/except structure  

## Functions (Chapter 4)
What is a function  
Built in functions  
min() max() functions  
String conversions with int() and float() functions  
Defining and invoking a function  
Arguments and Parameters  
Return of functions  
Void functions  

## Loops and Iteration (Chapter 5)
While loop and zero-trip loops  
Breaking the loop (break)  
Passing the iteration (continue)  
Indefinite loops(for) and definite loops(while)  
For loop (for i in set)  
Finding the largest value (for loop)  
Summing in a loop (find the summ of numbers in a set)  
Filtering in a loop (if inside a for loop)  
Searching using a Boolean variable  
None type  
is Operator (if ____ is ____)  

## Strings (Chapter 6)
Index operator []  
Length function len()  
Looping through strings (while ____ < len(something) )  
Looping through strings (for letter in fruit )  
String operations - slicing [:]  
"in" keyword as a logical operator  
String built in functions  
find() method  
upper() and lower() method  
replace() method  
lstrip(), rstrip(), strip()  
startswith()  

## Reading Files (Chapter 7)  
Opening a file open() and the handle  
The newline character \n  
Counting lines in a file with for loop  
Reading the whole file using read()  
Searching through a file with open() and using an if inside a for loop  
Skipping a line with a continue statement  
Using the "in" statement to skip line - if not '_____' in line:  
try: except: notation for files that can not be opened  
quit() function  
Bad file names without handle  

## Lists (Chapter 8)
Lists in Python []  
Iterating through lists with for loop  
Lists are mutable (their elements can be changed)  
Finding the numbers of elements of a list using the len() function  
The range() function  
Concatenating lists using +  
Lists slicing [:]  
dir() command to see what can you do with the list (methods of lists)  
List methods  
list(), append() methods  
"in" and "not in" methods in lists to verify if a certain element is in the list: 9 in some, 20 not in some  
sort() method in lists  
Built in functions and lists  len(), max(), min(), sum()  
Lists and strings - split() function  
Delimiters in split() function (the character based for splitting)  

## Dictionaries (Chapter 9)
Dictionaries and dictionary literals  
Dictionaries - counting  
Usage of "in" operator to check if a key is in the dictionary -> if name not in counts: counts[name] = 1  
get() method and default value of it -> get(name, 0)  
Counting with get()  
Count words in a line using dictionaries  
Definite loops and dictionaries -> Printing dictionary content with for loops  
Retrieving of keys and values using jjj.keys(), jjj.values() and jjj.items() methods  
Two-iteration variables used in dictionaries -> for aaa,bbb in jjj.items(): print(aaa, bbb)  

## Tuples (Chapter 10)  
Tuples are like lists, but they're "immutable"  
Tuple methods (not like lists) count and index - search tuple methods with dir() to find out tuple methods  
Tuples are more efficient in terms of memory use and performance  
Tuples and assignment  
Tuples and Dictionaries - items() method in dictionaries returns a list of tuples (key, value pairs)  
Tuples are Comparable  
Using sorted() for obtaining sorted tuples in a dictionary - t = sorted(d.items())  
Sorting by values instead of key - construct a list of tuples with a form (value, key), reverse assigning with a for loop  
Shorter version with list comprehension - print( sorted[ (v,k) for k,v in c.items() ] )  
Sorting a dictionary using tuples  

## Regular Expressions (Chapter 11)  
Regular Expression Module "import re"  
