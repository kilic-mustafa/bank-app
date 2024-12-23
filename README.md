# Bank App


## Description

Bank App is a banking application developed using Java Spring Boot, designed following the Layered Architecture principles. The project aims to manage banking operations while providing a user-friendly experience.




## Features

- Layered Architecture:
  - **Controller** layer handles HTTP requests.
  - **Service** layer contains business logic.
  - **Repository** layer manages database operations.
- Account and customer management.
- Authentication and authorization.
- Money transfers and balance checks.
- Centralized error handling (Exception management)


## Testing
- Comprehensive unit tests were written for the Service Layer, ensuring proper functionality and reliability of core business logic.
- Achieved 100% coverage for all service methods.

![361246363-cc02a066-9d55-49b3-951f-03d2f6e15317](https://github.com/user-attachments/assets/c0210607-89d3-43a9-a266-d3f6ec472fae)


## Setup and Run

1)Prerequisites:

- Java 17+
- Maven
- MySQL
  
2)Installation:

    git clone https://github.com/kilic-mustafa/bank-app.git
    
    cd bank-app
    
    mvn clean install

3)Run the Application:

    mvn spring-boot:run


## Contributing

To contribute to this project:

1) Fork this repository.
2) Create a new branch: git checkout -b feature/my-feature.
3) Commit your changes: git commit -m "Added my feature".
4) Push to your branch: git push origin feature/my-feature.
5) Open a pull request.


## License

This project is licensed under the MIT License - see the LICENSE file for details.
