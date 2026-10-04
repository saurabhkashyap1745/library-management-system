# 📚 College Library Management System

A lightweight, full-stack web application designed to digitize and manage college library book inventories. Built as part of BCA coursework to demonstrate seamless integration between a Python backend, an SQL database, and a modern frontend interface.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-lightgrey?style=flat&logo=flask)
![SQLite](https://img.shields.io/badge/SQLite-Database-green?style=flat&logo=sqlite)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-Styling-blue?style=flat&logo=tailwindcss)

---

## ✨ Features

- **Book Inventory Management:** Easily add new books with titles and authors directly into the database.
- **Real-Time Catalog View:** Dynamically lists all available books stored in the SQL database.
- **Responsive UI:** Clean, modern user interface styled with Tailwind CSS for optimal viewing on desktop and mobile devices.
- **Persistent Storage:** Uses SQLite to ensure data remains saved between sessions.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript, Tailwind CSS (via CDN)
- **Backend:** Python, Flask Framework
- **Database:** SQLite (SQL relational database)

---

## 📂 Project Directory Structure

```text
library-project/
│
├── app.py               # Main Flask application & SQL routing logic
├── requirements.txt     # Python dependencies list
└── templates/
    └── index.html       # Frontend HTML user interface
