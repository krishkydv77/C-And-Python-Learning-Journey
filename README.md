# C & Python Learning Journey

<p align="center">
  <b>From Programming Fundamentals to Advanced Python, OOP, Problem Solving & Data Analysis</b>
</p>

<p align="center">
  <a href="https://github.com/krishkydv77/C-And-Python-Learning-Journey">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub Repository"/>
  </a>
  <img src="https://img.shields.io/badge/C-Programming%20Fundamentals-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C Programming"/>
  <img src="https://img.shields.io/badge/Python-Core%20%26%20Advanced-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/OOP-Object--Oriented%20Programming-6C63FF?style=for-the-badge" alt="OOP"/>
  <img src="https://img.shields.io/badge/Status-Continuous%20Learning-success?style=for-the-badge" alt="Learning Status"/>
</p>

<p align="center">
  A practical programming repository covering C programming, Python fundamentals, advanced Python concepts, object-oriented programming, coding assignments, projects, and data analysis.
</p>



## About This Repository

Welcome to my **C & Python Learning Journey** — a structured collection of programming concepts, hands-on exercises, assignments, and practical implementations.

This repository documents my progression from understanding programming fundamentals to exploring advanced Python features and applying programming skills to problem-solving and data analysis.

The objective is not just to learn syntax, but to understand how programs work, how to write readable and reusable code, and how programming concepts translate into practical applications.

### What This Repository Covers

- C programming fundamentals and logical problem-solving.
- Python syntax, data types, operators, and control flow.
- Functions, arguments, recursion, and reusable code.
- Object-Oriented Programming (OOP).
- Iterators, generators, decorators, and advanced Python concepts.
- Exception handling, file handling, and modules.
- Coding assignments and programming exercises.
- Python projects and practical implementations.
- NumPy, Pandas, and data analysis fundamentals.
- Data visualization using Matplotlib, Seaborn, and Plotly.

## Quick Navigation

| Learning Area | Repository Folder | Purpose |
|---|---|---|
| Advanced Python | [Advanced Python concepts](./Advanced%20Python%20concepts/) | Advanced language concepts and Python techniques |
| C Programming | [C-Logical_concept_Assignmenet](./C-Logical_concept_Assignmenet/) | C programming and logical exercises |
| Python Projects | [Python - project](./Python%20-%20project/) | Practical Python projects |
| Python Assignments | [Python_concept_Assignment](./Python_concept_Assignment/) | Topic-based Python practice and assignments |



# Part 1 — C Programming

## 1. Introduction to C

C is a general-purpose, procedural programming language widely used in systems programming, embedded systems, operating systems, and performance-sensitive applications.

C helps develop a strong understanding of programming fundamentals, memory, data representation, and algorithmic problem-solving.

### Core Concepts

- Structure of a C program.
- Header files and `main()`.
- Variables and constants.
- Keywords and identifiers.
- Data types and type conversion.
- Input and output using `printf()` and `scanf()`.
- Operators and expressions.
- Compilation, linking, and execution.
- Syntax errors, runtime errors, and logical errors.

### Example

```c
#include <stdio.h>

int main(void) {
    int a = 10;
    int b = 20;

    printf("Sum = %d\n", a + b);

    return 0;
}
```

**Explanation:** The program declares two integer variables, calculates their sum, and displays the result.

## 2. Data Types and Variables

A variable is a named memory location used to store a value. A data type determines the kind of value a variable can represent and how operations on that value behave.

Common C data types include:

- `char` — character and small integer values.
- `int` — integer values.
- `float` — single-precision floating-point values.
- `double` — double-precision floating-point values.
- `void` — absence of a value or type in applicable contexts.

Related concepts:

- Signed and unsigned types.
- Type modifiers.
- Constants using `const`.
- Implicit and explicit type conversion.
- Scope and lifetime of variables.
- Format specifiers.

## 3. Operators and Expressions

Operators perform operations on operands.

- Arithmetic: `+`, `-`, `*`, `/`, `%`.
- Relational: `<`, `>`, `<=`, `>=`, `==`, `!=`.
- Logical: `&&`, `||`, `!`.
- Assignment: `=`, `+=`, `-=`, `*=`.
- Increment and decrement: `++`, `--`.
- Bitwise: `&`, `|`, `^`, `~`, `<<`, `>>`.
- Conditional operator: `?:`.
- `sizeof` operator.

Important concepts include operator precedence, associativity, short-circuit evaluation, and integer division.

## 4. Conditional Statements

Conditional statements execute different code depending on whether a condition is true or false.

- `if`
- `if-else`
- `else-if` ladder.
- Nested conditions.
- `switch-case`.
- Conditional operator.

These are useful for decision-making, validation, menu-driven applications, and business logic.

## 5. Loops and Iteration

Loops repeat a block of code while a condition or iteration rule is satisfied.

- `for` loop.
- `while` loop.
- `do-while` loop.
- Nested loops.
- `break`.
- `continue`.

Practice problems can include number patterns, multiplication tables, factorials, prime numbers, digit operations, and sequence generation.

## 6. Arrays and Strings

### Arrays

An array stores multiple elements of the same type in contiguous memory.

Topics:
- One-dimensional arrays.
- Multidimensional arrays.
- Array traversal.
- Searching and sorting.
- Passing arrays to functions.
- Array bounds and memory safety.

### Strings

C strings are character sequences terminated by the null character `'\0'`.

Topics:
- Character arrays.
- String input and output.
- String traversal.
- String length and comparison.
- String copying and concatenation.
- Standard library functions from `<string.h>`.
- Safe input handling and buffer boundaries.

## 7. Functions

A function is a reusable block of code that performs a specific task.

Topics:
- Function declaration and definition.
- Function calls.
- Parameters and return values.
- Standard library functions.
- User-defined functions.
- Function prototypes.
- Local and global scope.
- Passing arguments by value.
- Simulating reference-style updates using pointers.
- Recursive functions.

### Recursion

Recursion occurs when a function calls itself to solve a smaller version of a problem.

A recursive function needs a **base case** to stop recursion and a recursive case to continue solving the problem.

## 8. Pointers and Memory

A pointer stores the memory address of an object or function where applicable.

Topics:
- Address-of operator `&`.
- Dereference operator `*`.
- Pointer declaration and initialization.
- Pointer arithmetic.
- Pointers and arrays.
- Pointers and functions.
- Double pointers.
- Null pointers.
- Dynamic memory allocation.
- `malloc()`, `calloc()`, `realloc()`, and `free()`.
- Memory leaks and dangling pointers.

Pointer and memory concepts are fundamental to understanding how C interacts with memory directly.

## 9. Structures, Unions, and Enumerations

- `struct` — groups related members, potentially of different types.
- `union` — allows members to share storage.
- `enum` — defines named integral constants.
- `typedef` — introduces a type alias.
- Arrays of structures.
- Nested structures.
- Pointers to structures.
- Accessing members with `.` and `->`.

## 10. File Handling

File handling allows programs to read and write persistent data.

Topics:
- File pointers using `FILE *`.
- Opening and closing files.
- `fopen()` and `fclose()`.
- Reading and writing text files.
- `fprintf()` and `fscanf()`.
- `fgets()` and `fputs()`.
- Binary file operations.
- File modes and error checking.
- End-of-file handling.

## 11. Preprocessor and Compilation

- `#include`.
- `#define`.
- Header guards.
- Conditional compilation.
- Macros.
- Source files and header files.
- Compilation and linking.
- Build errors and warnings.
- Modular program design.

## 12. C Problem-Solving Practice

Recommended practice areas:

- Number-based problems.
- Pattern printing.
- Arrays and strings.
- Searching and sorting.
- Functions and recursion.
- Pointers and memory.
- Structures and records.
- File handling.
- Logical reasoning.
- Time and space complexity fundamentals.

**Explore:** [C Logical Concepts and Assignments](./C-Logical_concept_Assignmenet/)



# Part 2 — Python Programming Fundamentals

## 13. Introduction to Python

Python is a high-level, general-purpose programming language known for readable syntax and a broad ecosystem of libraries.

It is used in automation, backend development, data analytics, machine learning, artificial intelligence, and scripting.

### Core Concepts

- Python installation and execution.
- Interactive interpreter and script execution.
- Indentation and code blocks.
- Comments and documentation.
- Variables and naming conventions.
- Keywords and identifiers.
- Built-in data types.
- Dynamic typing.
- Type conversion.
- Basic input and output.

### Example

```python
name = "Krishan"
experience_area = "Python Programming"

print(f"{name} is learning {experience_area}.")
```

## 14. Python Data Types

Python provides built-in types for representing different kinds of data.

| Type | Definition | Example |
|---|---|---|
| `int` | Integer numbers | `age = 25` |
| `float` | Floating-point numbers | `price = 99.5` |
| `complex` | Complex numbers | `z = 2 + 3j` |
| `bool` | Boolean values | `is_active = True` |
| `str` | Text sequences | `name = "Python"` |
| `list` | Ordered, mutable collection | `[10, 20, 30]` |
| `tuple` | Ordered, immutable collection | `(10, 20, 30)` |
| `set` | Collection of unique elements | `{10, 20, 30}` |
| `dict` | Key-value mapping | `{"name": "Krishan"}` |
| `NoneType` | Represents absence of a value | `result = None` |

Important distinctions:

- Mutable vs immutable objects.
- Hashable vs unhashable objects.
- Identity vs equality.
- Type checking using `type()` and `isinstance()`.
- Explicit type conversion.
- Truthy and falsy values.

## 15. Python Operators

- Arithmetic operators.
- Comparison operators.
- Logical operators.
- Assignment operators.
- Bitwise operators.
- Membership operators: `in`, `not in`.
- Identity operators: `is`, `is not`.

**Important:** `==` compares values for equality, while `is` checks whether two references point to the same object.

## 16. Conditional Statements and Loops

### Conditional Statements

- `if`
- `elif`
- `else`
- Nested conditions.
- Conditional expressions.

### Loops

- `for` loops.
- `while` loops.
- Nested loops.
- `break`.
- `continue`.
- `pass`.
- `range()`.
- Looping through strings, lists, dictionaries, and other iterables.

Additional concepts:
- `enumerate()`.
- `zip()`.
- Loop `else` clauses.
- Comprehensions as concise alternatives for creating collections.

## 17. Python Collections

### Lists

Lists are ordered, mutable sequences.

Common operations:
- Indexing and slicing.
- Adding and removing elements.
- Updating elements.
- Searching and sorting.
- Nested lists.
- List comprehensions.

### Tuples

Tuples are ordered, immutable sequences.

Topics:
- Indexing and unpacking.
- Multiple assignment.
- Returning multiple values.
- Named tuples as a related concept.

### Sets

Sets store unique hashable elements.

Topics:
- Adding and removing elements.
- Union.
- Intersection.
- Difference.
- Symmetric difference.
- Membership testing.

### Dictionaries

Dictionaries map hashable keys to values.

Topics:
- Creating and updating key-value pairs.
- Accessing values.
- Iterating through keys, values, and items.
- Dictionary methods.
- Nested dictionaries.
- Dictionary comprehensions.
- Counting and grouping patterns.

## 18. String Manipulation

Strings are immutable sequences of Unicode characters.

Topics:
- Indexing and slicing.
- String formatting.
- f-strings.
- `split()` and `join()`.
- `strip()`, `replace()`, and `find()`.
- `startswith()` and `endswith()`.
- Case conversion.
- Searching and counting.
- String validation.
- Regular expressions using `re`.

---

# Part 3 — Functions and Functional Techniques

## 19. Functions in Python

A function is a reusable unit of code designed to perform a particular operation.

Functions help reduce duplication, organize programs, improve testability, and separate responsibilities.

### Function Concepts

- Defining functions with `def`.
- Calling functions.
- Parameters and arguments.
- Return values.
- Default arguments.
- Positional arguments.
- Keyword arguments.
- Variable-length arguments using `*args`.
- Variable-length keyword arguments using `**kwargs`.
- Keyword-only and positional-only parameters.
- Local and global scope.
- The `global` and `nonlocal` keywords.
- Docstrings and type hints.
- Recursive functions.
- Lambda expressions.
- Higher-order functions.

### Example

```python
def calculate_total(price: float, quantity: int = 1) -> float:
    """Return the total cost for the given quantity."""
    return price * quantity


print(calculate_total(250, 3))
```

**Output**

```text
750
```

## 20. Lambda, Map, Filter, and Reduce

### Lambda

A lambda is a small anonymous function consisting of a single expression.

```python
square = lambda number: number ** 2
print(square(5))
```

### `map()`

Applies a function to each element of an iterable.

### `filter()`

Selects elements that satisfy a condition.

### `reduce()`

Combines iterable elements cumulatively using a function from `functools`.

These techniques are useful for transformations and functional-style processing. For simple data transformations, comprehensions can often be more readable.

## 21. List, Set, and Dictionary Comprehensions

Comprehensions provide a concise way to construct collections.

```python
squares = [number ** 2 for number in range(1, 6)]

even_numbers = {
    number for number in range(1, 11)
    if number % 2 == 0
}

lookup = {
    number: number ** 2
    for number in range(1, 6)
}
```

Topics:
- Basic comprehensions.
- Conditional comprehensions.
- Nested comprehensions.
- Dictionary transformations.
- Readability and performance considerations.

## 22. Iterators and Iterables

An **iterable** is an object that can provide an iterator, typically through `iter()`.

An **iterator** is an object that returns elements one at a time through `next()` and follows the iterator protocol.

### Example

```python
numbers = [10, 20, 30]
iterator = iter(numbers)

print(next(iterator))
print(next(iterator))
print(next(iterator))
```

Important concepts:
- `iter()`.
- `next()`.
- The `StopIteration` exception.
- Iterator protocol.
- Custom iterator classes.
- Lazy evaluation.
- Single-pass iterators.
- Iteration over files and large datasets.

## 23. Generators

A **generator** is a convenient way to create an iterator that produces values lazily instead of building an entire sequence in memory at once.

Generators are useful for processing large files, streaming data, and creating memory-efficient pipelines.

### Generator Function

A generator function uses `yield` to produce values one at a time. Its execution can resume from where it paused.

```python
def generate_squares(limit: int):
    for number in range(1, limit + 1):
        yield number ** 2


for value in generate_squares(5):
    print(value)
```

### Generator Expression

```python
squares = (number ** 2 for number in range(1, 6))

for value in squares:
    print(value)
```

### Generator Concepts

- `yield` vs `return`.
- Lazy evaluation.
- Generator expressions.
- Iteration and `StopIteration`.
- Generator state.
- `yield from`.
- `send()` and generator communication.
- Memory-efficient iteration.
- Streaming data pipelines.

**Interview distinction:** `return` ends a function and returns a result. `yield` produces a value while preserving the generator's execution state for later resumption.

## 24. Decorators

A **decorator** is a callable that takes another callable and returns a callable, commonly adding behavior without modifying the original function's source code.

Decorators are frequently used for logging, timing, access checks, caching, and framework features.

### Example

```python
from functools import wraps


def log_call(function):
    @wraps(function)
    def wrapper(*args, **kwargs):
        print(f"Calling {function.__name__}")
        return function(*args, **kwargs)

    return wrapper


@log_call
def greet(name):
    return f"Hello, {name}!"


print(greet("Krishan"))
```

### Decorator Concepts

- Functions as first-class objects.
- Passing functions as arguments.
- Returning functions.
- Nested functions.
- Closures.
- `*args` and `**kwargs`.
- `functools.wraps`.
- Decorators with parameters.
- Stacking multiple decorators.
- Class decorators.
- Built-in decorators such as `@property`, `@staticmethod`, and `@classmethod`.

---

# Part 4 — Object-Oriented Programming (OOP)

## 25. What Is OOP?

**Object-Oriented Programming (OOP)** is a programming paradigm that organizes code around objects, which combine state (data) and behavior (methods).

OOP helps structure larger programs into reusable components and can improve maintainability when classes and relationships are designed appropriately.

### Core OOP Terminology

- **Class:** A blueprint that defines the attributes and behavior of a type of object.
- **Object:** An instance of a class.
- **Attribute:** Data associated with a class or object.
- **Method:** A function defined within a class.
- **Constructor:** The initialization mechanism used when an object is created; in Python, `__init__()` initializes the new instance.
- **Instance:** A concrete object created from a class.
- **State:** The current data held by an object.
- **Behavior:** The operations an object can perform.

### Example

```python
class Employee:
    def __init__(self, name, role):
        self.name = name
        self.role = role

    def introduce(self):
        return f"{self.name} works as an {self.role}."


employee = Employee("Krishan", "AI/ML Engineer")
print(employee.introduce())
```

## 26. The Four Pillars of OOP

### 26.1 Encapsulation

**Definition:** Encapsulation combines data and the methods that operate on it within a class. It also allows a class to control how its internal state is accessed or modified.

Python uses naming conventions and mechanisms such as properties to support encapsulation; it does not enforce private instance attributes in exactly the same way as some other languages.

```python
class BankAccount:
    def __init__(self, balance=0):
        self._balance = balance

    @property
    def balance(self):
        return self._balance

    def deposit(self, amount):
        if amount <= 0:
            raise ValueError("Amount must be positive")
        self._balance += amount


account = BankAccount(1000)
account.deposit(500)
print(account.balance)
```

### 26.2 Inheritance

**Definition:** Inheritance allows a class to derive behavior and attributes from another class, supporting code reuse and specialization.

```python
class Animal:
    def speak(self):
        return "Animal sound"


class Dog(Animal):
    def speak(self):
        return "Bark"


print(Dog().speak())
```

Topics:
- Single inheritance.
- Multilevel inheritance.
- Hierarchical inheritance.
- Multiple inheritance.
- Method Resolution Order (MRO).
- `super()`.
- Method overriding.
- Composition versus inheritance.

### 26.3 Polymorphism

**Definition:** Polymorphism allows different objects to be used through a common interface while providing behavior appropriate to their types.

```python
class EmailNotification:
    def send(self):
        return "Email sent"


class SMSNotification:
    def send(self):
        return "SMS sent"


for notification in [EmailNotification(), SMSNotification()]:
    print(notification.send())
```

Topics:
- Method overriding.
- Duck typing.
- Common interfaces.
- Operator overloading.
- Polymorphic behavior across unrelated classes.

### 26.4 Abstraction

**Definition:** Abstraction exposes essential operations while hiding implementation details that callers do not need to understand.

Python supports abstract base classes through the `abc` module.

```python
from abc import ABC, abstractmethod


class Payment(ABC):
    @abstractmethod
    def process(self, amount):
        pass


class CardPayment(Payment):
    def process(self, amount):
        return f"Processing card payment: {amount}"


payment = CardPayment()
print(payment.process(1000))
```

Topics:
- Abstract classes.
- Abstract methods.
- Interfaces as a design concept.
- Separating implementation from contract.
- Designing reusable components.

## 27. Special Methods and Object Lifecycle

Python special methods, often called *dunder methods*, allow classes to integrate with language features and built-in operations.

Examples:
- `__init__()` — initialize an instance.
- `__str__()` — human-readable string representation.
- `__repr__()` — developer-oriented representation.
- `__len__()` — support `len()`.
- `__eq__()` — equality comparison.
- `__add__()` — addition behavior.
- `__iter__()` — iterable protocol.
- `__next__()` — iterator protocol.
- `__enter__()` and `__exit__()` — context management.

Additional concepts:
- Instance methods.
- Class methods using `@classmethod`.
- Static methods using `@staticmethod`.
- Properties and setters.
- Class attributes vs instance attributes.
- Composition and object relationships.

---

# Part 5 — Advanced Python Concepts

## 28. Exception Handling

An exception is an event that interrupts the normal flow of program execution.

Python exception handling allows programs to respond to expected errors and release resources reliably.

### Main Constructs

- `try`.
- `except`.
- `else`.
- `finally`.
- `raise`.
- Custom exception classes.
- Exception chaining.
- Specific exception handling.
- Resource cleanup.

### Example

```python
def divide(a, b):
    if b == 0:
        raise ValueError("Divisor cannot be zero")
    return a / b


try:
    print(divide(10, 2))
except ValueError as error:
    print(f"Error: {error}")
finally:
    print("Operation completed")
```

Best practices:
- Catch specific exceptions.
- Avoid silently swallowing errors.
- Provide useful error messages.
- Use context managers for resource cleanup.
- Define custom exceptions for meaningful application errors.

## 29. File Handling

File handling enables programs to read, write, and process data stored in files.

Topics:
- `open()`.
- Read, write, and append modes.
- `read()`, `readline()`, and `readlines()`.
- `write()` and `writelines()`.
- Text vs binary mode.
- File encodings.
- Path handling with `pathlib`.
- CSV and JSON files.
- Exception handling for file operations.
- Context managers using `with`.

```python
from pathlib import Path

path = Path("example.txt")
path.write_text("Python file handling", encoding="utf-8")

content = path.read_text(encoding="utf-8")
print(content)
```

## 30. Modules and Packages

A module is a Python file containing definitions and statements. A package organizes related modules into a logical structure.

Topics:
- Importing modules.
- `import` and `from ... import ...`.
- Aliases.
- Standard library.
- Creating custom modules.
- Package organization.
- `__name__ == "__main__"`.
- Import paths.
- Virtual environments.
- Dependency management using `pip`.
- Requirements files.

## 31. Context Managers

A context manager manages setup and cleanup around a block of code.

The `with` statement is commonly used for files, locks, and database resources.

```python
with open("example.txt", "r", encoding="utf-8") as file:
    content = file.read()

print(content)
```

Topics:
- `with` statements.
- `__enter__()` and `__exit__()`.
- `contextlib`.
- Custom context managers.
- Resource-safe programming.

## 32. Closures and Scope

A closure is a function that retains access to variables from its enclosing lexical scope even after that outer function has returned.

Topics:
- LEGB name resolution.
- Local and global scope.
- Enclosing scope.
- Built-in scope.
- `global` and `nonlocal`.
- Nested functions.
- Closures.
- Closures in decorators and callbacks.

## 33. Copying and Object References

- Assignment and object references.
- Mutable and immutable objects.
- Shallow copy.
- Deep copy.
- `copy.copy()`.
- `copy.deepcopy()`.
- Aliasing.
- Mutation and shared state.

Understanding these concepts helps prevent unintended changes when multiple variables refer to the same mutable object.

## 34. Comprehensions and Unpacking

- List comprehensions.
- Set comprehensions.
- Dictionary comprehensions.
- Generator expressions.
- Sequence unpacking.
- Extended unpacking with `*`.
- Dictionary unpacking with `**`.
- Nested structures.
- Readability considerations.

## 35. Advanced Function Concepts

- First-class functions.
- Higher-order functions.
- Closures.
- Decorators.
- Recursive functions.
- Callback functions.
- Function annotations.
- Type hints.
- Positional-only and keyword-only parameters.
- Partial application using `functools.partial`.
- Caching using `functools.cache` or `lru_cache`.



# Part 6 — Python Projects and Practical Development

## 36. Python Projects

**Explore:** [Python - project](./Python%20-%20project/)

The project folder is the entry point for exploring the repository's practical Python implementations.

When reviewing a project, focus on:
- The problem being solved.
- Input and output.
- Program structure.
- Functions and classes.
- Data validation.
- Error handling.
- Dependency requirements.
- Execution instructions.
- Possible improvements.

A well-structured project should explain what it does, how to run it, and what concepts it demonstrates.

*Consult the folder for the projects currently available; individual project names and functionality should be documented from their source files.*

## 37. Python Assignments

**Explore:** [Python Concept Assignments](./Python_concept_Assignment/)

Assignments provide practice in translating programming concepts into working solutions.

Suggested practice categories:
- Variables and data types.
- Operators and conditions.
- Loops and patterns.
- Strings and collections.
- Functions and recursion.
- Comprehensions.
- OOP and class design.
- Exception handling.
- File handling.
- Advanced Python concepts.
- Logical and algorithmic problems.

For each exercise, aim to understand the logic, test edge cases, and write readable code instead of relying only on memorized solutions.

## 38. Data Analysis and Visualization

Python's data ecosystem makes it possible to move from general programming into structured data analysis.

### NumPy

NumPy provides multidimensional arrays and efficient numerical operations.

Topics:
- Arrays and array creation.
- Array shapes and dimensions.
- Indexing and slicing.
- Vectorized operations.
- Broadcasting.
- Aggregations.
- Reshaping and combining arrays.
- Numerical computation.

### Pandas

Pandas provides data structures and tools for tabular data analysis.

Topics:
- `Series` and `DataFrame`.
- Reading CSV and Excel files.
- Inspecting datasets.
- Data selection and filtering.
- Missing-value handling.
- Duplicate detection.
- Data type conversion.
- Sorting and grouping.
- Aggregation.
- Merging and joining DataFrames.
- Reshaping data.
- Exporting processed data.

### Matplotlib

Matplotlib is a visualization library for creating charts and customizing plots.

Topics:
- Line plots.
- Bar charts.
- Histograms.
- Scatter plots.
- Labels and legends.
- Axes and figure customization.
- Subplots.
- Saving figures.

### Seaborn

Seaborn builds on Matplotlib to provide statistical visualizations with convenient defaults.

Topics:
- Distribution plots.
- Box plots.
- Violin plots.
- Count plots.
- Scatter plots.
- Pair plots.
- Correlation heatmaps.
- Categorical data visualization.

### Plotly

Plotly supports interactive visualizations.

Topics:
- Interactive charts.
- Hover information.
- Zooming and panning.
- Interactive scatter and bar charts.
- Dashboard-oriented visualization concepts.

*These libraries are included in the repository's learning scope; refer to the existing project and assignment files to identify which examples are implemented.*



# Part 7 — Problem-Solving Roadmap

## 39. Programming Problem-Solving Skills

A systematic approach to problem-solving improves both code quality and technical interview performance.

1. Understand the problem statement.
2. Identify inputs, outputs, and constraints.
3. Work through a small example manually.
4. Design the algorithm or pseudocode.
5. Implement the solution.
6. Test normal and edge cases.
7. Analyze time and space complexity.
8. Refactor for readability.

### Complexity Fundamentals

**Time complexity** describes how an algorithm's running time grows as input size increases.

**Space complexity** describes how memory requirements grow with input size.

Common complexity classes:
- \(O(1)\) — constant.
- \(O(\log n)\) — logarithmic.
- \(O(n)\) — linear.
- \(O(n \log n)\) — linearithmic.
- \(O(n^2)\) — quadratic.
- \(O(2^n)\) — exponential.

Recommended practice topics:
- Searching and sorting.
- Counting and frequency maps.
- String manipulation.
- Array operations.
- Recursion.
- Hash-based lookup.
- Stack and queue fundamentals.
- Two-pointer techniques.
- Sliding-window fundamentals.

---

# Part 8 — Learning Roadmap

| Level | Focus Areas |
|---|---|
| Beginner | C syntax, Python syntax, variables, data types, operators |
| Core Programming | Conditions, loops, strings, arrays, collections |
| Problem Solving | Functions, recursion, searching, sorting, complexity |
| OOP | Classes, objects, encapsulation, inheritance, polymorphism, abstraction |
| Advanced Python | Iterators, generators, decorators, closures, comprehensions |
| Program Engineering | Exceptions, modules, file handling, context managers |
| Practical Development | Assignments, projects, reusable components |
| Data Analysis | NumPy, Pandas, Matplotlib, Seaborn, Plotly |
| Engineering Practices | Testing, debugging, logging, environments, code quality |

This roadmap is intended as a learning guide, not a claim that every topic has already been completed or implemented.


## Explore the Folders

Open the repository in VS Code or your preferred editor.

- Start with `C-Logical_concept_Assignmenet/` for C programming exercises.
- Explore `Python_concept_Assignment/` for Python practice.
- Use `Advanced Python concepts/` for advanced Python learning materials.
- Browse `Python - project/` for practical implementations.



# About Me


I am building practical engineering skills across Python, SQL, machine learning, data processing, and AI application development. This repository reflects my programming foundations, hands-on practice, and continuous learning.

- **GitHub:** [github.com/krishkydv77](https://github.com/krishkydv77)
- **LinkedIn:** [linkedin.com/in/krishan-kumar7](https://linkedin.com/in/krishan-kumar7)



## Explore the Repository

If you are learning C or Python, exploring object-oriented programming, or practicing problem-solving, feel free to browse the folders and learn from the available examples.

Feedback and suggestions for improving the learning materials are welcome.

<p align="center">
  <b>Learn the fundamentals. Understand the logic. Write better code. Build practical solutions.</b>
</p>
