# Nikkilodeonee

Welcome!

This profile is where I document my progress as a Java backend developer. Most repositories here are built to explore real backend problems rather than isolated framework features.

Instead of simple CRUD applications, I enjoy implementing business workflows, authentication and authorization, persistence, validation, scheduled jobs, and automated testing. Every larger project is an opportunity to learn another part of the backend ecosystem and make the codebase feel a little closer to something that could exist in production.

My current stack revolves around Java, Spring Boot, PostgreSQL, Spring Security, Docker, and automated testing, with a particular interest in backend architecture and security-oriented applications.

---

## Featured Projects

### 🔒 VulnTrack — Vulnerability Remediation API

My flagship project.

VulnTrack is an AppSec-inspired backend for managing vulnerabilities discovered during security scans. It models the lifecycle of security findings across company assets—from import and triage to remediation, risk acceptance, and audit history.

The project was an opportunity to work on more than REST endpoints. I wanted a backend with meaningful business rules, multiple user roles, state transitions, scheduled jobs, and realistic domain logic.

Highlights:

- Multi-module Spring Boot architecture
- JWT authentication and role-based access control
- Finding workflow with business-rule validation
- CVSS-based risk scoring and SLA management
- PostgreSQL with Flyway migrations
- Docker Compose development environment
- OpenAPI documentation
- Integration tests using MockMvc and Testcontainers
- GitHub Actions CI

**Repository:** https://github.com/Nikkilodeonee/vulntrack

---

### 🍔 Food Delivery REST API

Originally developed during Java backend training and later expanded independently.

The project models a typical ordering system with menus, carts, balances, and order placement. I used it to practice layered architecture, transactional service logic, persistence, security, database migrations, and testing.

Highlights:

- Multi-module architecture
- Spring Security
- JPA/Hibernate
- PostgreSQL + Flyway
- OpenAPI-generated DTOs
- Docker Compose
- Integration tests with MockMvc and Testcontainers
- GitHub Actions

**Repository:** https://github.com/Nikkilodeonee/spring-mvc-food-delivery

---

## Other Projects

### Backend

### spring-mvc-todo-rest

A smaller REST API focused on clean controller design, validation, exception handling, and CRUD operations. Built to reinforce Spring MVC fundamentals.

---

### Testing

### unit-testing-login

A console authentication service created specifically to practice unit testing.

The project covers login scenarios, failed authentication attempts, account lockout rules, and mocking with JUnit 5 and Mockito.

---

### Design Patterns

### design-patterns-smart-home

A collection of classic object-oriented design patterns implemented in a shared smart home simulation.

Patterns include Strategy, Observer, Factory, Builder, Adapter, Mediator, Command, and others.

---

### Computer Science

These repositories come from university coursework and personal experiments.

- Page replacement algorithms (FIFO, LRU, Optimal)
- CPU scheduling simulator
- Cats and Mice agent simulation

---

## Technologies

**Language**

- Java 17

**Backend**

- Spring Boot
- Spring MVC
- Spring Security
- Spring Data JPA
- Hibernate
- REST APIs

**Database**

- PostgreSQL
- H2
- Flyway

**Testing**

- JUnit 5
- Mockito
- MockMvc
- Testcontainers

**Tools**

- Maven
- Docker
- GitHub Actions
- Git

---

Thanks for stopping by. If you're interested in any of the projects or have feedback, feel free to open an issue or get in touch.
