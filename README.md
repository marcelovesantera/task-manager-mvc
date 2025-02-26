# Task Manager (ASP.NET Core MVC)

## Sobre o Projeto
O **Task Manager** é uma aplicação web desenvolvida em **ASP.NET Core MVC** que permite gerenciar tarefas com funcionalidades de **CRUD (Create, Read, Update, Delete)**.

## Tecnologias Utilizadas
- **ASP.NET Core MVC** (.NET 8)
- **Entity Framework Core** (EF Core)
- **SQL Server**
- **Bootstrap 5** (para estilização)

## Como Rodar o Projeto
### 1️⃣ Clone o Repositório
```bash
git clone https://github.com/marcelovesantera/task-manager-mvc.git
cd TaskManager
```

### 2️⃣ Configure a Connection String no `appsettings.json`
```json
"ConnectionStrings": {
    "DefaultConnection": "Server=SEU_SERVIDOR;Database=TaskManagerDB;User Id=SEU_USUARIO;Password=SUA_SENHA;TrustServerCertificate=True;"
}
```

### 3️⃣ Instale as Dependências
```bash
dotnet restore
```

### 4️⃣ Rode as Migrations
```bash
# Criar a estrutura do banco de dados
dotnet ef database update
```

### 5️⃣ Execute a Aplicação
```bash
dotnet run
```

## Funcionalidades
✅ Criar novas tarefas
✅ Listar todas as tarefas
✅ Editar tarefas existentes
✅ Marcar tarefas como concluídas
✅ Excluir tarefas

---

# Task Manager (ASP.NET Core MVC) - English Version

## 📌 About the Project
**Task Manager** is a web application built with **ASP.NET Core MVC** that allows users to manage tasks with full **CRUD (Create, Read, Update, Delete)** functionalities.

## 🚀 Technologies Used
- **ASP.NET Core MVC** (.NET 8)
- **Entity Framework Core** (EF Core)
- **SQL Server**
- **Bootstrap 5** (for styling)

## 📥 How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/marcelovesantera/task-manager-mvc.git
cd TaskManager
```

### 2️⃣ Configure the Connection String in `appsettings.json`
```json
"ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=TaskManagerDB;User Id=YOUR_USER;Password=YOUR_PASSWORD;TrustServerCertificate=True;"
}
```

### 3️⃣ Install Dependencies
```bash
dotnet restore
```

### 4️⃣ Run the Migrations
```bash
# Create the database structure
dotnet ef database update
```

### 5️⃣ Run the Application
```bash
dotnet run
```

## Features
✅ Create new tasks
✅ List all tasks
✅ Edit existing tasks
✅ Mark tasks as completed
✅ Delete tasks
