# 📝 Blog API

This is a RESTful Blog API built with **ASP.NET Core Web API**. It allows users to create, read, update, and delete blog posts. The system supports user authentication, comments, and categories.

---

## 🚀 Features

- View all blog posts
- View single post details
- View posts by category

### 🔐 Authenticated Users
- Register and login (JWT-based)
- Create, update, and delete own posts.
- Comment on posts

### 🛠 Admin
- Manage all posts and comments
- Manage categories

---

## 🧱 Tech Stack

- **ASP.NET Core Web API**
- **Entity Framework Core**
- **JWT Authentication**
- **SQL Server** or **PostgreSQL**
- **Swagger** (API documentation)
- **AutoMapper** (DTO Mapping)

---

## 📦 Database Structure (Simplified)

- **User**
  - `Id`, `Name`, `Email`, `PasswordHash`, `Role`
- **Post**
  - `Id`, `Title`, `Content`, `CreatedAt`, `AuthorId`, `CategoryId`
- **Comment**
  - `Id`, `PostId`, `AuthorId`, `Content`, `CreatedAt`
- **Category**
  - `Id`, `Name`

---

## 📂 Project Structure

