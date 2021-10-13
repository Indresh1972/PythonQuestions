# PythonQuestions

### 1.What are the key features of Python?

Python is one of the most popular programming languages used by data scientists and AIML professionals. This popularity is due to the following key features of Python:

Python is easy to learn due to its clear syntax and readability
Python is easy to interpret, making debugging easy
Python is free and Open-source
It can be used across different languages
It is an object-oriented language which supports concepts of classes
It can be easily integrated with other languages like C++, Java and more

### 2. What are Keywords in Python?
Keywords in Python are reserved words which are used as identifiers, function name or variable name. They help define the structure and syntax of the language.

There are a total of 33 keywords in Python 3.7 which can change in the next version, i.e., Python 3.8. A list of all the keywords is provided below:

Keywords in Python

False	class	finally	is	return
None	continue	for	lambda	try
True	def	from	nonlocal	while
and	del	global	not	with
as	elif	if	or	yield
assert	else	import	pass
break	except


### 3. What are Literals in Python and explain about different Literals?
Literals in Python refer to the data that is given in a variable or constant. Python has various kinds of literals including:

String Literals: It is a sequence of characters enclosed in codes. There can be single, double and triple strings based on the number of quotes used. Character literals are single characters surrounded by single or double-quotes.
Numeric Literals: These are unchangeable kind and belong to three different types – integer, float and complex.
Boolean Literals: They can have either of the two values- True or False which represents ‘1’ and ‘0’ respectively.
Special Literals: Special literals are sued to classify fields that are not created. It is represented by the value ‘none’.
Python Interview Questions PDF


### 4. How can you concatenate two tuples?
Solution ->

    Let’s say we have two tuples like this ->

    tup1 = (1,”a”,True)

    tup2 = (4,5,6)

Concatenation of tuples means that we are adding the elements of one tuple at the end of another tuple.

Now, let’s go ahead and concatenate tuple2 with tuple1:

    Code

    tup1=(1,"a",True)
    tup2=(4,5,6)
    tup1+tup2
    Output


All you have to do is, use the ‘+’ operator between the two tuples and you’ll get the concatenated result.

Similarly, let’s concatenate tuple1 with tuple2:

    Code

    tup1=(1,"a",True)
    tup2=(4,5,6)
    tup2+tup1
    Output


### 5. What are functions in Python?
Ans: Functions in Python refer to blocks that have organised, and reusable codes to perform single, and related events. Functions are important to create better modularity for applications which reuse high degree of coding. Python has a number of built-in functions like print(). However, it also allows you to create user-defined functions.

### 6. What is Pandas?
Pandas is an open source python library which has a very rich set of data structures for data based operations. Pandas with it’s cool features fits in every role of data operation, whether it be academics or solving complex business problems. Pandas can deal with a large variety of files and is one of the most important tools to have a grip on.

### 7. What is a Pandas Series?
Series is a one dimensional pandas data structure which can data of almost any type. It resembles an excel column. It supports multiple operations and is used for single dimensional data operations.

Creating a series from data:

Code

    import pandas as pd
    data=["1",2,"three",4.0]
    series=pd.Series(data)
    print(series)
    print(type(series))

### 8. What is pandas groupby?
A pandas groupby is a feature supported by pandas which is used to split and group an object.  Like the sql/mysql/oracle groupby it used to group data by classes, entities which can be further used for aggregation. A dataframe can be grouped by one or more columns.

Code

    df = pd.DataFrame({'Vehicle':['Etios','Lamborghini','Apache200','Pulsar200'], 'Type':["car","car","motorcycle","motorcycle"]})
    df

### 9. How will you remove duplicate elements from a list?
There are various methods to remove duplicate elements from a list. But, the most common one is, converting the list into a set by using the set() function and using the list() function to convert it back to a list, if required. ex: list0 = [2, 6, 4, 7, 4, 6, 7, 2]
list1 = list(set(list0)) print (“The list without duplicates : ” + str(list1)) o/p: The list without duplicates : [2, 4, 6, 7]

### 10. What is recursion?
Recursion is a function calling itself one or more times in it body. One very important condition a recursive function should have to be used in a program is, it should terminate, else there would be a problem of an infinite loop.

### 11. Explain Python List Comprehension
List comprehensions are used for transforming one list into another list. Elements can be conditionally included in the new list and each element can be transformed as needed. It consists of an expression leading a for clause, enclosed in brackets. for ex: list = [i for i in range(1000)]
print list

### 12. What is the bytes() function?
The bytes() function returns a bytes object. It is used to convert objects into bytes objects, or create empty bytes object of the specified size.

### 13. What are the different types of operators in Python?
Python has the following basic operators:
Arithmetic( Addition(+), Substraction(-), Multiplication(*), Division(/), Modulus(%) ), Relational ( <, >, <=, >=, ==, !=, ),
Assignment ( =. +=, -=, /=, *=, %= ),
Logical ( and, or not ), Membership, Identity, and Bitwise Operators

### 14. What is the ‘with statement’?
“with” statement in python is used in exception handling. A file can be opened and closed while executing a block of code, containing the “with” statement., without using the close() function. It essentially makes the code much more easy to read.

### 15. What is a map() function in Python?
The map() function in Python is used for applying a function on all elements of a specified iterable. It consists of two parameters, function and iterable. The function is taken as an argument and then applied to all the elements of an iterable(passed as the second argument). An object list is returned as a result.

    def add(n):
    return n + n number= (15, 25, 35, 45)
    res= map(add, num)
    print(list(res))
    
    o/p: 30,50,70,90

### 16. What is __init__ in Python?
_init_ methodology is a reserved method in Python aka constructor in OOP. When an object is created from a class and _init_ methodolgy is called to access the class attributes.

### 17. What are the tools present to perform statics analysis?
The two static analysis tool used to find bugs in Python are: Pychecker and Pylint. Pychecker detects bugs from the source code and warns about its style and complexity.While, Pylint checks whether the module matches upto a coding standard.

### 18. What is the difference between tuple and dictionary?
One major difference between a tuple and a dictionary is that dictionary is mutable while a tuple is not. Meaning the content of a dictionary can be changed without changing it’s identity, but in tuple that’s not possible.

### 19. What is pass in Python?
Pass is a statentemen which does nothing when executed. In other words it is a Null statement. This statement is not ignored by the interpreter, but the statement results in no operation. It is used when you do not want any command to execute but a statement is required.

### 20. How can an object be copied in Python?
Not all objects can be copied in Python, but most can. We ca use the “=” operator to copy an obect to a variable.

ex: var=copy.copy(obj)

### 21. How can a number be converted to a string?
The inbuilt function str() can be used to convert a number to a string.

### 22. What are module and package in Python?
Modules are the way to structure a program. Each Python program file is a module, importing other attributes and objects. The folder of a program is a package of modules. A package can have modules or subfolders.

### 23. What is object() function in Python?
In Python the object() function returns an empty object. New properties or methods cannot be added to this object.

### 24. What is the difference between NumPy and SciPy?
NumPy stands for Numerical Python while SciPy stands for Scientific Python. NumPy is the basic library for defining arrays and simple mathematica problems, while SciPy is used for more complex problems like numerical integration and optimization and machine learning and so on.

### 25. What does len() do?
len() is used to determine the length of a string, a list, an array, and so on. ex: str = “greatlearning”
    print(len(str))
    o/p: 13

### 26. Define encapsulation in Python?
Encapsulation means binding the code and the data together. A Python class for example.

### 27. What is the type () in Python?
type() is a built-in method which either returns the type of the object or returns a new type object based on the arguments passed.

    ex: a = 100
    type(a)
    
    o/p: int

### 28. What is split() function used for?
Split function is used to split a string into shorter string using defined seperatos. letters = (” A, B, C”)
    n = text.split(“,”)
    print(n)
    
    o/p: [‘A’, ‘B’, ‘C’ ]

### 29. What are the built-in types does python provide?
Ans. Python has following built-in data types:

Numbers: Python identifies three types of numbers:

Integer: All positive and negative numbers without a fractional part
Float: Any real number with floating-point representation
Complex numbers: A number with a real and imaginary component represented as x+yj. x and y are floats and j is -1(square root of -1 called an imaginary number)
Boolean: The Boolean data type is a data type that has one of two possible values i.e. True or False. Note that ‘T’ and ‘F’ are capital letters.

String: A string value is a collection of one or more characters put in single, double or triple quotes.

List: A list object is an ordered collection of one or more data items which can be of different types, put in square brackets. A list is mutable and thus can be modified, we can add, edit or delete individual elements in a list.

Set: An unordered collection of unique objects enclosed in curly brackets

Frozen set: They are like a set but immutable, which means we cannot modify their values once they are created.

Dictionary: A dictionary object is unordered in which there is a key associated with each value and we can access each value through its key. A collection of such pairs is enclosed in curly brackets. For example {‘First Name’ : ’Tom’ , ’last name’ : ’Hardy’} Note that Number values, strings, and tuple are immutable while as List or Dictionary object are mutable.

### 30. What is docstring in Python?
Ans. Python docstrings are the string literals enclosed in triple quotes that appear right after the definition of a function, method, class, or module. These are generally used to describe the functionality of a particular function, method, class, or module. We can access these docstrings using the __doc__ attribute. Here is an example:

    def square(n):
        '''Takes in a number n, returns the square of n'''
        return n**2
    print(square.__doc__)
    Ouput: Takes in a number n, returns the square of n.
    
### 31. How to Reverse a String in Python?
In Python, there are no in-built functions that help us reverse a string. We need to make use of an array slicing operation for the same.
    
    1
    str_reverse = string[::-1]
    Learn more: How To Reverse a String In Python
