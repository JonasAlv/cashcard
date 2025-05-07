
---

# 💳 CashCard API

A RESTful API built with Spring Boot for managing virtual cash cards. This project serves as an educational example for building secure, testable, and maintainable backend services.([GitHub][1])

## 🚀 Features

* Create, retrieve, update, and delete cash cards
* Secure endpoints with Spring Security
* Integration with Spring Data JPA for database operations
* Comprehensive testing using JUnit and AssertJ
* Built with Gradle for streamlined builds

## 🛠️ Technologies Used

* Java
* Spring Boot
* Spring Web
* Spring Data JPA
* Spring Security
* JUnit 5
* AssertJ
* Gradle

## 📦 Getting Started

### Prerequisites

* Java 17 or higher
* Gradle

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/JonasAlv/cashcard.git
   cd cashcard
   ```



2. Build the project:

   ```bash
   ./gradlew build
   ```



3. Run the application:

   ```bash
   ./gradlew bootRun
   ```



4. Access the API at `http://localhost:8080/cashcards`.

## 🧪 Running Tests

Execute the test suite using:

```bash
./gradlew test
```



## 📂 Project Structure

```plaintext
cashcard/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── cashcard/
│   │   │               ├── CashCardApplication.java
│   │   │               ├── controller/
│   │   │               ├── model/
│   │   │               └── repository/
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com/
│               └── example/
│                   └── cashcard/
│                       └── CashCardApplicationTests.java
├── build.gradle
└── settings.gradle
```



## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

