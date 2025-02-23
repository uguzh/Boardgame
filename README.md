# BoardGame - Full-Stack Web Application 🎲

This web application allows users to **browse, add, and review board games**. While anyone can view the game list and reviews, users must log in to contribute.

- View a list of board games and their reviews.
- Users can add board games and write reviews.
- Managers have additional permissions to edit or delete reviews.

Built with **Java, Spring Boot, Thymeleaf, HTML, CSS, JavaScript, and Bootstrap,** using **H2 in-memory database** for data storage.

🚀 Get started by exploring or contributing to the game database!

## Technologies

- Java
- Spring Boot
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features 🚀

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run 🚀

Follow these steps to set up and run the BoardGame application:

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/praduman8435/Boardgame.git
cd Boardgame
```

### 2️⃣ Open the Project in Your IDE
You can use **IntelliJ IDEA, Eclipse,** or any other Java-supported IDE.

### 3️⃣ Run the Application
- If using Maven, run:
  ```bash
  mvn spring-boot:run
  ```
- Or run the main class in your IDE:
  ```sh
  BoardGameDatabaseApplication.java
  ```
  
### 4️⃣ Login with Default Users  
Use these pre-configured credentials to log in:  
| **Role**   | **Username** | **Password** |
|-----------|------------|------------|
| User      | `bugs`     | `bunny`    |
| Manager   | `daffy`    | `duck`     |

### 5️⃣ Create Your Own Account!  
You can also **sign up as a new user** and customize your role to explore the application. 🎲  

