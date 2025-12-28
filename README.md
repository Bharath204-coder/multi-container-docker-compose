Docker Compose PHP & MariaDB Multi-Container Application
📌 Project Overview

This project demonstrates the deployment of a multi-container web application using Docker Compose.
The application consists of a PHP Apache web server and a MariaDB database, orchestrated together to simulate a real-world containerized stack used in production environments.

The primary focus of this project is container orchestration, service communication, persistent storage, and environment-based configuration, rather than application complexity.

🏗️ Architecture
Web Service
PHP application running on Apache
Exposed via host port 8083
Database Service
MariaDB database
Uses persistent storage for data durability
Docker Compose
Orchestrates multiple containers
Handles networking and dependency management

🛠️ Technologies Used

Docker
Docker Compose (v2)
PHP
Apache
MariaDB
Linux

⚙️ Key Features

Multi-container deployment using Docker Compose
Persistent volumes for database and application data
Environment variable–based database configuration
Secure database setup using a non-root user
Service dependency management using depends_on

How to Run the Project
Prerequisites

Docker installed

Docker Compose v2 enabled

Steps

Clone the repository:

git clone https://github.com/Bharath204-coder/docker-compose-php-mariadb-stack.git
cd docker-compose-php-mariadb-stack

Start the containers:
docker compose up -d

Verify running containers:
docker ps

Access the application:
curl localhost:8083
