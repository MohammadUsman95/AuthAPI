# 🔐 ASP.NET Core 10 – JWT Authentication API

A secure Web API built with **ASP.NET Core 10** implementing **JWT Authentication**, user registration, login, and protected endpoints.  
Designed using modern API security practices commonly used in **Europe** and the **Gulf region**.

---

## 🚀 Features

- User Registration (MS SQL Server + EF Core)
- User Login with hashed password verification
- JWT Token Generation (HmacSha256)
- Protected API using `[Authorize]`
- Configurable token expiry (appsettings.json)
- Tested using **Swagger** & **Postman**
- Clean and extensible architecture

---

## 🛠️ Tech Stack

- ASP.NET Core 10 Web API  
- Entity Framework Core  
- MS SQL Server  
- Microsoft Identity  
- JWT Bearer Authentication  
- Swagger / Postman  

---

## 📂 API Endpoints

### 🔸 Public
- `POST /api/auth/register`
- `POST /api/auth/login`

### 🔸 Protected (requires JWT token)
- `GET /api/weatherforecast`


