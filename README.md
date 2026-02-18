# FastAPI Auth Starter 🚀

Production-ready FastAPI authentication starter project with JWT, PostgreSQL, and Docker.

---

## ✨ Features

- FastAPI
- JWT Authentication (Register / Login)
- Role-based access (User / Admin)
- PostgreSQL
- SQLAlchemy ORM
- Alembic Migrations
- Docker & Docker Compose
- Health Check Endpoint
- Clean project structure

---

## 📂 Project Structure

app/
  ├── api/
  ├── core/
  ├── models/
  ├── schemas/
  └── main.py

---

## ⚙️ Requirements

- Docker
- Docker Compose

OR

- Python 3.11+
- PostgreSQL

---

## 🚀 Run with Docker

Clone the repository:

git clone https://github.com/Sany-matrix/fastapi-auth-starter.git
cd fastapi-auth-starter

Create environment file:

cp .env.example .env

Run:

docker-compose up --build

Open Swagger Docs:

http://localhost:8000/docs

---

## 🔐 API Endpoints

Register  
POST /auth/register

Login  
POST /auth/login

Health Check  
GET /health

---

## 🗄 Default Database Config

POSTGRES_USER=postgres  
POSTGRES_PASSWORD=postgres  
POSTGRES_DB=fastapi_db  

---

## 🧠 Use Cases

- Starter template for backend projects
- Connecting frontend applications to a secure API
- Learning FastAPI authentication
- Production-ready backend base

---

## 🛠 Tech Stack

- FastAPI
- PostgreSQL
- SQLAlchemy
- Alembic
- Docker
- python-jose (JWT)

---

## 📄 License

MIT

