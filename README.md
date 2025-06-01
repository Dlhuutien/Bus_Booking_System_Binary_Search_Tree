# Bus Booking System

## Description

This is a Bus Booking System built in Python, using a Binary Search Tree (BST) data structure to store and manage bus information. The system also uses a singly linked list to manage customer information and ticket bookings.

Users can perform operations such as adding, deleting, searching, and traversing data related to buses and customers, booking tickets, and saving/exporting data to files. The system supports tree balancing to optimize searching and data management.

---

## Technologies Used

- Programming Language: Python 3.x  
- Data Structures: Binary Search Tree (BST), Singly Linked List  
- File Handling: Reading and writing data from/to text files (.txt)

---

## Integration

The system integrates management of bus data, customer data, and ticket bookings through internal data structures (BST and Linked List).

Data can be loaded from files and saved back to files for persistent storage.

A Command-Line Interface (CLI) provides users with easy interaction and management capabilities.

---

## Role

- Manage bus data: add new buses, search, delete, traverse, and balance the BST.  
- Manage customers: add, search, delete, display, and save customer data.  
- Manage ticket bookings: enter new bookings, display bookings, and sort by bus ID and customer ID.  
- Save and load data from files to maintain data persistence across program runs.

---

## Database

- No SQL or NoSQL database is used.  
- Data is temporarily stored in memory using BST and linked list structures.  
- Data is saved and loaded from CSV-like text files (e.g., `buses.txt`, `customers.txt`) for easy storage and recovery.

---

## Backend

- Entire logic is written in Python and runs on the console (CLI).  
- Main classes: `Bus`, `Customer`, `BinarySearchTree` (managing buses), `LinkedList` (managing customers).  
- Key algorithms include insertion, search, deletion, tree traversal, and tree balancing.  
- File read/write functionalities for data import/export.

---

## Frontend

- User interface is a command-line interface (CLI).  
- Clear main navigation menu with options to manage Buses, Customers, and Bookings.  
- Users interact by entering choices via keyboard inputs.

---

## Architecture

- The system is designed as a monolithic application, with all functions contained within a single Python program.  
- Bus data is managed using a binary search tree structure to improve search efficiency.  
- Customer and booking data are managed using linked lists.  
- The system consists of main modules:  
  - Bus management (Bus + BST)  
  - Customer management (Customer + LinkedList)  
  - Booking management (Booking + LinkedList or combination)  
- Uses nested menu models for navigation.

---

## How to Use

1. Run the Python program.  
2. Use the displayed menu options to manage buses, customers, and ticket bookings.  
3. Data will be automatically saved to files upon exiting the program.

---

## Requirements

- Python 3.x interpreter installed on your machine.

---

## License

This project is licensed under the MIT License.
