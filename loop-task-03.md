
```markdown
#  Python Practice Task  

## Task: Upright Pyramid Pattern  

### 📌 Problem Statement  
Write a Python program that prints an **upright pyramid pattern** of stars (`*`) based on the number of rows entered by the user.  

- The number of stars increases with each row.  
- Each row is centered using spaces.  

---

### ✅ Example Output  

#### For 3 rows:
```
```
  * 
 *** 
***** 
```
```
#### For 5 rows:
```

```
    *
   ***
  *****
 *******
*********

````

---



### 💡 Hint

* Use `" " * (rows - i - 1)` to add spaces before stars.
* Use `"*" * (2 * i + 1)` to print stars in odd sequence (1, 3, 5, …).
