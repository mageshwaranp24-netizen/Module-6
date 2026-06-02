# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

        # Display private variables
        print("Length =", self.__length)
        print("Breadth =", self.__breadth)

# Create object
obj = Rectangle(10, 5)
```
## Output
<img width="370" height="173" alt="image" src="https://github.com/user-attachments/assets/e7ffa3a5-b401-4a28-a12a-6d96c514c3f9" />

## Result
Thus the  implementation of  Encapsulation in Python by defining a class Rectangle with private member variables __length and __breadth is completed successfully.
