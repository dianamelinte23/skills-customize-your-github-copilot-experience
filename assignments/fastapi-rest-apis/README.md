# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Create a small REST API in Python using FastAPI that manages a list of tasks. Students will practice defining routes, handling request data, and returning structured JSON responses.

## 📝 Tasks

### 🛠️ Set up the FastAPI app

#### Description
Build a basic FastAPI application that can run locally and respond to HTTP requests. The app should include a root endpoint and a tasks collection.

#### Requirements
Completed program should:

- Create a FastAPI application instance
- Define a root endpoint that returns a welcome message
- Define a `/tasks` endpoint that returns a list of task objects
- Use Python dictionaries or a simple in-memory list to store task data
- Run the app locally with Uvicorn or FastAPI's development server

### 🛠️ Add CRUD operations for tasks

#### Description
Extend the API so students can create, read, update, and delete tasks. Each task should include fields such as `id`, `title`, and `completed`.

#### Requirements
Completed program should:

- Create a `GET /tasks` endpoint to list all tasks
- Create a `GET /tasks/{task_id}` endpoint to fetch a single task
- Create a `POST /tasks` endpoint to add a new task
- Create a `PUT /tasks/{task_id}` endpoint to update an existing task
- Create a `DELETE /tasks/{task_id}` endpoint to remove a task
- Return JSON responses with clear status codes
- Handle missing task IDs gracefully with a 404-style response

### 🛠️ Validate inputs and improve the API

#### Description
Improve the application by adding request validation and cleaner response models. This helps make the API more reliable and easier to understand.

#### Requirements
Completed program should:

- Use FastAPI data models for task input and response payloads
- Validate required fields such as title and completion status
- Ensure task IDs are stored and returned consistently
- Add a short description for each endpoint using FastAPI docs
- Test the app through Swagger UI or API client requests
