
## Spring web messaging app

A sock.js and STOMP.js web chat app.
## Powered by

- [Spring](https://spring.io): Java framework
- [SpringSecurity](https://spring.io/projects/spring-security): Authentication Framework
- [SockJS](https://github.com/sockjs/sockjs-client): Websocket API
- [STOMP.js](https://github.com/stomp-js/stompjs): Websocket Client

## Default credentials
- Username: user
- Password: password

## Preview
<img width="485" alt="Screenshot 2023-10-22 at 11 37 32 PM" src="https://github.com/Taha-Chaudhry/spring-web-messaging-app/assets/46199675/35047305-6363-492c-b5ad-43c60ca07cc3">

<img width="583" alt="Screenshot 2023-08-12 at 10 41 00 AM" src="https://github.com/Taha-Chaudhry/spring-web-messaging-app/assets/46199675/ae8854fa-574d-497c-bb80-e3c823a3821b">



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

## References

Tutorial for WebSockets with Spring by [callicoder](https://www.callicoder.com/spring-boot-websocket-chat-example/)

## TODO
- Grafana/Prometheus monitoring support
- Spring actuator usage
- Kubernetes support
