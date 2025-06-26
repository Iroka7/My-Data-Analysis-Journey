# 📘 Stage 1: Python Basics

This stage of my Data Analysis journey introduces the foundational concepts of Python programming. Below is a structured summary of all that I reviewed and practiced in this stage.

---

## 🔹 1. Variables & Data Types

- **String**: `"Hello, World"`
- **Integer**: `10`
- **Float**: `3.14`
- **Boolean**: `True`, `False`

### Example:
```python
my_name = "Iggins"
my_age = 29
fav_number = 7.0
is_learning = False

#### Type checking

print(type(my_name))   # str
print(type(my_age))    # int
print(type(fav_number))  # float
print(type(is_learning))  # bool

##### Arithmetic operations

10 + 5      # 15
10 - 3      # 7
10 * 2      # 20
10 / 3      # 3.33...
10 // 3     # 3
10 % 3      # 1
2 ** 3      # 8


### String Operation

"Data" + "Science"     # "DataScience"
"Python" * 2           # "PythonPython"


### String Methods

greeting = "hello, Iggins"
greeting.upper()       # "HELLO, IGGINS"
greeting.title()       # "Hello, Iggins"
greeting.replace("Iggins", "friend")  # "hello, friend"


##### input and Output

name = input("What is your name?")
print(f"Welcome, {name}!")


####  Data Structures (lists, tuples, sets, dictionaries)

fruits = ["apple", "banana", "cherry"]
fruits.append("date")


colors = ("red", "blue", "green")

unique_items = {1, 2, 2, 3}
unique_items.add(4)


person = {"name": "Iggins", "age": 29}
person["status"] = "learning"





