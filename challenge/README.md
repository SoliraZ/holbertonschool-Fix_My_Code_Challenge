# 🛠️ Fix My Code Challenge 🐛

Welcome to the **Fix My Code Challenge**! This repository contains various coding challenges where the goal is to identify and fix bugs in existing code. Each challenge is written in a different programming language, and your mission is to make the code work as expected! 🚀

---

## 📂 Challenges Overview

### 0️⃣ FizzBuzz 🥤
**File:** `0-fizzbuzz.py`  
**Language:** Python 🐍  
**Description:**  
The classic FizzBuzz problem! Print numbers from 1 to `n` with the following rules:
- Multiples of 3: Print "Fizz" 🍋
- Multiples of 5: Print "Buzz" 🐝
- Multiples of both 3 and 5: Print "FizzBuzz" 🎉

**Issue:**  
15 should print "FizzBuzz" but currently prints "Fizz".  

**Run Example:**
```bash
$ ./0-fizzbuzz.py 15
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz
```

---

### 1️⃣ Print Square 🟦
**File:** `1-print_square.js`  
**Language:** JavaScript 🟨  
**Description:**  
Print a square of size `n` using the `#` character.  

**Issue:**  
The square size is incorrect for larger inputs.  

**Run Example:**
```bash
$ ./1-print_square.js 4
####
####
####
####
```

---

### 2️⃣ Sort 🔢
**File:** `2-sort.rb`  
**Language:** Ruby 💎  
**Description:**  
Sort integer arguments in ascending order.  

**Issue:**  
The sorting logic is incorrect, and the output is not sorted properly.  

**Run Example:**
```bash
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
-9
-1
2
9
12
31
32
41
```

---

### 3️⃣ User Password 🔒
**File:** `3-user.py`  
**Language:** Python 🐍  
**Description:**  
A `User` class with password hashing and validation using MD5.  

**Issue:**  
The tests should not print any errors, but some validations are failing.  

**Run Example:**
```bash
$ ./3-user.py
Test User
```

---

### 4️⃣ Double Linked List 🔗
**Directory:** `4-delete_dnodeint/`  
**Language:** C 🇨  
**Description:**  
Implementation of a doubly linked list with functions to add, delete, and print nodes.  

**Issue:**  
The deletion logic is buggy, leading to incorrect outputs and potential memory issues.  

**Run Example:**
```bash
$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint
```

---

## 🏆 How to Contribute
1. Clone the repository:
   ```bash
   git clone https://github.com/holbertonschool-Fix_My_Code_Challenge.git
   ```
2. Navigate to the challenge directory and fix the code!  
3. Test your solution thoroughly.  
4. Submit a pull request with your fixes.  

---

## 📜 License
This project is licensed under the Holberton School guidelines.  

---

Happy debugging! 🐞✨