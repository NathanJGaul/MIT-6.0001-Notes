# Lecture 1: What is Computation

## Topics
- represent knowledge with data structures
- iteration and recursion as computational metaphors
- abstraction of procedures and data types
- organization and modularize systems using object classes and methods
- different classes of algorithms, searching and sorting
- complexity of algorithms

## What does a computer do
- Fundamentally:
	- performs calculations
	- remember (store) results
- What kinds of calculations
	- built-in to the language
	- programmer defined calculations
- Computers only do what you tell them to do

## Types of knowledge
- declarative knowledge is a statement of fact
- imperative knowledge is the recipe or "how to"

### An Example
- declarative: square root of a number x is y such that y*y = x
- imperative: recipe for deducing square root of a number x
	1. Start with a guess, g
	2. If g*g is close enough to x, stop and say g is the answer
	3. Otherwise make a new guess by averaging g and x/g
	4. Using the new guess, repeat process until close enough

### What is a recipe
1. Sequence of simple steps
2. flow of control process that specifies when each step is executed
3. a means of determining when to stop

## Computers are machines
- how to capture a recipe in a mechanical process
- fixed program computer
	- calculator
- stored program computer
	- machine stores and executes instructions

### Basic machine architecture
- memory
	- stores data to be operated on
- arithmetic logic unit (alu)
	- basic primitive ops
- control unit
	- program counter
	- traverses the instructure set by incrementing the program counter

### Stored program computer
- sequence of instructions stored inside computer
	- built from predefined set of primitive instructions
	1. arithmetic and logic
	2. simple test
	3. moving data
- special program (interpreter) executes each instruction in order
	- use tests to change flow of control through sequence
	- stop when done

### Basic primitives
- Turing showed that you can compute anything using 6 primitives
- modern programming languages have more convenient set of primitives
- can abstract methods to create new primitives
- anything computable in one language is computable in any other language

## Creating recipes
- a programming language provides a set of primitive operations
- expressions are complex by legal combinations of primitives in a programming language
- expressions and computations have values and meanings in a programming language

### Aspects of languages
- primitive constructs
	- numbers, strings, simple operators, etc.
- syntax
	- "hi"5 -> is not a valid phrase
	- 45 * 5 -> is a valid phrase
- static semantics is which syntactically valid string have meaning
	- 3.2*5 -> syntactically valid
	- 3+"hi" -> static semantic error
- semantics is the meaning associated with a syntactically correct string of symbols with no static semantic errors
	- have only one meaning but may not be what programmer 

## Python programs
- a program is a sequence of definitions and commands
	- definitions evaluated
	- commands executed by Python interpreter in a shell
- commands (statements) instruct interpreter to do something
- can be types directly in a shell or stored in a file that is read into the shell and evaluated
	- Problem Set 0 will introduce you to these in Anaconda

## Objects
- programs manipulate data objects
- objects have a type that defines the kind of things programs can do to them
	- Ana is a human so she can walk, speak English, etc.
	- Chewbacca is a wookie so he can walk, "mwaaarhrhh", etc.
- objects are
	- scalar (cannot be subdivided)
	- non-scalar (have internal structure that can be accessed

### Salar objects
- int - whole numbers
- float - numbers containing decimals
- bool - represents Boolean values True and False
- NoneType - special has one value, None
- can use type() to determine the type of an object

### Type conversions (cast)
- can convert object of one type to another
- float(3) converts integer 3 to float 3.0
- int(3.9) truncates float 3.9 to integer 3

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNTEyMjMxOTEsNjMzMDE3MzY3LC0xOD
YzNjU3NTE0LDQ2OTU2NTIwLC0zMTc3Mjg2ODQsNzMwOTk4MTE2
XX0=
-->