Use C# and Build an ASP.NET Core Web API with Entity Framework Core, SQL Server, Authentication, Authorization | .NET8

## 🚀 Project Overview
I developed a **RESTful Web API** for managing New Zealand regions and their associated walks. This project demonstrates my understanding of ASP.NET Core, EF Core, and secure API development. Key features include CRUD operations, JWT authentication, role-based authorization, and advanced querying with filtering, sorting, and pagination.

---

## 🔥 Features I Implemented
- **Full CRUD Operations**:  
  - Create, read, update, and delete regions and walks via API endpoints.
- **JWT Authentication & Authorization**:  
  - Secured endpoints using JSON Web Tokens (JWT) and role-based access (e.g., `Reader` and `Writer` roles).
- **Advanced Data Handling**:  
  - Filter walks by difficulty, sort by name/length, and paginate results.
- **Repository Pattern**:  
  - Decoupled business logic from data access for scalable architecture.
- **AutoMapper Integration**:  
  - Streamlined mapping between domain models and DTOs.
- **Validation**:  
  - Enforced data integrity with model validation (e.g., walk difficulty must be "Easy", "Medium", or "Hard").
- **ASP.NET Core Identity**:  
  - User registration/login with role assignment.

---

## 🛠️ Technologies Used
- **Backend**: ASP.NET Core (.NET 8), C#
- **Database**: SQL Server, Entity Framework Core (EF Core) with Code-First Migrations
- **Authentication**: JWT Tokens, ASP.NET Core Identity
- **Tools**: AutoMapper, Swagger/OpenAPI, Postman
- **Architecture**: Repository Pattern, RESTful Design

---

## 📸 Screenshots
### Swagger UI (Authenticated Endpoints)
![Swagger UI](https://via.placeholder.com/600x300?text=Swagger+UI+with+JWT+Support)  
*Protected endpoints require a valid JWT token.*

### Postman Testing
![Postman](https://via.placeholder.com/600x300?text=Postman+Testing+CRUD+Operations)  
*Testing the `GET /api/walks` endpoint with filtering and sorting.*

---

## 🧠 What I Learned
- **REST API Design**: Followed REST principles for resource naming, HTTP methods, and status codes.
- **EF Core Migrations**: Managed database schema changes using migrations.
- **Dependency Injection**: Leveraged DI for loose coupling (e.g., injecting repositories into controllers).
- **Async/Await**: Improved performance with asynchronous database operations.
- **Security Best Practices**: Implemented JWT token generation/validation and role-based authorization.
- **API Documentation**: Used Swagger for interactive API exploration.

---

## 🚀 Getting Started
### Prerequisites
- .NET 8 SDK
- SQL Server (or Docker for SQL Server)
- IDE (Visual Studio 2022, VS Code, or JetBrains Rider)

### Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/nz-walks-api.git
   cd nz-walks-api
