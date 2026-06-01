# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```
class Demo:
    

    def __init__(self):
        self.status = "Alive"
        print(self.status)
    

    def __del__(self):
        print("Object is being destroyed")


obj = Demo()


del obj
```

## 🧪 Output
<img width="657" height="386" alt="image" src="https://github.com/user-attachments/assets/607ab49c-484b-4e55-8d30-d31090d12685" />

## Result
The program was executed successfully. A class with a constructor and destructor was implemented, where the constructor initializes and displays the status, and the destructor is automatically invoked when the object is deleted.
