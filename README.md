Below is a README file that you can use for a repository named "Mastering AI 01: Python for AI." This README file contains all the information you provided, structured in a way that is easy to follow and organized for a learning journey.

---

# Mastering AI 01: Python for AI

## Introduction

Welcome to **Mastering AI 01: Python for AI**! This repository is designed to help you master Python, with a focus on developing skills that are crucial for AI and machine learning. The content is organized into a detailed, step-by-step learning path that spans from Python fundamentals to advanced object-oriented programming (OOP) concepts.

Whether you are a beginner or have some programming experience, this guide will help you solidify your Python skills and prepare you for the challenges of AI development.

## Table of Contents

1. [Python Fundamentals](#1-python-fundamentals)
    - [1.1 Syntax and Semantics](#11-syntax-and-semantics)
    - [1.2 Variables and Data Types](#12-variables-and-data-types)
    - [1.3 Operators](#13-operators)
    - [1.4 Control Flow (Conditionals)](#14-control-flow-conditionals)
    - [1.5 Loops](#15-loops)
2. [Intermediate Python](#2-intermediate-python)
    - [2.1 Comprehensions](#21-comprehensions)
    - [2.2 Lambda Functions](#22-lambda-functions)
    - [2.3 Decorators](#23-decorators)
    - [2.4 Generators and Iterators](#24-generators-and-iterators)
    - [2.5 File Handling](#25-file-handling)
    - [2.6 Regular Expressions](#26-regular-expressions)
    - [2.7 Collections Module](#27-collections-module)
    - [2.8 Context Managers](#28-context-managers)
3. [Object-Oriented Programming (OOP)](#3-object-oriented-programming-oop)
    - [3.1 Classes and Objects](#31-classes-and-objects)
    - [3.2 Constructors (`__init__` method)](#32-constructors-__init__-method)
    - [3.3 Instance, Class, and Static Methods](#33-instance-class-and-static-methods)
    - [3.4 Encapsulation, Inheritance, Polymorphism, and Abstraction](#34-encapsulation-inheritance-polymorphism-and-abstraction)
    - [3.5 Special Methods and Operator Overloading](#35-special-methods-and-operator-overloading)
    - [3.6 Property Decorators and Getters/Setters](#36-property-decorators-and-getterssetters)
    - [3.7 Abstract Classes and Interfaces (using `abc` module)](#37-abstract-classes-and-interfaces-using-abc-module)

---

## 1. Python Fundamentals

### 1.1 Syntax and Semantics

**Concepts:**
- Indentation: Python uses indentation (whitespace) to define the structure of code blocks (e.g., functions, loops, conditionals).
- Comments: Use `#` for single-line comments and `'''` or `"""` for multi-line comments.
- Python Scripts vs. Interactive Mode: Writing and running Python scripts versus using the interactive interpreter (REPL).

**Practice:**
1. Write a Python script that prints "Hello, World!" and run it in both a script file and the interactive interpreter.
2. Experiment with indentation errors by creating a function and deliberately misaligning some of the code inside it.
3. Add single-line and multi-line comments to a Python script and observe how they are ignored during execution.
4. Write a script that includes both a print statement and a comment. Run it in the interactive mode and in a script file.
5. Create a Python script that includes multiple print statements with different levels of indentation. Observe the behavior and correct any indentation errors.

### 1.2 Variables and Data Types

**Concepts:**
- Variables: Containers for storing data values. Variables are dynamically typed in Python.
- Data Types:
  - Primitive Types: Integer (`int`), Float (`float`), String (`str`), Boolean (`bool`).
  - Complex Types: Complex numbers (`complex`).
- Type Conversion: Converting between types using functions like `int()`, `float()`, `str()`, etc.
- Input/Output:
  - `input()` function to take user input.
  - `print()` function to display output.

**Practice:**
1. Create variables of different types (int, float, string, bool) and print their types using the `type()` function.
2. Write a program that asks the user for two numbers and prints their sum, difference, product, and quotient.
3. Convert a float to an integer and observe the loss of precision. Write code to demonstrate this.
4. Write a program that takes a user’s name and age as input, then prints a greeting message including the name and calculates the year they will turn 100 years old.
5. Create a program that takes a string input from the user and checks if it can be converted to a number. If it can, convert it and print the number; otherwise, print an error message.

### 1.3 Operators

**Concepts:**
- Arithmetic Operators: `+`, `-`, `*`, `/`, `%`, `**`, `//`.
- Comparison Operators: `==`, `!=`, `>`, `<`, `>=`, `<=`.
- Logical Operators: `and`, `or`, `not`.
- Assignment Operators: `=`, `+=`, `-=`, `*=`, `/=`, etc.
- Bitwise Operators: `&`, `|`, `^`, `~`, `<<`, `>>`.

**Practice:**
1. Write a program that takes two numbers from the user and performs all the arithmetic operations (`+`, `-`, `*`, `/`, `%`, `**`, `//`) on them.
2. Create a script that compares two numbers and prints whether the first is greater than, less than, or equal to the second.
3. Write a program that demonstrates the use of all logical operators (`and`, `or`, `not`) by evaluating expressions and printing the results.
4. Develop a program that uses assignment operators to increment, decrement, multiply, and divide a number provided by the user.
5. Create a program that uses bitwise operators to perform AND, OR, XOR, and NOT operations on two integers provided by the user. Print the binary representation of the results.

### 1.4 Control Flow (Conditionals)

**Concepts:**
- If Statements: `if`, `elif`, `else`.
- Nested Conditionals: Conditionals within other conditionals.
- Ternary Operator: `x if condition else y` (short form of conditional).

**Practice:**
1. Write a program that takes a number as input and checks if it is positive, negative, or zero. Print an appropriate message.
2. Create a script that assigns grades (A, B, C, D, F) based on a numeric score provided by the user. Use nested conditionals to handle the different ranges of scores.
3. Develop a program that takes the current time (in 24-hour format) as input and prints whether it is morning, afternoon, evening, or night.
4. Write a program that uses a ternary operator to determine and print whether a number is even or odd.
5. Create a program that checks if a given year is a leap year or not using a series of conditionals.

### 1.5 Loops

**Concepts:**
- For Loop: Iterating over a sequence (e.g., list, string).
- While Loop: Repeating as long as a condition is true.
- Loop Control Statements: `break`, `continue`, `pass`.
- Nested Loops: Loops within loops.

**Practice:**
1. Write a program to print the first 10 Fibonacci numbers using a `for` loop.
2. Create a multiplication table (from 1 to 10) using nested `for` loops.
3. Develop a program that uses a `while` loop to keep asking the user for input until they enter the word "exit".
4. Write a script that iterates over a list of numbers and prints only the even numbers using the `continue` statement.
5. Implement a program that uses a `for` loop to iterate through a string and print each character on a new line. Use the `break` statement to stop the loop if a specific character is encountered.

---

## 2. Intermediate Python

### 2.1 Comprehensions

**Concepts:**
- List Comprehensions: Concise way to create lists.
- Dictionary Comprehensions: Create dictionaries in a single line.
- Set Comprehensions: Create sets using comprehensions.

**Practice:**
1. Use a list comprehension to create a list of squares of the first 10 positive integers.
2. Write a list comprehension to filter out even numbers from a list of integers provided by the user.
3. Create a dictionary comprehension that maps each letter in a string to its corresponding ASCII value.
4. Write a set comprehension to create a set of unique vowels found in a user-provided string.
5. Develop a list comprehension that generates a list of tuples containing a number and its square for numbers between 1 and 10.

### 2.2 Lambda Functions

**Concepts:**
- Anonymous Functions: Functions defined with `lambda` that have no name.
- Syntax: `lambda arguments: expression`.
- Use Cases: Typically used for short, simple functions passed as arguments.

**Practice:**
1. Write a lambda function to

 add 10 to a given number and test it.
2. Use a lambda function within the `sorted()` function to sort a list of tuples by the second element.
3. Create a list of tuples and use a lambda function to sort the list by the product of the tuple elements.
4. Implement a lambda function that filters out strings from a list that start with a given letter.
5. Write a script that uses a lambda function to calculate the cube of numbers in a list.

### 2.3 Decorators

**Concepts:**
- Function Wrapping: Decorators are functions that modify the behavior of other functions.
- Syntax: `@decorator_name` above a function definition.
- Use Cases: Used for logging, access control, memoization, etc.

**Practice:**
1. Write a simple decorator that prints "Function is running" before a function executes.
2. Create a decorator that checks if the input to a function is a non-negative integer before allowing the function to execute.
3. Write a memoization decorator that caches the results of an expensive function.
4. Develop a decorator that logs the execution time of a function.
5. Implement a decorator that modifies a function to only execute a certain number of times before stopping.

### 2.4 Generators and Iterators

**Concepts:**
- Iterators: Objects that can be iterated over (`__iter__()` and `__next__()` methods).
- Generators: Functions that yield values one at a time using `yield`.
- Use Cases: Efficient iteration over large datasets.

**Practice:**
1. Create a generator that yields the first `n` Fibonacci numbers.
2. Write an iterator class that returns even numbers up to a given limit.
3. Implement a generator that produces an infinite sequence of prime numbers.
4. Develop a generator that yields lines from a large text file one by one.
5. Create a generator expression to filter and yield only even numbers from a list.

### 2.5 File Handling

**Concepts:**
- Opening Files: `open()` function with modes like `r`, `w`, `a`, `b`.
- Reading and Writing: `read()`, `readline()`, `readlines()`, `write()`.
- Context Managers: Using `with` to manage file resources.

**Practice:**
1. Write a program that reads a text file and counts the occurrences of each word.
2. Create a script that writes a list of numbers to a file and then reads it back, printing the numbers line by line.
3. Develop a program that reads a CSV file and prints its content in a formatted way.
4. Implement a script that appends user input to a log file every time it is run.
5. Write a program that uses a context manager to safely open and read a file, handling any potential exceptions.

### 2.6 Regular Expressions

**Concepts:**
- Pattern Matching: Using the `re` module to search for patterns in strings.
- Basic Patterns: `.` (any character), `*` (0 or more), `+` (1 or more), `[]` (character set), `^` (start of string), `$` (end of string).
- Common Functions: `re.search()`, `re.match()`, `re.findall()`, `re.sub()`.

**Practice:**
1. Write a regular expression to validate an email address.
2. Create a script that extracts all the phone numbers from a given text.
3. Develop a program that replaces all occurrences of a specific word in a string with another word.
4. Write a regular expression to find all dates in a text that are in the format `dd-mm-yyyy`.
5. Implement a function that splits a string into a list of words, but only words that contain alphabetic characters.

### 2.7 Collections Module

**Concepts:**
- `defaultdict`: A dictionary that provides a default value for non-existent keys.
- `namedtuple`: Lightweight object type similar to a tuple, but with named fields.
- `deque`: Double-ended queue with fast appends and pops.
- `Counter`: A subclass of dictionary for counting hashable objects.

**Practice:**
1. Use `defaultdict` to group a list of words by their first letter.
2. Create a `namedtuple` to store and print information about a person (e.g., name, age, occupation).
3. Write a program that uses `deque` to simulate a queue where items are added to the end and removed from the beginning.
4. Develop a script that uses `Counter` to count the frequency of characters in a string.
5. Implement a program that uses `defaultdict` to count occurrences of words in a text, grouping them by their length.

### 2.8 Context Managers

**Concepts:**
- `with` Statement: Simplifies resource management by automatically handling cleanup.
- Custom Context Managers: Using `__enter__` and `__exit__` methods.

**Practice:**
1. Use a context manager to open and safely close a file for reading.
2. Implement a custom context manager that measures and prints the execution time of a code block.
3. Write a context manager that logs the entry and exit of a code block to a file.
4. Develop a context manager that temporarily changes the current working directory and then reverts it back.
5. Create a context manager that opens a network socket and ensures it is properly closed after use.

---

## 3. Object-Oriented Programming (OOP)

### 3.1 Classes and Objects

**Concepts:**
- Class Definition: Using the `class` keyword to define a blueprint for objects.
- Creating Objects: Instantiating objects from a class.
- Instance Attributes and Methods: Variables and functions that belong to an object.

**Practice:**
1. Define a `Car` class with attributes like `make`, `model`, and `year`, and a method `start_engine()`. Create instances and call methods.
2. Write a `Dog` class with methods `bark()` and `sit()`, and attributes like `name` and `breed`. Instantiate multiple `Dog` objects and call their methods.
3. Create a `BankAccount` class with methods to `deposit()`, `withdraw()`, and check the balance. Instantiate the class and simulate transactions.
4. Implement a `Book` class with attributes like `title`, `author`, and `pages`, and a method to display book details. Instantiate and test the class.
5. Develop a `Rectangle` class with methods to calculate the area and perimeter, and attributes for `length` and `width`. Create instances and compute area and perimeter.

### 3.2 Constructors (`__init__` method)

**Concepts:**
- Initialization: The `__init__` method runs as soon as an object is instantiated.
- Setting Initial State: Use `__init__` to set the initial state of the object.

**Practice:**
1. Modify the `Car` class to include an `__init__` method that takes `make`, `model`, and `year` as parameters and sets the corresponding attributes.
2. Create a `Circle` class with an `__init__` method that initializes the radius and calculates the area and circumference. Test it by creating different circles.
3. Write a `Student` class with an `__init__` method that takes `name` and `grades` as arguments and calculates the average grade. Instantiate and test.
4. Develop a `Movie` class with an `__init__` method that initializes attributes like `title`, `director`, `release_year`, and `rating`. Create instances and display movie details.
5. Implement a `Product` class that initializes `name`, `price`, and `quantity` attributes and includes a method to calculate the total cost. Create instances and compute costs.

### 3.3 Instance, Class, and Static Methods

**Concepts:**
- Instance Methods: Operate on the instance of the class.
- Class Methods: Operate on the class itself, not on instances (`@classmethod`).
- Static Methods: Do not operate on instances or the class itself, but are included in the class for organizational purposes (`@staticmethod`).

**Practice:**
1. Add an instance method to the `Car` class that prints a statement using the car's attributes (`make`, `model`, `year`).
2. Implement a class method in a `BankAccount` class to track and return the total number of accounts created.
3. Write a static method in the `Rectangle` class that checks if two rectangles have the same area. Test it with different instances.
4. Create a `Temperature` class with a class method to convert Celsius to Fahrenheit and a static method to check if a temperature is below freezing.
5. Develop a `Library` class with a class method to keep track of the number of books and a static method to check if a book is available based on a list of books.

### 3.4 Encapsulation, Inheritance, Polymorphism, and Abstraction

**Concepts:**
- Encapsulation: Bundling of data (attributes) and methods that operate on the data within one unit, and restricting access to some of the object's components.
- Inheritance: Deriving a new class from an existing class, enabling code reuse and extension.
- Polymorphism: Ability to use a unified interface to work with objects of different types.
- Abstraction: Hiding the complex implementation details and exposing only the necessary parts.

**Practice:**
1. Create a `Vehicle` class with basic attributes like `speed` and `color`, and a method `drive()`. Derive a `Car` class from `Vehicle` that adds specific attributes and methods.
2. Implement method overriding in the `Car` class to change how the `drive()` method behaves compared to the `Vehicle

` class.
3. Write a `Shape` class with a method `area()`. Derive `Circle` and `Rectangle` classes that implement the `area()` method differently, demonstrating polymorphism.
4. Use abstraction to define a `Payment` class with an abstract method `process_payment()` and implement this method differently in `CreditCardPayment` and `PaypalPayment` subclasses.
5. Implement a `BankAccount` class with private attributes `_balance` and methods to access and modify the balance using encapsulation.

### 3.5 Special Methods and Operator Overloading

**Concepts:**
- Magic Methods: Special methods with double underscores like `__str__`, `__repr__`, `__len__`, `__eq__`, etc.
- Operator Overloading: Defining how operators behave with objects of your custom class.

**Practice:**
1. Implement the `__str__` and `__repr__` methods in the `Car` class to provide meaningful string representations.
2. Overload the `+` operator in a `Vector` class to add two vectors by their components.
3. Write a `Fraction` class and overload the `*` operator to multiply two fractions.
4. Implement a `Time` class to represent hours and minutes, and overload the `-` operator to find the difference between two `Time` objects.
5. Create a `ComplexNumber` class and overload the `==` operator to compare two complex numbers for equality.

### 3.6 Property Decorators and Getters/Setters

**Concepts:**
- Property Decorators: Use `@property` to define getter methods that allow access to private variables.
- Getters and Setters: Control access to private attributes with methods that encapsulate them.

**Practice:**
1. Add a private attribute `_price` to the `Car` class and control its access using getter and setter methods.
2. Use the `@property` decorator to simplify access to the `_balance` attribute in the `BankAccount` class, with validation in the setter method.
3. Implement a `Person` class with a private `_age` attribute and use getter and setter methods to enforce that age cannot be set to a negative number.
4. Write a `Product` class with private attributes for `name`, `price`, and `quantity`, and implement property decorators to get and set these attributes with validation.
5. Develop a `Rectangle` class with private attributes `_length` and `_width` and use property decorators to calculate and retrieve the area.

### 3.7 Abstract Classes and Interfaces (using `abc` module)

**Concepts:**
- Abstract Base Classes: Classes that cannot be instantiated and are meant to be inherited.
- Abstract Methods: Methods that must be implemented in any subclass of an abstract class.

**Practice:**
1. Define an abstract class `Vehicle` with an abstract method `drive()` and implement it in the derived classes `Car` and `Bike`.
2. Create an abstract class `Animal` with an abstract method `make_sound()` and implement this method in `Dog` and `Cat` classes.
3. Write an abstract class `Shape` with abstract methods `area()` and `perimeter()`. Implement these methods in `Circle` and `Square` subclasses.
4. Develop an abstract base class `Employee` with an abstract method `calculate_salary()` and extend it in `FullTimeEmployee` and `PartTimeEmployee` classes.
5. Implement an abstract class `MediaPlayer` with an abstract method `play()` and create concrete classes `AudioPlayer` and `VideoPlayer` that implement `play()`.

---

## Conclusion

This repository is a comprehensive guide for anyone looking to master Python with a focus on AI. By following the structured learning path and completing the exercises provided, you will build a solid foundation in Python that will prepare you for advanced topics in AI, machine learning, and data science.

Happy coding!

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This README file should give learners clear instructions and goals for mastering Python as part of their journey into AI. You can adapt or expand the content as needed based on your specific use case or audience.
