# Sample Docker Compose package

Contains a prebuilt docker package for development.

Contains the following images

1- PHP Container
2- DB Mysql Container
3- PHPMyadmin Container


## Requires the following entries in a .env file

APP_NAME="Sample Project Name"
DOCKER_PROJECT_CODE=any_project_code
DOCKER_DB_ROOT_PASSWORD=root_password_goes_here
DOCKER_PROJECT_WEB_PORT=80
DOCKER_PROJECT_PMA_PORT=9002

DB_DATABASE=database_name
DB_USERNAME=db_user
DB_PASSWORD=db_user_password
