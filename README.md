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
4. Build the solution.
5. Run the application.
6. Test endpoints using Tasks.http.

## Database

SQLite is used for data persistence.
The database is automatically created when
the application starts.