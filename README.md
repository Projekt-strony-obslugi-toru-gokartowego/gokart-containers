# DockerContainers
Repository which helps to setup up required containers

To start up project simply execute below command 
```shell
docker-compose pull
docker-compose up 
```
For development purpose you can always pick desired services
```shell
docker-compose pull
docker-compose up -d gokart-service gokart-web
```

### API Documentation

Swagger: Access the Swagger API documentation
at (Docker): [http://localhost:15431/authentication-docs/swagger-ui/index.html](http://localhost:15431/authentication-docs/swagger-ui/index.html) when
gokart-service is running.
