# The Python Technical Test

lets start,

#### INTRO
Hello and welcome to DellEMC  assignment.
In this assignment you will be asked to complete the python test

### Python test:
#### Variables, Types and Data structures:
1. How do you create a variable in Python?
a. int x=5
b. x=5
c. x is 5
2. how do you declare a variable in Python
a. int x;
b. I have x
c. x
d. Python has no command for declaring a variable
3. Which of the following are Primitive Data structures?:
• Integer
• List
• Tuple
• Boolean
• Dictionary
4. Which of the following are Non-Primitive Data structures?:
• Integer
• List
• Tuple
• Boolean
• Dictionary
5. What will be the output of the following codes (try to answer without actually run it) • x = 5 print(type(x)) • x = "hi" print(type(x))
#### Functions:
1. how do you define a function in python?
a. def my_function():
b. public my_function()
c. function my_function():
d. my_function()=
2. Lets say we have a function book_hotel(name,number_of_rooms) which reserve number_of_rooms rooms under the given name. we found out that most people order just one room. Change the function signature so the default value of number_of_rooms will be 1. How should I call the function now, if I want only one room ? (you can write your name in the name argument).
3. What can be a valid return value of a function (select all correct answers)?
a. Number\integer
b. String
c. List
d. Tuple
e. Function
f. Object
#### Lists and Tuples
1. Write a function remove_duplicate(list) that receives a list and returns a new list that contains all
the elements of the first list without duplicates.
2. Given a list, check if “Moshe” is in the list, if it is – remove “Moshe” from the list, else- add
“Moshe” to the list.
3. Write a function “remove_ boundaries(list)” which receives a list and checks- if the list contains
less then three elements, the function will print :”not enough element in the list” . else, the
function returns a new list that contains all the elements of the first list without first and last
element ( the return statement should be written in one line).
4. Mark the right answers: what is the difference between Lists and tuples (there may be more than
one answer):
a. Tuple is mutable while List is immutable
b. List is mutable while Tuple is immutable
c. Tuple written with [] while string with ()
d. Tuple written with () while string with []
Dictionaries:
1. Which of the following are true of Python dictionaries:
a. Items are accessed by their position in a dictionary.
b. Dictionaries are accessed by key.
c. A dictionary can contain any object type except another dictionary.
d. Dictionaries can be nested to any depth.
e. All the keys in a dictionary must be of the same type.
f. Dictionaries are mutable.
2. Write a function switch_keys_values(dict) that receives a dictionary and replaces between keys
and values. If there are more than one key with the same value, there will be one key with list of
values. For example : for the dictionary : dict={'foo':1,'bar':2, 'baz’: 3, 'goo':1}
switch_keys_values(dict) will return {1: [‘foo’, ’goo’],2:‘bar’,'baz':3}
Loops:
1. Print all odd number between 3 to 21 , meaning (3,5,7,…). This should be done in one line and not
hard-coded (e.g do not write print(3,5,7,..)).
2. Write a function find_Moshe(students) that receives a list of students names, for each student in
students the function checks whether the student name is Moshe, if it isn’t Moshe print “isn’t
Moshe” and if it is Moshe will prints :”Found Moshe!” and quit.
3. Write a function ignore_Moshe_and_Haim(students) that receives a list of students names, for
each student except Moshe and Haim, the function prints the student name. if the student name
is Moshe or Haim – just ignore and continue.
4. Write a function my_range(num) which prints all the number between 0 to num. in the function
you are not allow to use the build-in function range(), hint: you should use a while loop.
#### Handle Exceptions:
1. If we ran the following code:
students=[{"fisrt_name":"Bar","last_name":"Refaeli"},{"first_name":"Madona"}]
for student in students:
print(student["last_name"])
we got the following output:
Refaeli
Traceback (most recent call last):
File "main.py", line 3, in <module>
print(student["last_name"])
KeyError: 'last_name'
Fix the code to handle KeyError error- so if the student doesn’t have last name
it should print: “student < first_name> doesn’t have last name!” without
throwing any exceptions.
2. If we ran the following code:
def Dell_concate(first,second):
print( first+second)
Dell_concate("Dell","EMC")
Dell_concate(1,"One")
we got the following output:
DellEMC
Traceback (most recent call last):
File "main.py", line 5, in <module>
Dell_concate(1,"One")
File "main.py", line 2, in Dell_concate
print( first+second)
TypeError: unsupported operand type(s) for +: 'int' and 'str'
Fix the code to handle erroes: in case of TypeError error-print “cannot concate
this two types” in case of other exception print “Unknown Error!”.
#### IO operations
1. Create (manually, not in code) a text file with the sentence “Hello” inside .
Create a function add_my_name(name) which open the file and write the name in the file. If
the there was some error you should print “failed to add name” (use what you learn in
handling exceptions).
2. Now create a function read_file() that reads the file you created . If the there was some error
you should print “failed to read file”
Pay attention! – in both sections don’t forget to close the file when you finish, you should set permission
so you can write to file or if it is only for reading .
3. Add code that ask from the user is name and id in print : “name : <name> ,id:<id>”
#### Lamba expression :
1. Write the following code as lambda expression :
def triple(num):
return num*3
2. What is true Lambda expression (more than one answer):
a. lambda function is a small anonymous function.
b. Lambda is a build-in function that make the code cleaner.
c. lambda function can take any number of arguments, but can only have one expression.
#### Class:
1. Build a class name Employee. Each employee has it’s name and worker_id (i.e. its attributes).
In addition . Add a method print_emp_details() to the employee which prints the employee
details. For example the following code:
p1 = Employee("John", 1234)
p1.print_emp_details()
will output:
worker name: John , worker id:1234
2. Take the class you built in section 1, and add a new method : change_name(new_name).
Which change the name of the worker to be new_name.
#### Modules:
1. Why do we want to split our code to modules? Circle the correct answers:
a. The code looks cleaner.
b. You must separate between
c. Easier maintenance.
d. Better performances.
e. You must define classes in different part than main.
2. take all the code you wrote and separates it to modules in the following way:
a. creates 2 modules : main, employee.
b. In employee define the class Employee from the previews section .
c. In main – add list of employee. Creates 2 employees- Ron with worker id-123 and
Harry with worker id-456.
Print both Ron and Harry details in main.
Comments and Documenting Your code:
In the code you wrote in the preview section (Modules) – add comment to the main and Employee
module if you feel like is needed. In addition use docstring in the begging of the employee class
to describe and document the class (for example- which attributes and methods the class has,
and describe the methods).
#### Decorator :
1. What does decorators do?
a. Decorators decorate the code , make it cleaner.
b. Decorators wrap a function, modifying its behavior.
c. Decorator is a class represent the main function.
2. Follow the instructions:
a. Create function my_func() which prints “this is my function!”
b. Create a decoration that wrap my_func() and print “before my function” before calling
my_func() and prints “after my function” after.
3. Change the decoration from the preview section to run my_func() twice.
4. Follow the instructions:
a. Create function say_hi(name) which prints “HI <name>!” for example say_hi(“dan”) will
print “Hi dan!”
b. Create a decoration that wrap my_ say_hi (name) and print “prepare to say hi” before
calling my_func() and prints “Bye” after.
• Pay attention! – you should take in mind you need to pass the name variable.


#### Deliverables
A GitHub Pull-Request to **YOUR DUPLICATED REPO**, containing all the scripts mentioned above with the solutions to the exercises.
PLEASE make sure your Pull Request contains all the requirements above.

#### General Guidelines
Your code should be as simple as possible.
Your code should be tested by running "vagrant destroy" and "vagrant up" and see all fixes and tasks are implemented.

