
#  Python Test Task – Library Management System

## Problem Statement
Write a Python program that simulates a **library management system** using both **Python basics** and **OOP concepts**.

---

## Requirements

1. Create a class `Book` with:
   - Attributes: `title`, `author`, `available` (default = True).  
   - Method: `display_info()` → prints book details.  

2. Create a class `Library` with:
   - Attribute: `books` (a list to store book objects).  
   - Methods:  
     - `add_book(book)` → adds a book to the library.  
     - `show_books()` → displays all books.  
     - `borrow_book(title)` → changes availability if the book is borrowed.  

3. In the main program:
   - Create a few books and add them to the library.  
   - Use a loop to display a menu:  
     1. Show all books  
     2. Borrow a book  
     3. Exit 

---

## 🖥 Example Run

```
--- Library Menu ---
1. Show all books
2. Borrow a book
3. Exit
Enter choice: 1
Python Basics by John Doe - Available
OOP in Python by Jane Smith - Available
Data Science 101 by Emily Brown - Available

--- Library Menu ---
1. Show all books
2. Borrow a book
3. Exit
Enter choice: 2
Enter book title: Python Basics
You borrowed 'Python Basics'.

--- Library Menu ---
1. Show all books
2. Borrow a book
3. Exit
Enter choice: 1
Python Basics by John Doe - Not Available
OOP in Python by Jane Smith - Available
Data Science 101 by Emily Brown - Available
```
