 Todo Application (Spring Boot + Thymeleaf + MySQL)

A simple Todo List web application built using **Spring Boot**, **Thymeleaf**, and **Bootstrap 5**. Users can add, view, mark tasks as completed, and delete tasks. The application stores tasks persistently using **MySQL**.

## 🛠 Tech Stack

- **Backend**: Spring Boot, Spring MVC, Spring Data JPA
- **Frontend**: Thymeleaf, Bootstrap 5, HTML
- **Database**: MySQL
- **Build Tool**: Maven

## 🚀 Features

- ✅ Add new tasks
- 🔁 Toggle task completion (mark as done)
- ❌ Delete tasks
- 🎨 Stylish UI with Bootstrap for a better user experience
- 💾 Data is stored persistently in MySQL

📁 Project Structure
todoapp/
│
├── src/
│   ├── main/
│   │   ├── java/com/app/todoapp/
│   │   │   ├── controller/              # Contains the TaskController for handling HTTP requests
│   │   │   │   └── TaskController.java
│   │   │   ├── models/                  # Contains the Task model entity
│   │   │   │   └── Task.java
│   │   │   ├── repository/              # Contains the TaskRepository interface for data access
│   │   │   │   └── TaskRepository.java
│   │   │   ├── services/                # Contains the business logic for tasks
│   │   │   │   └── TaskService.java
│   │   │   └── TodoappApplication.java  # Main Spring Boot Application class
│   │   └── resources/
│   │       ├── static/                  # Static resources like CSS, JavaScript, images
│   │       ├── templates/               # Contains Thymeleaf templates
│   │       │   └── tasks.html           # The HTML view for displaying tasks
│   │       └── application.properties   # Contains application configuration, including DB connection
└── test/
    └── java/com/app/todoapp/            # Test classes for the application


🤝 Contributing
We welcome contributions! If you'd like to contribute, please fork the repository, make your changes, and create a pull request. For any major changes, open an issue to discuss before making the changes.



