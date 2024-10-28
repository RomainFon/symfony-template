# Docker Symfony 7

> A Docker skeleton for Symfony 7

![Static Badge](https://img.shields.io/badge/Symfony-7.1-green)
![Static Badge](https://img.shields.io/badge/PHP-8.3-blue)
![Static Badge](https://img.shields.io/badge/MySQL-8.3.0-orange)
![Static Badge](https://img.shields.io/badge/Docker-2CA5E0)

## Prerequisites

- Docker Compose (v2.10+)

## Getting Started

1. Clone the project
```bash
git clone git@github.com:RomainFon/symfony-template.git
```

2. Configure the environment variables in **.env** file
```txt
DOCKER_APP_NAME=MY_APP_NAME
```

3. Build images
```bash
docker compose build
```

4. Run the containers
```bash
docker compose up -d
```

5. Install the dependencies
```bash
# Connect to the container www
docker compose exec www bash

# Install the dependencies
composer install
```

5. Access the application

- http://localhost:8000
