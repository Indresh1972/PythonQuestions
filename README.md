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

### 9. What is Pandas?
Pandas is an open source python library which has a very rich set of data structures for data based operations. Pandas with it’s cool features fits in every role of data operation, whether it be academics or solving complex business problems. Pandas can deal with a large variety of files and is one of the most important tools to have a grip on.

### 11. What is a Pandas Series?
Series is a one dimensional pandas data structure which can data of almost any type. It resembles an excel column. It supports multiple operations and is used for single dimensional data operations.

Creating a series from data:

Code

    import pandas as pd
    data=["1",2,"three",4.0]
    series=pd.Series(data)
    print(series)
    print(type(series))

### 12. What is pandas groupby?
A pandas groupby is a feature supported by pandas which is used to split and group an object.  Like the sql/mysql/oracle groupby it used to group data by classes, entities which can be further used for aggregation. A dataframe can be grouped by one or more columns.

Code

    df = pd.DataFrame({'Vehicle':['Etios','Lamborghini','Apache200','Pulsar200'], 'Type':["car","car","motorcycle","motorcycle"]})
    df
