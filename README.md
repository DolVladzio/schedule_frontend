# GCP
Dev: Build fronted docker image and push to a GCR - [![Dev-GCP: Build fronted docker image and push to a GCR](https://github.com/DolVladzio/schedule-frontend/actions/workflows/GCP-docker-image_dev.yml/badge.svg?branch=dev)](https://github.com/DolVladzio/schedule-frontend/actions/workflows/GCP-docker-image_dev.yml)

Prod: Build fronted docker image and push to a GCR - [![Prod-GCP: Build fronted docker image and push to a GCR](https://github.com/DolVladzio/schedule-frontend/actions/workflows/GCP-docker-image_prod.yml/badge.svg?branch=main)](https://github.com/DolVladzio/schedule-frontend/actions/workflows/GCP-docker-image_prod.yml)

# AWS
Dev: Build fronted docker image and push to a GitHub CR - [![Dev-AWS: Build fronted docker image and push to a GitHub CR](https://github.com/DolVladzio/schedule-frontend/actions/workflows/AWS-docker-image_dev.yml/badge.svg?branch=dev)](https://github.com/DolVladzio/schedule-frontend/actions/workflows/AWS-docker-image_dev.yml)

Prod: Build fronted docker image and push to a GitHub CR - [![Prod-AWS: Build fronted docker image and push to a GitHub CR](https://github.com/DolVladzio/schedule-frontend/actions/workflows/AWS-docker-image_prod.yml/badge.svg?branch=main)](https://github.com/DolVladzio/schedule-frontend/actions/workflows/AWS-docker-image_prod.yml)

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
