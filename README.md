# devops-docker-ci-cd

Minimal FastAPI service containerized with Docker and built automatically using GitHub Actions.

## Features
- Dockerized Python API (FastAPI)
- CI pipeline with GitHub Actions
- Ready for deployment as a microservice

## Run locally

```bash
docker build -t devops-docker-ci-cd .
docker run -p 8000:8000 devops-docker-ci-cd
