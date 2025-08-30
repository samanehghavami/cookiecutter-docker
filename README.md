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
