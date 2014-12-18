# Python training material for FAA.

## Curriculum topics

### 101: Introduction to Python programming
* Why Python?
  - Clean design: pretty, readable, functional, flexible OOP.
  - General purpose: write text processing utilities, glue stuff together, build websites, analyze data.
  - Efficient: YYMV.
  - Large community and collection of packages: stdlib, packages, frameworks, fora.
* Building blocks
  - Objects, values and variables
  - Expressions
  - Statements
* Simple data types
  - Numbers: `int`, `float`, `long`
  - Boolean: `True`, `False`
  - String
  - `None`
* [Compound data types][comptype]
  - Tuple
  - List
  - Set and frozenset
  - Dict
* Callable types
  - Functions
  - Methods
* Structured programming
  - Conditional execution
    + `if`
  - Looping
    + `while`
    + `for`
    + `next`
    + `continue`
  - Exception handling
    + `try`
    + `except`
    + `raise`
    + `else`
* Using packages
  - Stdlib
  - Module
  - Package
  - The `import` statement
* I/O
  - Interactive I/O
  - File I/O
    + Reading
    + Writing
    + The `with` context statement
    + Character encodings: a quick introduction.
* Writing functions
  - Implementing a suite of functions to use on lists
* Writing classes
  - Implementing a stack data structure

### 102: Data Analysis with Python
* Numpy
* Scipy
* Pandas

### 103: ML with Python
* Scikit Learn
* NLTK

## Other resources

### Online learning
* [MIT OCW 6.189][mitocw]: A Gentle Introduction to Programming using Python
* [Harvard CS 109][cs109]: Data Science

### Books
* Dive into Python (different books for [Python 2][dip2] and [Python 3][dip3]), Mark Pilgrim.
* [Python for Data Analysis][mckinney], Wes McKinney.
* [Problem solving with Algorithms and Data Structures][miller], Miller & Ranum.

### FAA resources:
* Akhil S. Behl: akhilb@fractalanalytics.com

<!--links-->
[mitocw]: http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2011/index.htm
[cs109]: http://cs109.github.io/2014
[dip2]: http://www.diveintopython.net
[dip3]: http://www.diveintopython3.net
[mckinney]: http://www.amazon.in/Python-For-Data-Analysis-McKinney/dp/9351100065
[miller]: http://interactivepython.org/courselib/static/pythonds/index.html
[comptype]: http://stackoverflow.com/questions/11801549/python-data-types-are-classes-or-data-structures
