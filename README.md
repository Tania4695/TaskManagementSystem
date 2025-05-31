# Task Management System (ASP.NET MVC)

A simple task management web application built with ASP.NET MVC. This mini-project allows users to register, log in, and manage their tasks through a web interface.

## 🔍 Project Description

This application enables users to add, view, edit, and delete tasks. It includes authentication and role-based authorization to ensure that only authorized users can manage tasks securely.

## 🛠️ Features

- **User Registration & Login**
  - Users can sign up and log in using a username and password.
  - Logout functionality provided.
  
- **Task Management**
  - Authenticated users can:
    - Create tasks (title, description, due date, status)
    - View tasks in a list format
    - Edit or delete tasks (delete is admin-only)

- **Task Status Handling**
  - Tasks have statuses like **To Do**, **In Progress**, and **Done**.
  - Users can update the task status.

- **User Roles**
  - Admins: Full privileges (including task deletion).
  - Users: Limited privileges.

---

## 🧱 Technologies Used

- ASP.NET MVC 5
- C#
- Entity Framework
- MS SQL Server
- HTML/CSS/JavaScript

---

## 📐 Database Schema (Simplified)

- **Users**
  - UserID
  - Username
  - PasswordHash
  - Role

- **Tasks**
  - TaskID
  - Title
  - Description
  - DueDate
  - Status
  - CreatedBy (UserID FK)

---

## 🚀 Getting Started

1. Clone the repository or [download ZIP](https://github.com/your-username/TaskManagementSystem/archive/refs/heads/main.zip)
2. Open the solution file `.sln` in Visual Studio.
3. Restore NuGet packages if prompted.
4. Configure the database connection string in `Web.config`.
5. Run the project (`Ctrl + F5`).
