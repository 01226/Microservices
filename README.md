Microservices Online Shopping Application

The Microservices Online Shopping Application is an example project that demonstrates the implementation of a microservices-based architecture using Spring Boot and Spring Cloud. It showcases various features such as service discovery, API gateway, security, and event-driven communication.

Microservices Architecture: The application is designed as a set of loosely coupled and independently deployable services that work together to form a complete online shopping system.

Service Discovery: Service discovery is implemented using Eureka Server, which allows services to register themselves and discover other services in the system dynamically.

API Gateway: Spring Cloud Gateway is used as an API gateway to provide a single entry point for client requests. It handles routing, load balancing, and other cross-cutting concerns such as authentication and rate limiting.

Security: Keycloak, an open-source identity and access management solution, is integrated to secure the application. It provides authentication and authorization capabilities, ensuring only authorized users can access the services.

Circuit Breaker: Resilience4j is utilized as a circuit breaker library to handle faults and failures in the system. It helps prevent cascading failures and provides fallback mechanisms for degraded services.

Event-Driven Architecture: Kafka, a distributed streaming platform, is used for asynchronous communication between microservices. It enables decoupling of services and allows them to communicate through events, ensuring loose coupling and scalability.
