# python

 * What is Python:
   -> Python is a high-level, interpreted, and general-purpose programming language known for its simple syntax and readability.
   -> It is widely used in Web Development, Data Science, Artificial Intelligence, Automation, and Software Development.
   -> Data means information that we store and use in a program.
  * Why Use Python:
   -> Easy to learn and read
   -> Large community support
   -> Used in web development, data science, AI, automation, and more
* Data Types in Python:
 -> Data types define the type of value a variable holds.

    Data Type	       Description    	         Example
    int               Integer numbers           10, -5
    float	           Decimal numbers	       3.14, 2.0
    str	           Text / characters	        "Hello"
    bool	            True or False	          True, False
    list	      Ordered, mutable collection	  [1, 2, 3]
   tuple	      Ordered, immutable collection	  (1, 2, 3)
   set	       Unordered, unique elements	  {1, 2, 3}
   dict	        Key-value pairs	              {"name": "Ram"}
Example:
x = 10          # int
y = 3.5         # float
name = "nayini" # string 

* What are Variables:

-> A variable is used to store data in memory.
-> Python does not require declaring the variable type explicitly.
Example:
a = 10
name = "Python"
a stores 10

* Rules for variable names:
-> Must start with a letter or _
-> Cannot start with a number
-> Case-sensitive (age ≠ Age)
-> No spaces allowed

* Type Conversion (Type Casting):
   -> Type conversion means changing one data type to another.

Example:
a = "10"
b = int(a)   # string to integer
print(b)     #10
* Common conversions:
-> int("5")      # int → float  int → string 
-> float(10)     # float → int float → string
-> str(100)      # string → int string → float

* Operators in Python
-> Arithmetic Operators
Operator	Description	Example
+	       Addition	10 + 5
-	     Subtraction	10 - 5
*	   Multiplication	10 * 5
/	      Division 	10 / 5
%	       Modulus	   10 % 3
**	       Power	   2 ** 3
//	  Floor division	10 // 3
->  Comparison Operators
Operator	 Description
==	       Equal to
!=	       Not equal
>	      Greater than
<	       Less than
>=	     Greater or equal
<=	      Less or equal
-> Logical Operators
Operator	  Description
and	    True if both are true
or     	 True if one is true
not	    Reverses result
-> Assignment Operators
x = 10
x += 5
x -= 2

-> Membership Operators
x = [1, 2, 3]
print(2 in x)
print(5 not in x)

->  Identity Operators
a = 10
b = 10
print(a is b)
print(a is not b)

* Print Statement
 -> Used to display output.
        print("Hello World")
        print("Sum:", 10 + 20)

*Libraries & Modules

Libraries provide reusable code.

import math
print(math.sqrt(16))

import random
print(random.randint(1, 10))

Common Libraries:
-> math
-> random
-> datetime
-> os
-> sys

*Built-in Functions
-> print()
-> len()
-> type()
-> sum()
-> max()
-> min()
-> range()

* String (str):
  
-> A string is a sequence of characters enclosed in single or double quotes.
-> Strings are immutable (cannot be changed).

name = "Python"

* Common String Functions
Function	    Description
len()	     Length of string
upper()	 Convert to uppercase
lower()	 Convert to lowercase
strip()	   Remove spaces
replace()	Replace text
split()	  Split string

text = "hello world"
print(text.upper())
print(text.split())

* List (list)

-> A list is an ordered collection of items.
-> Lists are mutable (changeable).

nums = [1, 2, 3, 4]
*Common List Functions
Function	  Description
append()	  Add element
insert()	  Insert at position
remove()	   Remove element
pop()	    Remove last item
sort()	   Sort list
len()	    Length of list

nums.append(5)
nums.sort()

* Tuple (tuple)
  
-> A tuple is an ordered collection of items.
-> Tuples are immutable.

points = (10, 20, 30)

* Common Tuple Functions
Function	  Description
count()	  Count value
index()	  Find index
len()	     Length of tuple

print(points.count(10))

* Set (set)

-> A set is an unordered collection of unique elements.
-> Sets are mutable but do not allow duplicates.

data = {1, 2, 3}

* Common Set Functions
Function	         Description
add()	            Add element
remove()	         Remove element
union()	         Combine sets
intersection()	   Common elements
len()	             Size of set

data.add(4)

* Dictionary (dict)

-> A dictionary stores data in key–value pairs.
-> Keys are unique and immutable.

student = {"name": "Ram", "age": 20}

* Common Dictionary Functions
Function	     Description
keys()	     Get all keys
values()	    Get all values
items()	    Key-value pairs
get()	       Get value safely
update()	   Update dictionary
len()	       Number of pairs

print(student.get("name"))
student.update({"age": 21})

*Loops

-> Loops are used to repeat a block of code multiple times, reducing repetition and improving efficiency.
* for Loop
-> The for loop is used to iterate over a sequence like a list, tuple, string, or range.

   for i in range(1, 6):
       print(i)

-> Common use cases:
-> Iterating through lists
-> Running code a fixed number of times

* while Loop
-> The while loop runs as long as a condition is true.

i = 1
while i <= 5:
    print(i)
    i += 1

-> Common use cases:
-> When the number of iterations is not known in advance

* Conditional & Control Statements:
  
* Conditional Statements
-> Conditional statements are used to make decisions based on conditions.
->They execute different blocks of code depending on whether a condition is True or False.

-> Types:
   if
   elif 
   if-else

age = 18
if age >= 18:
    print("Eligible")
else:
    print("Not Eligible")
    
* Control Statements

-> Control statements are used to control the flow of execution in a program.
-> They decide how and when loops or statements execute.

-> Types of Control Statements:
   break – exits the loop
   continue – skips the current iteration
   pass – does nothing (placeholder)

for i in range(5):
    if i == 3:
        break
    print(i)

for i in range(5):
    if i == 2:
        continue
    print(i)

if True:
    pass    

* What are Functions?
  
-> A function is a reusable block of code that performs a specific task.
-> A function is a block of code that performs a specific task.
-> Functions improve code reusability, readability, and maintainability.

  *Function syntax:
def function_name(parameters):
  
* Built-in Functions
-> Python provides many built-in functions.

Examples:

print()
len()
type()
sum()
max()
min()

🔹 User-Defined Functions

User-defined functions are created using the def keyword.

Syntax
def function_name(parameters):
    return value

📌 Types of User-Defined Functions
1️⃣ No Arguments, No Return
def greet():
    print("Hello Python")

2️⃣ Arguments, No Return
def add(a, b):
    print(a + b)

3️⃣ No Arguments, With Return
def get_number():
    return 10

4️⃣ Arguments, With Return
def square(n):
    return n * n
