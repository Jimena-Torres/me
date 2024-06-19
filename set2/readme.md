TODO: Reflect on what you learned this week and what is still unclear.
ctrl + to open the terminal

concatinate means to join together not to multiply/ or add/ together

COMMENTS
to declare a line is a comments i have to start with #. Commenting lets me put notes in my code/doc
Comments can be placed at the end of a line, and Python will ignore the rest of the line
I can put multiple comments and python will ignore them

INDENTATION
Print- when I type print leave a space (indentation) and use () and put what I want to print in the brackets with " "
e.g
if 5>2
print("YES")

put a space before print otherwise it will not work
i have to use the same number of spaces in the same block of code or it will be an error

VALUES
there're 4 different types of value

1. Integer: counting number (0,5,-4,100)
2. Float: real Number (decimal number)
3. Boolean: answer to a logical question (True, False)
4. String: text or thing to be treated as text "hello world" "dave"

# string can be declared with either single or double qoutes " " or ' '

VARIABLES
e.g my_variable = 42

my_variable is just the variable name. It's how we'll access this variable from now on
= this is the assignment operator it pulls the value into the variable
42 this is a value

A variable is created the moment you first assign a value to it.
e.g
x= "5"
y= "John"
print(x)
print (y)

Variable Rules
A variable name must start with a letter or the underscore character
A variable name cannot start with a number
A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and \_ )
Variable names are case-sensitive (age, Age and AGE are three different variables)

e.g. variable names

myvar = "John"
my_var = "John"
\_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"

#only numbers, letters, underscores, no spaces, no other signs

ASSING VALUES TO MULTIPLE VARIABLES IN ONE LINE
e.g
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)

or

assign the ONE/same value to multiple variables in one line:

x = y = z = "Orange"
print(x)
print(y)
print(z)

HOW TO UNPACK A COLLECTION

when I have a collection of values in a list, tuple, dictionary, ect. I can extract the values into their own variable.

e.g.

fruits = ["apple", "banana", "cherry"] #collection of values in a list
x, y, z = fruits #unpacking
print(x)
print(y)
print(z)

Output Variables

# can't use mathematical symbols with different value types

# But I can output different value types with ,

e.g
x = 5
y = 10
print(x + y) # Correct

x = "Python "
y = "is "
z = "awesome"
print(x + y + z) #Correct

x = 5
y = "John"
print(x + y) # ERROR

x = 5
y = "John"
print(x, y) # CORRECT

CASTING
casting is for specifying the data type of a variable
e.g

x = str(3) # x will be '3'
y = int(3) # y will be 3
z = float(3) # z will be 3.0

HOW TO GET THE TYPE OF VARIABLE
the data type of a variable is given back with the type() function

e.g
x = 5
y = "John"
print(type(x))
print(type(y))

The Case Matters (Lowercase & uppercase)

Variable names are case-sensitive.
e.g

a = 4
A = "Sally"

print (a)
print (A)

#these are not the same a=4 is a separate variable to A = 'Sally'

FUNCTIONS:
function is defined using the def
To call a function, type function name followed by parenthesis and double dots
e.g def my_name():

ARGUMENTS:
Information can be passed into functions as arguments

Arguments are specified after the function name, inside the parentheses. There is no limit to the number of arguments that can be passed into the function

def my_name(fname):
print (fname)

my_name("Lucy")
my_name("Pete")

When I call my_name , the names I typed will be replied

REFLECTION:
had trouble with conditional statements

RESEARCH - CONDITIONAL STATEMENTS

Equals: a == b
Not Equals: a != b
Less than: a < b
Less than or equal to: a <= b
Greater than: a > b
Greater than or equal to: a >= b

if statements arw written using the 'if' keyword

lists = []
dictionary: {}
key:value

[{},{},{}]

1: chocolate
]

[{key:value}]
[{1:choco}]

[[(),(),(),()]

    "(i0, j0)"

# = ("i[], j[]").format.(0)

# output would be = i0,j0

    "(i + (i) + ", j" + (j))"

.format(i,j) = Formats specified values in a string

("Jim has [] cats.".format(3))

# this will print jim has 3 cats

# [] is the placeholder

loop_7
(4-i) x [-] + (2i+1) x [*]
