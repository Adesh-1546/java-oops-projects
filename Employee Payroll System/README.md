# Employee Payroll System (Java OOP Project)

This project is a simple Employee Payroll System built using Core Java. It demonstrates key Object-Oriented Programming (OOP) concepts such as abstraction, inheritance, and polymorphism.

---

## 🚀 Features

* Add employees (Full-Time / Part-Time)
* Remove employees by ID
* Display all employee details
* Salary calculation based on employee type

---

## 🧠 OOP Concepts Used

### 1. Abstraction

* Abstract class `Employee` defines common structure
* Abstract method `calculateSalary()` implemented by subclasses

### 2. Inheritance

* `FullTimeEmployee` and `PartTimeEmployee` extend `Employee`

### 3. Polymorphism

* Method overriding of `calculateSalary()`
* Parent reference (`Employee`) used for different objects

### 4. Encapsulation

* Private fields with getter methods

---

## 📂 Project Structure

```text
Employee (Abstract Class)
   ├── FullTimeEmployee
   ├── PartTimeEmployee
   └── PayrollSystem
```

---

## 💻 How It Works

1. Create employee objects (Full-Time / Part-Time)
2. Add them to PayrollSystem
3. Display all employees
4. Remove an employee using ID
5. Display updated employee list

---

## 🧪 Sample Output

```
Initial Employee Details:
Employee [name=John Doe, id=101, salary=5000.0]
Employee [name=Jane Smith, id=102, salary=450.0]

Removing Employee...

Remaining Employee Details:
Employee [name=Jane Smith, id=102, salary=450.0]
```

---

## 🛠️ Tech Used

* Java
* Collections Framework (ArrayList)

---

## 🎯 Purpose

* Strengthen Core Java and OOP concepts
* Practice real-world class design
* Prepare for technical interviews

---

## 📌 Future Improvements

* Add user input (Scanner)
* Store data in database (JDBC)
* Add GUI or web interface


