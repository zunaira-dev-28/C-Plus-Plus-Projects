<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0E14,55:991B1B,100:0284C7&height=180§ion=header&text=C%2B%2B%20PROJECTS&fontSize=55&fontColor=00E5FF&animation=fadeIn&fontAlignY=42&desc=OOP%20%E2%80%A2%20DATA%20STRUCTURES%20%E2%80%A2%20STL%20UTILITIES&descAlignY=66&descSize=15" width="100%"/>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Language-C%2B%2B17-0B0E14?style=for-the-badge&logo=cplusplus&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/Paradigm-Object_Oriented-0B0E14?style=for-the-badge&labelColor=DC2626" />
  <img src="https://img.shields.io/badge/Focus-DSA_%26_STL-0B0E14?style=for-the-badge&labelColor=0284C7" />
</p>

---

### 📂 Repository Index

A structured collection of concise, single-file C++ implementations demonstrating **Object-Oriented Programming**, **Data Structures & Algorithms**, and **Standard Template Library (STL)** fundamentals.

#### 01. Object-Oriented Programming (`01-OOP-Concepts/`)
| File | Description & Core Concepts |
| :--- | :--- |
| `rpg_character_polymorphism.cpp` | Runtime polymorphism using base-class pointers, `virtual` functions, and `override` |
| `bank_account_encapsulation.cpp` | Data encapsulation, parameterized constructors, input validation, and `static` counters |
| `library_book_tracker.cpp` | Class-based record management with `std::vector` and persistent file I/O (`<fstream>`) |

#### 02. Data Structures & Algorithms (`02-DSA-Implementations/`)
| File | Description & Core Concepts |
| :--- | :--- |
| `singly_linked_list_crud.cpp` | Dynamic node allocation (`new`/`delete`), pointer traversal, insertion, deletion, and reversal |
| `undo_redo_stack.cpp` | Dual-stack state history engine using LIFO `std::stack` containers |
| `ticket_counter_queue.cpp` | Request processing simulator built on FIFO `std::queue` operations |

#### 03. STL & Logic Utilities (`03-STL-Utilities/`)
| File | Description & Core Concepts |
| :--- | :--- |
| `custom_leaderboard_sorter.cpp` | Multi-criteria sorting with `std::sort` and custom lambda comparators |
| `simple_xor_cipher.cpp` | Symmetric file encryption and decryption using bitwise `^` (XOR) and `<fstream>` |
| `cgpa_calculator.cpp` | Weighted academic GPA/CGPA calculator using `std::vector` and formatted console output |

---

### ⚙️ Compilation & Execution
Each file is self-contained and compiles cleanly with any C++17-compliant compiler:

```bash
g++ -std=c++17 -Wall folder_name/filename.cpp -o app
./app
