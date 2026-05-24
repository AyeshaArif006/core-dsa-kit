
A modular C++ repository containing solutions for a diverse set of Data Structures and Algorithms problems. This project covers advanced linear data structures, recursive matrix traversal, custom UI application architectures, and empirical performance benchmarking of hierarchical structures.

## Project Structure & Problem Overview

The repository is broken down into 4 core programmatic tasks:

###  Task 1: Window Manager ADT
* **Data Structure:** Doubly Linked List (`std::list` or custom implementation)
* **Concept:** Simulates a modern desktop OS window stacking environment where the head node always represents the active window.
* **Core Functions:**
  * `Create()`: Spawns a window with default constraints, title, and color.
  * `Activate()`: Simulates a mouse click, bringing a specified background window node back to the front of the list.
  * `Resize()` / `Delete()`: Modifies properties or safely destroys existing window objects.

###  Task 2: Advanced Text Editor Application
* **Concept:** A clean terminal/graphical text editor with a dedicated UI layout and accessible interaction menus.
* **Functionality Stack:**
  * **File Controls:** New File, Save, Save As, Close File, and a Persistent Recent Files History tracker.
  * **Buffer Actions:** Real-time typing mechanics, continuous line/paragraph tracking via custom layout mechanics, Find & Replace sub-routines, Word-Wrap logic, and active text/font configuration adjustments.
  * **Key Mappings:** Functional structural navigation mapping (`Pg-Up`, `Pg-Dn`, `Home`, `End`, `Delete`, `Backspace`).

###  Task 3: Recursive Grid Area Analyzer (Flood-Fill)
* **Concept:** Counts individual isolated matrix regions and calculates the precise area bounds of each block.
* **Algorithm:** Implements a 4-way Recursive Flood-Fill over an $(n+2) \times (n+2)$ bounded array. The two additional rows and columns act as an explicit black-cell boundary ring (`b`) to safely stop recursive indexing without hitting out-of-bounds segments.
* **Mechanics:** Iterates over the matrix step-by-step; upon spotting an unvisited target cell, it runs a 4-way recursive traversal to change symbols and log total pixel volumes.

###  Task 4: BST Performance Benchmark Engine
* **Data Structure:** Binary Search Tree (BST)
* **Concept:** Implements standard primitive primitives (`Insert`, `Search`, `Traverse`, `Delete`) paired with an empirical performance-tracking setup.
* **Benchmarking Suite:** Automatically generates 5 unique sets of 100 randomized numeric keys to time execution metrics, printing a structured latency comparison matrix:



---

## 🛠️ Compilation & Setup

```bash
# Clone the repository
git clone [https://github.com/AyeshaArif006/core-dsa-kit.git](https://github.com/AyeshaArif006/core-dsa-kit.git)
cd core-dsa-kit

