> **SIT737 - Cloud Native Application Development**
> **Task 4.1P: Building a Simple Calculator Microservice**

Project Overview
This project implements a simple calculator microservice that performs basic arithmetic operations (addition, subtraction, multiplication, division) via REST API endpoints. It handles errors such as invalid input or division by zero and logs all requests and errors using the Winston logging library.

Setup and Installation
1. Setting Up the Project
Install the necessary packages locally:

express: A web framework for building REST APIs.

winston: A logging library used to record information and errors to files or the console.

2. Creating a New Project
A new package.json file with default values is created for the project.

Features
1. Logging
The microservice uses Winston to log both successful operations and errors.

Logs are saved to both the console and log files (combined.log for all logs and error.log for errors).

The latest log entries are displayed and updated in real-time as new logs are written.

2. Arithmetic Operations
The microservice:

Executes basic arithmetic operations (addition, subtraction, multiplication, division) via REST API endpoints.

Returns results in JSON format.

Handles errors like invalid input or division by zero.

3. Logging Requests and Errors
Logs all requests and errors using the Winston library.

Saves logs to both the console and files (combined.log, error.log).

GitHub Repository
The code is hosted on GitHub:
https://github.com/Pandey023/sit737-2025-prac4p.git
