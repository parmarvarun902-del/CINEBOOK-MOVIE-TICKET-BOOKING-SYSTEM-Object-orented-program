# CINEBOOK-MOVIE-TICKET-BOOKING-SYSTEM-Object-orented-program
A movie ticket booking system showcasing C++ OOP concepts, movie selection, seat booking, pricing, and booking receipts.
# 🎬 CineBook – Movie Ticket Booking System

CineBook is a movie ticket booking system designed as an academic mini-project for Software Engineering and Object-Oriented Programming (OOP). It presents a modern, dark-themed interface that allows users to explore movies, select showtimes, choose seats, calculate ticket prices, and view booking confirmation details.

## 📌 Project Overview

The main purpose of CineBook is to demonstrate how a movie ticket booking workflow can be organised using object-oriented design principles and a user-friendly interface.

## ✨ Features

- 🎥 Movie selection with titles, genres, and prices
- 🕒 Multiple showtime options
- 💺 Visual seat-selection layout
- 💰 Automatic ticket price calculation
- 🧾 Booking summary with selected seats and total cost
- 🎟️ Booking confirmation receipt
- ⚠️ Input validation and exception-handling examples
- 🧩 Modular design using OOP concepts

## 🛠️ Technologies

- **Programming Language:** C++
- **GUI Framework:** Qt 6 (for the planned native desktop application)
- **Version Control:** Git and GitHub

*The technologies and features listed should be considered implemented only when supported by the uploaded source code.*

## 🧠 OOP Concepts

- **Classes and Objects:** Represent movies, seats, tickets, and bookings.
- **Encapsulation:** Protect data using private members and public methods.
- **Abstraction:** Define common ticket operations through an abstract class.
- **Inheritance:** Derive specific ticket types from a base ticket class.
- **Polymorphism:** Override virtual functions for ticket-price calculation.
- **Composition:** Organise booking information and associated seat details.
- **Exception Handling:** Handle invalid operations and booking errors.

## 📂 Project Structure

```text
CineBook/
├── README.md
├── CMakeLists.txt
├── include/
│   ├── Models.h
│   └── Cinema.h
├── src/
│   ├── main.cpp
│   ├── Models.cpp
│   └── Cinema.cpp
├── screenshots/
│   ├── movie-selection.png
│   ├── seat-selection.png
│   ├── selected-seat.png
│   └── booking-confirmation.png
└── docs/
    └── CineBook_Report.pdf
```

*This is the suggested structure. Keep only files and folders that actually exist in your repository.*

## 🚀 How to Run

For a Qt 6 desktop implementation:

1. Install Qt 6 and Qt Creator.
2. Clone or download this repository.
3. Open `CMakeLists.txt` in Qt Creator.
4. Select a compatible desktop kit.
5. Configure, build, and run the project.

The build instructions require a complete and correctly configured Qt project.

## 🧪 Testing

The project should be tested for movie selection, showtime selection, seat availability, price calculation, customer-name validation, duplicate-seat prevention, and booking confirmation.

Screenshots demonstrate sample interface states; they do not independently establish that all functions have passed testing.

## 🔮 Future Enhancements

- Database integration and persistent booking history
- Unique booking-reference generation
- Secure payment integration
- Multi-user seat availability management
- Functional booking history
- Improved accessibility and error messages

## 🎓 Academic Project

**Project:** CineBook – Movie Ticket Booking System
**Student:** Varun Parmar
**UID:** 25BCD10122
**Branch:** BCA (DS)
**Section:** 25BCD2(B)
**Semester:** 3
**Submitted to:** Mr. Jitendra Kumar
**Institution:** Chandigarh University

## 📄 License

This project is intended for educational and academic purposes. Add an open-source license if you want others to reuse or distribute the code under specific terms.
