# 🏦 ATM Software in Core Java

# 📌 Description
This is a simple **ATM Software** project implemented in **Core Java**. It allows users to perform basic banking operations such as depositing money, withdrawing money, and viewing their account balance. The program demonstrates key object-oriented programming (OOP) principles including **Encapsulation, Abstraction, and Modularity**.

---

## 🚀 Features
✅ Deposit Money  
✅ Withdraw Money  
✅ View Account Balance  
✅ Exit the Program  

---

## 🛠 Technologies Used
- **Java (Core Java)** 🖥️
- **Scanner Class** for User Input ⌨️

---

## 📥 Installation and Setup
1️⃣ Install **Java Development Kit (JDK)** if not already installed.  
2️⃣ Clone the repository from GitHub:
   ```sh
   git clone https://github.com/your-username/ATM-Software.git
   cd ATM-Software
   ```
3️⃣ Compile the Java file:
   ```sh
   javac ATM.java
   ```
4️⃣ Run the program:
   ```sh
   java ATM
   ```

---

## 🏗 Code Structure
### 📂 ATM Class
- **Private Property:** `balance` (Encapsulation) 🔒
- **Constructor:** Initializes the account with a given balance 🏦
- **Methods:**
  - `deposit(double amount)`: Adds money to the account ➕💰
  - `withdraw(double amount)`: Withdraws money if the balance is sufficient ➖💸
  - `viewBalance()`: Displays the current balance 📊
  
### 🎯 Main Method
- Creates an ATM account with an initial balance of `$1000`
- Provides a **menu-driven interface** using a `do-while` loop
- Handles user inputs and performs operations accordingly

---

## 💡 Example Usage
```
Welcome to the ATM!

Choose an option:
1. Deposit Money
2. Withdraw Money
3. View Balance
4. Exit
Enter your choice: 1
Enter amount to deposit: 500
Deposit successful! New Balance: $1500
```

---

## 🎓 OOP Concepts Demonstrated
- **Encapsulation:** Private balance variable 🔐
- **Abstraction:** Methods for deposit, withdrawal, and viewing balance 🎭
- **Modularity:** Structured code with separate methods 🏗️

---

## 🤝 Contribution
We welcome contributions! 🚀 Feel free to improve the code or add new features. Follow these steps:
1️⃣ Fork the repository 🍴
2️⃣ Create a new branch (`feature-new-feature`) 🌿
3️⃣ Commit your changes 💾
4️⃣ Push to the branch 🚀
5️⃣ Create a Pull Request 🔄

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE). 📃

