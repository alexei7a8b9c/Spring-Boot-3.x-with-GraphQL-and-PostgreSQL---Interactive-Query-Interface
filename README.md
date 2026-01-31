📚 Spring Boot 3.x GraphQL with PostgreSQL
A complete GraphQL API implementation using Spring Boot 3.2.0, GraphQL, and PostgreSQL with an interactive web interface.

🚀 Features
✅ Spring Boot 3.2.0 with Java 17

✅ GraphQL API with Spring GraphQL

✅ PostgreSQL 15 with JPA/Hibernate

✅ Interactive Web Console with Thymeleaf

✅ Complete CRUD Operations for Books

✅ Real-time Validation with Bean Validation

✅ Auto-generated Database Schema

✅ Docker Compose for PostgreSQL

✅ Actuator Endpoints for monitoring

✅ Comprehensive Logging with SLF4J

✅ CORS Configuration for frontend integration

📁 Project Structure
text
src/main/java/com/example/demo/
├── DemoApplication.java          # Main application class
├── config/
│   └── WebConfig.java           # CORS and web configuration
├── controller/
│   ├── BookController.java      # GraphQL resolvers
│   └── WebController.java       # Web page controllers
├── entity/
│   └── Book.java                # JPA entity with timestamps
├── repository/
│   └── BookRepository.java      # Spring Data JPA repository
├── service/
│   └── BookService.java         # Business logic layer
└── dto/
└── BookInput.java           # DTO for input validation

src/main/resources/
├── application.yml              # Application configuration
├── graphql/
│   └── schema.graphqls          # GraphQL schema definition
├── templates/
│   └── graphql-console.html     # Interactive web interface
└── data.sql                     # Initial sample data
🛠️ Prerequisites
Java 17 or higher

Maven 3.8+ or Gradle

PostgreSQL 15 (or Docker)

IDE (IntelliJ IDEA, Eclipse, or VS Code)

🌐 Access Points
Service	URL	Description
GraphQL Console	http://localhost:8080/	Interactive web interface
GraphQL Endpoint	http://localhost:8080/graphql	API endpoint
GraphiQL	http://localhost:8080/graphiql	Built-in GraphQL IDE
Health Check	http://localhost:8080/actuator/health	Application health
Metrics	http://localhost:8080/actuator/metrics	Performance metrics
GraphQL Schema	http://localhost:8080/actuator/graphql	Schema inspection