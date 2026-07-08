# Car Rental System (Java OOP Project)

This project is a console-based Car Rental System built using Core Java. It demonstrates real-world implementation of Object-Oriented Programming (OOP) concepts along with user interaction.

---

## 🚀 Features

* View available cars
* Rent a car for specific number of days
* Return a rented car
* Automatic price calculation based on rental duration
* Customer and rental management

---

## 🧠 OOP Concepts Used

### 1. Encapsulation

* Private fields in classes like `Car`, `Customer`, and `Rental`
* Access through getter methods

### 2. Abstraction

* Logic hidden inside methods like `rentCar()` and `returnCar()`

### 3. Inheritance

* Conceptually used in system design (can be extended further)

### 4. Polymorphism

* Method behavior varies based on object interaction

---

## 📂 Project Structure

```text id="x9v2km"
Car
Customer
Rental
CarRentalSystem
Main
```

---

## 💻 How It Works

1. System displays available cars
2. User enters name and selects a car
3. Rental duration is entered
4. Total price is calculated
5. User confirms rental
6. Car is marked as unavailable
7. User can return the car later

---

## 🧪 Sample Flow

```id="y3o2pf"
1. Rent a Car
2. Return a Car
3. Exit

Enter your choice: 1
Enter your name: Adesh
Available Cars:
C001 - Toyota Camry
C002 - Honda Accord

Enter car ID: C001
Enter days: 3
Total Price: $180.00
Confirm rental (Y/N): Y
```

---

## 🛠️ Tech Used

* Java
* Collections Framework (ArrayList)
* Scanner (User Input)

---

## 🎯 Purpose

* Apply OOP concepts in a real-world scenario
* Practice logic building and system design
* Strengthen Java fundamentals for interviews

---

## 📌 Future Improvements

* Add input validation (invalid car ID, negative rental days)
* Display total rented cars and available cars count
* Add login/authentication system
* Store data using database (JDBC)
* Add GUI (Swing/JavaFX) or Web version (Spring Boot)
* Maintain booking history

---


