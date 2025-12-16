# FastAPI Authentication & Authorization Project

## Description
This is a FastAPI project implementing user authentication, authorization, and role-based access control (Admin, User, Vendor). 
It demonstrates secure login, JWT token generation, and protected routes based on user roles.

## Features
- User registration and login
- JWT token-based authentication
- Role-based access control (Admin, User, Vendor)
- Protected API routes based on roles
- Simple CRUD operations for demo

## Requirements
- Python 3.11+
- FastAPI
- SQLAlchemy
- Pydantic
- Uvicorn
- MySQL (or SQLite for testing)

## Installation & Running
```bash
# Clone the repository
git clone <your-repo-link>
cd <project-folder>

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Run the server
uvicorn main:app --reload
