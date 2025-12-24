# Product Inventory Management System

A full-stack **Product Inventory Management System** built using **FastAPI** for the backend and **React.js** for the frontend.  
This project allows users to manage products efficiently through RESTful APIs and a modern web interface.

---

## 🚀 Features

- Add new products
- View all products
- Update existing product details
- Delete products
- REST API with FastAPI
- Interactive UI with React
- Database integration using SQLAlchemy
- CORS enabled for frontend-backend communication

---

## 🛠️ Tech Stack

### Backend
- Python
- FastAPI
- SQLAlchemy
- Postgresql
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
│   │   ├── index.html
│   │   └── manifest.json
│   └── src/
│       ├── App.js
│       ├── App.css
│       ├── TaglineSection.js
│       ├── TaglineSection.css
│       ├── index.js
│       └── index.css
│
├── database.py
├── database_models.py
├── models.py
├── main.py
├── .gitignore
└── README.md
```

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository
```
git clone https://github.com/Parvathakkar2003/PRODUCT_INVENTORY.git
cd PRODUCT_INVENTORY
```

---

### 2️⃣ Backend Setup (FastAPI)

Create and activate virtual environment:
```
python -m venv venv
venv\Scripts\activate
```

Install dependencies:
```
pip install fastapi uvicorn sqlalchemy psycopg2
```

Run backend server:
```
uvicorn main:app --reload
```

Backend URL:
```
http://127.0.0.1:8000
```

API Documentation:
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

Start frontend server:
```
npm start
```

Frontend URL:
```
http://localhost:3000
```

---

## 🔐 Git Ignore & Security

The following items are excluded from version control using `.gitignore`:
- Virtual environments (`venv/`, `env/`)
- Node modules (`node_modules/`)
- Environment files (`.env`)
- Database files (`*.db`)
- Cache files (`__pycache__/`)

No sensitive or unnecessary files are pushed to GitHub.

---

## 🔮 Future Improvements

- User authentication and authorization
- Product categories and filters
- Pagination and sorting
- Deployment to cloud platforms
- Role-based access control

## 📄 License

This project is created for educational and learning purposes.
