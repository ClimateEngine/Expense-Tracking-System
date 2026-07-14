# 💰 Expense Tracking System

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi)
![Streamlit](https://img.shields.io/badge/Streamlit-Frontend-FF4B4B?style=for-the-badge&logo=streamlit)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=for-the-badge)

</p>

---

# 📖 Project Summary

Managing personal finances shouldn't be complicated.

The **Expense Tracking System** is a full-stack web application that enables users to efficiently record, manage, and analyze their daily expenses. Built using **FastAPI**, **Streamlit**, and **MySQL**, the application provides an intuitive interface for tracking expenses while delivering insightful analytics through interactive visualizations.

Whether you're monitoring daily expenditures or reviewing monthly spending habits, this project demonstrates how backend APIs, databases, and frontend dashboards can work together to create a practical financial management solution.

---

# 🎯 Project Objective

The objective of this project is to develop a complete expense management system that allows users to:

- 💰 Record daily expenses
- 📅 Update previous expense records
- 📊 Analyze spending by category
- 📈 Monitor monthly expense trends
- ⚡ Build REST APIs using FastAPI
- 🎨 Develop an interactive user interface with Streamlit
- 🗄️ Store and retrieve data using MySQL
- 📉 Generate meaningful insights from expense data

---

# 🚀 Live Application

> ⚠️ **This project currently runs locally** using a Streamlit frontend, FastAPI backend, and MySQL database. It has not yet been deployed to a public server.
>
> 🔧 **A live demo link will be added here once the application is deployed.**

💡 Want to run it yourself? Jump to the **⚙️ Installation Guide** below.

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| 🐍 Python | Programming Language |
| ⚡ FastAPI | Backend REST API |
| 🎨 Streamlit | Frontend User Interface |
| 🗄️ MySQL | Database |
| 📊 Pandas | Data Processing |
| 📈 Streamlit Native Charts | Data Visualization |
| 🔐 python-dotenv | Environment Variable Management |

---

# 💼 Skills Demonstrated

This project showcases practical experience in the following areas:

## ⚡ Backend Development

- REST API Development
- FastAPI Framework
- CRUD Operations
- Request Validation with Pydantic
- API Routing

### 🗄️ Database Management

- MySQL
- SQL Queries & Aggregations
- Database Schema Design
- Connection Handling

### 🎨 Frontend Development

- Streamlit
- Interactive Dashboards
- Forms & User Inputs
- Data Visualization
- Tabbed Layouts

### 🐍 Python Programming

- Modular Programming
- Exception Handling
- Logging
- Environment Variables
- Project Structuring

### 📊 Data Analytics

- Expense Analysis
- Category-wise Insights
- Monthly Trends
- Interactive Charts

---

# ✨ Features & Highlights

## 💰 Expense Management

- ➕ Add new expenses
- ✏️ Update existing expenses
- 📅 Maintain expenses organized by date
- ♾️ Store unlimited expense records

---

## 📅 Date-wise Tracking

- Record expenses for any date
- Automatically retrieve and edit previous records
- Simple daily expense workflow

---

## 📊 Category-wise Analytics

Analyze expenses across categories such as:

- 🏠 Rent
- 🍔 Food
- 🛒 Shopping
- 🎬 Entertainment
- 📦 Other

Interactive **bar charts** and **percentage breakdowns** help visualize where money is being spent over any selected date range.

---

## 📈 Monthly Analytics

- Monthly spending overview
- Automatic aggregation by month
- Interactive bar chart of total monthly expenses

---

## ⚡ FastAPI Backend

REST APIs for:

- Adding & updating expenses
- Retrieving expenses by date
- Category-wise analytics
- Monthly analytics

---

## 🎨 Interactive Streamlit Dashboard

- Clean, tabbed UI
- Interactive forms with live editing
- Dynamic, auto-updating charts
- Easy navigation across modules

---

## 🗄️ MySQL Database

Efficiently stores and manages:

- Expense records
- Categories
- Notes
- Date-based records
- Category-wise aggregation queries
- Month-wise aggregation queries

---

# 📸 Web Module Preview

> 📌 Replace the placeholders below with your own screenshots once added to an `assets/` folder.

## ➕ Add / Update Expenses

```text
assets/add_update.png
```

---

## 📊 Category Analytics

```text
assets/category_analytics.png
```

---

## 📈 Monthly Analytics

```text
assets/monthly_analytics.png
```

<details>

<summary><strong>📌 How to add your screenshots (Click to Expand)</strong></summary>

1. Run the application locally.
2. Take screenshots of each module.
3. Create a folder named **assets/** in the project root.
4. Save your screenshots using the filenames shown above.
5. Replace the code blocks with image links like:

```markdown
![Add Update](assets/add_update.png)
```

Finally, commit your changes:

```bash
git add assets/
git commit -m "Add application screenshots"
git push
```

</details>

---

# 📊 Key KPIs

The application provides valuable financial insights including:

- 💰 Total expenses by category
- 📊 Category-wise spending percentage
- 📈 Monthly spending trends
- 📅 Daily expense records
- 📌 Historical expense analysis

---

# 🌐 Web Features

- ✅ FastAPI Backend
- ✅ Streamlit Frontend
- ✅ MySQL Database
- ✅ CRUD Operations
- ✅ REST API Architecture
- ✅ Dynamic Charts
- ✅ Category-wise Analytics
- ✅ Month-wise Analytics
- ✅ Date-based Filtering
- ✅ Modular Code Structure
- ✅ Secure Credential Management using `.env`

---

# 📂 Project Structure

```text
Expense-Tracking-System
│
├── Backend/
│   ├── server.py
│   ├── db_helper.py
│   ├── logging_setup.py
│   └── .env.example
│
├── Frontend/
│   ├── app.py
│   ├── add_update.py
│   ├── analytics_by_category.py
│   └── analytics_by_months.py
│
├── database/
│   └── expense_db_creation.sql
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

# ⚙️ Installation Guide

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/ClimateEngine/Expense-Tracking-System.git

cd Expense-Tracking-System
```

---

## 2️⃣ Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it:

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Configure MySQL

Run:

```text
database/expense_db_creation.sql
```

This creates the **expense_manager** database and the **expenses** table.

---

## 5️⃣ Configure Environment Variables

Create a `.env` file inside the **backend/** folder.

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=expense_manager
```

> 🔒 The `.env` file is excluded via `.gitignore`, ensuring your credentials remain secure.

---

## 6️⃣ Start the Backend

```bash
cd Backend

uvicorn server:app --reload
```

Backend URL:

```
http://127.0.0.1:8000
```

---

## 7️⃣ Start the Frontend

Open a second terminal and run:

```bash
streamlit run Frontend/app.py
```

The application opens at:

```
http://localhost:8501
```

---

# 📡 REST API Overview

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/expenses/{expense_date}` | Retrieve expenses for a specific date |
| POST | `/expenses/{expense_date}` | Add or update expenses |
| POST | `/analytics/` | Category-wise expense breakdown |
| GET | `/monthly_summary/` | Month-wise aggregated expense summary |

---

# 🚀 Future Enhancements

- 🔐 User Authentication
- 👥 Multi-user Support
- 📄 Export Reports (PDF / Excel)
- ☁️ Cloud Deployment with Hosted MySQL
- 📱 Mobile Responsive Design
- 💳 Income Tracking
- 📈 Budget Planning
- 🔔 Expense Notifications

---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Full-Stack Python Development
- REST API Design with FastAPI
- Backend Architecture & Routing
- SQL Database Design
- Aggregation Queries
- Streamlit Dashboard Development
- Data Visualization
- Environment Variable & Secrets Management
- Git & GitHub Version Control

---

# 👨‍💻 Developed By

## **Atharva Kulkarni**

**Climate Tech | Sustainability | Python | SQL | Power BI | Data Analytics**

Passionate about building data-driven applications that combine software development, analytics, and visualization to solve real-world problems.

<p>
<a href="https://github.com/ClimateEngine">
<img src="https://img.shields.io/badge/GitHub-ClimateEngine-181717?logo=github&logoColor=white" />
</a>
</p>

---

# ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub. It helps support the project and motivates future improvements!

---

# 📄 License

This project is intended for **educational purposes**, **portfolio demonstration**, and **learning**. Feel free to fork, explore, and build upon it with appropriate attribution.
