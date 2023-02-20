# DCIT-205-ASSIGNMENT
MINI PROJECT
README: School Management System Backend Service
This project is a NodeJS backend service for a school management system. The service provides two main functionalities: getting student details by student id and registering new students by supplying student details.

Prerequisites
To run this project, you need to have NodeJS and npm installed on your system.
Getting Started
To get started with this project, you need to follow these steps:
Clone the repository:
Install dependencies:
npm install
Start the server:
This will start the server on port 3000.
Endpoints
The following endpoints are available in this service:

GET /students/:id
This endpoint returns the details of a student with the specified id.

Request Parameters
Response

The response contains the details of the student in JSON format. If the student is not found, the response status code is 404.

POST /students
This endpoint registers a new student by supplying their details.

Request Body
Response

If the student is successfully registered, the response status code is 201, and the response body contains the details of the newly registered student in JSON format. If any of the required fields are missing, the response status code is 400.
