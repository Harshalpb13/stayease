## Stayease
Develop and deploy a RESTful API service using Spring Boot to streamline the room booking process for a hotel management aggregator application.

### Spring Security 
This project demonstrates a JWT authentication and authorization system using Spring Security in a Spring Boot application.

### Running the Project
To run the project, you can use the Gradle Wrapper provided in the repository. Follow these steps:


### Open a terminal.


Navigate to the root directory of the project where the build.gradle file is located.


### Run the following command:
./gradlew bootrun



### AuthController
The AuthController class defines endpoints for user authentication and registration.


/signin: Endpoint for user registration.

/login: Endpoint for user login.


### Request Objects

### AuthRequest


email: User's email address.

password: User's password.


### RegisterRequest


name: User's name.

email: User's email address.

password: User's password.

role: User's role. Default role is USER if not specified.


### Response Objects

### AuthResponse


message: Success message.
