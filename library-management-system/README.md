# Library Management System

A Python-based library management system with an interactive web interface, built using object-oriented programming principles and a real book dataset.

## What it does

This project simulates a digital library where users can register, log in, search for books, borrow and return them, while admins can manage the book collection (add/remove books). It features:

- **User authentication** with two role types: Admin and Regular User
- **Book search** by title, author, or genre
- **Borrow & return system** with day-based tracking
- **Book collection management** (add, delete, view all books) for admins
- **Interactive GUI** built with Gradio, so users can interact with the system through buttons and forms instead of typing commands

## How it's built

The core logic uses **object-oriented programming (OOP)**:

- `User` — a base class handling login functionality
- `Admin` and `RegularUser` — subclasses that inherit from `User`, representing different access levels
- `BookManager` — the main class that manages all library operations (searching, borrowing, returning, and book collection management)

The book dataset is loaded from a CSV file containing real book data (title, author, genre, language, publication year, and sales figures), which is cleaned and processed using **pandas**.

The interface itself is built with **Gradio**, organized into tabs for each feature (Register, Login/Logout, Search, Borrow, Return, etc.), making the system usable directly from a browser without needing to run code manually for each action.

## Tech stack

- Python
- pandas (data handling)
- Gradio (interactive web interface)

## How to run

1. Open the notebook in Google Colab or Jupyter Notebook
2. Run all cells in order
3. Once the Gradio interface launches, click the generated public URL to interact with the library system in your browser

## Note

This project was originally built as a group assignment during coursework. It demonstrates practical application of OOP concepts (inheritance, encapsulation), data handling with pandas, and building a functional user interface for a real-world use case.
