Use C programming language only. and **only** where specified, use C++, and Python. Where it is specified, use Java, or JavaScript. But default, everything here should be in pure C.
- without using computer libraries or frameworks (or atleast as minimally as possible).
- using vim standalone editor (ideal), or vim on the terminal of Ubuntu version 22.04.5 LTS or higher, on bash/zsh/dash shell, (ideally Ubuntu, but if not another post April 2022 Fedora/Debian versions).
- how to write programs given at the end (refer to this section).
- please go step by step, top to down, as this is way to strengthen the basics.

# 1 theoretical foundations (in order)
1. Theory of computation
2. Computational complexity theory
3. Computability theory
4. Algorithms
5. Algorithms and data structures
6. Algebraic geometry
7. Category Theory
8. Higher Category Theory
9. Topos theory
10. Model theory
11. Optimal Control
12. Partial differential equations
13. Convex optimization
14. Information geometry
15. Martingale (probability theory)
16. Stochastic differential equations

# 2 cs and ce (Computer Science and Computer Engineering)

## 1.1 CS and CE part 1: The basics, foundations, fundamentals (in any order):
- Reduction (complexity)
- Arithmetic circuit complexity
- Geometric complexity theory
- Theory of cryptography
- Turing machine
- Lambda calculus
- Recursion and continuations
- Pi-calculus
- Lexical analysis
- Program analysis
- Spectral graph theory
- Heap (data structures)
- Zipper data structure
- Sheaf theory
- Discrete geometry
- Categorical logic
- Domain theory
- Polymorphism (computer science)
- Functional programming
- Algebraic data type
- Homotopy theory
- Homotopy type theory
- Finite model theory
- Relational algebra
- Statistical signal processing
- Maxwell’s equations
- Linear programming
- Differential geometry
- DEC PDP-11 Instruction Set Architecture

### 1.2 Projects part 1:
1. binary system and IBM System/360 machine code.
2. Hardware project: Integrated circuits.  
2. objdump disassembler and GNU assembler for IBM System/360, and IBM System/360 assembly language (if possible, otherwise for IBM High Level Assembler (HLASM)).
3. GCC’s extended inline assembly.
4. IBM System/360 assembly language implementation (front-end) which also includes a standalone compiler, in C programming language (if possible, otherwise for IBM High Level Assembler (HLASM)).
5. An Algol 60 (if possible, or else Pascal) implementation (front-end) which also includes a standalone transpiler, in C.
6. A simple clone of Multics shell intepreter, and a simple Multics clone, in C.

## 2.1 CS and CE part 2:
- Circuit complexity
- Graph data structure
- Functional data structures
- buchberger’s algorithm
- Information theory
- Type theory
- Denotational semantics
- Control flow
- process calculus
- Data modeling
- Convex optimization
- Cybernetics
- System theory
- declarative programming
- homological algebra
- theory of cryptography
- proof theory
- Computational complexity theory
- Recursion/computability theory
- Set theory
- Geometric algorithms
- Spectral theory
- Algebraic graph theory

### 2.2 Artificial Intelligence and Machine Learning (AI and ML) part 1:
- Probably approximately correct (PAC) Learning
- computational learning theory
- empirical risk minimization
- Statistical learning theory


### 2.3 Projects part 2. 
1. A Fortran language implementation (front-end) which also includes a standalone transpiler, in C.
2. A custom developed C standard library function (method/subroutine), for example print-f.
3. Scheme language implementation (front-end) which also includes a standalone transpiler, in C.
4. A Unix shell intepreter (a simple bash/tcsh clone), and a simple Linux/Unix clone.
5. A C programming language implementation (front-end) which also includes a standalone transpiler, in C.

## 3.1 CS and CE part 3:
- Mathematical logic
- Formal logic
- Imperative programming.
- algebraic topology
- models of computation
- Logical calculi
- Theory of computation
- Graph theory

### 3.2 Projects part 3.
1. Implementation of SQL in C.
2. x-86-64 language implementation (front-end) which also includes a standalone compiler, in C programming language.
3. An Ada language implementation (front-end) which also includes a standalone transpiler, in C.
4. Optional project: Standard ML (S Meta Language) implementation (front-ends) in C with standalone interpreter (with bytecodes) and Virtual Machine, in C.
4. Machine Learning and AI: A Probably approximately correct (PAC) learning project.
5. A C++ language implementation (front-ends) in C with standalone interpreter (with bytecodes) and Virtual Machine, in C. 
7. A Python and CPython language implementations (front-ends) in C with standalone interpreter (with bytecodes) and Virtual Machine, in C.

### 3.3 AI and ML part 2:
- Neural tangent kernel,
- Mean-field theory
- Computational Learning Theory,
- Vapnik–Chervonenkis theory,
- Topological deep learning.
- Bias–variance tradeoff
- Empirical risk minimization
- Occam learning
- Kernel method
- Partially observable Markov decision process

### 3.4 Projects part 4.
1. C++/C: MySQL Connector/ODBC (MyODBC) and mysqld (server) in C++, and Connector/C (libmysqlclient) in C. 
2. C++: Java implementations (front-ends) in C++ with standalone interpreter (with bytecodes) and Virtual Machine.
3. C++: JavaScript implementations (front-ends) in C++ with standalone interpreter (with bytecodes) and Virtual Machine.
4. C++: Implementation of NoSQL in C++ .

### 3.5 Projects part 5.
1. Java: Scala implementations (front-ends) in Java with standalone interpreter (with bytecodes) and Virtual Machine.
2. Python: AI Project: Deep Multi-Agent Reinforcement Learning with Partially Observable Markov Decision Process (POMDP), Using Policy Gradients and a Transformer-Based Deep Neural Network, with an Exploration/Exploitation Balance, and Deep Q-Learning.
3. Java/C++/C: Distributed/Cloud computing architecture exercise: implement a project involving pi-calculus and an actor model (computer science).
4. Nvidia CUDA and compiler clone following GPGPU format, with a virtual ISA written in C.  
5. C++/C: MongoDB server (mongod) in C++ and low level driver (libmongoc + libbson) in C.

### 3.6 AI and ML part 3.
- check the README.md inside this folder path (`2_cs_and_ce/cs_and_ce_part_3/ai_and_ml_part3/`) for topics.

### 3.7 Projects part 6.
1. Python and JavaScript: Machine Learning and AI: Move on to hosting and deploying the PAC learning project (from the section Projects part 3.) locally first, then to Amazon Web Services (on SageMaker and Elastic Container Service), Microsoft Azure, or Digital Ocean if the first two options are unavailable.

# 4 applied,interdisciplinary science
Application of Computer science in Science, including Computational Science (Physics, Biology, etc.), Numerical Analysis, Combinatorics, mathematics of computing, as well as other interdisciplinary sciences (economics). Check the README.md inside this folder

# 5 more
- More: whatever I forgot to add (or any modifications to this list/readme) is found in the folder `more`.

# How to write programs:

Below is the process and steps I need to follow for writing programs: 
1. Start by thinking about the question before writing code: determine what is expected, the conditions, etc. (software requirements and software design). 
2. Before writing the entire code, look for answers in the software documentation, technical communication, and manual pages, if they are accessible and available. 
3. Whiteboard (abstraction), software architecture, data modeling, write pseudocode (design pattern), then boilerplate code (if necessary). 
4. Start coding. However, before targeting all requirements, first make sure you get the expected output on the terminal. 
5. Test regularly, not only for standard cases, but also for special cases (edge cases). 
6. Try to satisfy the other conditions. Also keep in mind the principle of separation of concerns (modular programming). 
7. Write unit tests whenever possible. 
8. Restructure (refactor) your code. 
9. The, optimize it to make it more efficient, run faster, and use less space or memory (time and space complexity). 
10. Once this is done, you can continue by fulfilling the other requirements, such as coding style, comments, best practices, etc

# Author:
- Davis Joseph (github: davisjoseph6), with help from Deniss.
