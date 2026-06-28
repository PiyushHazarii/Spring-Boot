# Spring Boot Learning Repository

![Java](https://img.shields.io/badge/Java-Backend-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-Learning%20Notes-brightgreen)
![Status](https://img.shields.io/badge/Status-Maintained-blue)
![Format](https://img.shields.io/badge/Format-PDF%20Notes%20%2B%20Diagrams-lightgrey)

A structured Spring Boot knowledge base containing detailed notes, diagrams, screenshots, and configuration snippets for learning backend development with Java and Spring Boot.

This repository is organized as a topic-wise learning archive. Each folder focuses on one important Spring Boot concept and includes deep explanation PDFs, visual references, or supporting notes.

## Repository Overview

- 29 detailed PDF notes covering Spring Boot fundamentals, MVC, data access, security, observability, transactions, and architecture.
- 63 visual assets including diagrams, screenshots, and flow references.
- 1 tracing configuration snippet for Zipkin and Micrometer setup.
- Topic-wise folder structure for quick revision and interview preparation.

## Technologies Covered

- Java backend development
- Spring Framework and Spring Boot
- Spring IoC and Dependency Injection
- Spring MVC and Servlet request flow
- Spring Data, Spring Data JDBC, Spring Data MongoDB, JPA, and Hibernate
- Spring Security authentication and authorization flow
- Spring AOP
- Spring Boot Actuator
- Transactions and exception handling
- Zipkin, Micrometer, and distributed tracing
- JSP and embedded servers

## Recommended Study Path

1. Start with [Why Spring](./Why%20Spring/) and [Terminology](./Terminology/) to understand why Spring Boot exists and the language used across the ecosystem.
2. Move to [Architecture](./Architecture/), [Spring IOC](./Spring%20IOC/), and [Dependency Injection](./Dependency%20Injection/) to build the core mental model.
3. Study [Annotations](./Annotations/), [Spring Bean Scope](./Spring%20Bean%20Scope/), [Configurations](./Configurations/), and [Spring Boot Starter](./Spring%20Boot%20Starter/) to understand how Spring Boot wires applications.
4. Learn the web layer through [Servlets](./Servlets/), [Spring MVC](./Spring%20MVC/), [JSP Files](./JSP%20Files/), and [HandleExceptionHandler](./HandleExceptionHandler/).
5. Build persistence knowledge with [Spring Data](./Spring%20Data/), [Spring Data JDBC](./Spring%20Data%20JDBC/), [Spring Data MongoDB](./Spring%20Data%20MongoDB/), [Hibernate](./Hibernate/), [Entity LifeCycle](./Entity%20LifeCycle/), [Mappings](./Mappings/), and [Transactions](./Transactions/).
6. Finish with production and cross-cutting topics: [Spring AOP](./Spring%20AOP/), [Spring Security](./Spring%20Security/), [Spring Security Anuj sir](./Spring%20Security%20Anuj%20sir/), [Spring Boot Actuator](./Spring%20Boot%20Actuator/), and [Zipkin & Micrometer](./Zipkin%20%26%20Micrometer/).

## Topic Index

| Folder | Focus Area | What You Will Find |
| --- | --- | --- |
| [Why Spring](./Why%20Spring/) | Spring foundation | Why Spring was created, problems with traditional Java EE, loose coupling, testability, and developer productivity. |
| [Terminology](./Terminology/) | Spring Boot vocabulary | A broad terminology guide covering core Spring Boot concepts from beginner to advanced level. |
| [Architecture](./Architecture/) | Application architecture | Spring Boot layered architecture, request flow, components, and how application parts connect. |
| [Annotations](./Annotations/) | Spring annotations | Metadata, annotation categories, how Spring reads annotations, and where common annotations are used. |
| [Spring IOC](./Spring%20IOC/) | IoC container | Inversion of Control, Spring container behavior, bean creation, lifecycle, and internal wiring. |
| [Dependency Injection](./Dependency%20Injection/) | DI fundamentals | Constructor injection, loose coupling, testing benefits, common mistakes, and Spring Boot DI flow. |
| [Spring Bean Scope](./Spring%20Bean%20Scope/) | Bean lifecycle | Singleton, prototype, web scopes, memory behavior, lifecycle impact, and scope selection. |
| [Configurations](./Configurations/) | App configuration | Spring Boot configuration, auto-configuration, properties, environment behavior, and debugging tips. |
| [Spring Boot Starter](./Spring%20Boot%20Starter/) | Dependency management | Starter dependencies, dependency simplification, version management, and how starters reduce setup effort. |
| [Embedded Servers](./Embedded%20Servers/) | Runtime server | Embedded Tomcat, Jetty, Undertow, traditional deployment comparison, and request handling basics. |
| [Servlets](./Servlets/) | Servlet foundation | Servlet concepts, servlet container flow, and how Spring MVC builds on the servlet model. |
| [Spring MVC](./Spring%20MVC/) | Web layer | MVC pattern, controllers, request lifecycle, REST APIs, view handling, and internal dispatch flow. |
| [JSP Files](./JSP%20Files/) | Server-side views | JSP usage in Spring Boot, dynamic HTML rendering, MVC integration, and practical view flow. |
| [HandleExceptionHandler](./HandleExceptionHandler/) | Exception flow | HandlerExceptionResolver, centralized exception handling, HTTP status mapping, and clean API responses. |
| [Spring Data](./Spring%20Data/) | Data access | Spring Data purpose, repository abstraction, boilerplate reduction, and database interaction patterns. |
| [Spring Data JDBC](./Spring%20Data%20JDBC/) | JDBC repositories | Spring Data JDBC design, persistence model, comparison with JPA, and when to use it. |
| [Spring Data MongoDB](./Spring%20Data%20MongoDB/) | NoSQL persistence | MongoDB basics, document persistence, repositories, annotations, and real-world usage. |
| [Hibernate](./Hibernate/) | ORM | Hibernate, JPA, entity mapping, SQL abstraction, persistence context, and database operations. |
| [Entity LifeCycle](./Entity%20LifeCycle/) | JPA entity states | Entity states, persistence context behavior, lifecycle transitions, and common persistence mistakes. |
| [Mappings](./Mappings/) | Entity relationships | JPA relationships, ownership, cascading, fetching, database behavior, and mapping best practices. |
| [Transactions](./Transactions/) | Data consistency | Transaction fundamentals, rollback behavior, propagation, isolation, and Spring transaction flow. |
| [Spring AOP](./Spring%20AOP/) | Cross-cutting concerns | Aspect-oriented programming, logging, security, transactions, advice types, and proxy-based execution. |
| [Spring Security](./Spring%20Security/) | Security basics | HTTP security configuration, authentication, authorization, password encoding, and security flow diagrams. |
| [Spring Security Anuj sir](./Spring%20Security%20Anuj%20sir/) | Security internals | Filter chain, AuthenticationManager, providers, SecurityContext, and detailed authentication architecture. |
| [Spring Boot Actuator](./Spring%20Boot%20Actuator/) | Monitoring | Health checks, metrics, management endpoints, production visibility, and secure actuator usage. |
| [Zipkin & Micrometer](./Zipkin%20%26%20Micrometer/) | Observability | Distributed tracing, Zipkin setup, Micrometer tracing, service latency tracking, and configuration snippets. |

## Repository Structure

```text
Spring-Boot/
|-- Annotations/
|-- Architecture/
|-- Configurations/
|-- Dependency Injection/
|-- Embedded Servers/
|-- Entity LifeCycle/
|-- HandleExceptionHandler/
|-- Hibernate/
|-- JSP Files/
|-- Mappings/
|-- Servlets/
|-- Spring AOP/
|-- Spring Bean Scope/
|-- Spring Boot Actuator/
|-- Spring Boot Starter/
|-- Spring Data/
|-- Spring Data JDBC/
|-- Spring Data MongoDB/
|-- Spring IOC/
|-- Spring MVC/
|-- Spring Security/
|-- Spring Security Anuj sir/
|-- Terminology/
|-- Transactions/
|-- Why Spring/
`-- Zipkin & Micrometer/
```

## How to Use This Repository

Clone the repository and open the topic folders directly:

```bash
git clone <repository-url>
cd Spring-Boot
```

Use the PDFs for concept learning and revision. Use the screenshots and diagrams as visual references for flows such as Spring Security, Spring AOP, mappings, and distributed tracing.

## Notes

This repository is a documentation and learning-notes repository. It is not currently structured as a runnable Spring Boot application with `pom.xml`, `build.gradle`, or source code modules.

The material is useful for:

- Spring Boot concept revision
- Backend interview preparation
- Understanding framework internals
- Building a strong mental model before implementing production projects
- Organizing future code examples by topic

## Future Improvements

- Add runnable sample projects for each topic.
- Add Java code examples alongside each PDF.
- Add interview questions and quick revision sheets.
- Add diagrams for common request, transaction, and security flows.
- Convert selected notes into Markdown for easier GitHub reading.
