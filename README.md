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

```
