## Problem Statement
Demonstrate **local, global, and nonlocal variables** in Python and how **scope** affects variable behavior in functions.

---

## 📝 Requirements
1. **Global Variable**
   - Create a global variable `counter = 0`.
   - Write a function `increment_global()` that increments the global `counter` using the `global` keyword.
2. **Local Variable**
   - Write a function `increment_local()` that declares a local variable `counter = 0` and increments it.
   - Show that this does not affect the global `counter`.
3. **Nonlocal Variable**
   - Write a function `outer_function()` with a variable `counter = 0`.
   - Inside it, define `inner_function()` that uses the `nonlocal` keyword to modify `counter`.
   - Call `inner_function()` inside `outer_function()` and print the updated `counter`.
4. Demonstrate how **local, global, and nonlocal scopes** behave differently.

## 🎯 Sample Output

```
Global counter: 1
Local counter: 1
Nonlocal counter: 1
Outer counter after inner: 1
Global counter at end: 1
```

---

## 💡 Concept Highlight

* **Global:** accessible and modifiable anywhere with `global`.
* **Local:** exists only inside the function.
* **Nonlocal:** allows nested functions to modify variables in the enclosing scope.
