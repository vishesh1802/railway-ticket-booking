# 🚆 Railway Ticket Booking System

A **Java-based Railway Ticket Booking System** that simulates essential functionalities of real-world train reservation — including searching trains, booking tickets, viewing bookings, and cancellations.
This project demonstrates clean Object-Oriented Programming (OOP) principles and modular design for a console-based reservation system.

---

## 🧭 Table of Contents

* [Features](#-features)
* [Tech Stack](#%ef%b8%8f-tech-stack)
* [Getting Started](#%ef%b8%8f-getting-started)

  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Run the Program](#run-the-program)
* [Project Structure](#-project-structure)
* [System Workflow](#-system-workflow)
* [Screenshots / Demo](#-screenshots--demo)
* [Future Enhancements](#-future-enhancements)
* [Contributing](#-contributing)


---

## Features

Search trains by **source** and **destination**
Display **seat availability** by class (Sleeper / AC / General)
Book tickets for **one or more passengers**
Generate a **unique booking ID**
View booked tickets
Cancel a ticket by ID
Simple **text-based console interface**

---

## Tech Stack

| Layer           | Technology Used                                          |
| --------------- | -------------------------------------------------------- |
| Language        | **Java (JDK 8+)**                                        |
| IDE (optional)  | IntelliJ IDEA / Eclipse / VS Code                        |
| Build Tool      | `javac` or Maven (if using dependencies)                 |
| Database        | MySQL database using XAMPP |
| Design          | Object-Oriented Programming (OOP)                        |
| Version Control | Git + GitHub                                             |

---

## ⚙️ Getting Started

### Prerequisites

Before running the project, ensure you have:

* Java JDK 8 or higher
* Git (optional)
* Any Java IDE or terminal

### Installation

```bash
# Clone the repository
git clone https://github.com/vishesh1802/railway-ticket-booking.git

# Navigate into the folder
cd railway-ticket-booking
```

### Run the Program

If you’re compiling manually:

```bash
javac *.java
java Main
```

If you’re using Maven:

```bash
mvn clean compile exec:java
```

Once started, the program will guide you through the menu options for booking, viewing, and cancelling tickets.

---

## Project Structure

```
railway-ticket-booking/
│
├── Main.java                # Entry point of the program
├── Train.java               # Model class for train details
├── Passenger.java           # Model for passenger info
├── Ticket.java              # Model for ticket booking
├── BookingSystem.java       # Core logic for booking/cancellation
├── Database.java (optional) # Stores in-memory train/ticket data
├── utils/                   # Helper utilities (if any)
└── README.md                # Project documentation (this file)
```

---

## 💡 System Workflow

**1. Train Search** → User enters source and destination → Available trains displayed
**2. Booking Flow** → User selects train, class, and enters passenger details
**3. Confirmation** → System generates booking ID and displays details
**4. View Tickets** → Displays all active bookings
**5. Cancellation** → User enters booking ID to cancel and free the seat

You can visualize it as:

```
[Search Trains] → [Select Train] → [Enter Details] → [Book Ticket]
                                     ↓
                                 [View/Cancel]
```

---

##Screenshots / Demo



Example:

```
=============================
 Welcome to Indian Railways
=============================
1. Search Trains
2. Book Ticket
3. View Bookings
4. Cancel Ticket
5. Exit
=============================
Enter your choice:
```

---

## Future Enhancements

Convert console system into **GUI (Swing / JavaFX)**
Add **Spring Boot backend + React frontend**
Use **MySQL / PostgreSQL database** for persistence
Implement **user authentication** (Admin / Passenger)
Integrate **payment simulation module**
Develop a **mobile-friendly web interface**
Add **analytics dashboard** (bookings per route, etc.)

---

## Contributing

Contributions are always welcome!
To contribute:

1. **Fork** this repository
2. Create a **feature branch**:

   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:

   ```bash
   git commit -m "Added new booking filter feature"
   ```
4. Push and open a Pull Request

---

⭐ *If you like this project, please give it a star on GitHub — it helps others discover it!*
