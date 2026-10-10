# Docker Compose Guide

## Introduction

Docker Compose is a tool used to define and manage applications that consist of multiple containers. It uses a YAML configuration file named `docker-compose.yml` to describe the application's services, configuration, and networking requirements.

## What Does the `services:` Block Do?

The `services:` block defines the containers that make up the application. In this project, it contains two services: `database`, which uses the MariaDB image, and `app`, which uses the Nextcloud image.

Each service has its own configuration, including its image, environment variables, and port settings.

## How Does Nextcloud Find the Database?

The Nextcloud application uses the `MYSQL_HOST=database` environment variable to identify the database service. Docker Compose creates a shared network for the services and provides DNS-based service-name discovery. Therefore, Nextcloud can connect to the MariaDB container using the hostname `database`.

The application also uses the database name, username, and password specified in the configuration to connect to MariaDB.

## What Is the Difference Between `docker run` and `docker-compose up -d`?

The `docker run` command starts an individual container and requires its configuration to be supplied through command-line options. When deploying multiple connected containers manually, separate commands and network configuration may be needed.

In contrast, `docker-compose up -d` reads the `docker-compose.yml` file and creates or starts the services defined in it. The `-d` option runs the containers in the background, allowing the terminal to be used for other commands.

## Port Mapping

The configuration uses `8080:80`. Port 8080 on the host or playground is mapped to port 80 inside the Nextcloud container. This allows users to access the web application through the playground's exposed port.

## Infrastructure as Code (IaC)

Infrastructure as Code means defining infrastructure using configuration files instead of relying entirely on manual setup. Docker Compose makes deployments more consistent, repeatable, and easier to maintain because the configuration can be saved, reviewed, and shared through GitHub.

## Conclusion

This activity demonstrates how Docker Compose can deploy a two-tier cloud application using Nextcloud and MariaDB. It also provides practical experience in container management, service networking, YAML configuration, and technical documentation.
