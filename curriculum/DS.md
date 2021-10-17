# Data Structures ("CS2")

## ALGORITHMS

### Basic Analysis [2 hours]

1. Explain what is meant by “best”, “expected”, and “worst” case behavior of an algorithm. [Familiarity]
2. In the context of specific algorithms, identify the characteristics of data and/or other conditions or
assumptions that lead to different behaviors. [Assessment]
3. Determine informally the time and space complexity of simple algorithms. [Usage]
4. State the formal definition of big O. [Familiarity]
6. Perform empirical studies to validate hypotheses about runtime stemming from mathematical analysis.
Run algorithms on input of various sizes and compare performance. [Assessment]
7. Give examples that illustrate time-space trade-offs of algorithms. [Familiarity]

### Fundamental Data Structures and Algorithms [9 hours]

_cd: could add 8. (Depth-first/breadth first) here but it's not in now_

1. Implement basic numerical algorithms. [Usage]
2. Implement simple search algorithms and explain the differences in their time complexities. [Assessment]
3. Be able to implement common quadratic and O(N log N) sorting algorithms. [Usage]
4. Describe the implementation of hash tables, including collision avoidance and resolution. [Familiarity]
5. Discuss the runtime and memory efficiency of principal algorithms for sorting, searching, and hashing.
[Familiarity]
6. Discuss factors other than computational efficiency that influence the choice of algorithms, such as
programming time, maintainability, and the use of application-specific patterns in the input data.
[Familiarity]
7. Explain how tree balance affects the efficiency of various binary search tree operations. [Familiarity]
9. Demonstrate the ability to evaluate algorithms, to select from a range of possible options, to provide
justification for that selection, and to implement the algorithm in a particular context. [Assessment]

## DISCRETE STRUCTURES

### Sets, Relations, and Functions [4 hours]

_cd: Don't do sets currently, that is in M251_

1. Explain with examples the basic terminology of functions, relations, and sets. [Familiarity]
2. Perform the operations associated with sets, functions, and relations. [Usage]
3. Relate practical examples to the appropriate set, function, or relation model, and interpret the associated
operations and terminology in context. [Assessment]

### Basic Logic [9 hours]

_cd: Don't do proofs currently, that is in M251_

1. Convert logical statements from informal language to propositional and predicate logic expressions.
[Usage]
2. Apply formal methods of symbolic propositional and predicate logic, such as calculating validity of
formulae and computing normal forms. [Usage]
4. Describe how symbolic logic can be used to model real-life situations or applications, including those
arising in computing contexts such as software analysis (e.g., program correctness), database queries, and
algorithms. [Usage]

### Proof Techniques [10 hours]

5. Explain the parallels between ideas of mathematical and/or structural induction to recursion and recursively
defined structures. [Assessment]

### Basics of Counting [5 hours]

5. Solve a variety of basic recurrence relations. [Usage]
6. Analyze a problem to determine underlying recurrence relations. [Usage]
7. Perform computations involving modular arithmetic. [Usage]

### Graphs and Trees [3 hours]

_cd: Don't do non-tree graphs currently._

1. Illustrate by example the basic terminology of graph theory, as well as some of the properties and special
cases of each type of graph/tree. [Familiarity]
2. Demonstrate different traversal methods for trees and graphs, including pre-, post-, and in-order traversal of
trees. [Usage]
3. Model a variety of real-world problems in computer science using appropriate forms of graphs and trees,
such as representing a network topology or the organization of a hierarchical file system. [Usage]
4. Show how concepts from graphs and trees appear in data structures, algorithms, proof techniques
(structural induction), and counting. [Usage]

### Discrete Probability [6 hours]

5. Apply the tools of probability to solve problems such as the average case analysis of algorithms or
analyzing hashing. [Usage]

## INFORMATION ASSURANCE AND SECURITY

### Defensive Programming [1 hour]

_cd: could add 5. Exceptions but not currently covering, prefer in OS module of Sys_

1. Explain why input validation and data sanitization is necessary in the face of adversarial control of the
input channel. [Familiarity]
2. Explain why you might choose to develop a program in a type-safe language like Java, in contrast to an
unsafe programming language like C/C++. [Familiarity]
3. Classify common input validation errors, and write correct input validation code. [Usage]
5. Demonstrate the identification and graceful handling of error conditions. [Usage]

## PROGRAMMING LANGUAGES

### Object-Oriented Programming [4 hours]

1. Design and implement a class. [Usage]
2. Use subclassing to design simple class hierarchies that allow code to be reused for distinct subclasses.
[Usage]
3. Correctly reason about control flow in a program using dynamic dispatch. [Usage]
4. Compare and contrast (1) the procedural/functional approach (defining a function for each operation with
the function body providing a case for each data variant) and (2) the object-oriented approach (defining a
class for each data variant with the class definition providing a method for each operation). Understand
both as defining a matrix of operations and variants. [Assessment]

### Functional Programming [3 hours]

1. Write basic algorithms that avoid assigning to mutable state or considering reference equality. [Usage]
2. Write useful functions that take and return other functions. [Usage]
3. Compare and contrast (1) the procedural/functional approach (defining a function for each operation with
the function body providing a case for each data variant) and (2) the object-oriented approach (defining a
class for each data variant with the class definition providing a method for each operation). Understand
both as defining a matrix of operations and variants. [Assessment]

### Basic Type Systems [1 hour]

_cd: Type checking is in DS currently but not a focus_

1. For both a primitive and a compound type, informally describe the values that have that type. [Familiarity]
3. Describe examples of program errors detected by a type system. [Familiarity]
5. Give an example program that does not type-check in a particular language and yet would have no error if
run. [Familiarity]
6. Use types and type-error messages to write and debug programs. [Usage]

## SOFTWARE DEVELOPMENT FUNDAMENTALS

### Algorithms and Design [11 hours]

1. Discuss the importance of algorithms in the problem-solving process. [Familiarity]
2. Discuss how a problem may be solved by multiple algorithms, each with different properties. [Familiarity]
3. Create algorithms for solving simple problems. [Usage]
4. Use a programming language to implement, test, and debug algorithms for solving simple problems.
[Usage]
5. Implement, test, and debug simple recursive functions and procedures. [Usage]
6. Determine whether a recursive or iterative solution is most appropriate for a problem. [Assessment]
7. Implement a divide-and-conquer algorithm for solving a problem. [Usage]
8. Apply the techniques of decomposition to break a program into smaller pieces. [Usage]
9. Identify the data components and behaviors of multiple abstract data types. [Usage]
10. Implement a coherent abstract data type, with loose coupling between components and behaviors. [Usage]
11. Identify the relative strengths and weaknesses among multiple designs or implementations for a problem.
[Assessment]

### Fundamental Programming Concepts [10 hours]

_cd: Currently no file I/O planned for DS, may be in final project_

1. Analyze and explain the behavior of simple programs involving the fundamental programming
constructs variables, expressions, assignments, I/O, control constructs, functions, parameter passing,
and recursion. [Assessment]
2. Identify and describe uses of primitive data types. [Familiarity]
3. Write programs that use primitive data types. [Usage]
4. Modify and expand short programs that use standard conditional and iterative control structures and
functions. [Usage]
5. Design, implement, test, and debug a program that uses each of the following fundamental
programming constructs: basic computation, simple I/O, standard conditional and iterative structures,
the definition of functions, and parameter passing. [Usage]
7. Choose appropriate conditional and iteration constructs for a given programming task. [Assessment]
8. Describe the concept of recursion and give examples of its use. [Familiarity]
9. Identify the base case and the general case of a recursively-defined problem. [Assessment]

### Fundamental Data Structures [12 hours]

1. Discuss the appropriate use of built-in data structures. [Familiarity]
2. Describe common applications for each of the following data structures: stack, queue, priority queue, set,
and map. [Familiarity]
3. Write programs that use each of the following data structures: arrays, records/structs, strings, linked lists,
stacks, queues, sets, and maps. [Usage]
4. Compare alternative implementations of data structures with respect to performance. [Assessment]
5. Describe how references allow for objects to be accessed in multiple ways. [Familiarity]
6. Compare and contrast the costs and benefits of dynamic and static data structure implementations.
[Assessment]
7. Choose the appropriate data structure for modeling a given problem. [Assessment]

### Development Methods [10 hours]

__cd: Contracts were not a focus this semester but should have been, may also do 12. program style__

6. Describe how a contract can be used to specify the behavior of a program component. [Familiarity]
7. Refactor a program by identifying opportunities to apply procedural abstraction. [Usage]
8. Apply a variety of strategies to the testing and debugging of simple programs. [Usage]

## SOFTWARE ENGINEERING

### Software Design [3 hours]

1. Articulate design principles including separation of concerns, information hiding, coupling and cohesion,
and encapsulation. [Familiarity]
2. Use a design paradigm to design a simple software system, and explain how system design principles have
been applied in this design. [Usage]
3. Construct models of the design of a simple software system that are appropriate for the paradigm used to
design it. [Usage]
4. Within the context of a single design paradigm, describe one or more design patterns that could be
applicable to the design of a simple software system. [Familiarity]

## SYSTEM FUNDAMENTALS

### Cross-Layer Communications [3 hours]

_cd: Doing HW and OS but not VM in DS, only touching on errors, doing trace and single step_

1. Describe how computing systems are constructed of layers upon layers, based on separation of concerns,
with well-defined interfaces, hiding details of low layers from the higher layers. [Familiarity]
2. Describe how hardware, VM, OS, and applications are additional layers of interpretation/processing.
[Familiarity]
3. Describe the mechanisms of how errors are detected, signaled back, and handled through the layers.
[Familiarity]
4. Construct a simple program using methods of layering, error detection and recovery, and reflection of error
status across layers. [Usage]
5. Find bugs in a layered program by using tools for program tracing, single stepping, and debugging. [Usage]

### State and State Machines [6 hours]

1. Describe computations as a system characyterized by a known set of configurations with transitions from
one unique configuration (state) to another (state). [Familiarity]
2. Describe the distinction between systems whose output is only a function of their input (Combinational)
and those with memory/history (Sequential). [Familiarity]
