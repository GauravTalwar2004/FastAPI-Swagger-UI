# Task Manager API

A RESTful API for managing tasks, built with FastAPI and SQLAlchemy.

## Features

- Full CRUD operations (Create, Read, Update, Delete) for tasks
- SQLite database with SQLAlchemy ORM
- Automatic request/response validation using Pydantic
- Interactive API documentation via Swagger UI

## Tech Stack

- **Framework:** FastAPI
- **Database:** SQLite
- **ORM:** SQLAlchemy
- **Validation:** Pydantic

## API Endpoints

| Method | Endpoint          | Description         |
|--------|-------------------|----------------------|
| GET    | `/`               | Health check         |
| GET    | `/tasks`          | Get all tasks        |
| POST   | `/tasks`          | Create a new task    |
| GET    | `/tasks/{task_id}`| Get a single task    |
| PUT    | `/tasks/{task_id}`| Update a task        |
| DELETE | `/tasks/{task_id}`| Delete a task         |

## Getting Started

1. Clone the repository
   \`\`\`
   git clone https://github.com/GauravTalwar2004/FastAPI-Swagger-UI.git
   cd FastAPI-Swagger-UI
   \`\`\`

2. Create and activate a virtual environment
   \`\`\`
   python -m venv venv
   venv\Scripts\activate
   \`\`\`

3. Install dependencies
   \`\`\`
   pip install fastapi uvicorn sqlalchemy pydantic
   \`\`\`

4. Run the server
   \`\`\`
   uvicorn main:app --reload
   \`\`\`

5. Visit `http://127.0.0.1:8000/docs` for interactive API documentation


