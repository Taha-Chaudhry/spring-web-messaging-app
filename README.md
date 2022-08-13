
## Spring web messaging app

A sock.js and STOMP.js web chat app.
## Powered by

- [Spring](https://spring.io) (**duh**): Java framework
- [SockJS](https://github.com/sockjs/sockjs-client): Websocket API
- [STOMP.js](https://github.com/stomp-js/stompjs): Websocket Client




## Docker Usage

#### Build the image

```
    docker image build -t spring-boot-websocket-app .
```

#### Create and run container on port 8080

```
    docker run --name spring-boot-websocket-app -p 8080:8080 spring-boot-websocket-app
```


## Maven usage
Alternatively, the app can be run with maven:
```
    ./mvnw spring-boot:run
```

## Spring Actuator Usage
Still in development
## References

Tutorial for WebSockets with Spring by [callicoder](https://www.callicoder.com/spring-boot-websocket-chat-example/)
