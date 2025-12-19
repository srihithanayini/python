# python

 * What is Python:
   -> Data means information that we store and use in a program.
  * Why Use Python?
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

* What are Functions?
  
  A function is a block of code that performs a specific task.
  functions are 2 types.they are
  1)Built in functions
  2)user defined functions
  *Function syntax:
def function_name(parameters):
    # code
    return value

Built-in Functions:

print("Hello")
len("Python")
type(10)
User-Defined Function:

You can create your own function using def.

def add(a, b):
    return a + b

print(add(3, 5))
