# Data Types and Operators

## Introduction
Ee will explore the basic data types in Python and understand how to use operators to manipulate these data. Python is a dynamically typed programming language, meaning you don't need to explicitly declare variable types. The basic data types we will cover are numbers (int and float), strings (str), and booleans (bool).

## 1. Numbers
In Python, numbers can mainly be of two types: `int` (integers) and `float` (floating-point numbers).

### 1.1 Integers (int)
Integers are numbers without a decimal part. For example, `5`, `100`, `-3` are integers.

```py
a = 10
b = -5
print(type(a))  # Prints <class 'int'>
```

### 1.2 Floating-Point Numbers (float)
Floating-point numbers have a decimal part. For example, `3.14`, `-0.001` are floating-point numbers.

```py
x = 4.5
y = -0.12
print(type(x))  # Prints <class 'float'>
```

## 2. Strings (str)
Strings are sequences of characters used to store text.

```py
name = "Alice"
message = "Hello, world!"
print(type(name))  # Prints <class 'str'>
```
You can use either single or double quotes to create strings.

## 3. Booleans (bool)
Booleans represent one of two values: `True` or `False`. They are often the result of a comparison or condition.

```py
isTrue = True
isFalse = False
print(type(isTrue))  # Prints <class 'bool'>
```

## 4. Operators
Operators allow performing operations on variables and values.

### 4.1 Arithmetic Operators
- Addition: `+`
- Subtraction: `-`
- Multiplication: `*`
- Division: `/`
- Integer Division: `//`
- Modulo (remainder of division): `%`
- Power: `**`

```py
# Examples
addition = 5 + 3       # 8
division = 8 / 2       # 4.0
power = 2 ** 3         # 8
```

### 4.2 Comparison Operators
- Equal to: `==`
- Not equal to: `!=`
- Greater than: `>`
- Less than: `<`
- Greater than or equal to: `>=`
- Less than or equal to: `<=`

```py
# Examples
a = 5
b = 3
result = a > b  # True
```

### 4.3 Logical Operators
- `and`: Returns True if both statements are true
- `or`: Returns True if one of the statements is true
- `not`: Reverses the result, returns False if the result is true

```py
# Examples
result = (a > b) and (a != 0)  # True
```

## Conclusion
Understanding data types and operators is fundamental in Python. These concepts are the basis for data manipulation and programming logic. In upcoming courses, we will explore how these data types and operators can be used in more complex data structures and in flow control.
