# TodoApi (.NET 8 Minimal API)

This project is a simple Todo list API built with ASP.NET Core 8 using Minimal API architecture and Entity Framework Core (In-Memory).

It was developed as part of an interview preparation challenge to demonstrate clean backend development practices in C#.

## ✅ Features

- ✅ Built with .NET 8 and Minimal APIs
- ✅ CRUD operations for todo items
- ✅ EF Core with InMemory database
- ✅ Async/await support
- ✅ Swagger UI for testing

## 📦 Endpoints

| Method | Route              | Description             |
|--------|--------------------|-------------------------|
| GET    | `/todoitems`       | Get all todo items      |
| GET    | `/todoitems/{id}`  | Get a specific item     |
| GET    | `/todoitems/complete` | Get only completed items |
| POST   | `/todoitems`       | Create a new item       |
| PUT    | `/todoitems/{id}`  | Update an item          |
| DELETE | `/todoitems/{id}`  | Delete an item          |

## ▶️ How to Run

```bash
dotnet run
```

## 🌐 Live Demo

The API is live on Azure App Service:

👉 [https://todoapi-tiago32.azurewebsites.net](https://todoapi-tiago32.azurewebsites.net)

Visit `/swagger` for interactive API testing.
