# MyApp

MyApp is a web application consisting of independent components developed in Go, Next.js (TypeScript), and WordPress.

## Getting Started

To get the application running locally, follow these steps:

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository

2. Navigate to the project directory

3. Build and start the containers
docker-compose up --build

This command will build the Docker images for each component and start the containers.

4. Access the applications:

- Go Application: http://localhost:8080
- Next.js (TypeScript) Application: http://localhost:3000
- WordPress: http://localhost:8000

Here is the Docker Hub Image 
1.docker pull contactamitpanddey/go-app:latest


2.docker pull contactamitpanddey/wordpress-site:latest


3.docker pull contactamitpanddey/next-app:latest

