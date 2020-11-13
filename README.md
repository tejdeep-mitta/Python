# Python
python material
Python is a high-level, interpreted, interactive and object-oriented scripting language. Python is designed to be highly readable. It uses English keywords frequently where as other languages use punctuation, and it has fewer syntactical constructions than other languages.

Windows Installation
Here are the steps to install Python on Windows machine.

Open a Web browser and go to https://www.python.org/downloads/.

https://www.python.org/downloads/ 


Follow the link for the Windows installer python-XYZ.msi file where XYZ is the version you need to install.

To use this installer python-XYZ.msi, the Windows system must support Microsoft Installer 2.0. Save the installer file to your local machine and then run it to find out if your machine supports MSI.

Run the downloaded file. This brings up the Python install wizard, which is really easy to use. Just accept the default settings, wait until the install is finished, and you are done.

https://www.python.org/downloads/release/python-314/



Python is Interpreted - Python is processed at runtime by the interpreter. You do not need to compile your program before executing it. This is similar to PERL and PHP.

Python is Interactive - You can actually sit at a Python prompt and interact with the interpreter directly to write your programs.

Python is Object-Oriented - Python supports Object-Oriented style or technique of programming that encapsulates code within objects.

Python is a Beginner's Language - Python is a great language for the beginner-level programmers and supports the development of a wide range of applications from simple text processing to WWW browsers to games.

Python Features
Python's features include -

Easy-to-learn - Python has few keywords, simple structure, and a clearly defined syntax. This allows the student to pick up the language quickly.

Easy-to-read - Python code is more clearly defined and visible to the eyes.

Easy-to-maintain - Python's source code is fairly easy-to-maintain.

A broad standard library - Python's bulk of the library is very portable and cross-platform compatible on UNIX, Windows, and Macintosh.

Interactive Mode - Python has support for an interactive mode which allows interactive testing and debugging of snippets of code.

Portable - Python can run on a wide variety of hardware platforms and has the same interface on all platforms.

Extendable - You can add low-level modules to the Python interpreter. These modules enable programmers to add to or customize their tools to be more efficient.

Databases - Python provides interfaces to all major commercial databases.

GUI Programming - Python supports GUI applications that can be created and ported to many system calls, libraries and windows systems, such as Windows MFC, Macintosh, and the X Window system of Unix.

Scalable - Python provides a better structure and support for large programs than shell scripting.

Apart from the above-mentioned features, Python has a big list of good features, few are listed below -

It supports functional and structured programming methods as well as OOP.

It can be used as a scripting language or can be compiled to byte-code for building large applications.

It provides very high-level dynamic data types and supports dynamic type checking.

var a="hello"

a=120
b="10"

a+b;


It supports automatic garbage collection.

It can be easily integrated with C, C++, COM, ActiveX, CORBA, and Java.

Python Application:

console--- text based application  DOS os 
GUI
Web 
enterprise application
3D CAD application
Audio /Video based application
Bussiness Application 


Data Types
======================
String 
Number
List
Tuple
Set  
Dictionary
==========================
Built-in List Functions & Methods[]
Python includes the following list functions -

Sr.No.	Function with Description
1	cmp(list1, list2)
Compares elements of both lists.

2	len(list)
Gives the total length of the list.

3	max(list)
Returns item from the list with max value.

4	min(list)
Returns item from the list with min value.

5	list(seq)
Converts a tuple into list.

Python includes following list methods

Sr.No.	Methods with Description
1	list.append(obj)
Appends object obj to list

2	list.count(obj)
Returns count of how many times obj occurs in list

3	list.extend(seq)
Appends the contents of seq to list

4	list.index(obj)
Returns the lowest index in list that obj appears

5	list.insert(index, obj)
Inserts object obj into list at offset index

6	list.pop(obj=list[-1])
Removes and returns last object or obj from list

7	list.remove(obj)
Removes object obj from list

8	list.reverse()
Reverses objects of list in place

9	list.sort([func])
Sorts objects of list, use compare func if given


A tuple is a collection of objects which ordered and immutable. Tuples are sequences, just like lists. The differences between tuples and lists are, the tuples cannot be changed unlike lists and tuples use parentheses, whereas lists use square brackets.
()
Built-in Tuple Functions
Python includes the following tuple functions -

Sr.No.	Function with Description
1	cmp(tuple1, tuple2)
Compares elements of both tuples.

2	len(tuple)
Gives the total length of the tuple.

3	max(tuple)
Returns item from the tuple with max value.

4	min(tuple)
Returns item from the tuple with min value.

5	tuple(seq)
Converts a list into tuple.


Python Set
A Python set is the collection of the unordered items. Each element in the set must be unique, immutable, and the sets remove the duplicate elements. Sets are mutable which means we can modify it after its creation.
{}
Set Operations:

Union of two Sets
Example 1: using union | operator
Days1 = {"Monday","Tuesday","Wednesday","Thursday", "Sunday"}    
Days2 = {"Friday","Saturday","Sunday"}    
print(Days1|Days2) #printing the union of the sets   

Example 2: using union() method

Days1 = {"Monday","Tuesday","Wednesday","Thursday"}    
Days2 = {"Friday","Saturday","Sunday"}    
print(Days1.union(Days2)) #printing the union of the sets   

Intersection of two sets
Example 1: Using & operator

Days1 = {"Monday","Tuesday", "Wednesday", "Thursday"}    
Days2 = {"Monday","Tuesday","Sunday", "Friday"}    
print(Days1&Days2) #prints the intersection of the two sets    

Example 2: Using intersection() method

set1 = {"Devansh","John", "David", "Martin"}    
set2 = {"Steve", "Milan", "David", "Martin"}    
print(set1.intersection(set2)) #prints the intersection of the two sets   

Difference between the two sets
Example 1 : Using subtraction ( - ) operator

Days1 = {"Monday",  "Tuesday", "Wednesday", "Thursday"}    
Days2 = {"Monday", "Tuesday", "Sunday"}    
print(Days1-Days2) #{"Wednesday", "Thursday" will be printed}   

Example 2 : Using difference() method

Days1 = {"Monday",  "Tuesday", "Wednesday", "Thursday"}    
Days2 = {"Monday", "Tuesday", "Sunday"}    
print(Days1.difference(Days2)) # prints the difference of the two sets Days1 and Days2 


Symmetric Difference of two sets
The symmetric difference of two sets is calculated by ^ operator or symmetric_difference() method. Symmetric difference of sets, it removes that element which is present in both sets. Consider the following example:xample - 1: Using ^ operator

a = {1,2,3,4,5,6}  
b = {1,2,9,8,10}  
c = a^b  
print(c)  
Output:

{3, 4, 5, 6, 8, 9, 10}
Example - 2: Using symmetric_difference() method

a = {1,2,3,4,5,6}  
b = {1,2,9,8,10}  
c = a.symmetric_difference(b)  
print(c)  
Python Built-in set methods
Python contains the following methods to be used with the sets.

SN	Method	Description
1	add(item)	It adds an item to the set. It has no effect if the item is already present in the set.
2	clear()	It deletes all the items from the set.
3	copy()	It returns a shallow copy of the set.
4	difference_update(....)	It modifies this set by removing all the items that are also present in the specified sets.
5	discard(item)	It removes the specified item from the set.
6	intersection()	It returns a new set that contains only the common elements of both the sets. (all the sets if more than two are specified).
7	intersection_update(....)	It removes the items from the original set that are not present in both the sets (all the sets if more than one are specified).
8	Isdisjoint(....)	Return True if two sets have a null intersection.
9	Issubset(....)	Report whether another set contains this set.
10	Issuperset(....)	Report whether this set contains another set.
11	pop()	Remove and return an arbitrary set element that is the last element of the set. Raises KeyError if the set is empty.
12	remove(item)	Remove an element from a set; it must be a member. If the element is not a member, raise a KeyError.
13	symmetric_difference(....)	Remove an element from a set; it must be a member. If the element is not a member, raise a KeyError.
14	symmetric_difference_update(....)	Update a set with the symmetric difference of itself and another.
15	union(....)	Return the union of sets as a new set.
(i.e. all elements that are in either set.)
16	update()	Update a set with the union of itself and others.  

Python Dictionary is used to store the data in a key-value pair format. The dictionary is the data type in Python, which can simulate the real-life data arrangement where some specific value exists for some particular key. It is the mutable data-structure. The dictionary is defined into element Keys and values.

Keys must be a single element
Value can be any type such as list, tuple, integer, etc.

Creating Functions:

Python Function
Functions are the most important aspect of an application. A function can be defined as the organized block of reusable code, which can be called whenever required.

Python allows us to divide a large program into the basic building blocks known as a function. The function contains the set of programming statements enclosed by {}. A function can be called multiple times to provide reusability and modularity to the Python program.

The Function helps to programmer to break the program into the smaller part. It organizes the code very effectively and avoids the repetition of the code. As the program grows, function makes the program more organized.


Python provide us various inbuilt functions like range() or print(). Although, the user can create its functions, which can be called user-defined functions.

There are mainly two types of functions.

User-define functions - The user-defined functions are those define by the user to perform the specific task.
Built-in functions - The built-in functions are those functions that are pre-defined in Python.

Syntax:

def my_function(parameters):  
      function_block  
return expression  

Python File Handling:
a file operation can be done in the following order.

Open a file
Read or write - Performing operation
Close the file

Syntax:

file object = open(<file-name>, <access-mode>, <buffering>)     
r-read

rb-It opens the file to read-only in binary format

r+-It opens the file to read and write both.

rb+--It opens the file to read and write both in binary format.

w-It opens the file to write only. It overwrites the file if previously exists or creates a new one if no file exists with the same name.

wb-write binary

w+-It opens the file to write and read both. It is different from r+ in the sense that it overwrites the previous file if one exists whereas r+ doesn't overwrite the previously written file. It creates a new file if no file exists. The file pointer exists at the beginning of the file.

wb+-It opens the file to write and read both in binary format. 
a--append 
ab--It opens the file in the append mode in binary format



fo = open("foo.txt", "wb")
print "Name of the file: ", fo.name
print "Closed or not : ", fo.closed
print "Opening mode : ", fo.mode
print "Softspace flag : ", fo.softspace
fo.close

Syntax
fileObject.write(string)
Here, passed parameter is the content to be written into the opened file.



# Open a file
fo = open("foo.txt", "wb")
fo.write( "Python is a great language.\nYeah its great!!\n")

# Close opend file
fo.close()


Syntax
fileObject.read([count])
Here, passed parameter is the number of bytes to be read from the opened file. This method starts reading from the beginning of the file and if count is missing, then it tries to read as much as possible, maybe until the end of file.

Example
Let's take a file foo.txt, which we created above.


# Open a file
fo = open("foo.txt", "r+")
str = fo.read(10);
print "Read String is : ", str
# Close opend file
fo.close()


Run time error

syntax
logic

Exception Handling:
Syntax
Here is simple syntax of try....except...else blocks -

try:
   You do your operations here;
   ......................
except ExceptionI:
   If there is ExceptionI, then execute this block.
except ExceptionII:
   If there is ExceptionII, then execute this block.
   ......................
else:
   If there is no exception then execute this block. 

List of Standard Exceptions -

Sr.No.	Exception Name & Description
1	
Exception

Base class for all exceptions

2	
StopIteration

Raised when the next() method of an iterator does not point to any object.

3	
SystemExit

Raised by the sys.exit() function.

4	
StandardError

Base class for all built-in exceptions except StopIteration and SystemExit.

5	
ArithmeticError

Base class for all errors that occur for numeric calculation.

6	
OverflowError

Raised when a calculation exceeds maximum limit for a numeric type.

7	
FloatingPointError

Raised when a floating point calculation fails.

8	
ZeroDivisionError

Raised when division or modulo by zero takes place for all numeric types.

9	
AssertionError

Raised in case of failure of the Assert statement.

10	
AttributeError

Raised in case of failure of attribute reference or assignment.

11	
EOFError

Raised when there is no input from either the raw_input() or input() function and the end of file is reached.

12	
ImportError

Raised when an import statement fails.

13	
KeyboardInterrupt

Raised when the user interrupts program execution, usually by pressing Ctrl+c.

14	
LookupError

Base class for all lookup errors.

15	
IndexError

Raised when an index is not found in a sequence.

16	
KeyError

Raised when the specified key is not found in the dictionary.

17	
NameError

Raised when an identifier is not found in the local or global namespace.

18	
UnboundLocalError

Raised when trying to access a local variable in a function or method but no value has been assigned to it.

19	
EnvironmentError

Base class for all exceptions that occur outside the Python environment.

20	
IOError

Raised when an input/ output operation fails, such as the print statement or the open() function when trying to open a file that does not exist.

21	
IOError

Raised for operating system-related errors.

22	
SyntaxError

Raised when there is an error in Python syntax.

23	
IndentationError

Raised when indentation is not specified properly.

24	
SystemError

Raised when the interpreter finds an internal problem, but when this error is encountered the Python interpreter does not exit.

The except Clause with No Exceptions
You can also use the except statement with no exceptions defined as follows -
try:
   You do your operations here;
   ......................
except ExceptionI:
   If there is ExceptionI, then execute this block.
except ExceptionII:
   If there is ExceptionII, then execute this block.
   ......................
else:
   If there is no exception then execute this block. 




try:
   You do your operations here;
   ......................
except:
   If there is any exception, then execute this block.
   ......................
else:
   If there is no exception then execute this block. 


try:
   You do your operations here;
   ......................
except(Exception1[, Exception2[,...ExceptionN]]]):
   If there is any exception from the given exception list, 
   then execute this block.
   ......................
else:
   If there is no exception then execute this block. 


try:
   You do your operations here;
   ......................
   Due to any exception, this may be skipped.
finally:
   This would always be executed.

Iterator and genrator



