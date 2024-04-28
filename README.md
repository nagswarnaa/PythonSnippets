# Important Python Snippets For Competetive Coding 

### Type-Conversions, Assignments

```python
# Initial Assignment and Print
n = 1
print(n)

# Re-assigning to a String
n = "123"

# Converting to Integer
n = int(n)
print(type(n))  # Should output: <class 'int'>

# Converting Integer to String
n = str(n)
print(type(n))  # Should output: <class 'str'>

# Converting String to Floating Point
n = "1.23"
n = float(n)
print(type(n))  # Should output: <class 'float'>

# Converting Floating Point to Integer
n = 1.23
n = int(n)
print(n)  # Should output: 1

# Multi Assignment
x, y = 1, 2

# Unpacking
x, y = [1, 2]

# Increment Operation
n = 1
n += 1
print(n)  # Corrected to print the value of n

# Converting Boolean to Integer
b = True
print(int(b))  # Should output: 1

# Converting Integer to Boolean
i = 0
print(bool(i))  # Should output: False

# Check and Convert Boolean
n = ""
print(bool(n))  # Should output: False (empty string is considered False)

# Converting Boolean to String
b = True
print(str(b))  # Should output: 'True'

#Global Varibales
def declare_global():
    global new_global_variable
    new_global_variable = "Declared and modified globally."

declare_global()
print(new_global_variable)  # This will print: Declared and modified globally.


```
## Conditional statements

```
# Example 1: Basic if statement
x = 5
if x > 0:
    print("x is positive")

# Example 2: if-else statement
y = -5
if y > 0:
    print("y is positive")
else:
    print("y is not positive")

# Example 3: elif statement
z = 0
if z > 0:
    print("z is positive")
elif z == 0:
    print("z is zero")
else:
    print("z is negative")

# Example 4: Nested if statements
a = 10
b = 20
if a < b:
    print("a is less than b")
    if a == 10:
        print("a is 10")

# Example 5: if with logical operators
a = 10
b = 5
if a > 0 and b > 0:
    print("Both a and b are positive")

# Example 6: if with comparison operators
if a >= b:
    print("a is greater than or equal to b")

# Example 7: Using if with lists
my_list = [1, 2, 3]
if 2 in my_list:
    print("2 is in the list")

# Example 8: Using if with dictionaries
my_dict = {'name': 'Alice', 'age': 25}
if 'name' in my_dict:
    print("name is a key in the dictionary")

# Example 9: One-line if statement
if a > b: print("a is greater than b")

# Example 10: Conditional expression (ternary operator)
result = "a is greater than b" if a > b else "b is greater than or equal to a"
print(result)

```
