# User Portal

The **User Portal** is a web-based interface that allows users to view user information fetched from a REST API.  
It provides a clean, responsive UI to display user details such as name and image.

---

## Features

- View user details
- Fetch data from REST API
- Responsive user interface
- Clean and simple layout
- Error handling for failed API requests

---

## Tech Stack

- Frontend: HTML5, CSS3, JavaScript (ES6)
- Backend: JSON Server (Mock REST API)

---

## User Portal Structure

user/
│
├── user.html
├── users.js
└── style.css

---

## How to Run the User Portal

### Step 1: Start JSON Server
```bash
json-server --watch db.json --port 3000
