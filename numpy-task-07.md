## Python Task – NumPy Joining Arrays

## Task

Write a Python program that demonstrates how to **join arrays** in NumPy:

1. Create two **1D arrays**:

   ```
   [1, 2, 3]
   [4, 5, 6]
   ```
2. Join them using `np.concatenate()`.
3. Create two **2D arrays**:

   ```
   [[1, 2], [3, 4]]
   [[5, 6], [7, 8]]
   ```
4. Join them:

   * Along **axis=0** (row-wise).
   * Along **axis=1** (column-wise).

## Expected Output

```
Joined 1D Array: [1 2 3 4 5 6]

Joined 2D Array (axis=0):
 [[1 2]
  [3 4]
  [5 6]
  [7 8]]

Joined 2D Array (axis=1):
 [[1 2 5 6]
  [3 4 7 8]]
```

---

✅ This task helps practice **joining NumPy arrays** for both **1D and 2D arrays** using `np.concatenate()`.
