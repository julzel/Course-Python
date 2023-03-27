# Strings

In Python, strings are used to represent text data. They can be declared by enclosing the text in either single quotes (') or double quotes ("). For example:

```python
name = 'Alice'
greeting = "Hello, world!"
```

Once a string is declared, we can perform a variety of operations on it.

### Concatenation

One common operation on strings is concatenation, which is the process of joining two or more strings together. This can be done using the + operator. For example:

```python
first_name = 'Alice'
last_name = 'Smith'

full_name = first_name + ' ' + last_name
print(full_name)  # output: Alice Smith
```

### String Methods

Python provides a number of built-in methods for working with strings. Here are some commonly used string methods:

#### `len()`

The `len()` method returns the length of a string. For example:

```python
message = 'Hello, world!'
print(len(message))  # output: 13
```

#### `lower()` and `upper()`

The `lower()` method returns a string with all lowercase letters, while the `upper()` method returns a string with all uppercase letters. For example:

```python
name = 'Alice'
print(name.lower())  # output: alice
print(name.upper())  # output: ALICE
```

#### `strip()`

The `strip()` method removes any leading or trailing whitespace from a string. For example:

```python
message = '   Hello, world!   '
print(message.strip())  # output: 'Hello, world!'
```

#### `replace()`

The `replace()` method replaces all occurrences of a substring with another substring. For example:

```python
message = 'Hello, world!'
new_message = message.replace('world', 'Python')
print(new_message)  # output: 'Hello, Python!'
```

#### `split()`

The `split()` method splits a string into a list of substrings based on a delimiter. For example:

```python
message = 'Hello, world!'
words = message.split(',')
print(words)  # output: ['Hello', ' world!']
```

### String Interpolation

String interpolation is the process of inserting variables or expressions into a string. In Python, we can do this using f-strings or the `.format()` method.

#### f-strings

An f-string is a string literal that is prefixed with the letter f or F. It allows us to insert variables or expressions directly into a string using curly braces `{}`. For example:

```python
name = 'Alice'
age = 25

message = f'My name is {name} and I am {age} years old.'
print(message)  # output: 'My name is Alice and I am 25 years old.'
```

#### `.format()`

The .format() method allows us to insert variables or expressions into a string using placeholders enclosed in curly braces {}. For example:

```python
name = 'Alice'
age = 25

message = 'My name is {} and I am {} years old.'.format(name, age)
print(message)  # output: 'My name is Alice and I am 25 years old.'
```

### Regular Expressions

Regular expressions are a powerful tool for working with text data. They allow us to search, match, and manipulate text patterns in a flexible and precise way. In Python, we can use the re module to work with regular expressions.

Here are some commonly used regular expression functions:

`search()`
The `search()` function searches for a pattern in a string and returns the first occurrence of the pattern. For example:

```python
import re

message = 'The quick brown fox jumps over the lazy dog.'
match = re.search('fox', message)
print(match.group())  # output: 'fox'
```

#### `findall()`

The `findall()` function searches for all occurrences of a pattern in a string and returns a list of matches. For example:

```python
import re

message = 'The quick brown fox jumps over the lazy dog.'
matches = re.findall('[aeiou]', message)
print(matches)  # output: ['e', 'u', 'i', 'o', 'u', 'o', 'e', 'a', 'o']
```

#### 'sub()'

The 'sub()' function replaces all occurrences of a pattern in a string with a new string. For example:

```python
import re

message = 'The quick brown fox jumps over the lazy dog.'
new_message = re.sub('fox', 'cat', message)
print(new_message)  # output: 'The quick brown cat jumps over the lazy dog.'
```

### [Next: Strings]()
