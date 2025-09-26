## Pandas Task – Series, DataFrames, CSV/JSON & Data Analysis

## Objective

Practice **Pandas fundamentals**: creating Series and DataFrames, working with CSV & JSON files, and performing basic data analysis.

---

## Task Instructions

### **Part 1 – Pandas Series**

1. Create a **Pandas Series** with values `[10, 20, 30, 40, 50]` and custom index `['a','b','c','d','e']`.
2. Access the value at index `'c'`.
3. Find the **sum** and **mean** of the Series.
4. Multiply all elements of the Series by 2.

---

### **Part 2 – Pandas DataFrame**

1. Create a DataFrame with the following data:

   | Name  | Age | Marks | City     |
   | ----- | --- | ----- | -------- |
   | John  | 20  | 85    | New York |
   | Alice | 19  | 92    | London   |
   | Bob   | 21  | 75    | Paris    |
   | Emma  | 22  | 90    | Tokyo    |
   | David | 20  | 60    | Sydney   |

2. Display the **first 3 rows**.

3. Display only the **Name** and **Marks** columns.

4. Filter students who scored **more than 80 Marks**.

---

### **Part 3 – Reading CSV & JSON**

1. Save the DataFrame as a **CSV file** (`students.csv`) and a **JSON file** (`students.json`).
2. Read both files back into Pandas using:

   * `pd.read_csv("students.csv")`
   * `pd.read_json("students.json")`
3. Display the first 5 rows after reading.

---

## Expected Outcomes

* Understand **Pandas Series** operations (indexing, aggregation, element-wise operations).
* Gain confidence in **DataFrame creation, filtering, sorting, and grouping**.
* Learn how to **read & write CSV/JSON files**.


##  Sample Output
---

### **Part 1 – Pandas Series**

```text
Series:
a    10
b    20
c    30
d    40
e    50
dtype: int64

Value at index 'c': 30
Sum: 150
Mean: 30.0
Series * 2:
a     20
b     40
c     60
d     80
e    100
dtype: int64
```

---

### **Part 2 – Pandas DataFrame**

```text
First 3 rows:
    Name  Age  Marks      City
0   John   20     85  New York
1  Alice   19     92    London
2    Bob   21     75     Paris

Name & Marks:
    Name  Marks
0   John     85
1  Alice     92
2    Bob     75
3   Emma     90
4  David     60

Marks > 80:
    Name  Age  Marks      City
0   John   20     85  New York
1  Alice   19     92    London
3   Emma   22     90     Tokyo
```
---

### **Part 3 – Reading CSV & JSON**

```text
Read from CSV:
    Name  Age  Marks      City
0   John   20     85  New York
1  Alice   19     92    London
2    Bob   21     75     Paris
3   Emma   22     90     Tokyo
4  David   20     60    Sydney

Read from JSON:
    Name  Age  Marks      City
0   John   20     85  New York
1  Alice   19     92    London
2    Bob   21     75     Paris
3   Emma   22     90     Tokyo
4  David   20     60    Sydney
```

