# 📚 Books REST API

A simple REST API built using **Node.js** and **Express** to manage a list of books in memory.  
Supports **CRUD** operations: **Create**, **Read**, **Update**, and **Delete**.

---

## 🚀 Features
- View all books (**GET**)
- Add a new book (**POST**)
- Update an existing book (**PUT**)
- Delete a book (**DELETE**)
- Data stored in memory (no database required)

---

## 📂 Project Structure
── index.html # Frontend UI for interacting with API
├── style.css # Styling for index.html
├── server.js # Node.js + Express server
├── package.json # Project metadata & dependencies
└── README.md # Project documentation


---

## 🛠️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/Aditi71/book-management.git
cd books-rest-api
```

2. **Install dependencies**
```bash
npm install
```


3. **Start the server**
node server.js
---

## Server will run on:

http://localhost:3000

---

🖥️ Frontend Usage

Open index.html in your browser

Use the form to add, update, or delete books

Books list updates dynamically from the API

---
 
⚠️ Notes

Data is stored in memory and will reset when the server restarts.

For a persistent version, connect it to a database like MongoDB or MySQL.


