# Object-Oriented Programming with C++ - Unit II

## Inheritance - Practical Programs

### Student Details

**Student Name:** Aditya Prabhakr Bhore  
**PRN:** 125UAD1103
**Class/Division:** SY B.Tech AI&DS: F  
**Course:** Object-Oriented Programming with C++  
**Course Code:** ADPC303  
**Unit:** Unit II - Inheritance  
**Language Standard:** C++

---

## About This Repository

This repository contains practical C++ programs for Unit II:
**Inheritance** of Object-Oriented Programming with C++.

The programs demonstrate different types of inheritance,
access control, constructors and destructors, function overriding,
abstract classes, virtual base classes, friend classes,
nested classes and inheritance-based mini-projects.

---

# List of Programs

## 1. Basic Single Inheritance

This program demonstrates single inheritance using `Person` as
the base class and `Student` as the derived class.

It shows how a derived class receives accessible members from
a base class and demonstrates the "is-a" relationship.

---

## 2. Protected Member Access

This program demonstrates how a derived class can access a
protected member of its base class.

It uses `Employee` as the base class and `Developer` as the
derived class to demonstrate protected member access.

---

## 3. Public versus Private Inheritance

This program demonstrates the difference between public and
private inheritance.

It shows how the accessibility of base-class members changes
depending on the inheritance mode.

---

## 4. Multilevel Inheritance

This program demonstrates multilevel inheritance using the
hierarchy `Person → Employee → Manager`.

It shows how a class can be derived from another derived class
and form a three-level class hierarchy.

---

## 5. Hierarchical Inheritance

This program demonstrates hierarchical inheritance using
`Vehicle` as a common base class.

The `Car` and `Bike` classes are derived from the `Vehicle` class.

---

## 6. Multiple Inheritance

This program demonstrates multiple inheritance using
academic and sports records.

The `Student` class inherits from both `Academic` and `Sports`
classes and calculates the total marks.

---

## 7. Resolving Multiple-Inheritance Ambiguity

This program demonstrates how ambiguity occurs when two base
classes contain member functions with the same name.

The scope-resolution operator is used to specify the required
base-class function.

---

## 8. Constructor and Destructor Order

This program demonstrates the order in which constructors and
destructors are called in inheritance.

During object creation, the base constructor executes first,
followed by the derived constructor. During destruction, the
derived destructor executes first, followed by the base destructor.

---

## 9. Parameterized Base Constructor

This program demonstrates how a derived-class constructor
initializes a parameterized base-class constructor.

It uses `Person` as the base class and `Student` as the
derived class.

---

## 10. Function Overriding

This program demonstrates function overriding using a virtual
member function.

The `Car` and `Boat` classes override the `move()` function
of the `Vehicle` base class.

---

## 11. Abstract Class

This program demonstrates the use of an abstract base class
with a pure virtual function.

The `Shape` class defines the pure virtual `area()` function,
which is implemented by the `Rectangle` and `Circle` classes.

---

## 12. Virtual Base Class and Diamond Inheritance

This program demonstrates virtual inheritance to solve the
duplicate-base problem in diamond inheritance.

The `Person` class is used as a virtual base class so that only
one `Person` part exists in the final derived class.

---

## 13. Friend Class

This program demonstrates the use of a friend class to access
private data of another class.

The `Auditor` class is declared as a friend of the `Account`
class and can access its private balance.

---

## 14. Nested Class

This program demonstrates how to create and use a class
inside another class.

The `Department` class is nested inside the `University` class.

---

# Mini-Projects

## 15. Vehicle Rental System

This mini-project develops an inheritance-based vehicle rental
application.

It uses a `Vehicle` base class and derived classes such as
`Car` and `Bike` to calculate rental charges and display
vehicle information.

The program demonstrates inheritance, function overriding,
virtual functions and constructors.

---

## 16. Employee Payroll System

This mini-project develops a salary management system using
an abstract base class and derived employee classes.

It calculates salary for permanent and contract employees
using pure virtual functions and function overriding.

The program demonstrates abstract classes, inheritance,
polymorphism, constructors and base-class references.

---

# OOP Concepts Covered

- Basic Single Inheritance
- Protected Members
- Public Inheritance
- Private Inheritance
- Multilevel Inheritance
- Hierarchical Inheritance
- Multiple Inheritance
- Multiple-Inheritance Ambiguity
- Scope-Resolution Operator
- Constructors and Destructors
- Constructor Chaining
- Parameterized Base Constructor
- Function Overriding
- Virtual Functions
- Abstract Classes
- Pure Virtual Functions
- Virtual Base Classes
- Diamond Inheritance
- Friend Classes
- Nested Classes
- Polymorphism
- Base-Class References

---

# Repository Structure

```text
OOP-cpp-unit-02
│
├── README.md
│
├── 01-Basic-Single-Inheritance
│   └── basic_single_inheritance.cpp
│
├── 02-Protected-Member-Access
│   └── protected_member_access.cpp
│
├── 03-Public-vs-Private-Inheritance
│   └── public_private_inheritance.cpp
│
├── 04-Multilevel-Inheritance
│   └── multilevel_inheritance.cpp
│
├── 05-Hierarchical-Inheritance
│   └── hierarchical_inheritance.cpp
│
├── 06-Multiple-Inheritance
│   └── multiple_inheritance.cpp
│
├── 07-Multiple-Inheritance-Ambiguity
│   └── multiple_inheritance_ambiguity.cpp
│
├── 08-Constructor-Destructor-Order
│   └── constructor_destructor_order.cpp
│
├── 09-Parameterized-Base-Constructor
│   └── parameterized_base_constructor.cpp
│
├── 10-Function-Overriding
│   └── function_overriding.cpp
│
├── 11-Abstract-Class
│   └── abstract_class.cpp
│
├── 12-Virtual-Base-Class
│   └── virtual_base_class.cpp
│
├── 13-Friend-Class
│   └── friend_class.cpp
│
├── 14-Nested-Class
│   └── nested_class.cpp
│
├── 15-Vehicle-Rental-System
│   └── vehicle_rental_system.cpp
│
└── 16-Employee-Payroll-System
    └── employee_payroll_system.cpp
