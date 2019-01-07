# Commonly used syntax for Python
1. To print something in the console use:
```python
print "Hello world"
```
This line prints the string "Hello world" in the console
This statement works only for Python 2
For python 3, print statement can be written as follows:
```python
print ("Hello World")
```
2. Defining variables in python:
```python
date1 = "June 28, 2020"
date2 = 28
date3 = True
```
Variables can be defined without having to mention their type (int, string, Boolean, etc...)

3. Arithmetic operators such as '+', '-', '\*', '/' and '%' can be used in python. Following line of code shows an implemenation of a combination of these operators:
```python
oper = 2*3/4
modulo = 234 % 2
```
modulo operator '%' in the statement above finds the remainder when 234 is divided by 2

4. Comments can be added using the '\#' prefix:
```python
city_name = "St. Potatosburg"
#blah
```
5. Basic arithmetic operations as shown in point 3 generate int results. to generate results as float use the argument float() or '.' as follows:
```python
float_result = float(9)/2
float_result = 9./2
```
6. To concat two different data type convert all data types to single form using functions str(), float(), int(), etc... as follows:
```python
same_data_type = "hello I'm number " + str(2) + " in string"
```
# Working with strings, list and consoles

1. When writing a string with "...'... ", to prevent premature end of the string use '\' operator as follows:
```python
my_String = 'There's a snake in my boot!'
#printing the string above would generate an error. So, use the following form instead
my_String = 'There\'s a snake in my boot!'
#printing this would generate no error
```
2. Access certain elements in a string using the following statement:
```python
str_element = "Names!"[5]
#the statement above capture the last element of the string "Names!"
```

3. Following functions enable you to do certain tasks with strings:
```python
str = "Names"
len(str) # gives the length of the string
str.upper() # converts the string to all uppercase
str.lower() # coverts the string to all lowercase
str(2000) # converts int 2000 to string
```

4. String can be formatter dynamically using operators like %s and %02d as shown below:
```python
number = 2
print "the number we are looking for is %s" %(number)
```
5. Information can be received from the console using 'raw_input()'
```python
name = raw_input("What is your name? ")
quest = raw_input("What is your quest? ")
color = raw_input("What is your favorite color? ")

print "Ah, so your name is %s, your quest is %s, " \
"and your favorite color is %s." % (name, quest, color)
```
# Working with Lists, For and While loops

1. Numerous operators can be used while dealing with lists as used in the code snippet below:
```python
mylist = [a, a, b]
#or
mylist = [a]*2 + [b]
#linearly traversing a list
#common way
for x in range(0, len(mylist)):
  if mylist[x] = 'a':
    return True
#or
for x in mylist:
  if x == 'a':
    return True
```

2. Following is the way to implement a while loop in python:
```python
while a<6:
  print "running"
```

Reference: http://interactivepython.org/runestone/static/pythonds/AlgorithmAnalysis/Dictionaries.html
