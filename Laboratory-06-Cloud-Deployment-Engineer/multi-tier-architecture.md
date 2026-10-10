# Multi-Tier Architecture

## What Is a Two-Tier Architecture?

A two-tier architecture is a system design that separates an application into two main components: the web/application tier and the database tier. In this mission, Nextcloud provides the web interface, while MariaDB stores the application's database information.

## The Web/Application Tier

The web/application tier is responsible for presenting the user interface and handling HTTP requests from users. In this deployment, Nextcloud allows users to access and manage their files through a web browser. It communicates with the database to retrieve and store the information required by the application.

## The Database Tier

The database tier stores and manages persistent application data, such as user account information, file metadata, and configuration records. MariaDB serves as the database management system for Nextcloud. The application connects to MariaDB using the database hostname and credentials configured in Docker Compose.

## Why Separate Them?

Separating the web application and database into different containers makes the system easier to manage, update, troubleshoot, and scale. It also provides better organization by allowing each container to perform a specific role. Docker's container networking enables the two services to communicate without combining them into a single container.

## Architecture Summary

- **Web/Application Tier:** Nextcloud
- **Database Tier:** MariaDB
- **Deployment Tool:** Docker Compose
- **Application Access:** HTTP through port 8080
- **Container Communication:** Docker Compose network
