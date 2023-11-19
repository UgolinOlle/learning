# Data Structures

## Introduction

Data structures are essential ways of storing and organizing data in Python. In this course, we will explore four fundamental types of data structures: lists, tuples, dictionaries, and sets.

## 1. Lists

Lists in Python are ordered and mutable collections. They can contain elements of different types.

### 1.1 Creating Lists

```py
my_list = [1, 2, 3]
mixed_list = ["text", 10, True]
```

### 1.2 Operations on Lists

- Adding elements: `append()`, `insert()`
- Removing elements: `remove()`, `pop()`
- Accessing elements: by index, e.g., `my_list[0]`
- Iterating through a list: `for` loop

```py
my_list.append(4)  # Adds 4 to the end
print(my_list)     # [1, 2, 3, 4]
```

## 2. Tuples

Tuples are ordered and immutable collections. They are often used to store sets of heterogeneous data.

### 2.1 Creating Tuples

```py
my_tuple = (1, "hello", 3.14)
```

### 2.2 Operations on Tuples

- Accessing elements: by index, e.g., `my_tuple[1]`
- Iterating through a tuple: `for` loop
- Tuples cannot be modified after their creation.

## 3. Dictionaries

Dictionaries in Python are unordered collections of key-value pairs.

### 3.1 Creating Dictionaries

```py
my_dict = {"name": "Alice", "age": 25}
```

### 3.2 Operations on Dictionaries

- Accessing values: `my_dict["name"]`
- Adding or modifying: `my_dict["age"] = 26`
- Removing key-value pairs: `del my_dict["age"]`
- Iterating through a dictionary: `for` loops over keys, values, or both

```py
print(my_dict["name"])  # Alice
```

## 4. Sets

Sets are unordered and unindexed collections. They are useful for storing unique elements.

### 4.1 Creating Sets

```py
my_set = {1, 2, 3}
```

### 4.2 Operations on Sets

- Adding elements: `add()`
- Removing elements: `remove()`, `discard()`
- Mathematical operations: union, intersection

```py
my_set.add(4)
print(my_set)  # {1, 2, 3, 4}
```

## Conclusion

Understanding data structures is crucial for efficient programming in Python. Each structure has its own characteristics and use cases. Lists and tuples are ideal for storing ordered collections, dictionaries for quick access to data via keys, and sets for maintaining unique collections.
