# 🤣 JokesWebApp

A fun web-based joke repository built with ASP.NET Core MVC. The app allows users to create, view, edit, and delete jokes in a user-friendly environment.

## ✨ Features

- **Complete CRUD functionality** - Create, read, update, and delete jokes
- **User management** - Registration and login with ASP.NET Core Identity
- **Authorization control** - Only logged-in users can create, edit, and delete jokes
- **Search function** - Search for specific jokes based on the question

## 🛠️ Technologies

- **Backend**
  - ASP.NET Core 8.0 MVC
  - Entity Framework Core
  - SQL Server
  - ASP.NET Core Identity

- **Frontend**
  - HTML, CSS, and JavaScript
  - Bootstrap for responsive design

## 📋 Project Structure

```
JokesWebApp/
├── Controllers/                 # Controllers handling HTTP requests
│   ├── HomeController.cs       # Home page handling
│   └── JokesController.cs      # Joke management (CRUD)
├── Models/                      # Data models
│   ├── Joke.cs                 # Joke model
│   └── ErrorViewModel.cs       # Error handling model
├── Data/                        # Database context and migrations
│   └── ApplicationDbContext.cs  # EF Core database context
├── Views/                       # MVC views
│   ├── Home/                   # Home page views
│   ├── Jokes/                  # Joke management views
│   └── Shared/                 # Shared views and layouts
└── wwwroot/                     # Static files (CSS, JS, images)
```

## 🚀 Getting Started

### Prerequisites
- .NET SDK 8.0 or later
- Visual Studio 2022 or similar IDE
- SQL Server (LocalDB works well for development)

### Installation

1. **Clone the repository**
   ```
   git clone https://github.com/iVejDev/JokesWebApp.git
   cd JokesWebApp
   ```

2. **Restore NuGet packages**
   ```
   dotnet restore
   ```

3. **Update the database**
   ```
   dotnet ef database update
   ```

4. **Start the application**
   ```
   dotnet run
   ```

5. Open your browser and navigate to `https://localhost:7247`

## 📱 Usage

1. **View all jokes** - Go to the home page to see all jokes
2. **Search for jokes** - Use the search function to find specific jokes
3. **Create a new joke** - Click on "Create New" (requires login)
4. **Edit a joke** - Click on "Edit" next to a joke (requires login)
5. **Delete a joke** - Click on "Delete" next to a joke (requires login)

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 👨‍💻 Developer

Developed by [iVejDev](https://github.com/iVejDev)

---

&copy; 2025 iVejDev. All rights reserved.
