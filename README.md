# 🔍 Python Operators: `is` vs `in`

This repository provides a clear explanation of the difference between Python’s `is` and `in` operators — two fundamental tools every Python developer should understand.

---

## 🧠 Understanding the Difference

### ✅ `is` Operator (Identity)

The `is` operator checks whether **two variables point to the same object in memory**. It does **not** compare values — it checks **object identity**.

```python
a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)  # True – both refer to the same object
print(a is c)  # False – same content, different memory locations
```

`📌 Use Case`: Commonly used to check against None
```python
if variable is None:
    # Handle case
```
## ✅ in Operator (Membership)
The in operator checks whether a value exists within an iterable like a list, tuple, string, or set.
```python
colors = ['red', 'green', 'blue']

print('red' in colors)    # True
print('yellow' in colors) # False
```
`📌 Use Case`: Efficient way to check if an element exists within a collection

## 📝 Summary


| Operator | Description                       | Example              | Output         |
|----------|-----------------------------------|----------------------|----------------|
| `is`     | Checks object identity            | `a is b`             | `True` or `False` |
| `in`     | Checks if a value is in a container | `'red' in colors`   | `True` or `False` |


## 📁 Folder Structure
```python
📦 is-vs-in-python
 ┣ 📜 README.md
 ┗ 📜 examples.py
```

## 💡 Why It Matters
Knowing when to use is vs in helps you:

* Avoid logical errors

* Write more Pythonic code

* Perform better in technical interviews
  
## 🤝 Connect with Me

I'm **Muhammad Farooq**, a passionate Frontend Developer with a strong foundation in **JavaScript**, **TypeScript**, **React**, **Next.js** and **Python** .  
I love crafting pixel-perfect UIs, building responsive web apps, and turning ideas into clean, production-ready code.

I'm always open to collaboration, feedback, and learning from the community. Let's connect and grow together! 🚀

- 🔗 [LinkedIn](https://www.linkedin.com/in/muhammad-farooq-developer/)
- 📫 Email: **muhammad888xyz@gmail.com**  
- 🧑‍💻 GitHub: [GitHub](https://github.com/Muhammad-Fraooq)
- 🌐 Portfolio: [Muhammad Farooq](https://porfolio-milestone-2-pk.vercel.app/)

Feel free to reach out for collaboration, open-source projects, or just to chat about tech!

## 📌 License
This project is open-source and available under the MIT License.

---

Let me know if you want me to generate the `examples.py` file to go along with it, or customize this with your real LinkedIn/email links.
