# Lesson Notes
## Topic

### Directions
- Read these notes and check out the related resources before you start writing any code for this lesson


### Related Resources
- [Python Strings](https://www.programiz.com/python-programming/string)
- [Python Basics: Strings](https://www.pythontutorial.net/python-basics/python-string/)


### Notes

- It's rare for programmers to use just one type of data -- a single data type -- in their scripts
- Commonly used Python data types include:
  - strings (text data)
  - numeric (such as **floating-point** numbers or **integers**)
  - lists
  - tuples
  - dictionaries
  - Boolean (True or False values)
- The built-in Python `input( )` function always returns a string (text data)
  - To do math when using the `input( )` function, you have to convert the string data the `input( )` function gives you to either a **floating-point** number (by using the `float ( )` function together with the `input ( )` function) OR an integer (using the `int( )` function together with the `input( )` function
  - Example: See the code snippet under [*Type Conversion in Python*](https://www.programiz.com/python-programming/numbers)
  - A *floating-point* number is a number that has a decimal point
  - An *integer* is just a number that DOES NOT have a decimal point (such as 3, 2758, -450, etc.)
 
### Examples

```python
# You can convert string input to a number in one step or in two steps

# Converting string input to numeric data in two steps
age = input ('Please enter your age:\n') # Step 1 is to get the data from the user
age = float(age) # Step 2 is to convert the string input to numeric data (a number)
print(age)
```
```python
# Converting string input to a number in one step
num_inches = float(input('Enter the number of inches to convert to centimeters:\n')) # Getting input and converting string input to a float in one step
num_cm = 2.54 * num_inches
print(f'You have {num_cm} centimeters!')
```
  
