# 🚆 Ticket Booking System (Java)

## 📌 Project Overview
The **Ticket Booking System** is a Java-based application that allows users to:
- Register and log in securely  
- Search trains by source & destination  
- Book seats on available trains  
- View and cancel tickets  
- Store user and train data in JSON files (local DB simulation)  

This project demonstrates clean modular code with entities, services, and utilities — making it easy to scale and extend.

---

## 🛠️ Tech Stack
- **Language:** Java 17+  
- **Libraries:** Jackson (for JSON serialization/deserialization)  
- **Storage:** JSON files (local DB)  
- **Build Tool:** Gradle / Maven  

---

## 📂 Project Structure
ticket-booking-system/
├── src/
│ ├── main/java/ticket/booking/entities/ # Entities (User, Train, Ticket)
│ ├── main/java/ticket/booking/services/ # Business logic services
│ ├── main/java/ticket/booking/util/ # Utility classes
│ └── test/java/ # Unit tests
│
├── localDb/
│ ├── users.json # Stores registered users
│ └── trains.json # Stores train details
│
├── build.gradle / pom.xml # Build file (Gradle/Maven)
└── README.md # Project documentation

