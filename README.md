# 🧠 FastAPI Student Management API

This is a beginner-friendly FastAPI project that implements a simple student management API. It supports full CRUD operations and uses Pydantic for request validation.

## 🚀 Features

- ✅ Create, read, update, and delete students
- ✅ Uses FastAPI and Pydantic
- ✅ Auto-generates Swagger docs at `/docs`
- ✅ Clean and easy-to-understand code

## 🧪 Sample Endpoints

- `GET /get-student/{student_id}`
- `POST /create-student/{student_id}`
- `PUT /update-student/{student_id}`
- `DELETE /delete-student/{student_id}`

## 📦 How to Run

```bash
pip install fastapi uvicorn
uvicorn myapi:app --reload
