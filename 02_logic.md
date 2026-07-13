## 2. Logic: The Geometric & Question-Driven Approach

This chapter approaches Boolean algebra not through abstract academic formulas, but through intuition, questions, and physical breadboard experiments.

### 🧩 The Primitives: NOT, AND, OR, XOR

Before wiring the boards, we challenge the foundational math with a fundamental questionnaire:

* **Are the underlying operators actually relations?**
  * Investigating the deep mathematical nature of logic gates.
* **Why focus solely on Boolean Algebra (NOT, AND)?**
  * Understanding minimal functional completeness and why we only need these two to build everything.
* **From (NOT, AND) to (OR, XOR):**
  * Practical translation of algebra into physical hardware. *Note: These are wired on separate, isolated breadboards!*

---

### 🧮 First Steps into Arithmetic

How do we move from simple logic gates to a machine that can actually calculate?

* **Binary Addition: *An Exercise for the Reader***
  * You will derive the core mechanics of binary adding yourself before looking at the solution.
* **Subtraction derived from Group Theory (The Go-Board Analogy) ⚪⚫**
  * Using the spatial dynamics of stones on a Go-board to understand group inverses and subtraction without negative numbers.
* **The Hardware Bottleneck: Why shifting from theory to circuits is brutal**
  * An honest look at propagation delays and the fundamental problem of the **Ripple-Carry-Effect**.
* **The Ripple-Carry & The Beauty of Padding**
  * How alignment and padding solve the structural issues of our data bus.
* **Generating the Sum (Concrete Schematic)**
  * The final, physical circuit diagram implemented on the board.
