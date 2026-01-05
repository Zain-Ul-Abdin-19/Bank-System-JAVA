# 💳 Z-U-A Bank — Java Banking Management System

Z-U-A Bank is a **desktop-based banking management system** built entirely in **Java Swing**.  
It provides a simple, file-driven simulation of a real-world banking environment — including secure login, account creation, deposits, withdrawals, and transaction history tracking — all through an intuitive graphical interface.

---

## 🚀 Features

- 🔐 **Owner Login System**  
  Default credentials are automatically generated (`admin / admin123`).

- 👤 **Account Management**  
  Create new bank accounts with unique account numbers and store user data in text files.

- 💵 **Deposits & Withdrawals**  
  Perform secure transactions that update account balances dynamically.

- 📜 **Transaction History**  
  Each deposit or withdrawal is logged with a timestamp for audit purposes.

- 📂 **File-based Persistence**  
  All data is stored locally using text files (`User_Data.txt`, `Transaction_History.txt`, `Owner_login.txt`).

- 🪟 **Intuitive Swing UI**  
  Clean interface with modular panels, responsive layouts, and dialog-driven operations.

---

## 🧠 System Architecture

The project follows a **modular design**:

| Component | Description |
|------------|-------------|
| `Main.java` | Core application class with GUI, logic, and event handling |
| `User_Data.txt` | Stores all customer details and balances |
| `Transaction_History.txt` | Logs deposits and withdrawals |
| `Owner_login.txt` | Contains owner/admin credentials |

---

## ⚙️ How to Run

### **Requirements**
- Java JDK 8 or above
- Any IDE that supports Java (IntelliJ IDEA, Eclipse, NetBeans, or VS Code)

### **Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/Zain-Ul-Abdin-19/Bank-System-JAVA.git
   cd Bank-System-JAVA
   ```
2. Compile the code:
   ```bash
   javac Main.java
   ```
3. Run the application:
   ```bash
   java Main
   ```
4. Login using default credentials:
   ```
   Username: admin
   Password: admin123
   ```

---

## 🧩 Project Structure

```
📦 Z-U-A-Bank
 ┣ 📜 Main.java
 ┣ 📄 User_Data.txt
 ┣ 📄 Transaction_History.txt
 ┣ 📄 Owner_login.txt
 ┗ 🖼️ logo.png (optional)
```

---

## 🧑‍💻 Author

**Zain-ul-Abdeen**   

---

## ⚠️ Disclaimer

It simulates a basic banking environment **without any real-world financial integration**.  
Always ensure ethical use and responsible data handling.

**Made with ❤️ in Java Swing**
