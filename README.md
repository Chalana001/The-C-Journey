# 🚀 My C Journey: The Hacker's Path (Java to RE)

Target: Reverse Engineering & Exploitation 🏴‍☠️

---

### ✅ C-0. Mental Model (Before Coding)
- [x] **1. What is a program?** (Input -> Process -> Output)
- [x] **2. Source code → Compiler → Binary** (Translation process)
- [x] **3. What is Memory?** (The Hotel Analogy / Addresses)
- [x] **4. CPU executes instructions, not code** (Opcodes vs Source)

---

### 💻 C-1. The Setup & Core Syntax (Fast Track)
*Goal: Read C, Compile manually, Understand the Build.*
- [ ] **1. Environment Setup:** GCC, VS Code, Linux/WSL terminal.
- [ ] **2. The Build Process:** Preprocessor (`#include`) -> Compiler -> Linker.
- [ ] **3. Entry Point:** `main(argc, argv)` and Command Line Arguments.
- [ ] **4. I/O & Formats:** `printf`, `scanf` and Format Specifiers (`%d`, `%x`, `%s`).
- [ ] **5. Control Flow:** Syntax differences from Java (if, loops).

---

### 🧠 C-2. Memory Fundamentals (THE BATTLEFIELD)
*This is where Engineers are separated from Coders.*
- [ ] **1. RAM vs CPU Registers:** How data moves.
- [ ] **2. Address vs Value:** Everything is a number.
- [ ] **3. Memory Layout:** Text, Data, BSS, Stack, Heap.
- [ ] **4. Stack Memory:** Stack Frames, Local variables.
- [ ] **5. Static / Global Memory:** Scope and Lifetime.

---

### 🗡️ C-3. Pointers (THE WEAPON)
*Spend the MOST time here. No shortcuts.*
- [ ] **1. Pointer Syntax:** `int *ptr`, `&` (Address of), `*` (Dereference).
- [ ] **2. Pointer Arithmetic:** `ptr + 1` (Jumping by data type size).
- [ ] **3. Pointers vs Arrays:** How `arr[i]` is actually `*(arr + i)`.
- [ ] **4. Pointers to Pointers:** `**ptr` (Handling complex data).
- [ ] **5. Function Arguments:** Pass by Reference vs Pass by Value.
- [ ] **6. Dangling Pointers:** Accessing dead memory.
- [ ] **7. NULL Pointers:** The Billion Dollar Mistake.

---

### ⚠️ C-4. Arrays & Strings (THE VULNERABILITIES)
*This feeds directly into exploitation later.*
- [ ] **1. Arrays in Memory:** Contiguous blocks.
- [ ] **2. Strings as Byte Arrays:** `char` arrays + `\0` (Null Terminator).
- [ ] **3. `char*` vs `char[]`:** Read-only string literals vs Mutable arrays.
- [ ] **4. Buffer Boundaries:** Lack of bounds checking in C.
- [ ] **5. Off-by-one Errors:** The classic logic bug.
- [ ] **6. Unsafe Functions:** `strcpy`, `gets` vs `strncpy`.

---

### 🏗️ C-5. Structs & Alignment (BINARY STRUCTURE)
*Learning how binaries store data.*
- [ ] **1. Struct Memory Layout:** How fields are packed.
- [ ] **2. Padding & Alignment:** Why `char` + `int` != 5 bytes.
- [ ] **3. Struct Pointers:** Accessing fields via `->`.
- [ ] **4. Nested Structs:** Complex data shapes.

---

### 💣 C-6. Heap Management (MANUAL MODE)
*These bugs = Security Gold.*
- [ ] **1. Manual Allocation:** `malloc`, `calloc`.
- [ ] **2. Resizing:** `realloc`.
- [ ] **3. Manual Deallocation:** `free`.
- [ ] **4. Memory Leaks:** Forgetting to free.
- [ ] **5. Use-After-Free (UAF):** Accessing memory after `free()`.
- [ ] **6. Double Free:** Crashing the allocator.

---

### ⚙️ C-7. Compilation & Linking (UNDER THE HOOD)
*You now understand what a binary really is.*
- [ ] **1. The Preprocessor:** Macros (`#define`), Conditional compilation.
- [ ] **2. Object Files:** What is `.o`?
- [ ] **3. Symbol Tables:** How functions find each other.
- [ ] **4. Static vs Dynamic Linking:** `.a` vs `.so` / `.dll`.

---

### 💾 C-8. Low-Level I/O (SYSTEM CALLS)
*Talking to the Kernel.*
- [ ] **1. File Descriptors:** integers representing files.
- [ ] **2. System Calls:** `open`, `read`, `write`, `close`.
- [ ] **3. Buffers:** How data is moved in chunks.
- [ ] **4. Binary I/O:** Reading raw bytes (Hex editing logic).

---
