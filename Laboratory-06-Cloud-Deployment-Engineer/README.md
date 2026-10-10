# Mission 6: The Cloud Deployment Engineer

## Mission Overview
This laboratory activity demonstrates how to deploy a multi-tier private cloud storage application using Docker Compose. The deployment consists of Nextcloud as the web application tier and MariaDB as the database tier.

## Objectives
- Understand two-tier architecture.
- Create a Docker Compose YAML configuration file.
- Deploy Nextcloud and MariaDB containers.
- Access the Nextcloud web interface through a browser.
- Document Infrastructure as Code (IaC) principles.
- Practice GitHub portfolio management.

## Commands Executed
```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

## Skills Learned
- Linux command-line operations
- YAML configuration
- Docker Compose
- Multi-container deployment
- Cloud application networking
- Markdown documentation
- GitHub version control
