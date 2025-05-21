# MagicVilla 🏡

MagicVilla is a full-stack .NET application that allows users to book, rent, and explore villas around the world. The solution is built using ASP.NET Core Web API and MVC architecture to provide a seamless and secure experience for both administrators and customers.

---

## 🌐 Project Overview

The project consists of three core components:
- **MagicVilla_VillaAPI**: RESTful Web API built using ASP.NET Core for handling backend services, business logic, and data operations.
- **MagicVilla_Web**: MVC web application with a Razor Pages frontend for interacting with the API and rendering user interfaces.
- **MagicVilla_Utility**: Contains shared definitions and utility classes.

---
## ✨ Features

- ✅ Full CRUD operations for villas
- 🌍 Web UI built with Razor Pages, HTML, CSS, Bootstrap
- 🔐 Secure JWT authentication with refresh tokens
- 🧑‍💼 Role-based access: Admin and Customer
- ⚙️ API versioning and documentation via Swagger
- 📂 Image/File upload support
- 🔄 Server-side pagination
- 🛡️ Global exception handling with middleware and filters
- 📊 Logging with Serilog
- 🔄 Caching for performance optimization
---


## 🚀 Technologies Used

- ASP.NET Core Web API & MVC
-  MS SQL Server
- Entity Framework Core (EF)
- Identity Framework
- Dependency Injection
- Repository Pattern
- Serilog (Logging)
- AutoMapper
- Caching (In-Memory)
- API Versioning
- Pagination
- JWT Authentication + Role-Based Access Control (RBAC) [Admin, Customer]
- Swagger / OpenAPI
- Custom Error Handling
- Filters & Middlewares
- Refresh Token Authentication
- File Uploads
- Clean Architecture Principles
---

## 📁 Project Structure Overview

### 🔧 MagicVilla_VillaAPI
- `Controllers/`: API endpoints for managing villas and related entities.
- `Data/`: Database context and related configurations.
- `Models/`: Domain models representing the villa data.
- `Repository/`: Implements the Repository pattern for data access.
- `Filters/`: Custom action filters for request validation or logging.
- `Middlewares/`: Custom middleware components (e.g., exception handling).
- `Extensions/`: Extension methods for service configuration.
- `Migrations/`: EF Core database migrations.
- `MappingConfig.cs`: AutoMapper profile setup.
- `ConfigureSwaggerOptions.cs`: Swagger documentation configuration.
- `Program.cs`: App entry point and dependency setup.

### 🖥️ MagicVilla_Web
- `Controllers/`: MVC controllers for routing.
- `Views/`: Razor Views for UI rendering.
- `Models/`: ViewModels and data transfer objects.
- `Services/`: Service classes to interact with APIs.
- `Extensions/`: Helper methods for service registration.
- `wwwroot/`: Static files (CSS, JS, images).

### 🔧 MagicVilla_Utility
- `SD.cs`: Contains static details and constants shared across the solution.

---
## 📸 Screenshots
![image](https://github.com/user-attachments/assets/57f6832e-64c7-45e0-bbd8-7c0ad3dcb88c)  
![image](https://github.com/user-attachments/assets/bf271f39-3376-4ee5-9490-e7460254e8e8)  
![image](https://github.com/user-attachments/assets/b2053910-3409-474c-a818-57c4fe1194ba)  
![image](https://github.com/user-attachments/assets/d08ae151-6c1f-4ac3-8b39-0fe28815b7d7)  
![image](https://github.com/user-attachments/assets/d5a3b16c-c187-404f-8d22-63a2df3a2a3e)  
![image](https://github.com/user-attachments/assets/0076dbe1-7f4c-4898-945f-845f74da3b58)  
![image](https://github.com/user-attachments/assets/92ae573e-a626-487c-866d-990440219881)  
![image](https://github.com/user-attachments/assets/cb11984d-a5ec-4b16-8a70-71ac792f9553)  
![image](https://github.com/user-attachments/assets/4d78118f-fa65-48a8-a5a8-0fe53bac64ae)  








