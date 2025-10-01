## Python Task – Ultimate NumPy Operations Practice

## Task

Write a Python program using **NumPy** that demonstrates:

1. Creating **1D and 2D arrays**  
2. Accessing elements using **indexing**  
3. Extracting elements using **slicing**  
4. Checking and converting **data types**  
5. **Reshaping** arrays  
6. **Enumerated iteration** using `np.ndenumerate()`  
7. **Joining arrays** with `concatenate` and `stack`  
8. **Splitting arrays** with `split`  
9. **Sorting** arrays with `np.sort()`  

---

##  Requirements

1. Import **NumPy**.  
2. Create a **1D array** `[15, 5, 25, 10, 20, 30]`.  
3. Create a **2D array**:  

   ```python
   [[7, 8, 9],
    [4, 5, 6]]

4. Perform the following operations:

* **Indexing**: Print the 2nd element of the 1D array and the element at row=0, col=2 of the 2D array.
* **Slicing**: Extract `[5, 25, 10]` from the 1D array.
* **Data type**: Print the data type and convert the 1D array to `float`.
* **Reshape**: Convert the 1D array into a `2x3` 2D array.
* **Enumeration**: Use `np.ndenumerate()` on reshaped array to print indices and values.
* **Joining**:

  * Concatenate the 1D array with `[35, 40]`.
  * Stack arrays `[1, 2, 3]` and `[4, 5, 6]` along both axis 0 and 1.
* **Splitting**: Split the original 1D array into 3 equal parts.
* **Search**:

  * Find the indices where elements are equal to `10`.
  * Use `np.searchsorted()` to find the position of `18` in the sorted array.
* **Sort**:

  * Sort the 1D array in ascending order.
  * Sort each row of the 2D array.
    
## Sample Output
```
1D Array: [15  5 25 10 20 30]

2D Array:
 [[7 8 9]
  [4 5 6]]

2nd element of 1D array: 5
Element at row=0, col=2 of 2D array: 9

Sliced 1D Array [5, 25, 10]: [ 5 25 10]

Data type of arr1D: int64
Converted to float: [15.  5. 25. 10. 20. 30.]

Reshaped 2x3 Array:
 [[15  5 25]
  [10 20 30]]

Enumerating reshaped array:
Index (0, 0) -> Value 15
Index (0, 1) -> Value 5
Index (0, 2) -> Value 25
Index (1, 0) -> Value 10
Index (1, 1) -> Value 20
Index (1, 2) -> Value 30

Concatenated 1D Array: [15  5 25 10 20 30 35 40]

Stacked Arrays (axis=0):
 [[1 2 3]
  [4 5 6]]
Stacked Arrays (axis=1):
 [[1 4]
  [2 5]
  [3 6]]

Splitted 1D Array into 3 parts:
Part 1: [15  5]
Part 2: [25 10]
Part 3: [20 30]


Sorted 1D Array: [ 5 10 15 20 25 30]
Sorted 2D Array row-wise:
 [[7 8 9]
  [4 5 6]]
```


## 📘 Concepts Covered

✔ Array creation
✔ Indexing & slicing
✔ Data types & conversion
✔ Reshaping
✔ Enumeration with indices
✔ Joining & stacking
✔ Splitting arrays
✔ Sorting arrays
