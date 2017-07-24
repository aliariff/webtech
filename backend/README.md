# Prerequisite
- MySql

# Installation Guide

- Clone the repo
- Download eclipse
- Add tomcat server to eclipse
- Go to file -> import -> import as existing maven project
- Select the repo directory and import the project
- Change user and password for the mysql in `src/main/resources/application.properties`
- Right clik project folder Run As -> Run on server (choose tomcat that already installed)
- It will run on http://localhost:8080/

# Run via Docker Image

- `docker volume create --name=db_data` first time only
- `docker-compose -f docker-compose.dev.yml pull && docker-compose -f docker-compose.dev.yml up -d`
- It will run on http://localhost:8080/

