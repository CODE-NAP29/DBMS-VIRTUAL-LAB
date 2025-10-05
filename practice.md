# 🏋️ TCL Practice Exercises

Sharpen your understanding of TCL with these exercises.

---

## 🔹 Level 1 – Basics
1. Insert a new record into `students` table. Use `ROLLBACK` to undo it.  
2. Update salary of an employee in `employees` table. Use `COMMIT` to save changes.  

---

## 🔹 Level 2 – Intermediate
3. Transfer ₹2000 from Account A to Account B using `UPDATE` + `COMMIT`.  
4. Insert 3 rows into `orders` table, then rollback only the last insert using `SAVEPOINT`.  

---

## 🔹 Level 3 – Advanced
5. Create a transaction where multiple employees get a bonus. If one update fails, rollback to `SAVEPOINT`.  
6. Use `SET TRANSACTION` to make a read-only transaction and try to insert a row. Observe what happens.  

---

💡 **Tip:** Always test TCL commands in a sample DB. Never in production.
