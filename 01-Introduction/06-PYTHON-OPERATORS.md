# Operators

In Python, operators are symbols that are used to perform various operations on values or variables. There are several types of operators in Python, including arithmetic operators, comparison operators, logical operators, and assignment operators.

### Arithmetic Operators

Arithmetic operators are used to perform mathematical operations on numerical values. Here are some commonly used arithmetic operators:

| Operator | Description    | Example                     |
| -------- | -------------- | --------------------------- |
| `+`      | Addition       | `2 + 3` evaluates to `5`    |
| `-`      | Subtraction    | `3 - 1` evaluates to `2`    |
| `*`      | Multiplication | `4 * 5` evaluates to `20`   |
| `/`      | Division       | `10 / 2` evaluates to `5.0` |
| `//`     | Floor Division | `11 // 2` evaluates to `5`  |
| `%`      | Modulo         | `5 % 2` evaluates to `1`    |
| `**`     | Exponentiation | `2 ** 3` evaluates to `8`   |

### Comparison Operators

Comparison operators are used to compare values and return a boolean value (`True` or `False`). Here are some commonly used comparison operators:

| Operator | Description              | Example                      |
| -------- | ------------------------ | ---------------------------- |
| `==`     | Equal                    | `3 == 3` evaluates to `True` |
| `!=`     | Not Equal                | `2 != 3` evaluates to `True` |
| `<`      | Less Than                | `2 < 3` evaluates to `True`  |
| `>`      | Greater Than             | `3 > 2` evaluates to `True`  |
| `<=`     | Less Than or Equal To    | `2 <= 2` evaluates to `True` |
| `>=`     | Greater Than or Equal To | `3 >= 2` evaluates to `True` |

### Logical Operators

Logical operators are used to combine boolean values and return a boolean value (`True` or `False`). Here are the three logical operators:

#### `and`

The `and` operator returns `True` if both operands are `True`, and `False` otherwise.

```python
x = 5
y = 10
z = 15

print(x < y and y < z)  # output: True
print(x < y and y > z)  # output: False
```

#### `or`

The `or` operator returns `True` if at least one of the operands is `True`, and `False` otherwise.

```python
x = 5
y = 10
z = 15

print(x < y or y > z)  # output: True
print(x > y or y > z)  # output: False
```

#### `not`

The `not` operator returns `True` if the operand is False, and False if the operand is `True`.

```python
x = 5
y = 10

print(not x < y)  # output: False
print(not x > y)  # output: True
```

| Operator | Description                                             | Example                 |
| -------- | ------------------------------------------------------- | ----------------------- |
| `and`    | Returns True if both statements are true                | `x < 5 and x < 10`      |
| `or`     | Returns True if one of the statements is true           | `x < 5 or x < 4`        |
| `not`    | Reverse the result, returns False if the result is true | `not(x < 5 and x < 10)` |

### Assignment Operators

Assignment operators are used to assign values to variables. Here are some commonly used assignment operators:

| Operator | Example   | Equivalent   |
| -------- | --------- | ------------ |
| `=`      | `x = 5`   | `x = 5`      |
| `+=`     | `x += 5`  | `x = x + 5`  |
| `-=`     | `x -= 5`  | `x = x - 5`  |
| `*=`     | `x *= 5`  | `x = x * 5`  |
| `/=`     | `x /= 5`  | `x = x / 5`  |
| `//=`    | `x //= 5` | `x = x // 5` |
| `%=`     | `x %= 5`  | `x = x % 5`  |
| `**=`    | `x **= 5` | `x = x ** 5` |

##### [Next: Chapter 02](../02-Variables-and-Data-Types/01-INTRO.MD)
