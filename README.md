🚀 Sisha Clean Architecture (Minimal)

Minimal, production-ready ASP.NET Core Clean Architecture solution template.

A clean and scalable starting point for building layered, maintainable, and testable .NET applications following Clean Architecture principles.



📦 NuGet Package

NuGet Page:
https://www.nuget.org/packages/Sisha.CleanArchitecture.Minimal/

Install directly from NuGet:

dotnet new install Sisha.CleanArchitecture.Minimal




✨ Features





Clean Architecture structure



Domain-Driven Design (DDD) friendly



BaseEntity & ValueObject included



ASP.NET Core MVC



Dependency Injection ready



Nullable reference types enabled



Implicit usings enabled



Minimal and extensible foundation



Production-ready folder structure



Distributed as official .NET Template (NuGet)



🧱 Project Structure

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




🏗 Architecture Overview

This template follows core Clean Architecture principles:





Domain → Core business rules and entities (independent of frameworks)



Application → Use cases, services, and contracts



Infrastructure → External concerns (Persistence, Repositories, Services)



Web → Presentation layer (ASP.NET Core MVC)

Dependency Flow

Web → Application → Domain
Infrastructure → Application & Domain

The Domain layer remains fully independent.



🚀 Create a New Project

After installing:

dotnet new sisha-clean -n MyProject


Then:

cd MyProject
dotnet build
dotnet run --project src/MyProject.Web




🎯 Why This Template?

This template is intentionally:





Minimal (no unnecessary complexity)



Clean and easy to understand



Ready for real-world extension



Suitable for enterprise scaling



Great for learning Clean Architecture

It provides structure without forcing heavy frameworks or patterns.



🧩 Included Base Classes

BaseEntity





Guid Id



Equality overrides



Clean identity handling

ValueObject





Structural equality support



GetEqualityComponents() pattern



DDD-friendly implementation



🛠 Requirements





.NET 8 SDK or newer



Visual Studio / VS Code / Rider



📄 License

MIT License



👨‍💻 Author

Developed by Mansarix



⭐ Support

If you find this template useful:





Star this repository



Use it in your projects



Share it with other .NET developers



Happy coding 🚀
