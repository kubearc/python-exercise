## Python Task – NumPy Joining Arrays (`concatenate` & `stack`)

## Task

Write a Python program that demonstrates joining arrays using **`np.concatenate()`** and **`np.stack()`**:

1. Create two **1D arrays**:

   ```
   [1, 2, 3]
   [4, 5, 6]
   ```

   * Join them using `np.concatenate()`.
   * Stack them using `np.stack()` along different axes.

2. Create two **2D arrays**:

   ```
   [[1, 2], [3, 4]]
   [[5, 6], [7, 8]]
   ```

   * Join along **axis=0** and **axis=1** using `np.concatenate()`.
   * Stack them along **axis=0** and **axis=1** using `np.stack()`.

## Expected Output

```
Concatenated 1D Array: [1 2 3 4 5 6]

Stacked 1D Arrays (axis=0):
 [[1 2 3]
  [4 5 6]]

Stacked 1D Arrays (axis=1):
 [[1 4]
  [2 5]
  [3 6]]

Concatenated 2D Array (axis=0):
 [[1 2]
  [3 4]
  [5 6]
  [7 8]]

Concatenated 2D Array (axis=1):
 [[1 2 5 6]
  [3 4 7 8]]

Stacked 2D Arrays (axis=0):
 [[[1 2]
   [3 4]]

  [[5 6]
   [7 8]]]

Stacked 2D Arrays (axis=1):
 [[[1 2]
   [5 6]]

  [[3 4]
   [7 8]]]
```

---

✅ This task shows the difference between **`concatenate()`** (merges along existing axes) and **`stack()`** (creates a new dimension).
