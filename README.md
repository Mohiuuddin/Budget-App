# 💰 Smart Budget Tracker — Logic-Driven Finance App

A functional, real-time budgeting application built with vanilla JavaScript. This project focuses on data entry, arithmetic processing, and dynamic UI updates to help users manage their income and expenses effectively.

**🔗 [Live Preview](https://mohiuuddin.github.io/Budget-App/)** 

---

## 🚀 Core Functionality

* **Real-Time Balance Calculation:** Automatically calculates the total available budget for the current month.
* **Income & Expense Tracking:** Separate modules for adding revenue and tracking spending with unique descriptions.
* **Percentage Logic:** Dynamically calculates the percentage of income spent for each expense item and the total budget.
* **DOM Manipulation:** High-performance updates to the user interface whenever a transaction is added or deleted.
* **Month Detection:** Automatically displays the current month and year (e.g., March 2026).

---

## 🛠️ Technical Implementation

### 1. Data Structure (The "Engine")
The application follows a modular architecture where the **Data Module** handles all calculations (Income, Expenses, and Percentages), and the **UI Module** handles the rendering. 
* Uses **JavaScript Objects** and **Arrays** to store and manipulate financial records.
* Implements **ID Management** to ensure every entry can be precisely tracked and deleted.

### 2. Event Delegation
Instead of attaching listeners to every item, the app uses **Event Delegation** on the parent container. This is a highly efficient memory management technique, showcasing advanced JavaScript knowledge.

### 3. Logic & Math
* Handles edge cases (like zero income) to prevent "Division by Zero" errors in percentage calculations.
* Formats numbers automatically to include commas and decimal points for a professional "Banking UI" feel.

---

## 📊 Project Statistics

* **JavaScript (55.7%):** The heavy lifting is done in JS, proving a strong grasp of application logic.
* **HTML/CSS (44.3%):** Focused on a clean, "FinTech-style" interface that prioritizes readability.

---

## 👨‍💻 Author

**Mohiuuddin** *ICT Professional & Full-Stack Developer* [LinkedIn](https://www.linkedin.com/in/mohiuddin777) | [GitHub](https://github.com/Mohiuuddin)
