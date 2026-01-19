# 🚀 skillink-backend-upc - Streamlined User Management API

![Download](https://img.shields.io/badge/Download%20Now-Click%20Here-brightgreen)

## 📖 Overview

The **skillink-backend-upc** project is the backend system for Skillink, designed to simplify user management. Built with Spring Boot and PostgreSQL, it presents a REST API that allows efficient handling of users, roles, and mentoring sessions. This project serves as an academic effort focused on best practices in configuration, security, and architecture in web applications.

## 🚀 Getting Started

To start using the skillink-backend-upc, follow the steps below to ensure proper installation and setup.

## 🛠 System Requirements

Before you download, make sure your system meets these requirements:

- **Operating System:** Windows, macOS, or Linux
- **Java Version:** Java 11 or higher installed
- **Database:** PostgreSQL 12 or higher

## 📥 Download & Install

Visit this page to download: [Releases Page](https://github.com/Ajay-lab-prog/skillink-backend-upc/releases).

Once there, look for the latest version and download the appropriate file for your operating system. 

## 🔧 Setting Up the Application

1. **Install Java**
   - Download and install the latest version of Java from the [official site](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
   - Follow the installation instructions for your operating system.

2. **Install PostgreSQL**
   - Visit the [PostgreSQL Download Page](https://www.postgresql.org/download/) and choose your operating system.
   - Follow the setup instructions provided.

3. **Download skillink-backend-upc**
   - Return to the [Releases Page](https://github.com/Ajay-lab-prog/skillink-backend-upc/releases).
   - Download the zipped project source code or the jar file, depending on your familiarity with running applications.

4. **Extract Files (if necessary)**
   - If you downloaded a zipped file, right-click on it and select "Extract All," then follow the prompts.

5. **Configure Database**
   - Open PostgreSQL and create a new database for skillink-backend-upc.
   - Note your database name, user, and password. You will need these for configuration.

6. **Set Up Application Properties**
   - Locate the `application.properties` file in the downloaded directory.
   - Edit the file to include your database name, user, and password. 
   - Example configuration:
     ```
     spring.datasource.url=jdbc:postgresql://localhost:5432/your_database_name
     spring.datasource.username=your_username
     spring.datasource.password=your_password
     ```

7. **Run the Application**
   - Open a terminal (Command Prompt on Windows, Terminal on macOS or Linux).
   - Navigate to the project directory where your jar file is located.
   - Execute the command:
     ```
     java -jar skillink-backend-upc.jar
     ```
   - If everything is set up correctly, the application will start running on your machine.

## ✔ Using the API

The API is designed for easy navigation:

- **Base URL:** `http://localhost:8080/api`
- **Endpoints** include:
  - `/users` for managing users
  - `/roles` for handling user roles
  - `/mentorships` for scheduling mentoring sessions

You can use tools like Postman to test these endpoints:

1. Open Postman.
2. Set the method to **GET**, **POST**, **PUT**, or **DELETE** based on the operation you wish to perform.
3. Enter your API endpoint in the URL bar, e.g., `http://localhost:8080/api/users`.
4. Click **Send** to see the response from the server.

## 💡 Basic Features

- **User Management:** Create, update, and delete user information.
- **Role Management:** Assign roles to users and manage access.
- **Mentoring Sessions:** Schedule sessions and manage appointments.

## ⭐ Additional Resources

To further assist you, please refer to the following resources:

- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [Project Contributor Guidelines](https://github.com/Ajay-lab-prog/skillink-backend-upc/blob/main/CONTRIBUTING.md)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Ajay-lab-prog/skillink-backend-upc/blob/main/LICENSE) file for more details.

## 🔗 Contact

For any inquiries or support, please open an issue on our [GitHub Issues Page](https://github.com/Ajay-lab-prog/skillink-backend-upc/issues) or contact the project maintainers via their GitHub profiles.

## 🚀 Download & Install Again

Remember, you can always download the latest version here: [Releases Page](https://github.com/Ajay-lab-prog/skillink-backend-upc/releases).