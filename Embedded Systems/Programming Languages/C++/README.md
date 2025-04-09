# Differences Between C and C++

## 🔧 Language Type & Paradigm

| Feature                    | C                         | C++                                                    |
|----------------------------|---------------------------|--------------------------------------------------------|
| Programming Paradigm       | Procedural                | Multi-paradigm (Procedural + Object-Oriented + more)   |
| Object-Oriented Programming| ❌ Not supported          | ✅ Fully supported                                      |
| Templates / Generics       | ❌                        | ✅ (`template<typename T>`)                             |
| Function Overloading       | ❌                        | ✅                                                      |
| Operator Overloading       | ❌                        | ✅                                                      | 
| Exception Handling         | ❌                        | ✅ (`try-catch`)                                        |

---

## 🛠️ Standard Library & Built-ins

| Feature               | C                              | C++                                                             |
|----------------------|--------------------------------|------------------------------------------------------------------|
| Standard Library      | Basic (`stdio.h`, `stdlib.h`) | Rich STL (`vector`, `map`, `string`, `algorithm`, etc.)         |
| Strings               | `char[]`, `char*`              | `std::string`                                                   |
| Input/Output          | `printf`, `scanf`              | `cin`, `cout` (streams) or still use C-style                    |
| Memory Management     | `malloc`, `free`               | `new`, `delete`, smart pointers, RAII                          |
| Namespaces            | ❌                             | ✅ (`namespace std {}` etc.)                                   |

---

## 🧠 Language Features & Syntax

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

## 🧪 Compilation & Performance

| Feature               | C                      | C++                                               |
|----------------------|------------------------|---------------------------------------------------|
| Compilation Speed     | Fast                   | Slightly slower due to complexity                 |
| Runtime Performance   | Very fast              | Almost as fast (can even outperform C sometimes)  |
| Binary Size           | Usually smaller        | Can be larger due to additional features          |

---

## 💡 Use Cases

| Use Case               | C                     | C++                                |
|------------------------|----------------------|-------------------------------------|
| Embedded Systems       | ✅ Often preferred    | ⚠️ Usable but less common           |
| System Programming     | ✅                    | ✅                                  |
| Game Development       | ⚠️ Too low-level      | ✅ Industry standard (Unreal, etc.) |
| High-Performance Apps  | ✅                    | ✅                                  |
| Teaching Programming   | ✅                    | ✅                                  |

---

## 🎯 Summary

- **C** = Simple, procedural, close to hardware, fast.
- **C++** = Adds abstraction, OOP, generics, and STL to C — still fast and powerful.
