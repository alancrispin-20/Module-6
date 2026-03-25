# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM :

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM :

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program :

class Number:

    def __init__(self, value):
        self.value = value

    def __lt__(self, other):
        return self.value < other.value

n1 = Number(int(input("Enter first number: ")))

n2 = Number(int(input("Enter second number: ")))

if n1 < n2:

    print("First number is less than second number")
else:

    print("First number is not less than second number")
    
## Output :
<img width="388" height="83" alt="image" src="https://github.com/user-attachments/assets/d71de1f2-d137-4be3-b7b0-45eaebff0c4f" />

## Result :

Thus the program is excuted and the output is obtained.
