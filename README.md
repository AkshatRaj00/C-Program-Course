# 🟦 C Programming Course

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,40:0b3d91,100:00d9ff&height=260&section=header&text=C%20PROGRAMMING&fontSize=62&fontColor=ffffff&fontAlignY=42&desc=Learn%20C%20Through%20Real%20Code&descSize=20&descAlignY=65&descColor=00d9ff&animation=twinkling" width="100%" />

### `C LANGUAGE • CORE PROGRAMMING • PRACTICAL EXAMPLES`

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2600&pause=800&color=00D9FF&center=true&vCenter=true&width=850&lines=LEARN+C+FROM+ZERO;POINTERS+%E2%80%A2+FUNCTIONS+%E2%80%A2+RECURSION;ARRAYS+%E2%80%A2+STRINGS+%E2%80%A2+STRUCTURES;LOOPS+%E2%80%A2+CONDITIONS+%E2%80%A2+SWITCH;PRACTICE+WITH+REAL+C+SOURCE+FILES" />

<br/>

[![C](https://img.shields.io/badge/C-Programming-00d9ff?style=for-the-badge&logo=c&logoColor=white&labelColor=081018)](https://en.cppreference.com/w/c)
[![GitHub](https://img.shields.io/badge/GITHUB-SOURCE-ffffff?style=for-the-badge&logo=github&logoColor=white&labelColor=111111)](https://github.com/AkshatRaj00/C-Program-Course)
[![License](https://img.shields.io/badge/LICENSE-MIT-00d084?style=for-the-badge&labelColor=111111)](LICENSE)

<br/>

**A practical C programming repository with self-contained source files and examples.**

</div>

---

# 🧠 What is this?

**C Program Course** is a practical learning repository containing small, focused C programs for understanding core programming concepts.

The repository is built around **writing code → compiling → running → observing the result** rather than only reading theory.

---

# ⚡ Learning Flow

```mermaid
flowchart LR

    A["👨‍💻 START"] --> B["📖 C BASICS"]

    B --> C["🔀 CONTROL FLOW"]
    B --> D["📦 ARRAYS"]
    B --> E["⚙️ FUNCTIONS"]

    C --> F["🔁 LOOPS"]
    C --> G["🔀 SWITCH / CONDITIONS"]

    D --> H["🔤 STRINGS"]
    D --> I["📊 ARRAY OPERATIONS"]

    E --> J["📥 PARAMETERS"]
    E --> K["🔄 RECURSION"]

    J --> L["📍 POINTERS"]
    L --> M["🧠 CALL BY REFERENCE"]

    H --> N["🏗️ STRUCTURES"]
    N --> O["🔗 UNION / TYPEDEF"]

    F --> P["💻 COMPILE"]
    G --> P
    I --> P
    K --> P
    M --> P
    O --> P

    P --> Q["▶️ RUN PROGRAM"]
    Q --> R["🎯 UNDERSTAND OUTPUT"]

    style A fill:#111111,stroke:#00d9ff,stroke-width:3px,color:#ffffff
    style B fill:#0b3d91,stroke:#00d9ff,color:#ffffff
    style C fill:#12345a,stroke:#00d9ff,color:#ffffff
    style D fill:#12345a,stroke:#00d9ff,color:#ffffff
    style E fill:#12345a,stroke:#00d9ff,color:#ffffff
    style L fill:#00d9ff,stroke:#ffffff,stroke-width:3px,color:#001018
    style P fill:#ff9f00,stroke:#ffffff,color:#111111
    style Q fill:#7c3aed,stroke:#ffffff,color:#ffffff
    style R fill:#00a86b,stroke:#ffffff,stroke-width:3px,color:#ffffff
```

---

# 📚 Concepts Covered

| Topic | Examples |
|---|---|
| 🟢 Basics | Hello World, input/output, integers |
| 🔀 Conditions | `if`, `else`, `switch` |
| 🔁 Loops | `for`, `while`, `do while` |
| 📦 Arrays | Accessing, changing and passing arrays |
| 🔤 Strings | String handling examples |
| ⚙️ Functions | Declaration, parameters, function calls |
| 🔄 Recursion | Recursive functions |
| 📍 Pointers | Pointer basics and memory references |
| 🔁 Parameter Passing | Call by value / reference |
| 🏗️ Structures | `struct` examples |
| 🔗 Union | `union` examples |
| 🏷️ Typedef | Custom type definitions |
| 🧪 Exercises | Additional practice programs |

---

# 🔥 Core Concepts

```mermaid
flowchart TD

    A["🧠 C CORE"] --> B["VARIABLES"]
    A --> C["CONTROL FLOW"]
    A --> D["FUNCTIONS"]
    A --> E["ARRAYS"]
    A --> F["POINTERS"]

    D --> G["PARAMETERS"]
    D --> H["RECURSION"]

    E --> I["STRINGS"]

    F --> J["MEMORY"]
    F --> K["CALL BY REFERENCE"]

    A --> L["USER DEFINED TYPES"]
    L --> M["STRUCT"]
    L --> N["UNION"]
    L --> O["TYPEDEF"]

    style A fill:#00d9ff,stroke:#ffffff,stroke-width:3px,color:#001018
    style F fill:#0b3d91,stroke:#00d9ff,stroke-width:3px,color:#ffffff
    style L fill:#7c3aed,stroke:#ffffff,color:#ffffff
    style J fill:#00a86b,stroke:#ffffff,color:#ffffff
    style H fill:#ff9f00,stroke:#ffffff,color:#111111
```

---

# 🧩 Repository Examples

```text
C-Program-Course/
│
├── hello.c
├── twonumber.c
├── operation.c
│
├── break.c
├── continue.c
├── for.c
├── while.c
├── dowhile.c
├── switchcase.c
│
├── arrayaccesing.c
├── arraychange.c
├── passingarry.c
│
├── string.c
├── strings.c
│
├── FunctionsDeclaration.c
├── FunctionParameters.c
├── RecursiveFunctions.c
│
├── Pointers.c
├── DanglingPointer.c
├── callbyvalue.c
├── callbyrefrences.c
│
├── structure.c
├── union.c
├── typedef.c
│
├── exercise3.c
│
├── mydirectory/
│   ├── InOut.c
│   ├── coment.c
│   ├── escape.c
│   ├── format.c
│   ├── ifelse.c
│   └── printinteger.c
│
├── docs/
│   └── ARCHITECTURE.md
│
└── LICENSE
```

---

# ⚙️ Compile & Run

## GCC

```bash
gcc hello.c -o hello
```

Run:

```bash
./hello
```

### Windows

```bash
gcc hello.c -o hello.exe
hello.exe
```

### Another example

```bash
gcc Pointers.c -o pointers
./pointers
```

---

# 🧪 Practical Workflow

```mermaid
flowchart LR

    A["📝 WRITE .c FILE"] --> B["⚙️ GCC COMPILER"]
    B --> C["📦 EXECUTABLE"]
    C --> D["▶️ RUN"]
    D --> E["👀 OBSERVE OUTPUT"]
    E --> F["🧠 UNDERSTAND CONCEPT"]

    F -.-> A

    style A fill:#111111,stroke:#00d9ff,color:#ffffff
    style B fill:#0b3d91,stroke:#00d9ff,color:#ffffff
    style C fill:#12345a,stroke:#00d9ff,color:#ffffff
    style D fill:#7c3aed,stroke:#ffffff,color:#ffffff
    style E fill:#ff9f00,stroke:#ffffff,color:#111111
    style F fill:#00a86b,stroke:#ffffff,color:#ffffff
```

---

# 🧠 Pointer Learning Path

```mermaid
flowchart TD

    A["VARIABLE"] --> B["ADDRESS"]
    B --> C["POINTER"]
    C --> D["DEREFERENCE"]
    D --> E["MODIFY VALUE"]

    E --> F["CALL BY REFERENCE"]

    F --> G["MEMORY UNDERSTANDING"]

    style A fill:#111111,stroke:#ffffff,color:#ffffff
    style B fill:#12345a,stroke:#00d9ff,color:#ffffff
    style C fill:#0b3d91,stroke:#00d9ff,stroke-width:3px,color:#ffffff
    style D fill:#7c3aed,stroke:#ffffff,color:#ffffff
    style E fill:#ff9f00,stroke:#ffffff,color:#111111
    style F fill:#00d9ff,stroke:#ffffff,color:#001018
    style G fill:#00a86b,stroke:#ffffff,stroke-width:3px,color:#ffffff
```

---

# 🔄 Function & Recursion

```text
FUNCTION
   │
   ├── Declaration
   │
   ├── Parameters
   │
   ├── Arguments
   │
   └── Return Value
           │
           ▼
       RECURSION
           │
           ├── Function calls itself
           ├── Base condition
           └── Recursive execution
```

---

# 🎯 Why Learn C?

```text
C PROGRAMMING
      │
      ├── 🧠 LOGIC
      ├── 🧮 MEMORY
      ├── 📍 POINTERS
      ├── ⚙️ FUNCTIONS
      ├── 🖥️ SYSTEM BASICS
      └── 🔧 LOW-LEVEL THINKING
```

C gives a strong foundation for understanding programming concepts at a lower level.

---

# 🛠️ Tools

| Tool | Purpose |
|---|---|
| `GCC` | Compile C programs |
| `Git` | Version control |
| `GitHub` | Store and share source code |
| `VS Code` | Write and debug C |
| `Terminal` | Compile and execute programs |

---

# 📈 Course Progression

```mermaid
flowchart LR

    A["01<br/>BASICS"] --> B["02<br/>CONTROL FLOW"]
    B --> C["03<br/>ARRAYS & STRINGS"]
    C --> D["04<br/>FUNCTIONS"]
    D --> E["05<br/>RECURSION"]
    E --> F["06<br/>POINTERS"]
    F --> G["07<br/>STRUCTURES"]
    G --> H["08<br/>ADVANCED PRACTICE"]

    style A fill:#111111,stroke:#00d9ff,color:#ffffff
    style B fill:#12345a,stroke:#00d9ff,color:#ffffff
    style C fill:#0b3d91,stroke:#00d9ff,color:#ffffff
    style D fill:#7c3aed,stroke:#ffffff,color:#ffffff
    style E fill:#ff9f00,stroke:#ffffff,color:#111111
    style F fill:#00d9ff,stroke:#ffffff,color:#001018
    style G fill:#00a86b,stroke:#ffffff,color:#ffffff
    style H fill:#111111,stroke:#ffffff,color:#ffffff
```

---

# 🚀 Quick Start

```bash
git clone https://github.com/AkshatRaj00/C-Program-Course.git

cd C-Program-Course

gcc hello.c -o hello

./hello
```

For Windows:

```bash
gcc hello.c -o hello.exe
hello.exe
```

---

# 👨‍💻 Author

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=071018&height=100&section=footer&text=AKSHAT%20RAJ&fontSize=30&fontColor=00D9FF&fontAlignY=50" width="100%" />

### Akshat Raj

**C Programming • Software Development • AI Engineering**

[![GitHub](https://img.shields.io/badge/GitHub-AkshatRaj00-111111?style=for-the-badge&logo=github)](https://github.com/AkshatRaj00)

</div>

---

# 📜 License

This project is licensed under the **MIT License**.

See [`LICENSE`](LICENSE) for details.

---

<div align="center">

### 💻 C PROGRAMMING

**Write Code → Compile → Run → Understand**

<br/>

`Built by Akshat Raj`

</div>
