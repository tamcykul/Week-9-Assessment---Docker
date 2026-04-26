# Hello World Docker CI/CD Project

## Overview
This project is a simple Hello World application that was containerized with Docker and automated with a CI/CD pipeline using GitHub Actions. The Docker image is pushed to Docker Hub.

## Tools Used
- Python
- Docker
- GitHub Actions
- Docker Hub

## Project Files
- `app.py` — Hello World application
- `Dockerfile` — Docker image instructions
- `.github/workflows/docker-ci.yml` — CI/CD pipeline
- `README.md` — project documentation

## Steps Followed

### 1. Created the application
I created a simple Hello World Python application in `app.py`.

### 2. Containerized the application
I created a `Dockerfile` to build the application into a Docker image.

### 3. Built the Docker image
Command used:
```bash
docker build -t hello-world .
