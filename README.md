# Nodejs Redis Pub/Sub Application

Redis Pub/Sub provides a lightweight and efficient mechanism for real-time messaging and event-driven architectures.
This application uses nodejs/expressjs and redis along with docker to serve the application


## Project commands
```

Make sure you have docker and docker-compose installed in the machine

Start commands:- 
1.) cd <project-root-directory>
2.) docker-compose up -d --build

Stop commands:-
1.) cd <project-root-directory>
2.) docker-compose down

```


## Endpoints

|        Service      | Method |             Endpoint           |          Body            | Description
|:--------------------|:-------|:-------------------------------|:-------------------------|:--------------------|
|`Publisher Service`  | POST   | http://localhost:3001/messages | {message: "Hello Yash"}  | Create new resource
|`Subscriber Service` | GET    | http://localhost:3002/messages |  Get all resources
