fake-queue is a project where a user can send a transaction object to the microservice named sender-service.
sender-service will encrypted the object and sent to the microservice name receiver-service.
receiver-service will decrypt the object and store in the database.

Communication between the microservices will be handled by Eureka Server.
