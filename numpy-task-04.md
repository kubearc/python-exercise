## Python Task – NumPy Copy, View & Iteration

## Task
Write a Python program using **NumPy** that demonstrates:

1. The difference between **copy** and **view**.  
2. Iterating over a **1D array**.  
3. Iterating over a **2D array** (row-wise and element-wise).  

---

## Requirements
1. Import **NumPy**.  
2. Create a **1D array** `[1, 2, 3, 4, 5]`.  
3. Create a **copy** and a **view** of this array.  
4. Modify the **original array** and show how it affects the **view** but not the **copy**.  
5. Iterate through:  
   - The **1D array** and print each element.  
   - A **2D array**:  
     ```
     [[10, 20, 30],
      [40, 50, 60]]
     ```  
     - Print each row.  
     - Print each element using nested iteration.  

## 🎯 Sample Output

```
Original Array: [1 2 3 4 5]

After modifying original array:
Original Array: [99  2  3  4  5]
Copy (independent): [1 2 3 4 5]
View (changes reflected): [99  2  3  4  5]

Iterating over 1D Array:
99 2 3 4 5 

2D Array:
 [[10 20 30]
  [40 50 60]]

Iterating row-wise:
[10 20 30]
[40 50 60]

Iterating element-wise:
10 20 30 40 50 60
```

---

✅ This task helps understand **copy vs. view in NumPy** and practice **iteration in 1D and 2D arrays**.
