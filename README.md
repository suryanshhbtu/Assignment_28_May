
## Check Criteria

This project utilizes the following technologies and dependencies:

- **Spring Boot**:
  - `spring-boot-starter-data-jpa`
  - `spring-boot-starter-web`
  - `spring-boot-devtools` (runtime, optional)

- **Database**:
  - `mysql-connector-j` (runtime)

- **Testing**:
  - `spring-boot-starter-test` (test scope)
  - `junit` (test scope)

- **API Documentation**:
  - `springfox-swagger2` version 2.7.0
  - `springfox-swagger-ui` version 2.7.0
  - `springdoc-openapi-starter-webmvc-ui` version 2.5.0

- **Logging**:
  - `log4j-core` version 3.0.0-alpha1
  - `log4j-api` version 3.0.0-alpha1

- **CSV Handling**:
  - `opencsv` version 5.8

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   cd project-directory
   ```

2. Build the project:
   ```
   mvn clean install
   ```

3. Run the project:
   ```
   mvn spring-boot:run
   ```

4. Open your web browser and navigate to `http://localhost:8080/swagger-ui/index.html#/` to view the Swagger Documentation of the application.

## Configuration

- **Database Configuration**:
  - Update `application.properties` with your database connection details.

- **Logging Configuration**:
  - Customize logging configurations in `log4j2.xml` as needed.

## Usage

- After starting the server, go to Swagger Documentation: `http://localhost:8080/swagger-ui/index.html#/`
- Use various available options along with their usage details.
