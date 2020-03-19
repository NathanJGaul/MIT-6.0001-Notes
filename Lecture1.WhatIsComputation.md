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



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzM3ODgwMzY1LDQ2OTU2NTIwLC0zMTc3Mj
g2ODQsNzMwOTk4MTE2XX0=
-->