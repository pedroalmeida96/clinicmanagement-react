# Clinic Management GUI

<!-- ABOUT THE PROJECT -->
## About The Project
Clinic Management Api is a Java application to make the management of doctors, patients and its appointments.

### Built With

This project uses:
* Java 11
* [Spring JPA](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/) for database access
* [Spring Web](https://spring.io/guides/gs/serving-web-content/) to serve HTTP requests
* Hibernate
* Lombok
* Postgres
* Maven

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

<!-- RUNNING THE APPLICATION LOCALLY -->
### Running the application locally

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `com.pedroalmeida.ClinicManagementApiApplication` class from your IDE.

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn spring-boot:run
```

## Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/pedroalmeida96/clinicmanagement-api.git
   ```
2. Run clean install command to generate .jar file and install the api application.
   ```sh
   mvn clean install
   ```
   
## Database
This application uses a PostgreSQL database instance and already have a few entries for testing purposes.

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

<!-- ENDPOINTS AND ENTITIES -->
## Endpoints and entities available
| Type     | APPOINTMENTS ENDPOINT |
|----------|---------------------|
| `GET`    | `/api/appointments` |
| `GET`    | `/api/appointments/{id}` |
| `POST`   | `/api/add`          |
| `DELETE` | `/delete/{id}`      |
| `PATCH`  | `/api/patch/{id}`   |

| Type     | DOCTORS ENDPOINT           |
|----------|----------------------------|
| `GET`    | `/api/doctors`             |
| `GET`    | `/api//doctors/{id}`       |
| `POST`   | `/api//doctors/add"`       |
| `DELETE` | `/api/doctors/delete/{id}` |
| `PATCH`  | `/api/doctors/patch"`      |

| Type     | PATIENTS ENDPOINT           |
|----------|-----------------------------|
| `GET`    | `/api/patients`             |
| `GET`    | `/api/patients/{id}`        |
| `POST`   | `/api/patients/add`         |
| `DELETE` | `/api/patients/delete/{id}` |
| `PATCH`  | `/api/patients/patch`       |


<!-- ROADMAP -->
## Roadmap

- [ ] Appointments fully implemented.
    - [X] Implementation
    - [ ] Testing
- [ ] Doctors fully implemented.
    - [X] Implementation
    - [ ] Testing
- [ ] Patients fully implemented.
    - [X] Implementation
    - [ ] Testing


<!-- FRONTEND APPLICATION -->
## Frontend application
Project Link: [https://github.com/pedroalmeida96/clinicmanagement-react](https://github.com/pedroalmeida96/clinicmanagement-react)

  
<!-- CONTACTS -->
## Contacts
Pedro Almeida - [https://www.linkedin.com/in/pedro-almeida-1493b9188/](https://www.linkedin.com/in/pedro-almeida-1493b9188/)

Project Link: [https://github.com/pedroalmeida96](https://github.com/pedroalmeida96)

