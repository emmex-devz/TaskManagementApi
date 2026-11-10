# Task Management API

## Project Overview

A RESTful API developed using ASP.NET Core Web API.
The application allows users to manage tasks through
standard HTTP operations.

## Technologies Used

- C#
- ASP.NET Core Web API
- .NET 10
- Entity Framework Core
- SQLite
- Visual Studio

## Features

- Create new tasks
- Retrieve all tasks
- Retrieve tasks by ID
- Update existing tasks
- Delete tasks
- Database persistence
- Input validation
- HTTP status code handling
- Filter tasks by completion status
- Search tasks by title
- Sort tasks by creation date
- Paginate task results
- API documentation using Swagger

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/tasks | Get all tasks |
| GET | /api/tasks/{id} | Get task by ID |
| POST | /api/tasks | Create task |
| PUT | /api/tasks/{id} | Update task |
| DELETE | /api/tasks/{id} | Delete task |

## How to Run

1. Clone the repository.
2. Open the solution in Visual Studio.
3. Restore NuGet packages.
4. Run `Update-Database` in Package Manager Console.
5. Build and run the application.
6. Open `/swagger` to test the API.

## Database

SQLite is used for data persistence.
Entity Framework Core migrations manage database
creation and schema updates.

Run `Update-Database` in the Package Manager
Console to apply the migrations.
