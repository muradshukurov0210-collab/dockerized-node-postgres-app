# Dockerized Node.js & PostgreSQL Application

This project demonstrates the containerization of a Node.js backend application built with Express and Sequelize, using PostgreSQL as the database.

The application provides RESTful APIs to perform CRUD (Create, Read, Update, Delete) operations on tutorial resources.

## Technologies Used
- Node.js (Express)
- Sequelize ORM
- PostgreSQL
- Docker
- Docker Compose

## Application Features
- Create, retrieve, update, and delete tutorials
- Filter tutorials by title or published status
- Persistent data storage using Docker volumes

## Project Structure
- `Dockerfile` – Defines the backend container
- `docker-compose.yml` – Manages backend and database containers
- `.env.example` – Sample environment variables
- `app/` – Application source code

## Dockerized Architecture
- Backend and database run in separate Docker containers
- Containers communicate through Docker internal network
- PostgreSQL data is persisted using Docker volumes

## How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/muradshukurov0210-collab/dockerized-node-postgres-app.git
cd dockerized-node-postgres-app
