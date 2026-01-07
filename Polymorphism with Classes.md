# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
<img width="798" height="580" alt="image" src="https://github.com/user-attachments/assets/e028e7c1-ce8a-4eea-bdd9-c1faee0cac7f" />

## Output
<img width="705" height="220" alt="image" src="https://github.com/user-attachments/assets/f90008fd-87a9-431a-a6fa-5992178838e0" />

## Result
<img width="705" height="220" alt="image" src="https://github.com/user-attachments/assets/4262bcc8-c840-4a92-b8e6-7be470c5edbe" />
