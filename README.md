# To-Do List Web Application
This is a simple to-do list web application built using HTML, CSS, and JavaScript. The application allows users to add new tasks, view the list of tasks, and mark tasks as completed.

## How to Run the Application Locally
To run the application locally, follow these steps:

1. Clone this repository to your local machine:
   git clone https://github.com/dau2004/My-to-do-app.git
2. Navigate to the project directory:
3. Open the index.html file in your web browser.

## Building the Docker Image and Running a Container
To build the Docker image and run a container using the image, follow these steps:

1. Make sure you have Docker installed on your system.

2. Clone this repository to your local machine (if you haven't already).

3. Navigate to the project directory: cd to-do-list
4. Build the Docker image using the provided Dockerfile:docker build -t my-to-do-app .
5. Once the image is built, you can run a container using the following command:docker run -d -p 8080:80 my-to-do-app
6. Access the application by navigating to http://localhost:8080 in your web browser.

## Assumptions or Decisions Made During Development
**Lightweight Stack:** The application was built using only HTML, CSS, and JavaScript to keep it lightweight and easy to deploy.

**Nginx Server:** A lightweight Nginx server was used to serve the static files of the web application, providing a simple and efficient deployment solution.

**Port Configuration:** The application is configured to run on port 8080 inside the Docker container, and this port is exposed to the host machine for easy access.

**No Backend Dependency:** Since this is a simple front-end application, there is no need for any backend server or database. All data is managed within the client-side JavaScript code.






