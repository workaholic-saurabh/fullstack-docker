Fullstack Application with Docker (React + Node.js + MySQL)

#This project demonstrates a full-stack web application running entirely in Docker containers, featuring:

Frontend: React (served on port 3000)

Backend: Node.js + Express (API running on port 5000)

Database: MySQL 8 (persistent storage)

#The entire stack is orchestrated using Docker Compose for easy setup and deployment.

Features

Dockerized React frontend and Node.js backend

Persistent MySQL database

Automatic backend connection retry until DB is ready

Easy setup with docker-compose up -d

#Project Structure
fullstack-docker/
│── frontend/        # React frontend
│── backend/         # Node.js backend
│── docker-compose.yml

Setup Instructions
1. Clone the repository
git clone git@github.com:workaholic-saurabh/fullstack-docker.git
cd fullstack-docker

2. Start the containers
docker compose up -d

3. Access the app

Frontend: http://localhost:3000

Backend API: http://localhost:5000

MySQL: running on port 3306 inside Docker network

Stopping the Application
docker compose down

Future Enhancements

Add user authentication (JWT)

Add CI/CD pipeline (GitHub Actions)

Deploy to cloud (AWS/GCP/Azure)

Author

Saurabh Chaudhary
https://github.com/workaholic-saurabh
https://www.linkedin.com/in/saurabh-chaudhary-320381361/







