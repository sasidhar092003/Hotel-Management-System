# Hotel Management System (Java)

A console-based Hotel Management System built using core Java. This application streamlines hotel operations such as multi-tier room booking (Luxury/Deluxe, Single/Double), customer tracking, food ordering, automated bill generation, and persistent data backup.

## 🚀 Features
- **Room Allocation:** Manage Luxury and Deluxe rooms for both single and double occupancy.
- **Customer Tracking:** Record customer details, contact numbers, and gender preferences.
- **Food Ordering System:** Add multiple food items to specific rooms dynamically using Java Collections.
- **Automated Billing:** Calculate room charges combined with food orders to generate itemized bills.
- **Data Persistence:** Automatically saves system state to a backup file using **Java Serialization** upon exit.
- **Asynchronous Backups:** Implements **Multithreading** (`Runnable`) to handle background file writing without blocking the main thread.
- **Error Handling:** Built-in custom exceptions (`NotAvailable`) and input validation to prevent runtime crashes.

## 🛠️ Tech Stack
- **Language:** Java (Core OOP, Collections, Exception Handling)
- **Concurrency:** Multithreading (`Runnable`, `Thread`)
- **Data Storage:** Java Object Serialization (File I/O)

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
