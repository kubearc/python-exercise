## Problem Statement
Demonstrate **polymorphism** in Python by creating a base class and multiple subclasses representing different shapes, each calculating its **area**.

---

## Requirements
1. Create a **base class** `Shape` with a method `area()`.
2. Create at least **three subclasses** that override the `area()` method:
   - `Circle` → area = π × r²
   - `Rectangle` → area = length × width
   - `Triangle` → area = 0.5 × base × height
3. Write a function `print_area(shape)` that takes any `Shape` object and prints its area.
4. Demonstrate **polymorphism** by passing different shape objects to the function.

## 🎯 Sample Output

```
Area: 78.53981633974483
Area: 24
Area: 10.5
```

---

## 💡 Concept Highlight

* **Polymorphism** allows the same function (`print_area`) to work differently depending on the **object type** (`Circle`, `Rectangle`, `Triangle`) passed.
* The `area()` method is **overridden** in each subclass to provide the correct implementation for that shape.
