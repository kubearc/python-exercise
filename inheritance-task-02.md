# Python Practice Task – Multilevel Inheritance (Person → Student → Graduate)

## Problem Statement
Write a Python program that demonstrates **multilevel inheritance**.

### Requirements
1. Create a **base class** `Person` with:
   * Attribute: `name`.
   * Method: `display_name()` → prints the person’s name.
2. Create a **child class** `Student` that inherits from `Person` and adds:
   * Attribute: `student_id`.
   * Method: `display_student()` → prints name and student ID.
3. Create a **child class** `Graduate` that inherits from `Student` and adds:
   * Attribute: `degree`.
   * Method: `display_graduate()` → prints name, ID, and degree.
4. Create an object of `Graduate` and call all methods.

## 🖥 Example Output

```
Name: Alice
Student ID: S123
Degree: MSc Computer Science
------------------------------
```
