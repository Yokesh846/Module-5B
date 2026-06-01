# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program
```
class Details:
    def getName(self):
        self.name = input("Enter name: ")
    
    def getAge(self):
        self.age = int(input("Enter age: "))


# Derived class 1
class Employee(Details):
    def getEmployeeDetails(self):
        self.getName()
        self.getAge()
        self.employee_id = input("Enter employee ID: ")
        self.department = input("Enter department: ")

    def showEmployee(self):
        print("\n--- Employee Details ---")
        print("Name:", self.name)
        print("Age:", self.age)
        print("Employee ID:", self.employee_id)
        print("Department:", self.department)


# Derived class 2
class Patient(Details):
    def getPatientDetails(self):
        self.getName()
        self.getAge()
        self.patient_id = input("Enter patient ID: ")
        self.disease = input("Enter disease: ")

    def showPatient(self):
        print("\n--- Patient Details ---")
        print("Name:", self.name)
        print("Age:", self.age)
        print("Patient ID:", self.patient_id)
        print("Disease:", self.disease)


# Create objects
emp = Employee()
pat = Patient()

# Get details
emp.getEmployeeDetails()
pat.getPatientDetails()

# Display details
emp.showEmployee()
pat.showPatient()
```
## Sample Output
<img width="629" height="837" alt="image" src="https://github.com/user-attachments/assets/13f2f2cb-cd88-447b-af8b-91ef3e019e58" />

