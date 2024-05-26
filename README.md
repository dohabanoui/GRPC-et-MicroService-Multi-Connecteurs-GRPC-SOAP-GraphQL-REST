# Multi-Connector Microservices with GRPC, SOAP, GraphQL, and REST

This project showcases the integration of gRPC and multi-connector microservices utilizing SOAP, REST, GraphQL, and GRPC. It encompasses both basic GRPC communication models and a distributed system integrating multiple web service technologies.



## Introduction

The project is split into two main parts:
1. **GRPC Implementation:** Illustrates the four basic gRPC communication models.
2. **Multi-Connector Microservices:** Constructs a distributed system with customer and account services connected via REST, GraphQL, SOAP, and GRPC.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Maven
- Protocol Buffers Compiler (protoc)
- Spring Boot
- GRPC Java library
- GraphQL Java library
- SOAP library (JAX-WS)

## Part 1: GRPC Implementation

### Unary Model

Unary RPCs are the simplest type of RPC. The client sends a single request and receives a single response.

### Server Streaming Model

The server streaming RPC allows the server to send multiple responses to a single client request.

### Client Streaming Model

Client streaming RPC allows the client to send a stream of requests to the server and receive a single response.

### Bidirectional Streaming Model

Bidirectional streaming RPC allows both the client and server to send a stream of messages to each other.

## Part 2: Multi-Connector Microservices

### Customer Service

The customer service manages customer information and is implemented with the following technologies:
- **REST API:** Using Spring Boot.
- **GraphQL API:** Using Spring Boot GraphQL.
- **SOAP API:** Using JAX-WS.
- **GRPC API:** Using GRPC Java.

### Account Service

The account service manages account information and is implemented with the following technologies:
- **REST API:** Using Spring Boot.
- **GraphQL API:** Using Spring Boot GraphQL.
- **SOAP API:** Using JAX-WS.
- **GRPC API:** Using GRPC Java.

### Integration with REST, GraphQL, SOAP, and GRPC


## Testing

- **GRPC Testing:** Use `grpcurl` or a GRPC client library.
- **REST API Testing:** Use Postman or curl.
- **GraphQL Testing:** Use GraphQL Playground or Postman.
- **SOAP Testing:** Use SOAP-UI or Postman.

## Conclusion

This project exemplifies a holistic approach to implementing and integrating various web service technologies, underscoring the versatility and interoperability of modern microservice architectures.

For further exploration, consider augmenting security layers, load balancing, or deploying the services on a Kubernetes cluster for enhanced scalability and management.
