# Microservice-Assignment

This app requires [Node.js](https://nodejs.org/) and [Docker](https://docs.docker.com/get-docker/) to run.

To start the server clone the repository and run docker-compose

```sh
git clone https://github.com/healertrix/Microservice-Assignment.git
cd Microservice-Assignment
npm i
docker-compose -f docker-compose.yml up -d
```

## Content Service 

The Swagger documentation for Content Service Api will be available at --> http://localhost:8080/content/api-docs/

## User Service 

The Swagger documentation for User Service Api will be available at --> http://localhost:8080/user/api-docs/

## User interaction Service 

The Swagger documentation for User Service Api will be available at --> http://localhost:8080/interaction/api-docs/

_______________
to stop the server run the following command in your terminal

```sh
docker-compose -f docker-compose.yml down
```


# Note

`Microservice Assignment.postman_collection.json` contains Postman collection to check the apis

`Design Document.pdf` contains design document for the project
