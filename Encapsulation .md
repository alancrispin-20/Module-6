# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM :

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM :

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program :

class Rectangle: 

    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

    def set_values(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

    def get_values(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

    def area(self):
        print("Area:", self.__length * self.__breadth)

l = float(input("Enter length: "))

b = float(input("Enter breadth: "))

r = Rectangle(l, b)

r.get_values()

r.area()

## Output :
<img width="172" height="132" alt="image" src="https://github.com/user-attachments/assets/0e82774d-b385-44d9-8229-aba587700e25" />

## Result :

Thus the program is excuted and the output is obtained .
