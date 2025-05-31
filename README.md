# 🧾 Employee Data Management System

Welcome to the **Employee Data Management System**, a complete backend management tool designed for corporate administrators to manage employee records efficiently. Built with Python, this system provides full CRUD (Create, Read, Update, Delete) operations on employee data stored in a CSV file — no external database required.

> 📁 This project is part of my growing portfolio in intelligent systems and backend logic automation. While my focus is AI/ML, I also create practical tools that build the foundation for smart applications.

---

## 🚀 Features

✔ Add new employees  
✔ Update any employee's details (name, position, salary, or email)  
✔ Delete employees by ID  
✔ Search and view employee information  
✔ Display a full list of current employees  
✔ Data persistence through CSV file  
✔ Intuitive command-line interface

---

## 🧠 Use Case

This system is ideal for small to medium businesses that need a simple, local solution for employee data management — especially when cloud integration isn't necessary or when working offline.

---

## 🛠 Technologies Used

- **Python 3**  
- **CSV File Handling**  
- Object-Oriented Programming (OOP)

---

## 📂 File Structure


---

## 📝 Sample Data (CSV)

Here’s how the `employees.csv` is structured:

| ID   | Name         | Position      | Salary  | Email               |
|------|--------------|---------------|---------|---------------------|
| 101  | John Smith   | Manager       | 55000   | john@company.com    |
| 102  | Jane Doe     | HR Specialist | 42000   | jane@company.com    |

You can edit this file directly or use the program to manage it through the UI.

---

## 🧪 How to Use

### ✅ Requirements

- Python 3.x installed  
(No external libraries needed — only built-in modules)

## Interaction Sample 
- action: Start Program
  menu:
    - "1. Add Employee"
    - "2. Update Employee"
    - "3. Delete Employee"
    - "4. Search Employee"
    - "5. List All Employees"
    - "6. Exit"

- action: Add Employee
  input:
    Employee ID: "103"
    Name: "Alice Johnson"
    Position: "Software Engineer"
    Salary: "47000"
    Email: "alice.johnson@company.com"
  output: "Employee has been added successfully."

- action: Search Employee
  input:
    Employee ID: "103"
  output: 
    - ID: 103
    - Name: Alice Johnson
    - Position: Software Engineer
    - Salary: 47000
    - Email: alice.johnson@company.com

- action: Update Employee
  input:
    Employee ID: "103"
    Attribute to Update: "3"  # Salary
    New Salary: "50000"
  output: "Employee updated successfully."

- action: Exit
  output: "Exiting the system."
## Error Handling Examples

- action: Add Employee
  input:
    Employee ID: "101"  # Already exists
  output: "Employee with ID 101 is already in our corporate."

- action: Update Employee
  input:
    Employee ID: "999"  # Doesn't exist
  output: "Employee with ID 999 is not in our corporate."

- action: Delete Employee
  input:
    Employee ID: "888"  # Doesn't exist
  output: "Employee with ID 888 is not in our corporate."

- action: Search Employee
  input:
    Employee ID: "777"  # Doesn't exist
  output: "Employee is not in our corporate."

- action: Invalid Menu Choice
  input: "9"
  output: "Invalid choice. Please try again."


## 👩‍💻 This project was developed by Mariam Ibrahim as part of her journey into AI, data systems, and automation.
Check out more of her work on [https://github.com/mariamibrahimzz/].

