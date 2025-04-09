## Differences Between C and C++

### 🔧 Language Type & Paradigm

| Feature                    | C                         | C++                                                    |
|----------------------------|---------------------------|--------------------------------------------------------|
| Programming Paradigm       | Procedural                | Multi-paradigm (Procedural + Object-Oriented + more)   |
| Object-Oriented Programming| ❌ Not supported          | ✅ Fully supported                                      |
| Templates / Generics       | ❌                        | ✅ (`template<typename T>`)                             |
| Function Overloading       | ❌                        | ✅                                                      |
| Operator Overloading       | ❌                        | ✅                                                      | 
| Exception Handling         | ❌                        | ✅ (`try-catch`)                                        |

---

### 🛠️ Standard Library & Built-ins

| Feature               | C                              | C++                                                             |
|----------------------|--------------------------------|------------------------------------------------------------------|
| Standard Library      | Basic (`stdio.h`, `stdlib.h`) | Rich STL (`vector`, `map`, `string`, `algorithm`, etc.)         |
| Strings               | `char[]`, `char*`              | `std::string`                                                   |
| Input/Output          | `printf`, `scanf`              | `cin`, `cout` (streams) or still use C-style                    |
| Memory Management     | `malloc`, `free`               | `new`, `delete`, smart pointers, RAII                          |
| Namespaces            | ❌                             | ✅ (`namespace std {}` etc.)                                   |

---

### 🧠 Language Features & Syntax

| Feature               | C                        | C++                                                               |
|----------------------|--------------------------|--------------------------------------------------------------------|
| Structures (`struct`) | Only holds data          | Can have methods, constructors, access specifiers (like classes)   |
| Classes & Objects     | ❌                       | ✅                                                                 |
| Access Specifiers     | ❌                       | ✅ (`public`, `private`, `protected`)                             |
| Inheritance           | ❌                       | ✅                                                                 |
| Virtual Functions     | ❌                       | ✅                                                                 |
| Constructors/Destructors| ❌                    | ✅                                                                 |
| Default Arguments     | ❌                       | ✅                                                                 |
| References (`int&`)   | ❌                       | ✅                                                                 |

---

### 🧪 Compilation & Performance

| Feature               | C                      | C++                                               |
|----------------------|------------------------|---------------------------------------------------|
| Compilation Speed     | Fast                   | Slightly slower due to complexity                 |
| Runtime Performance   | Very fast              | Almost as fast (can even outperform C sometimes)  |
| Binary Size           | Usually smaller        | Can be larger due to additional features          |

---

### 💡 Use Cases

| Use Case               | C                     | C++                                |
|------------------------|----------------------|-------------------------------------|
| Embedded Systems       | ✅ Often preferred    | ⚠️ Usable but less common           |
| System Programming     | ✅                    | ✅                                  |
| Game Development       | ⚠️ Too low-level      | ✅ Industry standard (Unreal, etc.) |
| High-Performance Apps  | ✅                    | ✅                                  |
| Teaching Programming   | ✅                    | ✅                                  |

---

### 🎯 Summary

- **C** = Simple, procedural, close to hardware, fast.
- **C++** = Adds abstraction, OOP, generics, and STL to C — still fast and powerful.

## C++ STL
Stands for The Standard Template Library.  that consist of different data structures and algorithms to effectively store and manipulate data.
If we say that data structures store data, we can say that algorithms are used to solve different problems, often by searching through and manipulating those data structures.
Using the right data structure and algorithm makes your program run faster, especially when working with lots of data.

### Key Concepts of the STL
The key components of the STL consist of containers, iterators, and algorithms, and the relationship betweem them:
- Containers are data structures that provides a way to store data, like vectors, lists, etc.
- Iterators are objects used to access elements of a data structure.
- Algorithms include functions, like sort() and find(), that perform operations on data structures through iterators.

In Computer Science, data structures and algorithms go hand in hand. A data structure is not worth much if you cannot search through it or manipulate it efficiently using algorithms, and algorithms are not worth much without a data structure to work on.
[STL](https://learn.microsoft.com/en-us/cpp/standard-library/cpp-standard-library-reference?view=msvc-170)
