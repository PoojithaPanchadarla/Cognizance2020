#                             `PYTHON`

######                                                      A PROGRAMMING LANGUAGE

<img src="C:\Users\COMPUTER\Downloads\1200px-Python-logo-notext.svg.png" alt="PYTHON LOGO" style="zoom:25%;" />



**Python** is basically an interpreted, high-level and general purpose programming language. Its design philosophy emphasizes *code readability* with its notable use of significant whitespace. Its language constructs an _object-oriented approach_ which aims to help programmers write clear and logical code for all types of projects. It supports multiple programming paradigms, which include _structured, object-oriented and functional programming_. In addition to this, **Python** is `dynamically typed` and `garbage-collected`. It is often described as a _batteries included_ language due to its comprehensive standard library.



#### DESIGN PHILOSOPHY AND FEATURES

**Python's** design offers some support for functional programming. It has `filter`, `map` and `reduce` functions; list comprehensions, dictionaries, sets and generator expressions. The language's core philosophy is summarized with a few aphorisms such as:

* `Beautiful is better than ugly`.
* `Explicit is better than implicit`.
* `Simple is better than complex`.
* `Complex is better than complicated`.
* `Readability counts`.

**Python** was designed to be highly extensible. It strives for a *simpler, less-cultured syntax and grammar* while giving developers a choice in their coding methodology. An important goal for its developers is keeping it fun to use. **Python** follows the *minimalist philosophy* and *emphasises on readability*.



#### SYNTAX AND SEMANTICS

**Python** is meant to be an easily readable language. Its formatting is visually uncluttered. It has fewer syntactic exceptions and special cases compared to `C` or `Pascal`. In addition to this, **Python** uses the *whitespace indentation*, rather than curly brackets or keywords, to delimit blocks. 

**Python's** statements include:

* The assignment statement (token '=', the equals sign)
* The `if` statement
* The `for` statement
* The `while` statement
* The `try` statement
* The `raise` statement
* The `class` statement
* The `def` statement
* The `with` statement
* The `break` statement
* The `continue` statement
* The `pass` statement
* The `assert` statement
* The `yield` statement
* The `return` statement
* The `import` statement
* The `print` statement



> Python uses the words `and`, `or` and `not` for its boolean operators rather than the symbolic `&&`, `||` and `!` used in Java and C. Python has a *string format* operator `%`



| **TYPE**             | **MUTABILITY** | **DESCRIPTION**                                              | **SYNTAX EXAMPLES**                                          |
| -------------------- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| `bool`               | immutable      | Boolean value                                                | `True`  `False`                                              |
| `bytearray`          | mutable        | Sequence of bytes                                            | `bytearray(b'some ASCII')`  `bytearray(b"some ASCII")`  `bytearray([119, 105, 107, 105])` |
| `bytes`              | immutable      | Sequence of bytes                                            | `b'some ASCII'`  `b"some ASCII"`  `bytes([119, 105, 107, 105])` |
| `complex`            | immutable      | Complex number with real and imaginary parts                 | `3+2.7j`                                                     |
| `dict`               | mutable        | Associative array of key and value pairs; can contain mixed types, keys must be a hashable type | `{'key1':1.0, 3 : False}`  `{}`                              |
| `ellipsis`           | immutable      | An ellipsis placeholder to be used as an index in NumPy arrays | `...`   `Ellipsis`                                           |
| `float`              | immutable      | Double precision floating pointnumber. The precision is machine dependent but in practice is generally implemented as a 64-bit IEEE 754 number with 53 bits of precision | `1.414`                                                      |
| `frozenset`          | immutable      | Unordered set, contains no duplicates; can contain mixed types, if hashable | `frozenset([4.0, 'string', True])`                           |
| `int`                | immutable      | Integer of unlimited magnitude                               | `42`                                                         |
| `list`               | mutable        | List, can contain mixed types                                | `[4.0, 'string', True]`  `[]`                                |
| `NoneType`           | immutable      | An object representing the absence of a value, often called null in other languages | `None`                                                       |
| `NotImplementedType` | immutable      | A placeholder that can be returned from overloaded operators to indicate unsupported operand types | `NotImplemented`                                             |
| `range`              | immutable      | A sequence of numbers commonly used for looping specific number of times in `for` loops | `range(1,0)`  `range(10, -5, -2)`                            |
| `set`                | mutable        | Unordered set, contains no duplicates; can contain mixed types; if hashable | `{4.0, 'string', True}`  `set()`                             |
| `str`                | immutable      | A character string: sequence of Unicode codepoints           | `'Wikipedia'`  `"Wikipedia"`  `"""Spanning multiple lines"""` |
| `tuple`              | immutable      | Can contain mixed types                                      | `(4.0, 'string', True)`  `('single element',)`  `()`         |





#### PROGRAMMING EXAMPLES

* *Hello world* program

```python
print('Hello, world!')
```





* Program to calculate the factorial of a positive integer

```python
n = int(input('Type a number, and its factorial will be printed: '))
if n < 0:
    raise ValueError('You must enter a non-negative integer')
    
fact = 1

for i in range(2, n + 1):
    fact *= i
print(fact)
```





#### LANGUAGES INFLUENCED BY PYTHON

1. *Boo*
2. *Cobra*
3. *CoffeScript*
4. *ECMAScript/JavaScript*
5. *GDScript*
6. *Go*
7. *Groovy*
8. *Julia*
9. *Nim*
10. *Ruby*
11. *Swift*

-----

------



~~For further information, click on the following link:~~

[PYTHON](https://en.wikipedia.org/wiki/Python_(programming_language))





###### THANK YOU

