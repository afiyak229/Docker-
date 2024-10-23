## Features

- A simple RESTful API built with Flask.
- Connection to a PostgreSQL database.
- Containerization using Docker.
- Multi-container setup with Docker Compose.

## Technologies Used

- **Python**: Programming language for the web application.
- **Flask**: Micro web framework for Python.
- **PostgreSQL**: Relational database management system.
- **Docker**: Platform for developing, shipping, and running applications.
- **Docker Compose**: Tool for defining and running multi-container Docker applications.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Clone the Repository

```bash
git clone https://github.com/yourusername/docker-flask-app.git
cd docker-flask-app


1) Building the Docker Image
To build the Docker image for the Flask application, run the following command in the root directory of the project:
docker build -t flask-app .


2) Running the Application
To run the application with the PostgreSQL database, use Docker Compose:
docker-compose up
This command will start the web application and the database. The application will be accessible at http://localhost:5000.
