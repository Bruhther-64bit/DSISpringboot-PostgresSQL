
---

# Form CRUD Application

A simple web application demonstrating CRUD (Create, Read, Update, Delete) operations on a form using **Spring Boot**, **PostgreSQL**, and **Thymeleaf**.

## Features

- Create new form entries
- View a list of all entries
- Update existing entries
- Delete entries
- User-friendly interface with Thymeleaf templates

## Tech Stack

- **Backend:** Spring Boot
- **Frontend:** Thymeleaf
- **Database:** PostgreSQL

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven
- PostgreSQL

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/form-crud-springboot.git
   cd form-crud-springboot
   ```

2. **Configure the database:**

   Create a PostgreSQL database (e.g., `formdb`).  
   Update your `src/main/resources/application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/formdb
   spring.datasource.username=your_db_username
   spring.datasource.password=your_db_password
   spring.jpa.hibernate.ddl-auto=update
   ```

3. **Build and run the application:**
   ```bash
   mvn spring-boot:run
   ```

4. **Access the application:**

   Open your browser and go to:  
   [http://localhost:8080](http://localhost:8080)

## Project Structure

```
src/
 └── main/
     ├── java/
     │    └── com.example.formcrud/
     │         ├── controller/
     │         ├── model/
     │         ├── repository/
     │         └── service/
     └── resources/
          ├── templates/
          │    └── (Thymeleaf HTML files)
          └── application.properties
```

## Usage

- **Add Entry:** Click "Add New" to create a new form entry.
- **Edit Entry:** Click "Edit" next to an entry to update it.
- **Delete Entry:** Click "Delete" to remove an entry.
- **View Entries:** The home page lists all entries.

## License

This project is licensed under the MIT License.

---


