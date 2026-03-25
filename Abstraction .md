# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM :

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM :

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program :
 from abc import ABC, abstractmethod

class Shape(ABC):

    @abstractmethod
    def calculate_area(self):
        pass

class Rectangle(Shape):

    def calculate_area(self):
        length = float(input("Enter length: "))
        width = float(input("Enter width: "))
        print("Area of Rectangle:", length * width)

class Circle(Shape):

    def calculate_area(self):
        radius = float(input("Enter radius: "))
        print("Area of Circle:", 3.14 * radius * radius)

r = Rectangle()

r.calculate_area()

c = Circle()

c.calculate_area()

## Output :
<img width="237" height="155" alt="image" src="https://github.com/user-attachments/assets/869ec750-ea9e-4976-b808-dc3a7b8060b9" />

## Result :
Thus the program is excuted and the output is obtained .
