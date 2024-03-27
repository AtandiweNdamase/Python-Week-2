# Python-Week-2
Functions:
are composed of a name and parameters which is declared by a If statment 
Named parameters are named operations to use to shorten code 
Keyword arguments must come after positional arguments 
order of first two arguments is important and atfter that the keyword arguments can be in any order
If users want to pass in numerous variables they  use the astrisk (*args) short for arguments 
Keyword arguments are handled by a method called (*Kwargs) keyword arguments are stored as dictionary and not tuple( kwargs have keys and values that can be passed in any order make it appropriate  for deictionary )
Variables and Scope:
Locals function allows us access to varibales in python
Global functions allow us access to variables outside fdefined functions 
When python looks up local funtions it reads the local variables then the global
Variables as function:
the 'code ' function in python can be used to confirm that functions are just variables
Lambda functions are handy to pass other python functions 
Anatomy of a class :
Classes have attributes
static varibles are defined outside the constructor, sattic varibles can still be changed  programmers put an underscore before the variable name to inidicate that if should not be modified  direclty 
Class inheritence:
it possible for one class to inhert all the attributes and variables of another class
the original class will bbe refered to as a parent class, if a child class has a class with same attribute as the parent class the childs class will overide the parent class
list is actually a class in python
super() is used to call a instance of a parent class
Handling Errors:
Exceptions can be seen/determined during runtime and can be retried unlike errors , but alll in all errors and exceptions belong to the base class exception 
Finally will always execute irregardless of an exception 
rising error 
Customs Exceptions:
Threading:
The operating system is responsible for allocating memory to each process running on the computer.it put walls between the processes so they cannot access each others memeory.
We can move two pieces of code into the same process , this way they get to share memory, we can run them in parallel at the same time they run in separate threads (import threads)
Multiprocessig
proess does not share memory (import multiprocesses)
good way to collect output from multiple processes is writing results to file
processes can have multiple threads
Working with files:
python cannot read or edit a file if it is being used in
Write files :
f.realine('line1/n') when you run the code you get a different line so this object contains some sort of bookmark of whivh lines of the file are already read.
f.readlines() is used to read all the lines of the file
Appending files 
close file by f.close(), then reopem to to see all written lines
CSV 
import csv
to write row in csv, writer.writerow
change commas to spaces by using delimiter'\t'
next() used to skip 
Filtering Data:
JSON , a Json string is a string . in order to change the string to a dictionary we need input import json 
passing a json string into a python object involves json.loads
Dumping Json :


