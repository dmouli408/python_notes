# 🐍 Python from Scratch: A 2-Week Learning Plan



![Python Banner](https://img.shields.io/badge/Python-Learning%20Path-blue?style=for-the-badge&logo=python&logoColor=white)
![Beginner Friendly](https://img.shields.io/badge/Beginner-Friendly-green?style=for-the-badge)
![14 Days](https://img.shields.io/badge/Duration-14%20Days-orange?style=for-the-badge)
![Examples](https://img.shields.io/badge/Examples-100+-red?style=for-the-badge)

# 🚀 Your Journey to Becoming a Python Pro

*A comprehensive, day-by-day guide to mastering Python basics with detailed explanations and examples.*

**✨ Interactive Learning Experience ✨**



---

## 🎯 What You'll Learn



| 🐍 **Python Basics** | 📊 **Data Structures** | 🔄 **Control Flow** | 📁 **File Handling** |
|:---:|:---:|:---:|:---:|
| Variables, Types, Operators | Lists, Tuples, Sets, Dicts | Conditions, Loops, Functions | I/O Operations, Modules |



---

## � Learning Schedule



### 🗓️ Your 14-Day Python Adventure



| 📚 **Week 1: Core Fundamentals** | 🚀 **Week 2: Advanced Concepts** |
|:---|:---|
| **Day 1:** [🐍 Introduction to Python](#day-1) | **Day 8:** [🔀 Conditional Statements](#day-8) |
| **Day 2:** [📊 Variables and Data Types](#day-2) | **Day 9:** [🔄 Loops: `for`](#day-9) |
| **Day 3:** [⚡ Operators](#day-3) | **Day 10:** [🔁 Loops: `while`](#day-10) |
| **Day 4:** [📝 Strings in Depth](#day-4) | **Day 11:** [🎯 Functions](#day-11) |
| **Day 5:** [📋 Data Structures: Lists](#day-5) | **Day 12:** [🔧 Advanced Functions](#day-12) |
| **Day 6:** [🎭 Tuples & Sets](#day-6) | **Day 13:** [📁 File I/O](#day-13) |
| **Day 7:** [🗂️ Dictionaries](#day-7) | **Day 14:** [📦 Modules and Libraries](#day-14) |



**💡 Pro Tip:** *Each day builds upon the previous, so follow the sequence for best results!*



---



# 🐍 Day 1: Introduction to Python




<img src="https://img.shields.io/badge/Day-1-brightgreen?style=for-the-badge" alt="Day 1">
<img src="https://img.shields.io/badge/Topic-Introduction-blue?style=for-the-badge" alt="Introduction">
<img src="https://img.shields.io/badge/Level-Beginner-green?style=for-the-badge" alt="Beginner">


### 🐍 What is Python?

- **🎯 High-Level:** Abstracts away hardware details, easy to use
- **⚡ Interpreted:** Executes code line by line, great for debugging  
- **🌐 General-Purpose:** Used for web, data science, automation, and more
- **💰 Open Source:** Free to use and modify
- **🖥️ Cross-Platform:** Runs on Windows, macOS, Linux

### ✨ Key Features

| 🎨 **Feature** | 📝 **Description** |
|:---|:---|
| 📖 **Readability** | Clean, English-like syntax |
| 🎯 **Simplicity** | Easy to learn for beginners |
| 📚 **Extensive Libraries** | Rich standard and third-party libraries |
| 👥 **Community** | Large, active global community |
| 🔧 **Versatility** | Web, AI, scripting, games, and more |

### 🛠️ Abbreviations

- **💻 IDE:** Integrated Development Environment (VS Code, PyCharm)
- **📋 PEP:** Python Enhancement Proposal (PEP 8 = style guide)
- **🔄 REPL:** Read-Eval-Print Loop (interactive shell)
- **⌨️ CLI:** Command Line Interface
- **🔧 Interpreter:** Program that executes Python code


### 🗝️ Python Keywords (Reserved Words)
Python keywords are reserved and cannot be used as variable names:
```python
import keyword
print(keyword.kwlist)  # List all Python keywords
# Examples: False, True, None, and, as, assert, break, class, continue, def, del, elif, else, except, finally, for, from, global, if, import, in, is, lambda, nonlocal, not, or, pass, raise, return, try, while, with, yield
```

### 🧑‍💻 Indentation & Whitespace
Python uses indentation (spaces/tabs) to define code blocks. No braces `{}`!
```python
if True:
    print("Indented block!")
    # 4 spaces is standard (PEP 8)
```

### 💤 The `pass` Statement
Use `pass` as a placeholder for empty code blocks:
```python
def future_function():
    pass  # Does nothing
```

### 🆘 Getting Help
Use `help()` for built-in docs:
```python
help(print)
help(str)
```

### 🏷️ The `__name__ == "__main__"` Idiom
Run code only if the file is executed directly:
```python
if __name__ == "__main__":
    print("This script is running directly!")
```

### 🐍 Your First Python Program
```python
# This is a comment. It is ignored by Python.
print("Hello, World!")  # Output: Hello, World!
```

### ✍️ Comments

---

### 🖨️ Printing in Python

Python's `print()` function is versatile and supports many features:

#### 1. Basic Printing
```python
print("Hello, World!")
```

#### 2. Printing Multiple Items
```python
print("A", "B", "C")  # Output: A B C
```

#### 3. Custom Separator (`sep`)
```python
print("A", "B", "C", sep="-")  # Output: A-B-C
```

#### 4. Custom End (`end`)
```python
print("Hello", end=" ")
print("World!")  # Output: Hello World!
```

#### 5. Printing Variables and Expressions
```python
name = "Alice"
age = 25
print("Name:", name, "Age:", age)
print("Sum:", 10 + 5)
```

#### 6. Formatted Strings (f-strings)
```python
score = 99
print(f"Your score is {score}!")
```

#### 7. Old Style Formatting (`%` operator)
```python
pi = 3.14159
print("Value of pi: %.2f" % pi)  # Output: Value of pi: 3.14
```

#### 8. String `.format()` Method
```python
user = "Bob"
points = 100
print("User: {} | Points: {}".format(user, points))
```

#### 9. Printing Escape Characters
```python
print("She said, \"Python is awesome!\"")
print('It\'s easy to learn.')
print("Line1\nLine2")  # Newline
print("Tab\tSeparated")  # Tab
```

#### 10. Printing Unicode and Emojis
```python
print("Smile: \u263A")  # ☺
print("Rocket: 🚀")
```

#### 11. Printing Raw Strings
```python
print(r"C:\\Users\\Alice")  # Output: C:\Users\Alice
```

#### 12. Printing with Input
```python
user_input = input("Enter something: ")
print("You entered:", user_input)
```

#### 13. Printing Without Newline
```python
for i in range(3):
    print(i, end=", ")
# Output: 0, 1, 2, 
```

#### 14. Printing Lists and Dictionaries
```python
fruits = ["apple", "banana", "cherry"]
print(fruits)
person = {"name": "Alice", "age": 25}
print(person)
```

#### 15. Printing with File Output
```python
with open("output.txt", "w") as f:
    print("Hello, file!", file=f)
```

---

### 📝 Comments in Python

#### 1. Single-Line Comments
```python
# This is a single-line comment
print("Hello")  # This is an inline comment
```

#### 2. Multi-Line Comments
```python
"""
This is a multi-line comment.
It can span several lines.
Useful for documentation or disabling code blocks.
"""
print("Multi-line comment above!")
```

#### 3. Docstrings (Documentation Strings)
Used for documenting modules, classes, functions.
```python
def greet():
    """This function prints a greeting."""
    print("Hello!")
```

#### 4. Commenting Out Code
```python
# print("This line is disabled and won't run.")
```

#### 5. Inline Comments
```python
total = 10 + 5  # Add two numbers
```

#### 6. Best Practices
- Keep comments concise and relevant.
- Use docstrings for functions/classes.
- Avoid obvious comments (e.g., `# increment x by 1` when code is `x += 1`).

---

### 💡 Python File Extensions
- `.py` : Standard Python script
- `.pyw`: Python script (no console window on Windows)

### 🔥 How Python Runs Code
1. You write code in a `.py` file.
2. The Python interpreter reads and executes each line.
3. Errors are shown immediately (great for learning!).

### 🖥️ Running Python
```bash
# Run interactively
python
# Run a script
python my_script.py
```

### 📜 Examples
1. **Print a message**
   ```python
   print("Welcome to Python!")
   ```
2. **Single-line comment**
   ```python
   # This prints a number
   print(42)
   ```
3. **Multi-line comment**
   ```python
   """
   This is a multi-line comment.
   It can span several lines.
   """
   print("Multi-line comment above!")
   ```
4. **Print multiple lines**
   ```python
   print("Line 1")
   print("Line 2")
   print("Line 3")
   ```
5. **Simple math and comments**
   ```python
   # Add two numbers
   a = 5
   b = 7
   result = a + b
   print("Sum:", result)
   ```
6. **Using the interactive shell (REPL)**
   ```python
   >>> print("Hello from REPL!")
   Hello from REPL!
   ```
7. **Error example (shows how Python helps you learn)**
   ```python
   print(unknown_var)  # NameError: name 'unknown_var' is not defined
   ```
8. **Using escape characters**
   ```python
   print("She said, \"Python is awesome!\"")
   print('It\'s easy to learn.')
   ```
9. **Printing with end and sep**
   ```python
   print("A", "B", "C", sep="-")  # Output: A-B-C
   print("Hello", end=" ")
   print("World!")  # Output: Hello World!
   ```
10. **Input from user**
    ```python
    name = input("Enter your name: ")
    print("Hello,", name)
    ```

---

---



# 📊 Day 2: Variables and Data Types




<img src="https://img.shields.io/badge/Day-2-brightgreen?style=for-the-badge" alt="Day 2">
<img src="https://img.shields.io/badge/Topic-Variables%20%26%20Data%20Types-blue?style=for-the-badge" alt="Variables">
<img src="https://img.shields.io/badge/Level-Beginner-green?style=for-the-badge" alt="Beginner">





### 🔑 Variables: The Building Blocks

- **📦 Variable:** A named location in memory to store data
- **➡️ Assignment:** Use `=` to assign a value
- **🔄 Dynamic Typing:** Python variables can change type
- **🔠 Case Sensitive:** `score` and `Score` are different




### 📝 Naming Conventions (PEP 8)
- Use **snake_case**: `user_name`, `total_score`
- Start with a letter or underscore (_)
- Cannot start with a number
- Only letters, numbers, underscores
- Case-sensitive


### 🛠️ Abbreviations
- **int**: Integer
- **float**: Floating-point number
- **str**: String
- **bool**: Boolean
- **type()**: Returns the type of a variable
- **id()**: Returns the memory address of an object

### 📊 Data Types in Python
| Type | Example | Description |
|------|---------|-------------|
| **int** | `42` | Whole numbers |
| **float** | `3.14` | Decimal numbers |
| **str** | `"Hello"` | Text data |
| **bool** | `True` | True/False |

### 🔄 Type Conversion (Casting)
- `int()`: Convert to integer
- `float()`: Convert to float
- `str()`: Convert to string
- `bool()`: Convert to boolean


### 💡 Special Types
- **NoneType**: `None` means no value
- **Complex**: `3+4j` (rarely used in basics)

### 🧬 Mutability vs. Immutability
- **Mutable:** Can be changed after creation (e.g., lists, dicts)
- **Immutable:** Cannot be changed (e.g., int, float, str, tuple)
```python
my_list = [1, 2, 3]
my_list[0] = 99  # OK
my_str = "hello"
# my_str[0] = "H"  # Error: 'str' object does not support item assignment
```

### 🧹 Deleting Variables
```python
x = 10
del x
# print(x)  # NameError: name 'x' is not defined
```

### 🔍 Checking Variable Existence
```python
var_name = "x"
print("x" in locals())  # False (if x not defined)
print("x" in globals()) # False (if x not defined)
```

### 🏷️ Type Hints (Python 3.5+)
```python
def add(a: int, b: int) -> int:
    return a + b
```

### 🆔 Memory Address with `id()`
```python
y = 123
print(id(y))  # Unique integer for object's memory address
```

### 🔢 Underscores in Numbers
```python
big_number = 1_000_000
print(big_number)  # Output: 1000000
```

### ➕ Augmented Assignment Operators
```python
count = 5
count += 2  # count = count + 2
count -= 1  # count = count - 1
count *= 3  # count = count * 3
count /= 2  # count = count / 2
print(count)
```

### 🧪 More Examples
1. **Type hints in variables**
   ```python
   age: int = 25
   name: str = "Bob"
   is_active: bool = True
   ```
2. **Check type and memory address**
   ```python
   x = "hello"
   print(type(x), id(x))
   ```
3. **Delete and check existence**
   ```python
   temp = 123
   print("temp" in locals())  # True
   del temp
   print("temp" in locals())  # False
   ```
4. **Immutability demonstration**
   ```python
   tup = (1, 2, 3)
   # tup[0] = 99  # Error: 'tuple' object does not support item assignment
   ```
5. **Using underscores in large numbers**
   ```python
   population = 7_900_000_000
   print(population)
   ```

### 📜 Examples
1. **Declaring variables of all types**
   ```python
   age = 21           # int
   price = 19.99      # float
   name = "Alice"     # str
   is_student = True  # bool
   print(type(age), type(price), type(name), type(is_student))
   ```
2. **Variable naming rules**
   ```python
   _private_var = "hidden"
   user1 = "Bob"
   # 1user = "error"  # Invalid: cannot start with number
   print(_private_var, user1)
   ```
3. **Dynamic typing**
   ```python
   x = 10
   print(type(x))  # int
   x = "ten"
   print(type(x))  # str
   ```
4. **Type conversion**
   ```python
   num = "100"
   num_int = int(num)
   num_float = float(num)
   print(num_int, num_float)
   print(type(num_int), type(num_float))
   ```
5. **Boolean conversion**
   ```python
   print(bool(0))      # False
   print(bool(1))      # True
   print(bool(""))     # False
   print(bool("abc"))  # True
   ```
6. **NoneType usage**
   ```python
   value = None
   print(value, type(value))
   ```
7. **Multiple assignment**
   ```python
   a, b, c = 1, 2, 3
   print(a, b, c)
   ```
8. **Swapping variables**
   ```python
   x = 5
   y = 10
   x, y = y, x
   print(x, y)  # 10 5
   ```
9. **String concatenation and formatting**
   ```python
   first = "Hello"
   second = "World"
   print(first + " " + second)
   print(f"{first}, {second}!")
   ```
10. **Input and type conversion**
    ```python
    age = input("Enter your age: ")
    age = int(age)
    print("You are", age, "years old.")
    ```

### 🧩 Quick Reference Table
| Syntax | Meaning |
|--------|---------|
| `=` | Assignment |
| `type(x)` | Get type |
| `is` | Identity check |
| `==` | Equality check |
| `input()` | User input |

### 🚩 Common Mistakes
- Forgetting quotes for strings: `name = Alice` (error)
- Mixing types: `print("Age: " + 21)` (error, must convert 21 to string)
- Using reserved words as variable names: `class = "Math"` (error)

### 🎨 Stylish Example: All-in-One
```python
# Declare variables
user_name = input("Enter your name: ")
user_age = int(input("Enter your age: "))
is_new_user = True

# Print with formatting
print(f"Welcome, {user_name}! Age: {user_age}. New user? {is_new_user}")

# Change type
user_age = str(user_age)
print("Your age as a string:", user_age)
```

---

---



# ⚡ Day 3: Operators




<img src="https://img.shields.io/badge/Day-3-brightgreen?style=for-the-badge" alt="Day 3">
<img src="https://img.shields.io/badge/Topic-Operators-blue?style=for-the-badge" alt="Operators">
<img src="https://img.shields.io/badge/Level-Beginner-green?style=for-the-badge" alt="Beginner">





### 🔢 Operators in Python

Operators are special symbols that perform operations on variables and values. They are the backbone of calculations, logic, and data manipulation in Python.

### 🧮 Types of Operators

| 🎯 **Type** | 📝 **Description** | 🔧 **Examples** |
|:---|:---|:---|
| 🧮 **Arithmetic** | Math operations | `+, -, *, /, %, **, //` |
| ⚖️ **Comparison** | Compare values | `==, !=, >, <, >=, <=` |
| 🧠 **Logical** | Boolean logic | `and, or, not` |
| ↔️ **Assignment** | Assign values | `=, +=, -=, *=, /=, %=, //=, **=` |
| 🧩 **Bitwise** | Bit-level operations | `&, |, ^, ~, <<, >>` |
| 🔍 **Membership** | Test for membership | `in, not in` |
| 🏷️ **Identity** | Test for same object | `is, is not` |




---

### 🧮 Arithmetic Operators
- `+` Addition
- `-` Subtraction
- `*` Multiplication
- `/` Division (float)
- `%` Modulus (remainder)
- `**` Exponentiation
- `//` Floor Division

### ⚖️ Comparison Operators
- `==` Equal to
- `!=` Not equal to
- `>` Greater than
- `<` Less than
- `>=` Greater than or equal to
- `<=` Less than or equal to

### 🧠 Logical Operators
- `and` Both conditions True
- `or` At least one True
- `not` Reverse the result

### ↔️ Assignment Operators
- `=` Assign
- `+=` Add and assign
- `-=` Subtract and assign
- `*=` Multiply and assign
- `/=` Divide and assign
- `%=` Modulus and assign
- `//=` Floor divide and assign
- `**=` Exponentiate and assign

### 🧩 Bitwise Operators
- `&` AND
- `|` OR
- `^` XOR
- `~` NOT
- `<<` Left shift
- `>>` Right shift

### 🔍 Membership Operators
- `in`
- `not in`
```python
fruits = ["apple", "banana"]
print("apple" in fruits)  # True
print("grape" not in fruits)  # True
```

### 🏷️ Identity Operators
- `is`
- `is not`
```python
a = [1, 2]

c = [1, 2]
print(a is b)      # True (same object)
print(a is c)      # False (same value, different object)
print(a == c)      # True (values are equal)
```

### 🏆 Operator Precedence
Order in which operations are performed:
```python
result = 2 + 3 * 4  # 2 + (3*4) = 14
result = (2 + 3) * 4  # (2+3)*4 = 20
```
Use parentheses to control precedence.

---

### 🏅 Full Python Operator Precedence Table

> **📊 Operators are evaluated in the following order (highest to lowest):**

| 🏆 **Precedence** | 🔧 **Operator(s)** | 📝 **Description** |
|:---:|:---|:---|
| **1** | `()` | Parentheses (grouping) |
| **2** | `x[index]`, `x.attribute`, `x(...)` | Indexing, slicing, attribute reference, function call |
| **3** | `**` | Exponentiation |
| **4** | `+x`, `-x`, `~x` | Unary plus, minus, bitwise NOT |
| **5** | `*`, `/`, `//`, `%` | Multiplication, division, floor division, modulus |
| **6** | `+`, `-` | Addition, subtraction |
| **7** | `<<`, `>>` | Bitwise shift left, right |
| **8** | `&` | Bitwise AND |
| **9** | `^` | Bitwise XOR |
| **10** | `\|` | Bitwise OR |
| **11** | `in`, `not in`, `is`, `is not`, `==`, `!=`, `<`, `>` | Comparisons, membership, identity |
| **12** | `not` | Logical NOT |
| **13** | `and` | Logical AND |
| **14** | `or` | Logical OR |
| **15** | `if - else` | Conditional expression |
| **16** | `lambda` | Lambda expression |
| **17** | `=`, `+=`, `-=`, etc. | Assignment |">
16
lambda
Lambda expression


17
=, +=, -=, etc.
Assignment






💡 **Pro Tip:** When in doubt, use parentheses `()` to make your code clear and avoid precedence mistakes!



---

### 📜 Examples
1. **Arithmetic Operators**
   ```python
   a = 10
   b = 3
   print("Add:", a + b)
   print("Subtract:", a - b)
   print("Multiply:", a * b)
   print("Divide:", a / b)
   print("Modulus:", a % b)
   print("Exponent:", a ** b)
   print("Floor Div:", a // b)
   ```
2. **Comparison Operators**
   ```python
   x = 5
   y = 10
   print(x == y)  # False
   print(x != y)  # True
   print(x > y)   # False
   print(x <= y)  # True
   ```
3. **Logical Operators**
   ```python
   age = 22
   is_student = True
   print(age < 25 and is_student)  # True
   print(age > 65 or is_student)   # True
   print(not is_student)           # False
   ```
4. **Assignment Operators**
   ```python
   count = 0
   count += 1
   print(count)
   total = 100
   total -= 10
   print(total)
   ```
5. **Bitwise Operators**
   ```python
   a = 5  # 0b0101
   b = 3  # 0b0011
   print(a & b)  # 1 (0b0001)
   print(a | b)  # 7 (0b0111)
   print(a ^ b)  # 6 (0b0110)
   print(~a)     # -6 (invert bits)
   print(a << 1) # 10 (shift left)
   print(a >> 1) # 2 (shift right)
   ```
6. **Membership Operators**
   ```python
   colors = ["red", "green", "blue"]
   print("red" in colors)      # True
   print("yellow" not in colors)  # True
   ```
7. **Identity Operators**
   ```python
   x = [1, 2, 3]
   y = x
   z = [1, 2, 3]
   print(x is y)  # True
   print(x is z)  # False
   print(x == z)  # True
   ```
8. **Operator Precedence**
   ```python
   print(2 + 3 * 4)      # 14
   print((2 + 3) * 4)    # 20
   print(2 ** 3 ** 2)    # 512 (right to left for **)
   ```
9. **Chained Comparisons**
   ```python
   x = 5
   print(1 < x < 10)  # True
   print(10 > x > 1)  # True
   ```
10. **Using Operators in Conditions**
    ```python
    score = 85
    if 80 <= score < 90:
        print("B grade")
    ```

---

### 🚩 Common Mistakes
- Using `=` instead of `==` in comparisons:
  ```python
  # if x = 5:  # SyntaxError
  if x == 5:
      print("x is 5")
  ```
- Integer division confusion:
  ```python
  print(5 / 2)   # 2.5
  print(5 // 2)  # 2
  ```
- Mixing types:
  ```python
  print("Sum:" + 5 + 3)  # TypeError
  print("Sum:", 5 + 3)   # Correct
  ```
- Bitwise vs. logical confusion:
  ```python
  print(True & False)  # 0 (bitwise)
  print(True and False)  # False (logical)
  ```
- Operator precedence errors:
  ```python
  print(2 + 3 * 4)      # 14, not 20
  print((2 + 3) * 4)    # 20
  ```
- Using `is` for value comparison (should use `==`):
  ```python
  a = 1000
  b = 1000
  print(a is b)  # False (may be True for small ints)
  print(a == b)  # True
  ```

---

### 🎨 Stylish Quick Reference Table
| Operator | Purpose | Example | Result |
|----------|---------|---------|--------|
| + | Addition | 2 + 3 | 5 |
| - | Subtraction | 5 - 2 | 3 |
| * | Multiplication | 4 * 2 | 8 |
| / | Division | 8 / 2 | 4.0 |
| // | Floor Division | 7 // 3 | 2 |
| % | Modulus | 7 % 3 | 1 |
| ** | Exponent | 2 ** 3 | 8 |
| == | Equal | 5 == 5 | True |
| != | Not Equal | 5 != 3 | True |
| > | Greater | 5 > 3 | True |
| < | Less | 3 < 5 | True |
| >= | Greater/Equal | 5 >= 5 | True |
| <= | Less/Equal | 3 <= 5 | True |
| and | Logical AND | True and False | False |
| or | Logical OR | True or False | True |
| not | Logical NOT | not True | False |
| in | Membership | 'a' in 'cat' | True |
| is | Identity | a is b | True/False |
| & | Bitwise AND | 5 & 3 | 1 |
| \| | Bitwise OR | 5 \| 3 | 7 |
| ^ | Bitwise XOR | 5 ^ 3 | 6 |
| ~ | Bitwise NOT | ~5 | -6 |
| << | Left Shift | 5 << 1 | 10 |
| >> | Right Shift | 5 >> 1 | 2 |

---
## <a id="day-4"></a>Day 4: Strings in Depth

### 📘 **Definition: String**
A **string** is a sequence of characters. In Python, strings are **immutable**, meaning they cannot be changed after they are created.

### ✍️ **String Creation**
- **Single quotes:** `'Hello'`
- **Double quotes:** `"Hello"`
- **Triple quotes:** `"""Hello"""` (for multi-line strings)

### 🛠️ **Common String Methods**
- `upper()`: Converts the string to uppercase.
- `lower()`: Converts the string to lowercase.
- `strip()`: Removes leading/trailing whitespace.
- `replace(old, new)`: Replaces a substring with another.
- `split(separator)`: Splits the string into a list of substrings.
- `find(substring)`: Returns the starting index of a substring.

### 📝 **String Formatting**
- **f-strings (Formatted String Literals):** A modern and convenient way to embed expressions inside string literals. They are prefixed with an `f` or `F`.

### 🔪 **Indexing and Slicing**
- **Indexing:** Accessing a single character at a specific position. Python uses 0-based indexing.
- **Slicing:** Extracting a portion of a string. `my_string[start:stop:step]`.

### 📜 **Examples**

1.  **String methods:**
    ```python
    text = "   Hello, World!   "
    print("Original:", repr(text))
    print("Stripped:", repr(text.strip()))
    print("Uppercase:", text.upper())
    print("Replaced:", text.replace("World", "Python"))
    print("Split:", text.split(','))
    ```

2.  **f-strings:**
    ```python
    name = "Alice"
    age = 30
    print(f"My name is {name} and I am {age} years old.")
    
    # You can also embed expressions
    num1 = 10
    num2 = 5
    print(f"The sum of {num1} and {num2} is {num1 + num2}.")
    ```

3.  **Indexing:**
    ```python
    word = "Python"
    print("First character:", word[0])   # P
    print("Last character:", word[-1])  # n
    # print(word[6]) # This would cause an IndexError
    ```

4.  **Slicing:**
    ```python
    s = "Programming"
    print("Slice [1:4]:", s[1:4])     # rog
    print("Slice from start [ :5]:", s[:5])  # Progr
    print("Slice to end [5: ]:", s[5:])    # amming
    print("Slice with step [::2]:", s[::2]) # Pormig
    ```

5.  **Combining methods:**
    ```python
    # Process a raw data string
    raw_data = "  user_id:123, name:John Doe  "
    clean_data = raw_data.strip()
    parts = clean_data.split(',')
    user_id_part = parts[0]
    user_id = user_id_part.split(':')[1]
    print("User ID:", user_id)
    ```

---

## <a id="day-5"></a>Day 5: Data Structures: Lists

### 📘 **Definition: List**
A **list** is an ordered and mutable collection of items. Lists can contain items of different data types. They are defined by enclosing a comma-separated sequence of items in square brackets `[]`.

### 🛠️ **Abbreviations**
- **Mutable:** The contents of the object can be modified after it is created.

### ⚙️ **Common List Methods**
- `append(item)`: Adds an item to the end of the list.
- `insert(index, item)`: Inserts an item at a given position.
- `remove(item)`: Removes the first occurrence of an item.
- `pop(index)`: Removes and returns the item at the given index (or the last item if index is not specified).
- `sort()`: Sorts the list in ascending order.
- `reverse()`: Reverses the order of items in the list.
- `len(list)`: Returns the number of items in the list (this is a function, not a method).

### 🔪 **Indexing and Slicing**
Lists use 0-based indexing and slicing, just like strings.

### 📜 **Examples**

1.  **Creating and accessing lists:**
    ```python
    fruits = ["apple", "banana", "cherry", "orange"]
    print("All fruits:", fruits)
    print("First fruit:", fruits[0])
    print("Last fruit:", fruits[-1])
    print("Slice of fruits:", fruits[1:3])
    ```

2.  **Modifying a list:**
    ```python
    numbers = [1, 2, 3, 4, 5]
    print("Original numbers:", numbers)
    numbers[2] = 10 # Change the value at index 2
    print("Modified numbers:", numbers)
    ```

3.  **Using `append()` and `insert()`:**
    ```python
    colors = ["red", "green", "blue"]
    print("Original colors:", colors)
    colors.append("yellow") # Add to the end
    print("After append:", colors)
    colors.insert(1, "purple") # Insert at index 1
    print("After insert:", colors)
    ```

4.  **Using `remove()` and `pop()`:**
    ```python
    animals = ["cat", "dog", "lion", "tiger"]
    print("Original animals:", animals)
    animals.remove("lion") # Remove by value
    print("After remove:", animals)
    popped_animal = animals.pop(0) # Remove by index
    print("Popped animal:", popped_animal)
    print("After pop:", animals)
    ```

5.  **Using `sort()` and `reverse()`:**
    ```python
    numbers = [4, 1, 7, 3, 9]
    print("Original numbers:", numbers)
    numbers.sort()
    print("Sorted numbers:", numbers)
    numbers.reverse()
    print("Reversed numbers:", numbers)
    ```

---

## <a id="day-6"></a>Day 6: Data Structures: Tuples & Sets

### 📘 **Definition: Tuple**
A **tuple** is an ordered and **immutable** collection of items. Tuples are defined by enclosing a comma-separated sequence of items in parentheses `()`.
- **Immutable:** Once a tuple is created, you cannot change its values.

### 📘 **Definition: Set**
A **set** is an **unordered** collection of **unique** items. Sets are mutable. They are defined by enclosing a comma-separated sequence of items in curly braces `{}`.
- **Unordered:** Items in a set do not have a defined order.
- **Unique:** Sets cannot contain duplicate items.

### ⚙️ **Common Tuple/Set Methods**
- **Tuple:** `count(item)`, `index(item)`
- **Set:** `add(item)`, `remove(item)`, `union(other_set)`, `intersection(other_set)`

### 📜 **Examples**

1.  **Creating and using tuples:**
    ```python
    point = (10, 20, 30)
    print("Tuple:", point)
    print("First element:", point[0])
    # point[0] = 15 # This would raise a TypeError because tuples are immutable
    ```

2.  **Tuple unpacking:**
    ```python
    coordinates = (12.5, 34.9)
    x, y = coordinates
    print("x coordinate:", x)
    print("y coordinate:", y)
    ```

3.  **Creating and using sets:**
    ```python
    # Creating a set from a list to get unique items
    numbers = [1, 2, 2, 3, 4, 4, 5, 5]
    unique_numbers = set(numbers)
    print("Unique numbers:", unique_numbers)
    ```

4.  **Set operations:**
    ```python
    set_a = {1, 2, 3, 4}
    set_b = {3, 4, 5, 6}
    print("Union:", set_a.union(set_b))
    print("Intersection:", set_a.intersection(set_b))
    print("Difference (A-B):", set_a.difference(set_b))
    ```

5.  **Adding and removing items from a set:**
    ```python
    colors = {"red", "green", "blue"}
    print("Original set:", colors)
    colors.add("yellow")
    print("After add:", colors)
    colors.remove("green")
    print("After remove:", colors)
    ```

---

## <a id="day-7"></a>Day 7: Data Structures: Dictionaries

### 📘 **Definition: Dictionary**
A **dictionary** is an unordered (in Python < 3.7) and mutable collection of key-value pairs. Each key must be unique and immutable (e.g., string, number, or tuple). Dictionaries are defined with curly braces `{}`, and they consist of keys and their corresponding values.

### 🛠️ **Abbreviations**
- **Key-Value Pair:** A pair of associated values where the key is a unique identifier for the value.

### ⚙️ **Common Dictionary Methods**
- `keys()`: Returns a view object that displays a list of all the keys.
- `values()`: Returns a view object that displays a list of all the values.
- `items()`: Returns a view object that displays a list of key-value tuple pairs.
- `get(key, default_value)`: Returns the value for a key, but if the key is not found, it returns a default value instead of raising an error.
- `pop(key)`: Removes the specified key and returns the corresponding value.

### 📜 **Examples**

1.  **Creating and accessing dictionaries:**
    ```python
    person = {
        "name": "John Doe",
        "age": 30,
        "city": "New York"
    }
    print("Person's name:", person["name"])
    print("Person's age:", person.get("age"))
    ```

2.  **Modifying a dictionary:**
    ```python
    car = {
        "brand": "Ford",
        "model": "Mustang",
        "year": 1964
    }
    print("Original car:", car)
    car["year"] = 2022 # Update a value
    car["color"] = "red" # Add a new key-value pair
    print("Modified car:", car)
    ```

3.  **Using `keys()`, `values()`, and `items()`:**
    ```python
    student = {"id": 123, "major": "Computer Science", "gpa": 3.8}
    print("Keys:", student.keys())
    print("Values:", student.values())
    print("Items:", student.items())
    ```

4.  **Using `get()` to avoid errors:**
    ```python
    config = {"theme": "dark", "font_size": 12}
    # print(config["language"]) # This would raise a KeyError
    language = config.get("language", "english") # Provide a default value
    print("Language:", language)
    ```

5.  **Removing items from a dictionary:**
    ```python
    product = {"id": "A123", "name": "Laptop", "price": 1200}
    print("Original product:", product)
    removed_value = product.pop("price")
    print("Removed value:", removed_value)
    print("Product after pop:", product)
    ```

---

## <a id="day-8"></a>Day 8: Conditional Statements

### 📘 **Definition: Conditional Statements**
**Conditional statements** allow you to execute certain blocks of code depending on whether a condition is true or false. They are fundamental for controlling the flow of a program.

### 🏛️ **Structure**
- **`if`:** The `if` statement is used to test a condition. If the condition is true, the code block inside the `if` statement is executed.
- **`else`:** The `else` statement can be combined with an `if` statement. It provides an alternative block of code to be executed if the `if` condition is false.
- **`elif` (else if):** The `elif` statement allows you to check multiple conditions. It is checked only if the preceding `if` (or `elif`) conditions were false.

### 📜 **Examples**

1.  **Simple `if` statement:**
    ```python
    age = 20
    if age >= 18:
        print("You are eligible to vote.")
    ```

2.  **`if-else` statement:**
    ```python
    temperature = 15
    if temperature > 25:
        print("It's a hot day.")
    else:
        print("It's not a hot day.")
    ```

3.  **`if-elif-else` statement:**
    ```python
    score = 85
    if score >= 90:
        grade = "A"
    elif score >= 80:
        grade = "B"
    elif score >= 70:
        grade = "C"
    else:
        grade = "D"
    print(f"Your grade is: {grade}")
    ```

4.  **Nested `if` statements:**
    ```python
    age = 25
    is_student = True
    if age < 30:
        if is_student:
            print("You are eligible for a student discount.")
        else:
            print("You are not a student, so no discount.")
    else:
        print("You are not eligible for the youth discount.")
    ```

5.  **Using logical operators in conditions:**
    ```python
    username = "admin"
    password = "password123"
    if username == "admin" and password == "password123":
        print("Login successful.")
    else:
        print("Invalid credentials.")
    ```

---

## <a id="day-9"></a>Day 9: Loops: `for`

### 📘 **Definition: `for` Loop**
A **`for` loop** is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string). It executes a block of code for each item in the sequence.

### 🔢 **The `range()` Function**
The `range()` function generates a sequence of numbers.
- `range(stop)`: Generates numbers from 0 up to (but not including) `stop`.
- `range(start, stop)`: Generates numbers from `start` up to `stop`.
- `range(start, stop, step)`: Generates numbers from `start` to `stop`, with an increment of `step`.

### 📜 **Examples**

1.  **Iterating over a list:**
    ```python
    fruits = ["apple", "banana", "cherry"]
    for fruit in fruits:
        print(fruit)
    ```

2.  **Iterating over a string:**
    ```python
    for char in "Python":
        print(char)
    ```

3.  **Using `range()`:**
    ```python
    # Print numbers from 0 to 4
    for i in range(5):
        print(i)

    # Print numbers from 5 to 9
    for j in range(5, 10):
        print(j)
    ```

4.  **Iterating over a dictionary:**
    ```python
    person = {"name": "Alice", "age": 28, "city": "London"}
    # Iterate over keys
    for key in person:
        print(key, "->", person[key])

    # Iterate over items (key-value pairs)
    for key, value in person.items():
        print(f"{key}: {value}")
    ```

5.  **Nested `for` loops:**
    ```python
    # Print a multiplication table
    for i in range(1, 6): # Rows
        for j in range(1, 6): # Columns
            print(f"{i} * {j} = {i*j}")
        print("-" * 10)
    ```

---

## <a id="day-10"></a>Day 10: Loops: `while`

### 📘 **Definition: `while` Loop**
A **`while` loop** repeatedly executes a target statement as long as a given condition is true.

### 🔄 **`break` and `continue`**
- **`break`:** Terminates the loop statement and transfers execution to the statement immediately following the loop.
- **`continue`:** Causes the loop to skip the remainder of its body and immediately retest its condition prior to reiterating.

### 📜 **Examples**

1.  **Simple `while` loop:**
    ```python
    count = 0
    while count < 5:
        print(f"Count is: {count}")
        count += 1
    ```

2.  **Using `break`:**
    ```python
    # Find the first number divisible by 7
    num = 1
    while True: # This could be an infinite loop without a break
        if num % 7 == 0:
            print(f"Found the number: {num}")
            break
        num += 1
    ```

3.  **Using `continue`:**
    ```python
    # Print only odd numbers
    num = 0
    while num < 10:
        num += 1
        if num % 2 == 0:
            continue # Skip the rest of the loop for even numbers
        print(num)
    ```

4.  **A simple guessing game:**
    ```python
    import random
    secret_number = random.randint(1, 10)
    guess = 0
    while guess != secret_number:
        guess = int(input("Guess the number (1-10): "))
    print("Congratulations! You guessed it.")
    ```

5.  **Processing a list until it's empty:**
    ```python
    tasks = ["Task 1", "Task 2", "Task 3"]
    while tasks: # The loop continues as long as the list is not empty
        current_task = tasks.pop(0) # Get and remove the first task
        print(f"Processing: {current_task}")
    print("All tasks processed.")
    ```

---

## <a id="day-11"></a>Day 11: Functions

### 📘 **Definition: Function**
A **function** is a block of organized, reusable code that is used to perform a single, related action. Functions provide better modularity for your application and a high degree of code reusing.

### 🛠️ **Abbreviations**
- **DRY (Don't Repeat Yourself):** A principle of software development aimed at reducing repetition of software patterns.

### 🏛️ **Structure**
- **`def` keyword:** Used to define a function.
- **Function name:** Follows the same naming conventions as variables (`snake_case`).
- **Parameters:** Input values that are passed to the function (optional).
- **Docstring:** A string literal for documenting the function's purpose (optional but highly recommended).
- **`return` statement:** Exits a function, optionally passing back a value.

### 📜 **Examples**

1.  **A simple function with no parameters:**
    ```python
    def greet():
        """This function prints a simple greeting."""
        print("Hello from a function!")

    greet() # Calling the function
    ```

2.  **A function with parameters:**
    ```python
    def greet_user(name):
        """Greets a user by their name."""
        print(f"Hello, {name}!")

    greet_user("Alice")
    greet_user("Bob")
    ```

3.  **A function with a `return` value:**
    ```python
    def add_numbers(x, y):
        """Adds two numbers and returns the result."""
        return x + y

    sum_result = add_numbers(10, 5)
    print("Sum:", sum_result)
    ```

4.  **A function to calculate the area of a circle:**
    ```python
    import math

    def calculate_circle_area(radius):
        """Calculates the area of a circle given its radius."""
        return math.pi * (radius ** 2)

    area = calculate_circle_area(5)
    print(f"Area of the circle: {area:.2f}")
    ```

5.  **A function with local and global scope:**
    ```python
    global_var = "I am global"

    def my_function():
        local_var = "I am local"
        print(global_var) # Can access global variables
        print(local_var)

    my_function()
    # print(local_var) # This would cause a NameError
    ```

---

## <a id="day-12"></a>Day 12: Advanced Function Concepts

### 📘 **Default Arguments**
You can provide a default value for a parameter. This makes the parameter optional when calling the function.

### 📘 **Keyword Arguments (`kwargs`)**
You can pass arguments using the name of the parameter, which makes the order of arguments irrelevant. `**kwargs` allows a function to accept an arbitrary number of keyword arguments.

### 📘 **Arbitrary Arguments (`*args`)**
A function can accept an arbitrary number of positional arguments by using `*args`.

### 📘 **Lambda Functions**
A **lambda function** is a small, anonymous function defined with the `lambda` keyword. It can take any number of arguments, but can only have one expression.

### 📜 **Examples**

1.  **Default arguments:**
    ```python
    def power(base, exponent=2):
        """Calculates the power of a number, defaulting to square."""
        return base ** exponent

    print("Square of 3:", power(3))
    print("3 to the power of 4:", power(3, 4))
    ```

2.  **Keyword arguments:**
    ```python
    def describe_pet(animal_type, pet_name):
        """Displays information about a pet."""
        print(f"I have a {animal_type} named {pet_name}.")

    describe_pet(animal_type="hamster", pet_name="Harry")
    describe_pet(pet_name="Lucy", animal_type="cat") # Order doesn't matter
    ```

3.  **Using `*args`:**
    ```python
    def sum_all(*numbers):
        """Sums all the numbers passed as arguments."""
        total = 0
        for num in numbers:
            total += num
        return total

    print("Sum:", sum_all(1, 2, 3, 4, 5))
    ```

4.  **Using `**kwargs`:**
    ```python
    def build_profile(**user_info):
        """Builds a dictionary containing everything about a user."""
        return user_info

    profile = build_profile(name="John Doe", age=30, city="New York", profession="Developer")
    print(profile)
    ```

5.  **Lambda functions:**
    ```python
    # A lambda function to add 10 to a number
    add_ten = lambda x: x + 10
    print("15 + 10 =", add_ten(15))

    # Often used for simple operations in other functions like sort
    points = [(1, 2), (4, 1), (5, -3)]
    points.sort(key=lambda p: p[1]) # Sort by the second element of each tuple
    print("Sorted points:", points)
    ```

---

## <a id="day-13"></a>Day 13: File I/O

### 📘 **Definition: File I/O**
**File I/O (Input/Output)** refers to the process of reading from and writing to files.

### 🏛️ **Structure**
- **Opening a file:** Use the `open()` function. It takes a path and a mode.
- **Modes:**
  - `'r'`: Read (default).
  - `'w'`: Write (overwrites existing file or creates a new one).
  - `'a'`: Append (adds to the end of the file).
  - `'r+'`: Read and write.
- **The `with` statement:** The recommended way to work with files. It automatically closes the file when the block is exited, even if errors occur.

### 📜 **Examples**

1.  **Writing to a file (overwrite):**
    ```python
    with open("greetings.txt", "w") as f:
        f.write("Hello, World!\n")
        f.write("This is a new file.")
    ```

2.  **Reading from a file:**
    ```python
    with open("greetings.txt", "r") as f:
        content = f.read()
        print(content)
    ```

3.  **Appending to a file:**
    ```python
    with open("greetings.txt", "a") as f:
        f.write("\nAppending a new line.")
    ```

4.  **Reading a file line by line:**
    ```python
    with open("greetings.txt", "r") as f:
        for line in f:
            print(line.strip()) # .strip() removes leading/trailing whitespace
    ```

5.  **Reading all lines into a list:**
    ```python
    with open("greetings.txt", "r") as f:
        lines = f.readlines()
        print("Lines as a list:", lines)
    ```

---

## <a id="day-14"></a>Day 14: Modules and Libraries

### 📘 **Definition: Module**
A **module** is a file containing Python code. It can define functions, classes, and variables. A module can also include runnable code. Grouping related code into a module makes the code easier to understand and use.

### 📘 **Definition: Library**
A **library** is a collection of related modules. Python has a rich **Standard Library** that comes with the installation.

### 🛠️ **Abbreviations**
- **PIP (Pip Installs Packages):** The standard package manager for Python. It allows you to install and manage additional libraries that are not part of the standard library.

### 🏛️ **Importing**
- `import module_name`: Imports the entire module.
- `from module_name import function_name`: Imports a specific function from a module.
- `import module_name as alias`: Imports a module with an alias.

### 📜 **Examples**

1.  **Using the `math` module:**
    ```python
    import math

    print("Value of Pi:", math.pi)
    print("Square root of 16:", math.sqrt(16))
    ```

2.  **Using the `random` module:**
    ```python
    import random

    print("Random number between 1 and 100:", random.randint(1, 100))
    
    choices = ["rock", "paper", "scissors"]
    print("Random choice:", random.choice(choices))
    ```

3.  **Using the `datetime` module:**
    ```python
    from datetime import datetime

    now = datetime.now()
    print("Current date and time:", now)
    print("Formatted time:", now.strftime("%Y-%m-%d %H:%M:%S"))
    ```

4.  **Importing with an alias:**
    ```python
    import numpy as np # numpy is a popular third-party library

    # You would first need to install it: pip install numpy
    # my_array = np.array([1, 2, 3])
    # print(my_array)
    print("This is just an example of aliasing.")
    ```

5.  **Creating and using your own module:**
    ```python
    # 1. Create a file named my_module.py with this content:
    # def greet(name):
    #     print(f"Hello, {name} from my_module!")

    # 2. In your main file, you can import and use it:
    # import my_module
    # my_module.greet("Pythonista")
    print("This example shows how you would structure your own modules.")
    ```



## 🎉 Congratulations! 🎉

**You've completed the 2-week Python basics course!**

✨ *You now have a strong foundation to build upon. Keep practicing, building projects, and exploring new libraries!* ✨

![Course Complete](https://img.shields.io/badge/Status-Course%20Complete-success?style=for-the-badge&logo=python)
![Build Projects](https://img.shields.io/badge/Next%20Step-Build%20Projects-orange?style=for-the-badge&logo=rocket)

---

### 🚀 What's Next?

- **🔧 Build Projects** - Create real applications
- **📚 Learn Frameworks** - Django, Flask, FastAPI  
- **🔬 Data Science** - NumPy, Pandas, Matplotlib
- **🤖 AI/ML** - TensorFlow, PyTorch





---

<div align="center">

**Made with ❤️ for Python learners everywhere**

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>
