# Multi-Tier Architecture

## What is Two-Tier Architecture?

A two-tier architecture is a system divided into two main layers or tiers that work together to provide an application service. In this laboratory activity, the two tiers are the Web/Application Tier and the Database Tier.
The Web/Application Tier handles the application interface and communicates with users, while the Database Tier stores and manages the application's persistent information.

## Web/Application Tier

The Web/Application Tier is responsible for providing the application that users access through a web browser. In this laboratory activity, Nextcloud serves as the Web/Application Tier.
- Providing the web interface.
- Handling HTTP requests from users.
- Providing private cloud storage functionality.
- Communicating with the database container.
- Allowing users to interact with the cloud storage application.

## Database Tier

The Database Tier is responsible for storing and managing persistent information required by the application. In this laboratory activity, MariaDB serves as the Database Tier.
The MariaDB container is responsible for storing information needed by Nextcloud, including user information, application data, file metadata, and other database records.
The database is separated from the web application so that data management can operate independently from the application interface.

## Why Separate the Tiers?

Separating the web application and database into different containers makes the system easier to manage and maintain. Each container has a specific responsibility, making the architecture more organized.
A separate database container also allows the database to be managed independently from the application container. This makes the system easier to maintain, troubleshoot, update, and scale compared with placing both components into one container.
