# Frontend with Docker [![Build and Push Fronted Docker Images to GCP Artifact Registry](https://github.com/DolVladzio/azure_schedule_frontend/actions/workflows/docker-image.yml/badge.svg?branch=main)](https://github.com/DolVladzio/azure_schedule_frontend/actions/workflows/docker-image.yml)

This project is a React-based frontend application containerized using Docker. It uses a multi-stage Docker build to optimize the final image size and runtime performance. The production build is served using Nginx.

---

## Prerequisites

- [Docker](https://www.docker.com/) installed on your machine.
- [Node.js](https://nodejs.org/) installed for local development.

---

## Getting Started

1. **Install Dependencies**
   Run the following command to install the required Node.js packages and update `package-lock.json` and then delete useless Node.js dir:
   
   ```
   npm install && rm -rf node_modules
   ```
