
# Student Management System

This is a Spring Boot-based Student Management System that demonstrates basic CRUD operations using the MVC architecture. The application allows users to add, view, edit, and delete student records.

## Features

- Create, Read, Update, and Delete (CRUD) operations for students.
- Thymeleaf-based front-end UI templates.
- Uses Spring Data JPA for data persistence.
- Maven-based project structure.

## Technologies Used

- Java 17+
- Spring Boot
- Spring Data JPA
- Thymeleaf
- Maven
- H2 (or configurable RDBMS)

## Project Structure

```
student-management/
├── src/
│   ├── main/
│   │   ├── java/com/example/studentmanagement/
│   │   │   ├── controller/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   └── service/
│   │   └── resources/
│   │       ├── templates/
│   │       └── application.properties
├── pom.xml
```

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.6+

### How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/student-management.git
cd student-management
```

2. Build the project:

```bash
mvn clean install
```

3. Run the application:

```bash
mvn spring-boot:run
```

4. Visit `http://localhost:8080` in your browser.

## Screenshots

(Add screenshots of the list and form views here.)

## License

This project is licensed under the MIT License.
