# 💻 Software Projects Repository

Welcome to my software development  repository\! This collection showcases several projects demonstrating proficiency in full-stack web development, database design, GUI programming, game development, and systems utilities across various technology stacks.

-----

## 📋 Table of Contents

  * [Project 1: Expense Tracking System](https://www.google.com/search?q=%23-project-1-expense-tracking-system)
  * [Project 2: Mobile Kharedo Store (PHP/SQL)](https://www.google.com/search?q=%23-project-2-mobile-kharedo-store-phpsql)
  * [Project 3: Library Management System (MongoDB/Neo4j)](https://www.google.com/search?q=%23-project-3-library-management-system-mongodbneo4j)
  * [Project 4: Hospital Management System (C)](https://www.google.com/search?q=%23-project-4-hospital-management-system-c)
  * [Project 5: Multi-threaded Downloader Utility (Python)](https://www.google.com/search?q=%23-project-5-multi-threaded-downloader-utility-python)
  * [Project 6: Classic Snake Game (C++)](https://www.google.com/search?q=%23-project-6-classic-snake-game-c)
  * [🚀 Getting Started](https://www.google.com/search?q=%23-getting-started)
  * [💬 Feedback and Contact](https://www.google.com/search?q=%23-feedback-and-contact)

-----

## 💰 Project 1: Expense Tracking System

A desktop application built for efficient personal finance management, allowing users to track income and expenses and visualize financial data.

### Detailed Explanation

This system is a standalone desktop application built using **Python**. It features a user-friendly GUI created with the **Tkinter** library. The backend uses **SQLite** for secure data storage, and it incorporates **Matplotlib** for generating visual insights (pie charts) into spending habits and income sources.

### Features

  * **User Authentication:** Secure **registration** and **login** functionality with database validation.
  * **Record Management:** Users can add detailed records for both **Expenses** (category, amount, date, description) and **Income** (source, amount, date).
  * **Data Visualization:** Generates **pie charts** from expense categories and income sources for quick financial analysis.
  * **Database Design:** Uses three normalized tables (`USERS`, `EXPENSES`, `INCOME`) with foreign key constraints (`ON DELETE CASCADE`) to maintain data integrity.

### Technologies Used

| Category | Technology | Key Files |
| :--- | :--- | :--- |
| **Language** | Python | `main.py`, `database.py` |
| **GUI** | Tkinter | `main.py` |
| **Database** | SQLite3 | `database.py`, `User.db` |
| **Visualization** | Matplotlib | `main.py` |

-----

## 📱 Project 2: Mobile Kharedo Store (PHP/SQL)

A dynamic, full-featured e-commerce web application developed as a semester project for exploring, purchasing, and managing mobile phones.

### Detailed Explanation

This project (`db-proj main`) is an essential demonstration of a multi-user, database-driven web application. It is primarily developed using **PHP** for server-side scripting and business logic, with **HTML** and **CSS** handling the presentation layer. It relies on a relational database (typically MySQL) to manage user accounts, product inventory, shopping cart contents, and order histories.

### Features

  * **User Management:** Complete authentication workflows, including user **registration** and **login**.
  * **Product Catalog:** Users can **explore** the full range of mobile devices available in the store.
  * **E-commerce Flow:** Functionality to **add products to the cart**, view cart contents, and finalize an **order**.
  * **Admin Panel:** A dedicated administrative interface to **manage mobile inventory** (add, update, delete products) and process customer orders.

### Technologies Used

| Category | Technology |
| :--- | :--- |
| **Server-Side** | PHP |
| **Front-End** | HTML, CSS |
| **Database** | SQL (e.g., MySQL) |

-----

## 📚 Project 3: Library Management System (MongoDB/Neo4j)

A project exploring different database models for managing library records and analyzing movie data.

### Detailed Explanation

This section showcases two distinct database assignments:

1.  **Task 1 (Library Management):** Uses **Python/Tkinter** for the GUI and **MongoDB** (a NoSQL document database) for storing book and lending records, demonstrating non-relational database interaction.
2.  **Task 2 (Movie Database Analysis):** Focuses on **Neo4j** (a Graph Database) and the **Cypher** query language. It involves creating a graph model of movies, actors, and relationships (`[:ACTED_IN]`) and querying complex data relationships using Python.

### Technologies Used

| Category | Technology | Key Files |
| :--- | :--- | :--- |
| **GUI/Base** | Python, Tkinter | `task1.py` |
| **NoSQL DB** | MongoDB (`pymongo`) | `task1.py` |
| **Graph DB** | Neo4j (Cypher) | `task2.py`, `Task2.pdf` |

-----

## ⚕️ Project 4: Hospital Management System (C)

A menu-driven, console-based application for basic hospital record keeping and administration.

### Detailed Explanation

This project is implemented in the **C programming language**, providing a foundational example of systems programming and file handling. It uses a structured, console-based approach to manage patient and doctor data. Data persistence is achieved using standard C **file I/O operations** (reading and writing to external files).

### Features

  * **Authentication:** Basic login system for administrative access.
  * **Patient Records:** Functions to **admit new patients**, view specific patient records, display the full list, and delete/discharge records.
  * **Doctor Records:** Management functions for **doctor information**, including display and removal.
  * **Search:** Allows quick lookup of patient or doctor data.

### Technologies Used

| Category | Technology | Key Files |
| :--- | :--- | :--- |
| **Language** | C | `Hospital Management System.c` |
| **Interface** | Console (Standard I/O) | `Hospital Management System.c` |
| **Storage** | File I/O | `Hospital Management System.c` |

-----

## ⚙️ Project 5: Multi-threaded Downloader Utility (Python)

A powerful command-line interface (CLI) tool for accelerating file downloads using concurrency.

### Detailed Explanation

This **Python CLI tool** uses the `click` library for easy argument parsing and the **`concurrent.futures.ThreadPoolExecutor`** module to implement multi-threading. The file is logically split into chunks, and each segment is downloaded concurrently via separate threads using the `requests` library.

### Features

  * **Concurrent Downloading:** Utilizes a `ThreadPoolExecutor` to handle multiple file segments simultaneously, significantly increasing download speed.
  * **Integrity Check:** Automatically calculates and displays the **SHA256 Hash** of the downloaded file to verify data integrity against corruption.
  * **CLI Interface:** User-friendly command-line input for specifying the URL, number of threads, and output filename.

### Technologies Used

| Category | Technology | Key Files |
| :--- | :--- | :--- |
| **Language** | Python 3 | `downloader.py` |
| **CLI** | Click | `downloader.py` |
| **Networking** | Requests | `downloader.py` |
| **Concurrency** | `concurrent.futures` | `downloader.py` |

-----

## 🐍 Project 6: Classic Snake Game (C++)

A modern implementation of the classic Snake game developed using C++ and the Raylib library for simple and effective graphics.

### Detailed Explanation

This project is a console-style game built entirely in **C++**. It leverages the powerful yet easy-to-use **Raylib** library to handle all graphical elements, window management, and input processing. The game logic is based on a grid system defined by constants (`cellSize` and `cellCount`). The snake's body is managed efficiently using a **`std::deque`** (double-ended queue), a core C++ Standard Template Library container, which allows for fast, fluid addition and removal of segments as the snake moves and grows.

### Features

  * **Raylib Graphics:** Uses the Raylib framework for a simple, fast, and colorful presentation with clearly defined colors for game elements and states.
  * **Grid-Based Movement:** The game is played on a defined grid, ensuring classic snake movement behavior.
  * **Collision Detection:** Includes logic to detect collisions with the game boundaries (walls) and self-collision (hitting its own tail).
  * **Score Tracking:** Displays the current score, which increments when the snake consumes food.
  * **Fluid Control:** Handles player input with checks to prevent the snake from immediately reversing direction, preventing instant game over.

### Technologies Used

| Category | Technology | Key Files |
| :--- | :--- | :--- |
| **Language** | C++ | `main.cpp` |
| **Graphics/Game Engine** | Raylib | `main.cpp` |
| **Data Structures** | `std::deque` | `main.cpp` |

-----

## 🚀 Getting Started

To run these projects, ensure you have the necessary environments set up:

### **1. Python Environments**

Install Python 3.x and the required packages for the respective projects.

```bash
# General Python packages
pip install click requests matplotlib

# For Library Management (MongoDB Driver)
pip install pymongo

# For Library Management (Neo4j Driver)
pip install neo4j
```

### **2. Web/PHP Environment (Mobile Kharedo Store)**

1.  Set up a local server environment (e.g., **XAMPP**, **WAMP**, or **MAMP**) to run PHP and an SQL database (like MySQL).
2.  Place the project files in the server's root directory (e.g., `htdocs`).
3.  Configure your database and update the connection details in the PHP files to match your local setup.

### **3. C Project (Hospital Management System)**

Requires a standard C compiler (e.g., **GCC**).

```bash
# Compile the file
gcc "Hospital Management System.c" -o hms

# Run the compiled program
./hms
```

### **4. C++ Game Environment (Classic Snake Game)**

Requires a C++ compiler (e.g., **g++**) and the **Raylib** library installed and linked correctly on your system.

```bash
# Example compilation command (may vary based on your system/Raylib installation)
g++ main.cpp -o snake -lraylib

# Run the compiled program
./snake
```

-----

## 💬 Feedback and Contact

We welcome any feedback, suggestions, or bug reports you may have regarding these projects\!

### How to Provide Feedback

  * **Open an Issue:** For bugs or feature requests, please use the [GitHub Issues tab](https://www.google.com/search?q=https://github.com/YourUsername/YourRepository/issues) of this repository (Note: you will need to replace `YourUsername/YourRepository` with your actual repository path).
  * **Contact Directly:** Feel free to reach out to the project owner via email or LinkedIn (Please replace the placeholders below with your actual contact information):

| Platform | Contact |
| :--- | :--- |
| **Email** | `ihsanbmf@gmail.com' |
