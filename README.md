# Cookiecutter Docker Cluster

A Cookiecutter template for generating a Docker Compose cluster with:  
- Backend service (custom image)  
- Frontend service (custom image)  
- Optional database (MongoDB, PostgreSQL, or MySQL)  
- Optional reverse proxy (Traefik)

---

## Features
- Choose any backend image from Docker Hub  
- Choose any frontend image from Docker Hub  
- Add a database if needed (Mongo, Postgres, MySQL)  
- Add Traefik reverse proxy automatically if required  
- Generates a ready-to-use `docker-compose.yml`  

---

## Getting Started

### 1. Install Cookiecutter
```bash
pip install cookiecutter
```

### 2. Generate a Project
```bash
cookiecutter gh:YOUR_USERNAME/cookiecutter-docker-cluster
```
### 3.Answer the Questions
```bash
project_slug [my_cluster]: my_app
backend_image [nginx:latest]: myorg/backend:1.0
frontend_image [nginx:alpine]: myorg/frontend:2.0
use_database [yes/no]: yes
database [mongo/postgres/mysql]: postgres
use_reverse_proxy [yes/no]: yes
```
### 4.Navigate into the Project
```bash
cd my_app
```
### 5.Run with docker compose
```bash
docker compose up -d
```
## Requirements
Docker & Docker Compose

Python 3.7+

Cookiecutter
