# rest-api-spring-boot

A simple and efficient Spring Boot REST API that performs full CRUD operations (Create, Read, Update, Delete) for managing student information. This project uses Spring Boot, Spring Data JPA, and MySQL to provide seamless database interaction. 

The API allows users to add a new student, retrieve all students, get a student by ID, update student details, and delete a student. It is built using Java, Spring Boot, Spring Data JPA, MySQL, Maven, and is developed in Eclipse IDE, with API testing done through Postman.

The project follows a structured architecture with controller, service, repository, model, and main layers. It exposes REST endpoints such as POST /students to create a student, GET /students to fetch all students, GET /students/{id} to retrieve a specific student, PUT /students/{id} to update student details, and DELETE /students/{id} to remove a student.

The API can be tested using Postman by sending appropriate HTTP requests with JSON bodies for POST and PUT operations. Database configuration is handled in the application.properties file using standard MySQL connection properties, and the application can be run by cloning the repository, opening it in an IDE like Eclipse or IntelliJ, configuring the database, and starting the Spring Boot application. Future improvements may include adding validation, proper exception handling, JWT-based authentication, and features like pagination and sorting.

Screenshots:

Post : Add Student

<img width="1919" height="1077" alt="Screenshot 2026-03-27 053733" src="https://github.com/user-attachments/assets/807d06b8-dfa5-432b-a87e-9896385aeed2" />

GET : Fetch all students



<img width="1919" height="819" alt="Screenshot 2026-03-27 053828" src="https://github.com/user-attachments/assets/933924f9-92d3-4f49-85e1-980dc149c4d6" />


PUT : 

<img width="1919" height="1077" alt="Screenshot 2026-03-27 054225" src="https://github.com/user-attachments/assets/0a703ea9-6efc-4c9a-a02f-587a8f5f83ed" />

<img width="1911" height="1050" alt="Screenshot 2026-03-27 054242" src="https://github.com/user-attachments/assets/edd37179-ed44-46bf-80ea-b821f1093eb4" />



DELETE :

<img width="1919" height="1079" alt="Screenshot 2026-03-27 054416" src="https://github.com/user-attachments/assets/4c6ffc38-8857-4c8e-b373-feb343b8f471" />

<img width="1918" height="1078" alt="Screenshot 2026-03-27 054432" src="https://github.com/user-attachments/assets/c66e73dc-95bf-40de-88f4-b299c888657f" />

<img width="1919" height="976" alt="Screenshot 2026-03-27 054652" src="https://github.com/user-attachments/assets/a333e806-5393-4760-9154-2c9e5bfba43f" />


