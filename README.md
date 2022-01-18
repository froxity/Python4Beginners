# Introduction
This guidlines for beginners to start with python along with examples.
You can checkout the youtube video explaining coding process: [Python for Beginners - Learn Python in 1 Hour](https://www.youtube.com/watch?v=kqtD5dpn9C8&ab_channel=ProgrammingwithMosh).

Below is source code and exercise that has been explained inside the [video](https://www.youtube.com/watch?v=kqtD5dpn9C8&ab_channel=ProgrammingwithMosh).

## Get started

### Output value using print(value)
```python
print("Hello World")
```
Terminal output:
```
Hello World
```
### Variable
- We check in a patient named John Smith.
- He is 20 years old.
- He is new patient.
```python
name = "John Smith" #string variable
age = 20 #integer variable
patient = True #boolean variable (it can False)
```
### Receiving Input
```python
name = input("What is your name? ")
print("Hello " + name)
```
Terminal Output:
```
What is your name? Mosh
Hello Mosh
```
### Type Conversion

We have multiple type of conversion

 - str() : Change value to string
 - int() : Change value to integer
 - float() : Change value to decimal/floating point
 - bool() : Change value boolean type

```python
birth_year = input("Enter your birth year: ")
age = 2022 - int(birth_year)
print(age)
``` 
Terminal Output:
```
Enter your birth year: 1982
38
```
Another example:-
```python
# First method
first = input("First: ")
second = input("Second : ")
sum = float(first) + float(second)

# Second method
first = float(input("First: "))
second = float(input("Second : "))
sum = first + second
print("Sum: " + str(sum))
``` 
Terminal Output:
```
First: 10.1
Second: 20
Sum: 30.1
```
### String modification
```python
course = 'Python for Beginners'
print(course.upper())
print(course)
```
Terminal Output:
```
PYTHON FOR BEGINNERS
Python for Beginners
```
