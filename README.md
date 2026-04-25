# fibonacci
# 🔢 Fibonacci (Optimized DP)

This project demonstrates how to compute the **nth Fibonacci number** using a **space-optimized Dynamic Programming approach**.

---

## 📌 Problem

Find the nth Fibonacci number:

F(0) = 0  
F(1) = 1  
F(n) = F(n-1) + F(n-2)

---

## 💡 Approach

Instead of using recursion or full DP array, we optimize space by storing only the last two values:

- `prev2` → F(n-2)
- `prev1` → F(n-1)

---
