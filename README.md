# Mini Fullstack Labs – Todo Project #1

This repository is a small full-stack practice project built to demonstrate an end-to-end workflow using:

- Backend: ASP.NET Web API
- Database: SQLite (Entity Framework Core)
- Frontend: HTML and JavaScript (Fetch API)

The purpose of this project is to build a clean and reusable full-stack template that can be extended into many other small projects such as Notes, Book List, Movie Tracker, and simple CRM systems.

---

## Features

- Create a new task
- View all tasks
- Mark a task as done or undone
- Delete a task (if implemented)
- Data is persisted in a SQLite database
- RESTful API with Swagger documentation
- Simple web UI consuming the API

---

## Tech Stack

Backend:
- ASP.NET Web API (.NET 8)
- Entity Framework Core
- SQLite

Frontend:
- HTML
- Vanilla JavaScript (Fetch API)

Tools:
- Swagger
- Git

---

## Project Structure


TodoApi/
Controllers/
Data/
Models/
Program.cs

web/
index.html


---

## Getting Started

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd <your-repo-folder>
```

### 2. Run the backend

```bash
cd TodoApi
dotnet run
```

The API will be available at:

http://localhost:5085

Swagger UI:

http://localhost:5085/swagger

3. Run the frontend

Open the following file in your browser:

web/index.html

Make sure the backend is running before using the web UI.

API Endpoints
```
GET /api/Tasks

POST /api/Tasks

PUT /api/Tasks/{id}
```
Purpose of This Project

This project is built as:

A full-stack learning exercise

A starter template for small CRUD-based projects

A practice for database modeling, REST API design, and frontend-backend integration

Future projects will reuse this structure and extend it with new entities and features.

Roadmap

Notes App

Book Tracker

Movie Tracker

Simple CRM

Expense Tracker

Each project will be based on the same full-stack template.
