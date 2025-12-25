# FastAPI Todo CRUD API

A simple and well-structured RESTful Todo API built using **FastAPI** and **Pydantic**.  
This project demonstrates core backend concepts such as CRUD operations, data validation, enums, and automatic API documentation.

---

## 🚀 Features

- Create, Read, Update, and Delete Todos
- Priority handling using Python `IntEnum`
- Request & response validation with Pydantic models
- Interactive API documentation with Swagger UI
- Clean and beginner-friendly FastAPI project structure

---

## 🛠 Tech Stack

- Python
- FastAPI
- Pydantic
- Uvicorn

---

## ⚙️ Installation & Setup

1. Clone the repository:
git clone https://github.com/your-username/fastapi-todo-crud-api.git
cd fastapi-todo-crud-api

2. Install dependencies:
pip install -r requirements.txt

3. Run the application:
uvicorn main:api --reload

---

## 📌 API Documentation

Once the server is running, access:

- Swagger UI: http://127.0.0.1:8000/docs
- ReDoc: http://127.0.0.1:8000/redoc

---

## 📮 API Endpoints

Method | Endpoint | Description

GET | /todos | Get all todos

GET | /todos/{id} | Get a single todo

POST | /todos | Create a new todo

PUT | /todos/{id} | Update an existing todo

DELETE | /todos/{id} | Delete a todo

---

## 📚 Learning Outcomes

- Understanding FastAPI request/response lifecycle
- Using Pydantic models for validation
- Working with enums in APIs
- Designing RESTful endpoints
- Debugging validation and JSON errors

---

## 🔮 Future Improvements

- Database integration (SQLite + SQLAlchemy)
- Async endpoints
- Pagination and filtering
- Authentication & authorization
- Unit testing with Pytest

---

## 👤 Author

Samiksha Ganesh Salunke  


requirements.txt


fastapi
uvicorn
pydantic
