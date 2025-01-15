# Library Management System

A simple **Library Management System** built using **Java** and **XML** to manage books, members, and transactions efficiently. This system is designed to be a lightweight and flexible solution for small to medium-sized libraries.

---

## Features

- **Book Management**  
  - Add, update, delete, and search for books.  
  - Maintain records of book details (title, author, genre, ISBN, etc.).

- **Member Management**  
  - Add, update, and remove members.  
  - Track member details (name, contact information, etc.).

- **Transaction Management**  
  - Issue and return books.  
  - Track overdue books and calculate fines.  

- **Data Storage**  
  - Uses **XML files** for storing books, members, and transaction data.  

- **User Interface**  
  - Command-line interface for user interactions.

---

## Technologies Used

- **Programming Language**: Java  
- **Data Storage**: XML files  
- **Libraries**: JAXB (Java Architecture for XML Binding) for XML processing  

---

## Requirements

- **Java Development Kit (JDK)** version 8 or higher  
- **IDE**: IntelliJ IDEA, Eclipse, or any Java-compatible IDE  

---

## Installation and Setup

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/library-management-system.git
   cd library-management-system
   ```

2. Open the project in your preferred IDE.  

3. Compile and run the `Main.java` file to start the application.

---

## Folder Structure

```
library-management-system/
├── src/
│   ├── com/library/
│   │   ├── Main.java
│   │   ├── model/
│   │   │   ├── Book.java
│   │   │   ├── Member.java
│   │   │   └── Transaction.java
│   │   ├── service/
│   │   │   ├── BookService.java
│   │   │   ├── MemberService.java
│   │   │   └── TransactionService.java
│   │   └── util/
│   │       └── XMLHandler.java
├── data/
│   ├── books.xml
│   ├── members.xml
│   └── transactions.xml
└── README.md
```

---

## Usage

1. **Add Books and Members**  
   Use the options in the command-line menu to add books and members to the system.

2. **Issue and Return Books**  
   Manage book transactions by selecting the appropriate options.

3. **Data Persistence**  
   All changes are saved automatically in the XML files.

---

## Contribution

Contributions are welcome! Please fork the repository and create a pull request with detailed information about the changes.

---

## License

This project is licensed under the [MIT License](LICENSE).
