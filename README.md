# Sisha Clean Architecture (Minimal)

Minimal and production-ready ASP.NET Core Clean Architecture solution template.

> A clean starting point for building scalable, maintainable, layered .NET applications.

---

## ✨ Features

- Clean Architecture structure
- Domain-driven design friendly
- BaseEntity & ValueObject included
- ASP.NET Core MVC
- Dependency Injection ready
- Nullable enabled
- Lightweight & extensible
- Ready for NuGet template usage

---

## 🧱 Project Structure

    src/
     ├── ProjectName.Domain
     │    ├── Entities
     │    ├── ValueObjects
     │    └── Interfaces
     │
     ├── ProjectName.Application
     │    ├── Interfaces
     │    ├── Services
     │    └── DTOs
     │
     ├── ProjectName.Infrastructure
     │    ├── Persistence
     │    ├── Repositories
     │    └── Services
     │
     └── ProjectName.Web
          ├── Controllers
          ├── Views
          └── Models

---

## 🚀 Install as .NET Template

Install globally from NuGet:
```bash
dotnet new install Sisha.CleanArchitecture.Minimal
