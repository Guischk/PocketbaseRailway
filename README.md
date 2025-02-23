# Pocketbase Dockerfile for Railway Template

This repository contains a Dockerfile used to build a Docker image for [Pocketbase](https://pocketbase.io/) tailored for deployment on [Railway](https://railway.app/).

## Overview

- Provides a reproducible environment for running Pocketbase.
- Simplifies deployment on Railway with the necessary configurations.

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed.
- A Railway account for deployment.

### Building the Image

```bash
docker build -t pocketbase-railway .
```

### Running the Container Locally

```bash
docker run -p 8090:8090 pocketbase-railway
```

## Deployment on Railway

1. Connect your Railway project to this repository.
2. Railway will detect the Dockerfile and build the image automatically.
3. Configure environment variables in Railway as needed.

## Customizations

Feel free to modify the Dockerfile or this README to suit your needs.
