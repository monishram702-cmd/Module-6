# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

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

## 💻 Program
```
class Fish:
    def type(self): 
        print("fish")

class Shark(Fish):
    def type(self): 
        print("shark") 
obj_goldfish = Fish() 
obj_hammerhead = Shark() 
for fish in (obj_goldfish, obj_hammerhead):
    fish.type()
```
## Output
<img width="1037" height="346" alt="image" src="https://github.com/user-attachments/assets/c4c895cb-c5d1-4d95-ae8e-3aaccab38d2d" />

## Result
Thus To write a Python program that demonstrates class inheritance by creating a parent class Fish with a method type, and a child class Shark that overrides the type method. Hence the code has been executed successfully.
