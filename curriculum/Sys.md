## INFORMATION ASSURANCE AND SECURITY

### Foundational Concepts in Security [1 hour]

1. Analyze the tradeoffs of balancing key security properties (Confidentiality, Integrity, and Availability).
[Usage]
2. Describe the concepts of risk, threats, vulnerabilities and attack vectors (including the fact that there is no
such thing as perfect security). [Familiarity]
3. Explain the concepts of authentication, authorization, access control. [Familiarity]
4. Explain the concept of trust and trustworthiness. [Familiarity]
5. Describe important ethical issues to consider in computer security, including ethical issues associated with
fixing or not fixing vulnerabilities and disclosing or not disclosing vulnerabilities. [Familiarity]

### Principles of Secure Design [1 hour]

3. Discuss the implications of relying on open design or the secrecy of design for security. [Familiarity]
4. Explain the goals of end-to-end data security. [Familiarity]
5. Discuss the benefits of having multiple layers of defenses. [Familiarity]
7. Describe the cost and tradeoffs associated with designing security into a product. [Familiarity]

### Defensive Programming [1 hour]

1. Explain why input validation and data sanitization is necessary in the face of adversarial control of the
input channel. [Familiarity]
2. Explain why you might choose to develop a program in a type-safe language like Java, in contrast to an
unsafe programming language like C/C++. [Familiarity]
3. Classify common input validation errors, and write correct input validation code. [Usage]
4. Demonstrate using a high-level programming language how to prevent a race condition from occurring and
how to handle an exception. [Usage]
5. Demonstrate the identification and graceful handling of error conditions. [Usage]

## INFORMATION MANAGEMENT

### Information Management Concepts [1 hour]

1. Describe how humans gain access to information and data to support their needs. [Familiarity]
2. Describe the advantages and disadvantages of central organizational control over data. [Assessment]
3. Identify the careers/roles associated with information management (e.g., database administrator, data
modeler, application developer, end-user). [Familiarity]
4. Compare and contrast information with data and knowledge. [Assessment]
5. Demonstrate uses of explicitly stored metadata/schema associated with data. [Usage]
6. Identify issues of data persistence for an organization. [Familiarity]

## NETWORKING AND COMMUNICATION

### Introduction [1.5 hours]

1. Articulate the organization of the Internet. [Familiarity]
2. List and define the appropriate network terminology. [Familiarity]
3. Describe the layered structure of a typical networked architecture. [Familiarity]
4. Identify the different types of complexity in a network (edges, core, etc.). [Familiarity]

### Networked Applications [1.5 hours]

1. List the differences and the relations between names and addresses in a network. [Familiarity]
2. Define the principles behind naming schemes and resource location. [Familiarity]
3. Implement a simple client-server socket-based application. [Usage]

## PARALLEL AND DISTRIBUTED COMPUTING

### Parallelism Fundamentals [2 hours]

1. Distinguish using computational resources for a faster answer from managing efficient access to a shared
resource. [Familiarity]
2. Distinguish multiple sufficient programming constructs for synchronization that may be interimplementable but have complementary advantages. [Familiarity]
3. Distinguish data races from higher level races. [Familiarity]

### Parallel Decomposition [1 hour]

1. Explain why synchronization is necessary in a specific parallel program. [Usage]
2. Identify opportunities to partition a serial program into independent parallel modules. [Familiarity]

### Communication and Coordination [1 hour]

1. Use mutual exclusion to avoid a given race condition. [Usage]
2. Give an example of an ordering of accesses among concurrent activities (e.g., program with a data race)
that is not sequentially consistent. [Familiarity]

### Parallel Architecture [1 hour]

1. Explain the differences between shared and distributed memory. [Familiarity]

## PROGRAMMING LANGUAGES

### Basic Type Systems [1 hour]

1. For both a primitive and a compound type, informally describe the values that have that type. [Familiarity]
2. For a language with a static type system, describe the operations that are forbidden statically, such as
passing the wrong type of value to a function or method. [Familiarity]
3. Describe examples of program errors detected by a type system. [Familiarity]
4. For multiple programming languages, identify program properties checked statically and program
properties checked dynamically. [Usage]
5. Give an example program that does not type-check in a particular language and yet would have no error if
run. [Familiarity]
6. Use types and type-error messages to write and debug programs. [Usage]

## SOFTWARE ENGINEERING

### Software Processes [2 hours]

1. Describe how software can interact with and participate in various systems including information
management, embedded, process control, and communications systems. [Familiarity]
5. Describe how programming in the large differs from individual efforts with respect to understanding a large
code base, code reading, understanding builds, and understanding context of changes. [Familiarity]

## SYSTEM FUNDAMENTALS

### Computational Paradigms [3 hours]

1. List commonly encountered patterns of how computations are organized. [Familiarity]
2. Describe the basic building blocks of computers and their role in the historical development of computer
architecture. [Familiarity]
3. Articulate the differences between single thread vs. multiple thread, single server vs. multiple server
models, motivated by real world examples (e.g., cooking recipes, lines for multiple teller machines and
couples shopping for food). [Familiarity]
4. Articulate the concept of strong vs. weak scaling, i.e., how performance is affected by scale of problem vs.
scale of resources to solve the problem. This can be motivated by the simple, real-world examples.
[Familiarity]
7. Write a simple sequential problem and a simple parallel version of the same program. [Usage]
8. Evaluate performance of simple sequential and parallel versions of a program with different problem sizes,
and be able to describe the speed-ups achieved. [Assessment]

### Cross-Layer Communications [3 hours]

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

1. Describe computations as a system characterized by a known set of configurations with transitions from
one unique configuration (state) to another (state). [Familiarity]
2. Describe the distinction between systems whose output is only a function of their input (Combinational)
and those with memory/history (Sequential). [Familiarity]
3. Describe a computer as a state machine that interprets machine instructions. [Familiarity]
4. Explain how a program or network protocol can also be expressed as a state machine, and that alternative
representations for the same computation can exist. [Familiarity]

### Parallelism [3 hours]

1. For a given program, distinguish between its sequential and parallel execution, and the performance
implications thereof. [Familiarity]
2. Demonstrate on an execution time line that parallelism events and operations can take place simultaneously
(i.e., at the same time). Explain how work can be performed in less elapsed time if this can be exploited.
[Familiarity]
3. Explain other uses of parallelism, such as for reliability/redundancy of execution. [Familiarity]
5. Write more than one parallel program (e.g., one simple parallel program in more than one parallel
programming paradigm; a simple parallel program that manages shared resources through synchronization
primitives; a simple parallel program that performs simultaneous operation on partitioned data through task
parallel (e.g., parallel search terms; a simple parallel program that performs step-by-step pipeline
processing through message passing). [Usage]
