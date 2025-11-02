# 📘 Online Bookstore Management System

A console-based application built using **Core Java** concepts such as **OOP**, **Collections**, and **File Handling**.  
It simulates an online platform where users can browse, purchase, and manage books — without relying on external frameworks or databases.  
This project demonstrates how fundamental Java principles can be used to design a complete management system.

---

## 🎯 Objectives

- Automate the process of book selling and inventory management.  
- Demonstrate the use of **Core Java** in developing a console-based application.  
- Ensure data persistence using **File Handling** techniques.  
- Design a simple and user-friendly interface for both administrators and customers.

---

## ⚠️ Problem Statement

In traditional bookstores, managing book inventory, tracking sales, and handling customer records manually can be time-consuming and error-prone.  
As the number of books and customers increases, maintaining accurate records becomes increasingly difficult.  

The **Online Bookstore Management System** overcomes these challenges by automating book management, sales tracking, and customer operations — ensuring faster processing, improved accuracy, and easier access to information within a simple console-based Java application.

---

## 👥 Intended Beneficiaries

- 👨‍💼 **Administrators:** Manage book inventory, update stock, and track sales efficiently.  
- 👩‍💻 **Customers:** Browse, search, and purchase books easily via a console interface.  
- 🏪 **Bookstore Owners:** Maintain accurate records of transactions, improving efficiency and reducing errors.

---

## 🧰 System Requirements

### 💻 Software Requirements
- **Operating System:** Windows / macOS / Linux  
- **Programming Language:** Java (Core Java)  
- **JDK Version:** JDK 8 or above  
- **IDE (Optional):** IntelliJ IDEA / Eclipse / NetBeans / VS Code  
- **Storage:** File Handling (Text Files for Data Persistence)

### ⚙️ Hardware Requirements
- **Processor:** Intel Core i3 or higher  
- **RAM:** Minimum 2 GB (4 GB recommended)  
- **Hard Disk:** Minimum 100 MB of free space  
- **Display:** 1024 × 768 resolution or higher  
- **Input Devices:** Standard keyboard and mouse

---

## ✨ Features

- 👨‍💼 **Administrator Module:** Add, update, delete, and view books.  
- 👩‍💻 **Customer Module:** Register, log in, browse books, add to cart, and purchase.  
- 💾 **File Handling:** Ensures data persistence without databases.  
- 🧩 **OOP Design:** Demonstrates encapsulation, abstraction, and modular programming principles.  

---

## 🏗️ Creating the Project

- 🖥️ Open your preferred Java IDE such as **Eclipse**, **IntelliJ IDEA**, **NetBeans**, or even a text editor like **Notepad**.  
- 📁 Create a new Java project named **OnlineBookstore**.  
- 📦 Inside the project, create a package named **com.bookstore** (optional if not using an IDE).  
- 📄 Add a new Java class file named **OnlineBookstore.java**.  
- 🚀 Set up the `main()` method to serve as the entry point of the program.

```java
// File: OnlineBookstore.java
package com.bookstore;

public class OnlineBookstore {
    public static void main(String[] args) {
        System.out.println("Welcome to the Online Bookstore!");
        // Entry point of the application
        // Future functionality will be added here
    }
}


---

## 🧪 Test and Run the Application

- 🏗️ **Compile all Java files** and run the `OnlineBookstore.java` file.  
- 👨‍💼 **Admin Module:** Log in as an administrator to add, view, update, or delete books.  
- 👩‍💻 **Customer Module:** Log in as a customer to browse, search, and purchase books.  
- 💾 **Verify data updates** are correctly saved in the text files after every operation.  
- ⚠️ **Test for invalid inputs** to ensure the program handles errors gracefully without crashing.  

```java
// File: TestBookstore.java
public class TestBookstore {
    public static void main(String[] args) {
        OnlineBookstore.loadBooks();  // Load data from file
        OnlineBookstore.main(null);   // Run main menu
        OnlineBookstore.saveBooks();  // Save data after exit
    }
}