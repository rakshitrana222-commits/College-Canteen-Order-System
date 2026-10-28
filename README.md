College Canteen Order System

A Python-based command-line interface (CLI) application designed to streamline food ordering in a college canteen. This project demonstrates core Object-Oriented Programming (OOP) principles, Data Structures, Algorithms (DSA), and CSV-based data persistence.

Features

Menu Management & View: Display all menu items along with their category, price, and availability status.

Linear Search: Search menu items by food name or category.

Merge Sort: Display the menu sorted dynamically by price (ascending order).

Order Placement: Interactive prompt for students to place food orders.

Queue Management (FIFO): Serves pending orders in first-in, first-out order using Python's collections.deque.

Action Stack (LIFO): Allows undoing/cancelling the most recent order placed during the active session.

Data Persistence: Automatically saves and loads menu items and historical orders using CSV files.

Concepts & Technologies Used

1. Object-Oriented Programming (OOP)

Encapsulation: Encapsulates entity details in classes (MenuItem, Person, Student, Order).

Inheritance: Student inherits from the base Person class, reusing the name attribute.

Properties: Managed order calculation through `@property def total(self)
