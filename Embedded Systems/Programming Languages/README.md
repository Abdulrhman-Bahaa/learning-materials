# Programming Languages
These are my notes that are related to programming languages, **NOT** a start point for learning

The most common programming languages for embedded systems are:
- ## 1️⃣ C (Most Widely Used)
  - Direct hardware control
  - Low memory usage
  - Fast execution
  - Used in: Microcontrollers (AVR, STM32, ESP32, etc.), RTOS

- ## 2️⃣ C++ (For Complex Systems)
  - Object-oriented for large projects
  - Still low-level enough for efficiency
  - Used in: Embedded Linux, Automotive systems

- ## 3️⃣ Assembly (For Ultra Low-Level Control)
  - Maximum optimization
  - Direct access to CPU registers
  - Used in: Bootloaders, firmware, low-power devices

- ## 4️⃣ Python (For Embedded Linux & AI on Edge Devices)
  - Easy to code & debug
  - Used with MicroPython & Raspberry Pi
  - Used in: IoT devices, Machine learning on embedded

- ## 5️⃣ Rust (For Safety-Critical Systems)
  - Memory safety (no buffer overflows)
  - High performance like C
  - Used in: Medical devices, Automotive, Aerospace
 
## ✅ Core Basics of Any Programming Language

1. **Syntax**  
   - The rules and structure for writing code.

2. **Data Types**  
   - Common types:
     - `int`
     - `float`
     - `bool`
     - `string`
     - `char`
     - `null` / `None` / `undefined`

3. **Variables**  
   - Used to store and reuse values.

4. **Operators**  
   - **Arithmetic**: `+`, `-`, `*`, `/`, `%`  
   - **Comparison**: `==`, `!=`, `<`, `>`  
   - **Logical**: `&&`, `||`, `!` (or `and`, `or`, `not`)

5. **Control Flow**  
   - **Conditionals**: `if`, `else`, `elif`, `switch`  
   - **Loops**: `for`, `while`, `do-while`

6. **Functions / Methods**  
   - Reusable blocks of code that:
     - Take input (parameters)
     - Perform actions
     - Return output

7. **Data Structures**  
   - Used to organize collections of data:
     - **Lists / Arrays**
     - **Dictionaries / Hash Maps**
     - **Sets**
     - **Tuples / Pairs**

8. **Object-Oriented Programming (OOP)**  
   - Create and use **classes** and **objects**
   - Key concepts:
     - Encapsulation
     - Inheritance
     - Polymorphism
     - Abstraction

9. **Error Handling**  
   - Handle exceptions and bugs gracefully with:
     - `try`
     - `catch` / `except`
     - `finally`
     - `throw` / `raise`

10. **Input/Output (I/O)**  
    - Interact with users or files:
      - Read input
      - Print or log output
      - File read/write

11. **Modules / Libraries / APIs**  
    - Use external or built-in code to add extra functionality.
    - Examples:
      - `import math`
      - `require('fs')`
      - `fetch('api/data')`


 
> [!IMPORTANT]
Before learning how to code, it is **Highly Recommended** to touch type with wpm upove 50 and 99% accuracy. use [typing.com](https://www.typing.com/) to test.
If the score is below the recommended, follow the following:
> 1. Improve Typing Speed:
>    - Practice Touch Typing: Learn to type without looking at the keyboard. Use websites like [typing.com](https://www.typing.com/) to improve your typing skills.
>    - Use Proper Finger Placement: Use all your fingers efficiently and ensure that you use the correct fingers for each key.
>    - Increase Typing Speed Gradually: Set a goal to increase your words-per-minute (WPM) each week. Try to beat your previous score with each practice session.
> 2. Familiarize Yourself with Keyboard Shortcuts:
>    - IDE Shortcuts: Learn the shortcuts for your code editor or IDE (Visual Studio Code, for example). These shortcuts can help you navigate, refactor, or run your code without using > the mouse.
>    - Autocomplete: Make sure to take advantage of autocomplete features in most code editors. This can save you time by auto-suggesting variable names, function calls, or even entire code blocks.
> Common Coding Snippets: Learn to use or create code snippets for repetitive tasks. For example, in VSCode, you can create custom snippets to automatically insert common functions or loops.
> 3. Use a Comfortable Editor:
>    - Choose a Lightweight Code Editor: Use an editor that is lightweight and fast so you’re not wasting time waiting for it to load or respond. Editors like VSCode, Sublime Text, and Atom are good options.
>    - Customization: Customize your editor to match your style, e.g., adding dark mode, custom themes, or installing extensions that make coding faster.

## Data Structures & Algorithms
**Data Structures** are a fundamental element of computer science. They provide a specific way to organize and store data so that it can be accessed and used efficiently. Different types of data structures include arrays, linked lists, stacks, queues, hash tables, trees, and graphs. Each of these has its unique characteristics and use-cases, and is optimal for certain kinds of operations. For example, arrays are excellent for random access, while linked lists work well for frequent insertions and deletions. The correct choice of data structure can significantly enhance the performance of your programs.

**Algorithms** are fundamental to computer programming as they provide step-by-step instructions for executing tasks. An efficient algorithm can help us to find the solution we are looking for, and to transform a slow program into a faster one.

Data structures and algorithms (DSA) go hand in hand. A data structure is not worth much if you cannot search through it or manipulate it efficiently using algorithms, and the algorithms in this tutorial are not worth much without a data structure to work on.
DSA is about finding efficient ways to store and retrieve data, to perform operations on data, and to solve specific problems.
By understanding DSA, you can:
- Decide which data structure or algorithm is best for a given situation.
- Make programs that run faster or use less memory.
- Understand how to approach complex problems and solve them in a systematic way.


[Roadmap](https://roadmap.sh/datastructures-and-algorithms)



      
## [Coding sandards/conventions](https://en.wikipedia.org/wiki/Coding_conventions)
> A set of guidelines for a specific programming language that recommend programming style, practices, and methods for each aspect of a program written in that language.
> 
> These conventions usually cover file organization, indentation, comments, declarations, statements, white space, naming conventions, programming practices, programming principles, programming rules of thumb, architectural best practices, etc.
> 
> These are guidelines for software structural quality. Software programmers are highly recommended to follow these guidelines to help improve the readability of their source code and make software
> maintenance easier. Coding conventions are only applicable to the human maintainers and peer reviewers of a software project. Conventions may be formalized in a documented set of rules that an entire team or company follows or may be as informal as the habitual coding practices of an individual. Coding conventions are not enforced by **compilers**.
