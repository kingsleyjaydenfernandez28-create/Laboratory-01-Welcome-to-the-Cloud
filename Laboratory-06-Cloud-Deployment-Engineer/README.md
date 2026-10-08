# Laboratory 06 – Cloud Deployment Engineer

## Mission Overview

This laboratory activity focused on deploying a multi-tier private cloud storage application using Docker Compose. The application consisted of Nextcloud as the web application and MariaDB as the database. Instead of deploying the containers separately, Docker Compose was used to define and deploy the entire application stack using a YAML configuration file.
The activity introduced Infrastructure as Code (IaC), where infrastructure configuration is written as code. This approach makes deployment more organized, repeatable, and easier to manage.

## Objectives
- Explain the concept of a multi-tier application architecture.
- Understand the purpose and structure of a `docker-compose.yml` file.
- Use a Linux command-line text editor to create a configuration file.
- Deploy a multi-container application using Docker Compose.
- Understand how Nextcloud communicates with a MariaDB database.
- Document deployment procedures using Markdown.
- Apply Infrastructure as Code principles.
- Expand the GitHub Cloud Computing Portfolio.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down

```
### Skills Learned
This laboratory activity helped develop practical skills in Docker, Docker Compose, Linux command-line operations, multi-container deployment, and Infrastructure as Code. I learned how multiple containers can work together as one application and how a YAML configuration file can simplify the deployment process. I also learned how the Nextcloud application communicates with a MariaDB database through Docker networking and environment variables. The activity improved my understanding of how cloud engineers can automate infrastructure instead of relying only on manual commands.
