# 📘 Module 01 - Introduction to .NET (Notes)

# 1. What is .NET?

### Definition

.NET is a software development platform developed by Microsoft to build different types of applications.

### Think of it as

A toolbox that contains everything required to build applications.

### Applications built using .NET

* Desktop Applications
* Web Applications
* Mobile Applications
* Web APIs
* Cloud Applications
* Games (using Unity with C#)

### Interview Point

* .NET is a **Platform**.
* It is **NOT** a programming language.

---

# 2. What is a Platform?

A platform is an environment that provides all the tools, libraries and runtime required to build and run applications.

### Easy Example

Python → Language

VS Code → Editor

.NET → Platform

---

# 3. Why did Microsoft create .NET?

Before .NET, developers had to build many things from scratch and different languages followed different approaches.

Microsoft created .NET to provide:

* Common libraries
* Runtime
* Development tools
* Better productivity
* Faster application development

---

# 4. What is .NET Framework?

.NET Framework is the first implementation of the .NET platform.

### Features

* Windows only
* Older technology
* Mainly used for legacy applications

### Limitation

It only supports Windows.

---

# 5. What is .NET Core?

.NET Core is the modern implementation of .NET introduced to overcome the limitations of .NET Framework.

### Features

* Cross-platform
* Open Source
* High Performance
* Cloud Friendly

Supports:

* Windows
* Linux
* macOS

---

# 6. Evolution of .NET

.NET Framework

↓

.NET Core 1

↓

.NET Core 2

↓

.NET Core 3.1

↓

.NET 5

↓

.NET 6

↓

.NET 7

↓

.NET 8

↓

.NET 9

↓

.NET 10

---

# 7. Why is there no .NET Core 4?

Microsoft skipped the name ".NET Core 4" to avoid confusion with ".NET Framework 4.x".

Instead, they introduced **.NET 5**.

---

# 8. Why was the word "Core" removed?

Microsoft wanted a single, unified platform.

Instead of continuing with ".NET Core", they simplified the name to ".NET".

Example:

.NET Core 3.1

↓

.NET 5

↓

.NET 6

↓

.NET 7

↓

.NET 8

↓

.NET 9

↓

.NET 10

---

# 9. What is C#?

C# is an object-oriented programming language developed by Microsoft.

It is the primary language used to build applications on the .NET platform.

### Remember

C# = Language

.NET = Platform

Visual Studio = IDE

---

# 10. What is CLR?

CLR stands for Common Language Runtime.

It is the execution engine of .NET.

Responsibilities:

* Executes .NET applications
* Memory Management
* Exception Handling
* Garbage Collection
* Security
* Contains the JIT Compiler

---

# 11. What is IL?

IL stands for Intermediate Language.

When a C# program is compiled, it is first converted into IL instead of machine code.

Reason:

One IL program can run on different operating systems.

---

# 12. What is JIT?

JIT stands for Just-In-Time Compiler.

Its job is to convert IL into machine code just before execution.

---

# 13. Code Execution Flow

C# Code

↓

C# Compiler

↓

Intermediate Language (IL)

↓

CLR

↓

JIT Compiler

↓

Machine Code

↓

CPU

↓

Output

---

# 14. Key Takeaways

* .NET is a platform.
* C# is a programming language.
* Visual Studio is an IDE.
* .NET Framework supports only Windows.
* .NET Core introduced cross-platform support.
* Modern development uses .NET 5 and above.
* CLR executes .NET programs.
* JIT converts IL into machine code.
* The CPU executes machine code.

