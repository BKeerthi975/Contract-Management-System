# 📑 Contract Management System

## 📌 Project Overview
This is a simple **Contract Management System** implemented in Python.  
It allows users to manage different types of contracts (regular, project-based, and compliance contracts) with features like **adding, updating, deleting, tracking, and displaying contracts**.  

The system also includes a **basic authentication feature** for login security before accessing contract operations.

---

## ✨ Features
- 🔐 **User Authentication** – Login before accessing the system.  
- 📄 **Add Contract** – Create new contracts with details.  
- 💰 **Update Contract Amount** – Modify the amount of an existing contract.  
- ❌ **Delete Contract** – Remove contracts from the system.  
- 👨‍💼 **Manage Project Contracts** – Update the project manager for project contracts.  
- ✅ **Track Compliance Contracts** – Update compliance status for compliance contracts.  
- 📜 **Display All Contracts** – View all stored contracts.  

---

## 🛠️ Tech Stack
- **Language**: Python 3  
- **Concepts Used**: OOP (Inheritance, Polymorphism), Dictionary-based storage, Authentication system  

---

## 🚀 How It Works
1. The system starts with a **login screen** (username & password).  
2. Once logged in, users can perform operations from a menu:  
   - Add new contracts (Project/Compliance/Other).  
   - Update contract amounts.  
   - Delete contracts.  
   - Manage project managers for project contracts.  
   - Track compliance status for compliance contracts.  
   - Display all contracts.  
3. Data is stored temporarily in memory (dictionary).  

---

## 📂 Project Structure
```
📦 Contract-Management-System
 ┣ 📜 contract_system.py     # Main Python file with all classes & logic
 ┣ 📜 README.md              # Documentation
```

---

## ▶️ Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/contract-management-system.git
   cd contract-management-system
   ```

2. Run the program:
   ```bash
   python contract_system.py
   ```

3. Login with sample credentials:
   ```
   Username: james
   Password: 123#45
   ```

4. Use the menu to add, update, delete, and view contracts.

---

## 📖 Example (Sample Run)
```
Enter username: james
Enter password: 123#45
Login successful!

Contract Management System Menu:
1. Add Contract
2. Update Contract Amount
3. Delete Contract
4. Manage Project Contracts
5. Track Contract Compliance
6. Display All Contracts
7. Exit
```

---

## 📖 Future Enhancements
- Store contracts in a **database (SQLite/MySQL)**.  
- Add **GUI interface** (Tkinter/Flask Web App).  
- Implement **role-based authentication** (Admin/User).  
- Export contracts to **CSV/Excel reports**.  

---

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).
