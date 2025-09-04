```markdown
# Python Practice Task  

## Task: Bank Account Management  

### Problem Statement  
Write a Python program that simulates a simple **bank account system** using **classes and objects**.  

---

### Requirements  

1. Create a class `BankAccount` with:  

   - **Attributes**:  
     * `account_holder`  
     * `balance` (default = 0)  

   - **Methods**:  
     * `deposit(amount)` → adds money to balance.  
     * `withdraw(amount)` → subtracts money if balance is sufficient, otherwise show error.  
     * `display_balance()` → prints the current balance.  

2. In the main program:  
   - Create an object of `BankAccount`.  
   - Perform deposit, withdrawal, and display balance operations.  

---

### 🔎 Example Output  

```
```
Account Holder: Alice
Initial Balance: 0

Depositing 500...
Balance after deposit: 500

Withdrawing 200...
Balance after withdrawal: 300

Withdrawing 500...
Insufficient balance!

Final Balance: 300

````
```
### 💡 Hint

* Use `self` to access attributes inside the class.
* Always check for sufficient balance before withdrawing.
* You can create multiple `BankAccount` objects for different users.
