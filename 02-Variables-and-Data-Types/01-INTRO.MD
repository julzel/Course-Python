# Variables and Data Types

In this lesson, we'll dive into the basics of declaring variables in Python and assigning values to them. We'll also explore the different data types that variables can hold, including strings, integers, floats, and booleans.

### Declaring Variables

Variables are used to store data in a Python program. To declare a variable, simply choose a name for the variable and use the assignment operator (=) to assign a value to it. For example:

```python
x = 5
```

In this example, we declare a variable x and assign the value 5 to it. Once a variable is declared, we can use it in our program to reference the value it holds.

### Data Types

In Python, variables can hold different data types, including:

- Strings
- Integers
- Floats
- Booleans

#### Strings

Strings are used to represent text in a Python program. To declare a string variable, enclose the text in either single quotes (`'`) or double quotes (`"`). For example:

```python
name = 'Alice'
```

We can also concatenate strings using the + operator, or access individual characters in a string using indexing. For example:

```python
message = 'Hello, ' + name + '!'
print(message)  # output: Hello, Alice!

first_char = name[0]
print(first_char)  # output: A
```

#### Integers

Integers are whole numbers without any decimal point. To declare an integer variable, simply assign an integer value to a variable. For example:

```python
age = 25
```

We can perform basic mathematical operations on integers using operators such as +, -, \*, and /. For example:

```python
x = 5
y = 3
sum = x + y
diff = x - y
prod = x * y
quot = x / y

print(sum)   # output: 8
print(diff)  # output: 2
print(prod)  # output: 15
print(quot)  # output: 1.6666666666666667
```

#### Floats

Floats are numbers with decimal points. To declare a float variable, simply assign a float value to a variable. For example:

```python
pi = 3.14
```

We can perform basic mathematical operations on floats using the same operators as with integers. For example:

```python
x = 3.5
y = 2.25
sum = x + y
diff = x - y
prod = x * y
quot = x / y

print(sum)   # output: 5.75
print(diff)  # output: 1.25
print(prod)  # output: 7.875
print(quot)  # output: 1.5555555555555556
```

#### Booleans

Booleans are used to represent true/false values. To declare a boolean variable, simply assign either True or False to a variable. For example:

```python
is_student = True
```

We can perform logical operations on booleans using operators such as and, or, and not. For example:

```python
x = True
y = False
z = not x
w = x or y

print(z)  # output: False
print(w)  # output: True
```
