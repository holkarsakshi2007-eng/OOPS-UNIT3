Sakshi Dadaso Holkar

126UAD2007

SY-F

## Object-Oriented Programming

Unit-3

Prorams:-

1 Function overloading Compile-time polymorphism


2 Area calculator Function overloading with different parameters

3 Unary minus operator Unary operator overloading

4 Prefix and postfix increment Unary operator overloading

5 Complex number addition Binary + operator overloading

6 Distance comparison Relational operator overloading

7 Non-member/friend operator Operator overloading using friend function

8 Base pointer without virtual function Static binding demonstration

9 Base pointer with virtual function Run-time polymorphism

10 Base reference with virtual function Dynamic binding through references

11 Abstract class Pure virtual function

12 Collection of shape pointers Polymorphic processing

13 Virtual destructor Safe deletion through base pointer

14 Object slicing Why references/pointers are needed

15 Payment system Abstract interface and real-world example

16 Payroll mini-project Integrated polymorphism application


# Polymorphism & Dynamic Binding

Welcome to the third module of my C++ OOP journey! This section explores **Compile-Time Polymorphism** (Function and Operator Overloading) and **Run-Time Polymorphism** (Virtual Functions, Abstract Interfaces, and Dynamic Binding).

---

##  Unit 3: Topics & Programs

Here is the structured breakdown of all compile-time and run-time polymorphism concepts implemented in this unit:

| S.No. | Topic / Concept | Description |
| :---: | :--- | :--- |
| **1** | **Function Overloading** | Achieving compile-time polymorphism by defining multiple functions with the same name but different signatures. |
| **2** | **Area Calculator** | Practical application of function overloading using varying parameter lists for geometric calculations. |
| **3** | **Unary Minus Operator** | Overloading unary operators (like `-`) to invert object states. |
| **4** | **Prefix & Postfix Increment** | Handling operator overloading variations for increment operators (`++x` vs `x++`). |
| **5** | **Complex Number Addition** | Overloading binary operators (like `+`) to perform arithmetic directly on custom objects. |
| **6** | **Distance Comparison** | Implementing relational operator overloading (`<`, `>`, `==`) for custom classes. |
| **7** | **Friend Operator Overloading** | Using non-member friend functions to overload operators where the left operand is not a class instance. |
| **8** | **Static Binding (No Virtual)** | Demonstrating early binding behavior when base pointers point to derived objects without virtual keywords. |
| **9** | **Run-Time Polymorphism** | Enabling late binding using virtual functions with base pointers. |
| **10** | **Dynamic Binding via References** | Achieving polymorphic behavior through base class references instead of pointers. |
| **11** | **Abstract Class & Pure Virtual** | Designing mandatory interface structures using pure virtual functions (`= 0`). |
| **12** | **Shape Pointers Collection** | Processing heterogeneous collections of objects polymorphically using base pointers. |
| **13** | **Virtual Destructor** | Ensuring safe resource cleanup and preventing memory leaks in polymorphic hierarchies. |
| **14** | **Object Slicing** | Demonstrating data loss when assigning derived objects to base objects and why references/pointers prevent it. |
| **15** | **Payment System (Interface)** | Real-world application of abstract interfaces to handle multiple payment gateways polymorphically. |
| **16** | **Payroll Mini-Project** | Capstone application integrating inheritance, virtual functions, and polymorphic employee management. |

---

##  Capstone Applications 

* **Compile-Time vs. Run-Time:** Clear separation of how C++ resolves function calls at compile-time (overloading) versus run-time (virtual functions).
* **Memory & Safety:** Avoiding object slicing and ensuring resource cleanup using virtual destructors.
* **Real-World Modeling:** The **Payment System** and **Payroll Mini-Project** showcase scalable software design patterns using pure virtual interfaces.

---

##  Compilation & Execution

To compile and test any program in this unit, use your standard C++ compiler:

```bash
# Navigate to the specific program directory
cd "Folder-Name"

# Compile the source file
g++ program_name.cpp -o output

# Run the executable
./output

