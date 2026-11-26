# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with FastAPI to practice defining routes, handling requests, and returning structured JSON responses.

## 📝 Tasks

### 🛠️ Create API Routes

#### Description
Set up a FastAPI application with routes that demonstrate GET and POST requests.

#### Requirements
Completed program should:

- Create a FastAPI application instance.
- Return a JSON welcome response from a root `GET` route.
- Return a list of items from a `GET` route.
- Use a Pydantic model to validate data in a `POST` route.

### 🛠️ Test the API

#### Description
Run the API locally and verify that each route behaves correctly.

#### Requirements
Completed program should:

- Start the server with Uvicorn.
- Successfully handle a valid item creation request.
- Return HTTP 422 for invalid request data.
- Include example requests and responses in the assignment.
