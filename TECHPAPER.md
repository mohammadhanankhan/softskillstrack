# Service-Oriented Architecture

## What is service-oriented architecture (SOA)?

Imagine I want to build a new web application that allows people to pay for their parking tickets online. Well, I could spend years developing a subsystem that functions as a street map and then another subsystem for dealing with the payments and yet another for login, user authentication and so on. Or I could simply avail of Google’s map service, a payment gateway service from Paypal and a user login service from Facebook, my job then would be to integrate these diverse services by creating some common process that guides the user through the use of these different services to deliver the desired functionality.

**Thus, instead of building a system based around all my different internal components within my well-bounded piece of software, my new application would instead be built with an architecture that is orientated around services, a service-oriented architecture.**

There are two major roles within Service-oriented Architecture:

1. _Service provider:_ The service provider is the maintainer of the service and the organization that makes available one or more services for others to use. To advertise services, the provider can publish them in a registry, together with a service contract that specifies the nature of the service, how to use it, the requirements for the service, and the fees charged.

1. _Service consumer:_ The service consumer can locate the service metadata in the registry and develop the required client components to bind and use the service.

## Components Of SOA:

![Components Image](https://media.geeksforgeeks.org/wp-content/uploads/Screenshot-248.png)

## Principles of SOA:

- **Abstraction:** Each component in the system provides a service. We as designers of the system are not interested in the internal functioning of these components. Because we don't need that information, we **abstract** it away by encapsulating it. Only the provider of the service needs to know the internal logic of the component. To us, they are simply services.

- **Loose coupling:** All of these different services are loosely coupled, this means these different modules can join or leave from the system as need be, thus maintaining their independence.

- **Reusability:** Designed as components, services can be reused more effectively, thus reducing development time and the associated costs.

- **Autonomy:** Services have control over the logic they encapsulate and, from a service consumer point of view, there is no need to know about their implementation.

## Advantages of SOA:

- **Easy maintenance:** Because all services are self-contained and independent, they can be modified and updated as needed without affecting other services.

* **Scalability:** It’s important to be able to scale a business to meet the needs of the client, however certain dependencies can get in the way of that scalability. In SOA, services can run on different servers within an environment, hence scalability is greatly increased.

* **Service reusability:** In SOA, applications are made from existing services. Thus, services can be reused to make many applications.

* **Reliability:** SOA applications are more reliable because it is easy to debug small services rather than huge codes.

* **Platform independent:** SOA allows making a complex application by combining services picked from different sources, independent of the platform.

## Conclusion:

Service-Oriented Architecture (SOA) is an architectural approach in which applications are built with an architecture that is orientated around services.

SOA integrates software components that have been separately deployed and maintained and allows them to communicate and work together to form an application across different systems.

## References:

- [Wikipedia](https://en.wikipedia.org/wiki/Service-oriented_architecture)
- [Medium](<https://medium.com/@SoftwareDevelopmentCommunity/what-is-service-oriented-architecture-fa894d11a7ec#:~:text=Service%2DOriented%20Architecture%20(SOA),of%20vendors%20and%20other%20technologies.>)
- [GeeksforGeeks](https://www.geeksforgeeks.org/service-oriented-architecture/)
