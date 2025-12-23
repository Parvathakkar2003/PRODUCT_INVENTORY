# Product Inventory Management System

A full-stack **Product Inventory Management System** built using **FastAPI** for the backend and **React** for the frontend.  
This application allows users to manage products efficiently with CRUD operations and a clean user interface.

---

## 🚀 Features

- Add new products
- View product list
- Update existing products
- Delete products
- RESTful API using FastAPI
- React-based frontend
- Database integration using SQLAlchemy
- CORS enabled for frontend-backend communication

---

## 🛠️ Tech Stack

### Backend
- Python
- FastAPI
- SQLAlchemy
- SQLite
- Uvicorn

### Frontend
- React.js
- JavaScript
- HTML
- CSS

---

## 📁 Project Structure

```
PRODUCT_INVENTORY/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── App.js
│       ├── App.css
│       ├── TaglineSection.js
│       ├── TaglineSection.css
│       └── index.js
│
├── database.py
├── database_models.py
├── models.py
├── main.py
├── .gitignore
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```
git clone https://github.com/Parvathakkar2003/PRODUCT_INVENTORY.git
cd PRODUCT_INVENTORY
```

---

### 2️⃣ Backend Setup (FastAPI)

Create and activate a virtual environment:
```
python -m venv venv
venv\Scripts\activate   # On Windows
```

Install dependencies:
```
pip install fastapi uvicorn sqlalchemy
```

Run the FastAPI server:
```
uvicorn main:app --reload
```

Backend will run at:
```
http://127.0.0.1:8000
```

API Docs:
```
http://127.0.0.1:8000/docs
```

---

### 3️⃣ Frontend Setup (React)

Navigate to frontend folder:
```
cd frontend
```

Install dependencies:
```
npm install
```

Start React app:
```
npm start
```

Frontend will run at:
```
http://localhost:3000
```

---

## 🔒 Environment & Security

The following are intentionally ignored using `.gitignore`:
- Virtual environments (`venv/`)
- Node modules (`node_modules/`)
- Environment files (`.env`)
- Database files (`*.db`)

No sensitive information is pushed to GitHub.

---

## 🔮 Future Enhancements

- User authentication & authorization
- Product categories
- Search and filter functionality
- Deployment (Render / Vercel)
- Pagination and sorting
- Role-based access control

---

## 📄 License

This project is created for learning and academic purposes.
