# 🐍 Python Interview Master Checklist (Basic → Advanced)

> Goal: Never forget Python fundamentals, track mastery, and stay interview-ready.

---

## ✅ LEVEL 1: Python Basics (Must-Know)

### Python Fundamentals
- [ ] What is Python (features, use cases)
- [ ] Python execution model (source → bytecode → PVM)
- [ ] Interpreted vs compiled (CPython, PyPy, JIT)
- [ ] Dynamic typing
- [ ] Indentation and code blocks
- [ ] Keywords and identifiers
- [ ] Comments (single-line, multi-line)

### Variables & Data Types
- [ ] Variables and naming rules
- [ ] Numeric types (int, float, complex)
- [ ] Boolean type
- [ ] Strings
- [ ] Lists
- [ ] Tuples
- [ ] Sets
- [ ] Dictionaries
- [ ] Range
- [ ] bytes, bytearray, memoryview
- [ ] Built-in type categories

### Operators
- [ ] Arithmetic operators
- [ ] Comparison operators
- [ ] Logical operators
- [ ] Assignment operators
- [ ] Membership operators (in, not in)
- [ ] Identity operators (is, is not)
- [ ] Difference between `==` and `is`
- [ ] `/` vs `//`
- [ ] Walrus operator `:=`

### Control Flow
- [ ] if / elif / else
- [ ] for loop
- [ ] while loop
- [ ] break
- [ ] continue
- [ ] pass
- [ ] match-case (Python 3.10+)

### Type Conversion & Built-ins
- [ ] int(), float(), str()
- [ ] type()
- [ ] len()
- [ ] range()
- [ ] sorted()
- [ ] min(), max(), sum()
- [ ] dir()
- [ ] help()

---

## ✅ LEVEL 2: Core Python (Interview Core)

### Strings
- [ ] Indexing
- [ ] Slicing
- [ ] Reverse string
- [ ] upper(), lower()
- [ ] split()
- [ ] join()
- [ ] isalnum()
- [ ] String immutability

### Lists & Tuples
- [ ] append() vs extend()
- [ ] remove(), pop()
- [ ] List slicing
- [ ] List vs tuple differences
- [ ] Copying lists (reference vs copy)
- [ ] Remove duplicates
- [ ] Preserve order while removing duplicates

### Dictionaries & Sets
- [ ] Dictionary creation
- [ ] Accessing keys safely (in, get)
- [ ] KeyError handling
- [ ] Dictionary vs list
- [ ] Set properties (uniqueness)
- [ ] Dictionary merging (update, |)
- [ ] collections.Counter basics

### Functions
- [ ] Function definition
- [ ] Parameters and arguments
- [ ] Default arguments
- [ ] *args
- [ ] **kwargs
- [ ] return vs yield
- [ ] First-class functions
- [ ] Passing functions as arguments

---

## ✅ LEVEL 3: Intermediate Python

### Comprehensions
- [ ] List comprehension
- [ ] Dictionary comprehension
- [ ] Generator expressions
- [ ] Conditional comprehensions

### Iteration Model
- [ ] Iterables vs iterators
- [ ] __iter__()
- [ ] __next__()
- [ ] StopIteration
- [ ] Generators
- [ ] yield keyword

### Exception Handling
- [ ] try / except
- [ ] else with try
- [ ] finally
- [ ] Built-in exceptions
- [ ] Custom exceptions
- [ ] Raising exceptions
- [ ] Exception Groups (Python 3.11+)

### Scope & Namespace
- [ ] Local scope
- [ ] Global scope
- [ ] Built-in scope
- [ ] LEGB rule
- [ ] Namespace concept
- [ ] global keyword

---

## ✅ LEVEL 4: Object-Oriented Python

### OOP Basics
- [ ] Class definition
- [ ] Object creation
- [ ] __init__()
- [ ] self
- [ ] Instance attributes
- [ ] Instance methods

### OOP Concepts
- [ ] Encapsulation
- [ ] Abstraction
- [ ] Inheritance
- [ ] Multiple inheritance
- [ ] Polymorphism

### Advanced OOP
- [ ] super()
- [ ] Method overriding
- [ ] Method Resolution Order (MRO)
- [ ] issubclass()
- [ ] isinstance()

### Method Types
- [ ] Instance methods
- [ ] @classmethod
- [ ] @staticmethod

### Access Modifiers (Python-style)
- [ ] Public members
- [ ] Protected (_)
- [ ] Private (__)

### Magic / Dunder Methods
- [ ] __str__()
- [ ] __repr__()
- [ ] __eq__()
- [ ] __len__()
- [ ] __enter__()
- [ ] __exit__()

---

## ✅ LEVEL 5: Python Internals & Memory

### Memory Management
- [ ] Private heap
- [ ] Reference counting
- [ ] Garbage collection
- [ ] Cyclic GC
- [ ] gc module
- [ ] sys.getsizeof()

### Copying Objects
- [ ] Shallow copy
- [ ] Deep copy
- [ ] copy.copy()
- [ ] copy.deepcopy()

### Global Interpreter Lock
- [ ] What is GIL
- [ ] Impact on multithreading
- [ ] CPU-bound vs IO-bound
- [ ] Workarounds (multiprocessing, C extensions)

---

## ✅ LEVEL 6: Advanced Python Concepts

### Decorators
- [ ] Decorator basics
- [ ] Function decorators
- [ ] functools.wraps
- [ ] Use cases (logging, auth, timing)

### Context Managers
- [ ] with statement
- [ ] File context manager
- [ ] Custom context managers
- [ ] __enter__ / __exit__

### Closures
- [ ] Closure definition
- [ ] Lexical scope
- [ ] State retention

### Metaclasses
- [ ] What is a metaclass
- [ ] type
- [ ] __new__ in metaclasses
- [ ] Use cases

### Monkey Patching
- [ ] Runtime modification
- [ ] Use cases and risks

---

## ✅ LEVEL 7: Concurrency & Async

### Threading & Multiprocessing
- [ ] threading module
- [ ] multiprocessing module
- [ ] Thread vs process
- [ ] When to use which

### Async Programming
- [ ] asyncio basics
- [ ] async / await
- [ ] Coroutines
- [ ] Event loop
- [ ] Async vs threading

---

## ✅ LEVEL 8: Files, OS & System

### File Handling
- [ ] open() modes
- [ ] Read / write files
- [ ] Binary files
- [ ] CSV files
- [ ] JSON files
- [ ] Large file handling (streaming)

### OS & System
- [ ] os module
- [ ] sys module
- [ ] File deletion (remove, rmdir)
- [ ] Environment variables

---

## ✅ LEVEL 9: Debugging, Testing & Performance

### Debugging
- [ ] pdb
- [ ] Breakpoints
- [ ] Tracebacks
- [ ] logging module

### Testing
- [ ] Unit testing concept
- [ ] unittest
- [ ] pytest
- [ ] Assertions
- [ ] Testing side effects

### Performance & Optimization
- [ ] Profiling (cProfile)
- [ ] Built-in optimizations
- [ ] Generators for memory efficiency
- [ ] Avoiding globals
- [ ] NumPy for performance

---

## ✅ LEVEL 10: Python Ecosystem (Role-Based)

### Packaging & Environment
- [ ] pip
- [ ] venv
- [ ] Dependency management
- [ ] PYTHONPATH
- [ ] __name__ == "__main__"

### Web & APIs
- [ ] Flask basics
- [ ] Django basics
- [ ] REST APIs
- [ ] ORM concepts
- [ ] requests module

### Databases & Networking
- [ ] SQL database connection
- [ ] ORM usage
- [ ] NoSQL basics
- [ ] HTTP requests
- [ ] Socket programming basics

### Data Science & ML (Optional)
- [ ] NumPy arrays vs lists
- [ ] Pandas DataFrames
- [ ] Missing data handling
- [ ] Data aggregation
- [ ] scikit-learn basics
- [ ] Model persistence

---

## 🎯 Completion Rule
- Basics + Core + Intermediate = **Mandatory**
- Advanced + Internals = **Strong Interview Signal**
- Ecosystem = **Role Dependent**