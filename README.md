# 🐍 Python from Scratch: A 2-Week Learning Plan

<div style="text-align: center; padding: 20px; background: linear-gradient(135deg, #3498db 0%, #8e44ad 100%); color: white; border-radius: 10px; margin-bottom: 30px;">
  <h2>🚀 Your Journey to Becoming a Python Pro</h2>
  <p><em>A comprehensive, day-by-day guide to mastering Python basics with detailed explanations and examples.</em></p>
</div>

---

## 🗓️ Learning Schedule

### Week 1: Core Fundamentals
- **Day 1:** [Introduction to Python](#day-1)
- **Day 2:** [Variables and Data Types](#day-2)
- **Day 3:** [Operators](#day-3)
- **Day 4:** [Strings in Depth](#day-4)
- **Day 5:** [Data Structures: Lists](#day-5)
- **Day 6:** [Data Structures: Tuples & Sets](#day-6)
- **Day 7:** [Data Structures: Dictionaries](#day-7)

### Week 2: Control Flow, Functions, and Beyond
- **Day 8:** [Conditional Statements](#day-8)
- **Day 9:** [Loops: `for`](#day-9)
- **Day 10:** [Loops: `while`](#day-10)
- **Day 11:** [Functions](#day-11)
- **Day 12:** [Advanced Function Concepts](#day-12)
- **Day 13:** [File I/O](#day-13)
- **Day 14:** [Modules and Libraries](#day-14)

---

## <a id="day-1"></a>Day 1: Introduction to Python

### 📘 **Definition: What is Python?**
Python is a **high-level, interpreted, general-purpose programming language**.
- **High-Level:** It abstracts away complex details of the computer's hardware.
- **Interpreted:** It executes code line by line, which makes debugging easier.
- **General-Purpose:** It can be used to create a wide variety of applications.

### 🌟 **Key Characteristics**
- **Readability:** Python's syntax is clean and easy to read, almost like plain English.
- **Simplicity:** It's relatively easy to learn, making it ideal for beginners.
- **Large Standard Library:** Comes with a rich library of pre-built modules and functions.
- **Cross-Platform:** Python code can run on Windows, macOS, and Linux without modification.

### 🛠️ **Abbreviations**
- **IDE (Integrated Development Environment):** A software application that provides comprehensive facilities to computer programmers for software development. Examples: VS Code, PyCharm, Sublime Text.
- **PEP (Python Enhancement Proposal):** A design document providing information to the Python community, or describing a new feature for Python or its processes or environment. `PEP 8` is the style guide for Python code.

### 🐍 **Your First Python Program: Hello, World!**
This is the traditional first program for learning any new language. It's a simple program that outputs `Hello, World!` to the screen.

```python
# This is a comment. It is ignored by the interpreter.
print("Hello, World!")
```

### ✍️ **Comments**
Comments are used to explain code. They are ignored by the Python interpreter.
- **Single-line comments:** Start with a `#`.
- **Multi-line comments:** Enclosed in triple quotes (`"""..."""` or `'''...'''`).

### 📜 **Examples**

1.  **Printing a simple message:**
    ```python
    print("Welcome to your Python journey!")
    ```

2.  **Using a single-line comment:**
    ```python
    # This line of code prints a number.
    print(123)
    ```

3.  **Using a multi-line comment:**
    ```python
    """
    This is a multi-line comment.
    It can span across multiple lines.
    This program calculates the sum of two numbers.
    """
    print(10 + 5)
    ```

4.  **Printing multiple lines:**
    ```python
    print("Line 1")
    print("Line 2")
    print("Line 3")
    ```

5.  **A program with comments explaining the logic:**
    ```python
    # Define two numbers
    num1 = 10
    num2 = 20

    # Calculate the sum
    sum_result = num1 + num2

    # Print the result
    print("The sum is:", sum_result)
    ```

---

## <a id="day-2"></a>Day 2: Variables and Data Types

### 📘 **Definition: Variables**
A **variable** is a container for storing a data value. In Python, you create a variable the moment you first assign a value to it.

###  conventions **Naming Conventions (PEP 8)**
- Use `snake_case` for variable names (e.g., `my_variable`, `user_name`).
- Variable names must start with a letter or an underscore.
- They cannot start with a number.
- They can only contain alpha-numeric characters and underscores (A-z, 0-9, and _).
- Variable names are case-sensitive (`age`, `Age`, and `AGE` are three different variables).

### 📘 **Definition: Data Types**
A **data type** is a classification that specifies which type of value a variable has and what type of mathematical, relational, or logical operations can be applied to it without causing an error.

### 📊 **Core Data Types**
- **Integer (`int`):** Whole numbers, positive or negative, without decimals.
- **Float (`float`):** Numbers, positive or negative, containing one or more decimals.
- **String (`str`):** A sequence of characters, enclosed in single, double, or triple quotes.
- **Boolean (`bool`):** Represents one of two values: `True` or `False`.

### 🔄 **Type Casting**
Type casting is the process of converting a variable from one data type to another.

### 📜 **Examples**

1.  **Creating variables of different data types:**
    ```python
    # Integer
    age = 25
    print("Age:", age, "Type:", type(age))

    # Float
    price = 19.99
    print("Price:", price, "Type:", type(price))

    # String
    name = "John Doe"
    print("Name:", name, "Type:", type(name))

    # Boolean
    is_student = True
    print("Is Student:", is_student, "Type:", type(is_student))
    ```

2.  **Using snake_case for variable names:**
    ```python
    first_name = "Alice"
    last_name = "Smith"
    user_age = 30
    is_active_user = False
    print(first_name, last_name, user_age, is_active_user)
    ```

3.  **Type casting from `int` to `str`:**
    ```python
    age = 30
    age_as_string = str(age)
    print("My age is " + age_as_string) # You can't concatenate string with int directly
    ```

4.  **Type casting from `float` to `int`:**
    ```python
    price = 29.99
    price_as_int = int(price) # The decimal part is truncated
    print("Price as integer:", price_as_int)
    ```

5.  **Type casting from `str` to `int` and `float`:**
    ```python
    num_str1 = "100"
    num_str2 = "50.75"

    num_int = int(num_str1)
    num_float = float(num_str2)

    print("String to int:", num_int)
    print("String to float:", num_float)
    ```

---

## <a id="day-3"></a>Day 3: Operators

### 📘 **Definition: Operators**
**Operators** are special symbols in Python that carry out arithmetic or logical computation. The value that the operator operates on is called the **operand**.

### 🧮 **Arithmetic Operators**
- `+` (Addition)
- `-` (Subtraction)
- `*` (Multiplication)
- `/` (Division - results in a float)
- `%` (Modulus - remainder of division)
- `**` (Exponentiation - `x ** y` = x to the power of y)
- `//` (Floor Division - division that results in a whole number, rounded down)

### ⚖️ **Comparison Operators**
- `==` (Equal to)
- `!=` (Not equal to)
- `>` (Greater than)
- `<` (Less than)
- `>=` (Greater than or equal to)
- `<=` (Less than or equal to)

### 🧠 **Logical Operators**
- `and` (Returns `True` if both statements are true)
- `or` (Returns `True` if one of the statements is true)
- `not` (Reverses the result, returns `False` if the result is true)

### ↔️ **Assignment Operators**
- `=` (Assign)
- `+=` (Add and assign, e.g., `x += 3` is `x = x + 3`)
- `-=` (Subtract and assign)
- `*=` (Multiply and assign)
- `/=` (Divide and assign)

### 📜 **Examples**

1.  **Arithmetic Operators:**
    ```python
    a = 10
    b = 3
    print("Addition:", a + b)
    print("Subtraction:", a - b)
    print("Multiplication:", a * b)
    print("Division:", a / b)
    print("Modulus:", a % b)
    print("Exponentiation:", a ** b)
    print("Floor Division:", a // b)
    ```

2.  **Comparison Operators:**
    ```python
    x = 5
    y = 10
    print("Is x equal to y?", x == y)
    print("Is x not equal to y?", x != y)
    print("Is x greater than y?", x > y)
    print("Is x less than or equal to y?", x <= y)
    ```

3.  **Logical Operators:**
    ```python
    age = 22
    is_student = True
    print("Is eligible for discount?", age < 25 and is_student)
    print("Is a senior or a student?", age > 65 or is_student)
    print("Not a student?", not is_student)
    ```

4.  **Assignment Operators:**
    ```python
    count = 0
    count += 1  # Increment by 1
    print("Count:", count)

    total = 100
    total -= 10 # Decrement by 10
    print("Total:", total)
    ```

5.  **Combining operators:**
    ```python
    # Calculate the area of a rectangle
    length = 15
    width = 10
    area = length * width

    # Check if the area is greater than 100
    is_large_area = area > 100
    print("Area:", area)
    print("Is the area large?", is_large_area)
    ```

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

<div style="text-align: center; padding: 20px; background: linear-gradient(135deg, #1abc9c 0%, #16a085 100%); color: white; border-radius: 10px; margin-top: 30px;">
  <h3>🎉 Congratulations! You've completed the 2-week Python basics course! 🎉</h3>
  <p><em>You now have a strong foundation to build upon. Keep practicing, building projects, and exploring new libraries!</em></p>
</div>
