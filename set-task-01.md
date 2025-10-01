
# Python Sets – Task & Solution

This exercise covers **set creation, updating, removing, and performing set operations** in Python.

## Task

1. **Create a Set**

   * Create a set named `fruits` with values: `"apple"`, `"banana"`, `"cherry"`.
   * Print the set.

2. **Add Elements**

   * Add `"mango"` to the set.
   * Add multiple elements `"orange"` and `"grapes"` at once.

3. **Remove Elements**

   * Remove `"banana"` using `.remove()`.
   * Try removing `"kiwi"` safely using `.discard()`.

4. **Set Operations**

   * Create another set `tropical = {"mango", "papaya", "pineapple"}`.
   * Perform the following:

     * **Union** of `fruits` and `tropical`.
     * **Intersection** of `fruits` and `tropical`.
     * **Difference** between `fruits` and `tropical`.

5. **Set Methods**

   * Find the length of `fruits`.
   * Clear all elements from `tropical`.

---

## Sample Output

```
Initial fruits set: {'apple', 'banana', 'cherry'}
After adding mango: {'apple', 'banana', 'cherry', 'mango'}
After adding multiple: {'apple', 'grapes', 'banana', 'cherry', 'mango', 'orange'}
After removing banana: {'apple', 'grapes', 'cherry', 'mango', 'orange'}
After discarding kiwi (no error): {'apple', 'grapes', 'cherry', 'mango', 'orange'}

Union: {'apple', 'grapes', 'cherry', 'mango', 'orange', 'papaya', 'pineapple'}
Intersection: {'mango'}
Difference: {'apple', 'grapes', 'cherry', 'orange'}

Length of fruits: 5
Tropical after clear: set()
```

---

## 📘 Concepts Covered

✔ Set creation
✔ Adding elements (`add`, `update`)
✔ Removing elements (`remove`, `discard`)
✔ Union, Intersection, Difference
✔ Length of set
✔ Clearing a set
