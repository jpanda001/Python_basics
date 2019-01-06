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
