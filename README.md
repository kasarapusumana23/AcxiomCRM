# AcxiomCRM

AcxiomCRM is a role-based Customer Relationship Management web application
developed using ASP.NET Core MVC, Entity Framework Core, SQLite and
ASP.NET Core Identity.

## Technologies

- ASP.NET Core MVC
- .NET 10
- Entity Framework Core
- SQLite
- ASP.NET Core Identity
- Bootstrap
- Razor Views
- C#

## Implemented Features

### Authentication
- User Registration
- Login
- Logout
- Password hashing using ASP.NET Core Identity
- Password policy
- Account lockout
- Authentication-protected pages
- Anti-forgery protection

### Dashboard
- CRM dashboard
- Customer KPI
- Authenticated user display
- Logout

### Customer Management
- Create customer
- View customer details
- Edit customer
- Search customers
- Deactivate customer
- Server-side validation
- Client-side validation

### Roles

Implemented roles:

- Admin
- Manager
- SalesExecutive

Newly registered users are assigned the SalesExecutive role.

## Database

SQLite database managed using Entity Framework Core migrations.

## How to Run

```bash
dotnet restore
dotnet build
dotnet ef database update
dotnet run

## Live Demo
https://acxiomcrm-kiu0.onrender.com/?utm_source=chatgpt.com
