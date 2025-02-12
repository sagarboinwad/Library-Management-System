# Library Management System

 Library Management System (LMS) built in Java to automate the management of books in a library. This system helps keep track of books, borrowers, and staff, allowing users to perform operations like adding, updating, deleting books, and issuing books to borrowers. It can be expanded to include advanced features like user authentication, search functionality, and reports.

## Project Overview

The **Library Management System** is a college-based Java project designed to automate and manage the fundamental operations of a library. This console-based application enables users to add new books, issue books to borrowers, return issued books, and display issue details. Built with simplicity and functionality in mind, this system can be a valuable learning project for beginners and a practical tool for small libraries.

This project includes a structured **architecture**, **project report**, and **proposal** to provide a comprehensive overview of the system design and implementation. For further details, feel free to reach out.

# My Project
Image of the project:

![Project Screenshot](assests/img1.png)
![](assests/img2.png)
![](assests/img3.png)
![](assests/img4.png)
Features:
Book Management:

Add new books to the library.
Update book details (e.g., title, author, and quantity).
Delete books from the system.
Borrower Management:

Register borrowers.
Issue and return books.
Keep track of borrowed books and due dates.
Staff Management:

Track staff members and their roles.
Search Functionality:

Search for books by title, author, or genre.
Persistent Storage:

Data is stored locally, and the system can be integrated with a database (like MySQL) for real-world applications.
Table of Contents:
Requirements
How to Use
Features
Screenshots
Contributing
License


## Tech Stack

- **Language**: Java
- **Platform**: Console-based

## Project Structure

The project consists of two main classes:
1. **Project** (Main class): Contains the main loop and menu interface, handling user input and directing actions.
2. **Library**: Manages the collection of books, including adding, issuing, returning, and displaying book details.

Additionally, a **Book** class encapsulates individual book properties and actions, supporting the `Library` class for organized book management.

## Classes and Methods

### 1. `Project` (Main Class)

- **Purpose**: Drives the main menu loop for user interaction and directs to relevant actions in the `Library` class.
- **Key Methods**:
  - `main()`: Provides the interactive console menu, capturing and handling user input.

### 2. `Library`

- **Purpose**: Manages a list of `Book` objects and provides methods for adding, issuing, and returning books.
- **Key Methods**:
  - `addBook(Scanner scanner)`: Adds a new book to the library collection.
  - `issueBook(Scanner scanner)`: Issues an available book, setting issue and return dates.
  - `returnBook(Scanner scanner)`: Returns an issued book by book ID.
  - `issueDetails()`: Displays details of books currently issued.
  - `exit()`: Exits the program.

### 3. `Book`

- **Purpose**: Encapsulates properties of a single book and provides methods to issue or return the book.
- **Key Methods**:
  - `issue(String issueDate, String returnDate)`: Issues the book with specific dates.
  - `returnBook()`: Returns the book, clearing issue details.
  - `printDetails()`: Prints book details, including issue information if applicable.

## How to Use

### Prerequisites
1. **Java Development Kit (JDK)**: Ensure you have the JDK installed on your system. [Download the JDK](https://www.oracle.com/java/technologies/javase-downloads.html) if not already installed. To verify, run the following command in your terminal:
   ```bash
   java -version
   ```

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/siddhesh-wagh/library-management-system.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd library-management-system
   ```

3. **Compile and Run the Project**:
   - **Compile**:
     ```bash
     javac Project.java
     ```
   - **Run**:
     ```bash
     java Project
     ```

4. Follow the menu prompts in the console to add, issue, return, and view details of books.

## Sample Usage

- **Add Book**: Enter book details, including name, price, and unique book ID.
- **Issue Book**: Enter the book ID and specify the issue and return dates.
- **Return Book**: Provide the book ID to mark it as returned.
- **Issue Details**: View details of currently issued books.

## Future Enhancements

- **Database Integration**: Add a database layer (e.g., MySQL) for persistent storage.
- **User Authentication**: Introduce user roles (e.g., admin, borrower) for secure access.
- **Graphical User Interface**: Transition to a GUI-based system for easier usability.
- **Enhanced Search and Sort**: Implement search and sorting features for efficient book management.

## Project Documentation

This project includes:
- **Architecture Diagram**: Detailed system architecture for better understanding and scalability.
- **Project Proposal**: Initial proposal outlining the goals, features, and project scope.
- **Project Report**: A complete project report with documentation of classes, methods, and usage.



## Contributing

Contributions to the project are welcome! Feel free to open issues or submit pull requests to improve functionality or add new features.

--- 
