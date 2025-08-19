# Object-oriented-programming
# Aim
To study and implement classes and objects in C++.

# Tools
Visual Studio Code

# Theory
## Overview of OOP

Object-Oriented Programming (OOP): A programming paradigm where programs are designed using objects that combine data and behavior.

Purpose: To improve modularity, reusability, and maintainability of code.

### Class

Definition: A class is a user-defined blueprint that represents real-world entities by combining data members (variables) and member functions (methods).

Key Features:

Provides data hiding and security.

Uses access specifiers → private, public, protected.

Memory is allocated only when objects are created.

### Object

Definition: An instance of a class that represents a specific entity in the program.

🔹 Methods (Member Functions)

Definition: Functions declared inside a class that define the behavior of objects.

Types:

Inside Class Definition: Defined directly inside the class body.

Outside Class Definition: Declared inside class but defined outside using scope resolution ::.

Special Methods:

Constructor: Special method used to automatically initialize objects at the time of creation.

Destructor: Special method used to clean up and release resources when an object goes out of scope.

Additional Features:

Methods can be overloaded (same name, different parameters).

Methods can be static (shared by all objects).

Methods can be declared as const (do not modify object data).

### Core OOP Concepts (One-Line Definitions)

Encapsulation: Binding of data and methods together in a single unit (class).

Abstraction: Displaying only essential details while hiding the background implementation.

Inheritance: Mechanism by which a new class (derived) acquires properties of an existing class (base).

Polymorphism: Ability of a function, operator, or method to exist in multiple forms.

Dynamic Binding: Process of linking a function call with its definition at runtime.

Message Passing: Interaction between objects through function/method calls.

Friend Function: A non-member function that is allowed access to private/protected members of a class.

Operator Overloading: Redefining operators to perform operations on user-defined types.
Perfect Anshika 👌 You’ve written **algorithms in step-by-step form**. I’ll now **add proper numbering** to each algorithm and make it **exam-ready** with a neat structure.

---

#  Algorithms – OOPs (Classes, Objects, Methods in C++)

---

### **1. Create a class Car and its related objects**

**Algorithm:**

1. Start.
2. Define a class `Car` with attributes: **brand** and **year**.
3. Declare an array of `Car` objects.
4. For each car, input **brand** and **year**.
5. Display **brand** and **year**.
6. End.

---

### **2. Calculate area and volume of cube**

**Algorithm:**

1. Start.
2. Define a class `Area` with members: **length, width, height**.
3. Input **length, width, and height**.
4. If `length = width` → print **"Cube"**, else print **"Cuboid"**.
5. If `length` or `width < 0` → print **"Error"**.
6. Else calculate and display:

   * **Area = length × width**.
   * **Volume = length × width × height**.
7. End.

---

### **3. Volume of cube using methods inside and outside the class**

**Algorithm:**

1. Start.
2. Define a class `Cube` with members: **height, width, length**.
3. Inside the class, define method **volume\_in()** → calculates and prints volume (`length × width × height`).
4. Declare method **volume\_out()** inside class (prototype only).
5. Define **volume\_out()** outside the class → calculates and prints volume.
6. Input **height, width, length**.
7. Call **volume\_in()** (inside-class method).
8. Call **volume\_out()** (outside-class method).
9. End.

---

### **4. Cube volume (public and private objects)**

**Algorithm:**

1. Start.
2. Define a class `Cube` with **private data members**: length, width, height.
3. Define a **public function volume()** that calculates and returns `length × width × height`.
4. Create an object of `Cube`.
5. Call **volume()** and display the result.
6. End.

---

### **5. Conclusion**

* We learned the basics of **OOP concepts** in C++.
* Understood **classes, objects, data members, and class methods**.
* Practiced writing algorithms with:

  * Inside-class methods.
  * Outside-class methods.
  * Use of **private** and **public** access.

---

