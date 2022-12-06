# Docker MariaDB

## About this project

This project aims to make it very easy to setup a local development environment. This repository contains the files to quickly setup a useable database and DBMS.

**Docker is mandatory and thus needs to be installed**

## Settings

### Project
- PROJECT_NAME (maria_db): Name on which the containers will be based. {PROJECT_NAME}_mariadb for the maria DB container and {PROJECT_NAME} for the adminer container.

### MariaDB

- MARIADB_VERSION (latest): Version of the maria DB container.
- MARIADB_ROOT_PASSWORD (root): Value of the root password.
- MARIADB_USER (test): Name of the generated user for the generated database.
- MARIADB_PASSWORD (test): Password of the generated user for the generated database.
- MARIADB_DATABASE (test): Name of the generated database.
- MARIADB_PORT (3306): Exposed port the database.
- MARIADB_OPTION_RESTART (unless-stopped): Restart behavior of the container.

### Adminer

- ADMINER_VERSION (latest): Version of the adminer container.
- ADMINER_DESIGN (hydra): Used theme for adminer.
- ADMINER_PORT (8080): Exposed port for adminer.
- ADMINER_OPTION_RESTART (unless-stopped): Restart behavior of the container.