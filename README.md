# 🐍 Road to Learn Python – Beginner Friendly Roadmap

Welcome to the **Python Beginner Roadmap** 🚀.
This guide is practical, not boring theory-heavy. After each concept, you’ll practice with **problems + mini-projects**.

---

## 📌 Topics Covered

1. **Data Types**
2. **Variables**
3. **Strings** (formatting, slicing, searching, counting, etc.)
4. **Lists & List Methods** (sorting, indexing, updating, adding, removing)
5. **Sets & Set Methods**
6. **Tuples & Tuple Methods**
7. **Dictionaries & Dictionary Methods** (update, add, delete)
8. **Conditional Statements**
9. **Loops (for & while)**
10. **Functions**
11. **Global Variables**
12. **Mini Project 1** (using above concepts)
13. **OOP Basics** – Classes, Objects
14. **Class Methods**
15. **Inheritance**
16. **Mini Project 2** (using OOP)
17. **Bonus: Regular Expressions**
18. **Bonus Project**
---

## Python Tutorial Book 
Download Link: https://static.realpython.com/python-basics-sample-chapters.pdf?utm_source=chatgpt.com

## 🧑‍💻 1. Data Types

**Types:** int, float, str, bool

### 🔹 Practice Problems

1. Check the type of: `12`, `12.5`, `"Hello"`, `True`, `[1,2,3]`

   * **Output:** `<class 'int'>`, `<class 'float'>`, `<class 'str'>`, `<class 'bool'>`, `<class 'list'>`
2. Convert `12.5` → int, and `15` → float

   * **Output:** `12`, `15.0`

---

## 🧑‍💻 2. Variables

### 🔹 Practice Problems

1. Assign your name to a variable `name` and age to `age`, print `"My name is X and I am Y years old"`

   * **Input:** `name="Ali", age=22`
   * **Output:** `My name is Ali and I am 22 years old`
2. Swap two variables without using a third variable.

   * **Input:** `a=5, b=10`
   * **Output:** `a=10, b=5`

---

## 🧑‍💻 3. Strings

### 🔹 Practice Problems

1. Slice `"Python"` to get `"Pyt"`

   * **Output:** `Pyt`
2. Count how many `"a"` are in `"banana"`

   * **Output:** `3`
3. Format a string: `"Hello {name}, you are {age}"`

   * **Input:** `name="Sara", age=20`
   * **Output:** `Hello Sara, you are 20`

---

## 🧑‍💻 4. Lists

### 🔹 Practice Problems

1. Sort `[5,3,9,1]` → `[1,3,5,9]`
2. Get the **last item** from `[10,20,30]`

   * **Output:** `30`
3. Remove `"apple"` from `["apple","banana","cherry"]` → `["banana","cherry"]`

---

## 🧑‍💻 5. Sets

### 🔹 Practice Problems

1. Find unique items in `[1,2,2,3,4,4]`

   * **Output:** `{1,2,3,4}`
2. Find intersection: `{1,2,3}` & `{2,3,4}`

   * **Output:** `{2,3}`

---

## 🧑‍💻 6. Tuples

### 🔹 Practice Problems

1. Access index `1` from `(10,20,30)`

   * **Output:** `20`
2. Check if `50` exists in `(10,20,30)`

   * **Output:** `False`

---

## 🧑‍💻 7. Dictionaries

### 🔹 Practice Problems

1. Update age in `{"name":"Ali","age":20}` → `{"name":"Ali","age":21}`
2. Delete key `"age"` from dictionary

---

## 🧑‍💻 8. Conditional Statements

### 🔹 Practice Problems

1. If number is >0 → `"Positive"`, <0 → `"Negative"`, else → `"Zero"`

   * **Input:** `num=-5`
   * **Output:** `Negative`

---

## 🧑‍💻 9. Loops

### 🔹 Practice Problems

1. Print numbers 1 to 5 using `for` loop
2. Print even numbers between 1–10 using `while` loop

---

## 🧑‍💻 10. Functions

### 🔹 Practice Problems

1. Create a function that returns the square of a number.

   * **Input:** `square(5)`
   * **Output:** `25`
2. Function that takes a list `[1,2,3]` and returns sum → `6`

---

## 🧑‍💻 11. Global Variables

### 🔹 Practice Problem

1. Use a global variable inside a function.

---

## 🎯 Mini Project 1 – **Number Guessing Game** 🎮

👉 **Description:**

* Computer selects a random number (1–20).
* User has 3 chances to guess.
* If correct → `"You Win!"`, else → `"Try Again!"`

---

## 🧑‍💻 12. OOP Basics

### 🔹 Practice Problems

1. Create a `Car` class with attributes `brand` and `model`
2. Create an object from the class and print details

---

## 🧑‍💻 13. Inheritance

### 🔹 Practice Problems

1. Create `Animal` class → `Dog` class inherits from it.
2. Dog should have an extra method `bark()`.

---

## 🎯 Mini Project 2 – **Simple Banking System** 💰

👉 **Description:**

* Create a `BankAccount` class with:

  * deposit method
  * withdraw method
  * balance check method
* Create multiple accounts & perform operations.

---

## 🎁 Bonus: Regular Expressions

### 🔹 Practice Problem

1. Extract all numbers from `"User123 bought 45 items"`

   * **Output:** `[123, 45]`

---

## 🎯 Bonus Project – **Email Validator** 📧

👉 **Description:**

* Input: user enters an email.
* Use regex to validate format (`abc@xyz.com`).
* Print `"Valid Email"` or `"Invalid Email"`.


