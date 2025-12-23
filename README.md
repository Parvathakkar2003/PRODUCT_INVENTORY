# Product Inventory Management System (FastAPI + React)

A full-stack **Product Inventory Management System** developed using **FastAPI** for the backend and **React.js** for the frontend.  
This application enables users to perform CRUD operations on products with a clean UI and RESTful API architecture.

---

## 🚀 Features

- Create, read, update, and delete products
- RESTful APIs built with FastAPI
- Interactive frontend built with React
- Database integration using SQLAlchemy
- CORS enabled for frontend-backend communication
- Clean and modular project structure

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

## ⚙️ How to Run the Project Locally

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
venv\Scripts\activate
```

Install dependencies:
```
pip install fastapi uvicorn sqlalchemy
```

Run the FastAPI server:
```
uvicorn main:app --reload
```

Backend will be available at:
```
http://127.0.0.1:8000
```

API Documentation:
```
http://127.0.0.1:8000/docs
```

---

### 3️⃣ Frontend Setup (React)

Navigate to the frontend directory:
```
cd frontend
```

Install dependencies:
```
npm install
```

Start the React development server:
```
npm start
```

Frontend will run at:
```
http://localhost:3000
```

---

## 🔐 Security & Git Ignore

The following files and folders are intentionally excluded from GitHub using `.gitignore`:
- Virtual environments (`venv/`, `env/`)
- Node dependencies (`node_modules/`)
- Environment variable files (`.env`)
- Database files (`*.db`)
- Cache files (`__pycache__/`)

This ensures no sensitive or unnecessary files are pushed to the repository.

---

## 🔮 Future Enhancements

- User authentication and authorization
- Product categories and search
- Pagination and sorting
- Deployment using Render / Railway / Vercel
- Role-based access control


## 📄 License

This project is developed for educational and learning purposes.
