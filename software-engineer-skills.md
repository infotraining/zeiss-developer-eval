# Junior C++ Developer - List of Essential Skills

## Core C++ Language Fundamentals
- Syntax & basic constructs - variables, types, loops, functions, pointers, references, constness
- RAII
- Object-Oriented Programming (OOP) - classes, objects, inheritance, polymorphism, encapsulation
- Memory basics - `new`, `delete`, stack vs heap, pointer safety
- Operator overloading
- Cast operators & type conversions
  - cast operators in C++
  - narrowing conversions
- Exception handling - safety guarantees
- Value semantics vs reference (pointer) semantics - basics
- Efficient passing arguments and returning values from functions
- Understanding compilation model - headers, translation units, linking basics

## Software Engineering
- Git - branching, committing, merging, basic workflows
- Static analysis tools - clang-tidy, etc.
- Logging - using logging libraries; Understanding log levels and best practices
- Debugging - using Visual Studio debugger
- Build systems - especially **CMake**, now industry standard for C++ projects
- Compiler usage - invoking `g++` / `clang++` from command line, reading error messages
- Data structures - arrays, lists, stacks, queues, trees
- Algorithms - sorting, searching, complexity basics (Big-O intuition)
- SOLID - how to avoid strong coupling in code

## Software Testing
- Writing unit tests (GTEST)
- Basic knowledge of unit test frameworks

# Mid C++ Developer - List of Essential Skills

## Core C++ Language Fundamentals
- Templates and generic programming
  - function templates
  - class templates
- Type deduction and type traits
  - type deduction in template functions
  - Class Template Argument Deduction (CTAD) + deduction guides
  - using type traits in generic code
  - writing custom type traits
  - `if constexpr` (C++17) in generic code
- Lambda expressions (closures, capturing variables)
- STL containers (performance characteristics)
  - vector, deque, list
  - associative containers
- STL algorithms
  - find, sort, transform, etc.
  - writing custom generic algorithms
  - parallel algorithms (C++17)
- Namespace & ADL (Argument Dependency Lookup)

### Multithreading & Concurrency (basics)
- `std::thread` & `std::jthread`
- Synchronization primitives:
  - mutexes
  - lock guards
  - condition variables
  - latches
- Race conditions & deadlocks
- Working with sanitizers

## Software Engineering Skills
- Basic knowledge of design patterns
- UML
  - class diagrams
  - state machine diagrams
  - sequence diagrams
- Experience with memory management
  - using sanitizers/profilers to find memory leaks
- Experience with software testing frameworks
  - GTest
  - GMock - writing mocks and stubs (difference between them in unit tests)
- Doxygen - generating documentation from source code comments
- SOLID - advanced understanding and application


# Senior C++ Developer - List of Essential Skills

## Core C++ Language (Advanced)

### Move Semantics
- Value categories (lvalues, xvalues, prvalues) and how they affect:
  - overload resolution
  - RVO & NRVO
- Move semantics, perfect forwarding, reference collapsing

### Templates (Advanced Level)
- Variadic templates & fold expressions
- SFINAE & concepts
- CRTP (Curiously Recurring Template Pattern)
- Type traits & metaprogramming
- Writing custom type traits
- `constexpr` programming and compile-time computation

### Multithreading & Concurrency
- Memory model:
  - data races
  - atomics & fences
- Cache behavior:
  - cache ping-pong
  - false sharing
  - cache coherence
- Working with sanitizers

### Strong Types & Code Expressiveness
- Strong types
- User-defined literals

## Software Engineering Skills
- Experience with optimizing and debugging complex software systems
- Proficiency in cross-platform development

### API Design Skills
- API design (stable, minimal, expressive)
- SOLID & Dependency Injection
- Error handling models:
  - status codes
  - exceptions
  - `std::expected`
- Dependency management and layering
- Encapsulation vs performance tradeoffs

### Design Patterns
- Knowledge and practical use of senior-level design patterns

### Senior-Level Soft Skills
- Mentoring juniors and mid-levels
- Leading code reviews with clarity
