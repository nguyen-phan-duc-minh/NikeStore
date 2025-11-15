# 🏬 NikeStore – ASP.NET Core MVC E-Commerce Website

NikeStore is a modern **ASP.NET Core MVC** web application that simulates a real-world **e-commerce platform** for Nike products.  
It includes both **user** and **admin** interfaces for managing products, orders, and customer data efficiently.

**Author:** Nguyễn Phan Đức Minh  
**Role:** AI Researcher | Deep Learning, Machine Learning

---

## 🚀 Features

### 🛍️ User Side
- Browse and search Nike products (shoes, clothing, accessories)
- View product details with images and descriptions
- Add items to cart and checkout
- Manage user account and order history
- Responsive front-end with Razor Views and Bootstrap

### ⚙️ Admin Side
- Admin dashboard under `/Admin` area
- Manage products (CRUD)
- Manage categories, users, and orders
- Authentication and authorization for admin access
- Statistics and management tools

---

## 🧩 Project Architecture

| Layer / Folder | Purpose |
|----------------|----------|
| **Controllers/** | MVC Controllers for handling routes and logic |
| **Models/** | Entity classes and data structures |
| **Views/** | Razor pages for frontend (HTML + C# integration) |
| **Repository/** | Data access layer implementing the Repository Pattern |
| **Areas/Admin/** | Separate MVC area for admin dashboard |
| **Migrations/** | Entity Framework Core migration files |
| **wwwroot/** | Static files (CSS, JS, images) |
| **appsettings.json** | Application configuration (DB connection, keys) |
| **Program.cs** | Entry point and dependency injection setup |

---

## 🏗️ Folder Structure

```bash
NikeStore/
│── Areas/
│   └── Admin/
│       ├── Controllers/
│       ├── Views/
│       └── Models/
│
│── Controllers/
│── Models/
│── Repository/
│── Views/
│── Migrations/
│── wwwroot/
│── Properties/
│
│── appsettings.json
│── appsettings.Development.json
│── Program.cs
│── NikeStore.csproj
│── NikeStore.sln
