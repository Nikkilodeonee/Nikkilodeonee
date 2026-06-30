# Roman Sushkin

Backend repositories built with Java and Spring Boot. Most projects here explore real backend problems — business workflows, authentication, persistence, validation, scheduled jobs, and testing — rather than isolated framework demos.

Every larger repo is a step toward production-shaped code: multi-module layout, PostgreSQL, Flyway, Docker, and CI-tested integrations. Particular interest in backend architecture and security-oriented applications.

`Java 17` · `Spring Boot` · `Spring Security` · `PostgreSQL` · `Docker` · `JUnit` · `Testcontainers`

---

## Featured projects

### [vulntrack](https://github.com/Nikkilodeonee/vulntrack) — Vulnerability Remediation API

[![Build and Test](https://github.com/Nikkilodeonee/vulntrack/actions/workflows/build.yml/badge.svg)](https://github.com/Nikkilodeonee/vulntrack/actions/workflows/build.yml)

Flagship project — an AppSec-inspired backend for managing vulnerabilities discovered during security scans. Models the full lifecycle of security findings across company assets: import, triage, remediation, risk acceptance, and audit history.

Built around meaningful domain logic — multiple user roles, state transitions, scheduled jobs, and business-rule validation beyond basic CRUD.

| | |
| :-- | :-- |
| **Architecture** | Multi-module Maven — `api` · `persistence` · `service` · `web` |
| **Security** | JWT authentication, RBAC — Admin · Security Analyst · Engineer · Viewer |
| **Domain** | Finding workflow, comments, accepted-risk handling, audit history |
| **Risk & SLA** | CVSS-based scoring, SLA deadlines, hourly overdue escalation job |
| **Ops & quality** | PostgreSQL, Flyway, Docker Compose, OpenAPI, MockMvc + Testcontainers |

---

### [spring-mvc-food-delivery](https://github.com/Nikkilodeonee/spring-mvc-food-delivery) — Food Delivery REST API

[![Build and Test](https://github.com/Nikkilodeonee/spring-mvc-food-delivery/actions/workflows/build.yml/badge.svg)](https://github.com/Nikkilodeonee/spring-mvc-food-delivery/actions/workflows/build.yml)

Multi-module ordering backend — menus, carts, balances, and order placement. Layered architecture with secured REST endpoints, transactional persistence, database migrations, and integration testing.

| | |
| :-- | :-- |
| **Architecture** | `api` · `persistence` · `service` · `web` with OpenAPI-generated DTOs |
| **API & persistence** | JPA entities, transactional order and balance logic |
| **Reliability** | Request validation, centralized error handling, optimistic locking on balances |
| **Ops & quality** | PostgreSQL, Flyway, Docker Compose, MockMvc + Testcontainers |

---

## More repositories

### Backends

| Repository | Summary |
| :-- | :-- |
| [**spring-mvc-todo-rest**](https://github.com/Nikkilodeonee/spring-mvc-todo-rest) | REST API — CRUD, validation, exception handling, structured error responses |

### Testing & patterns

| Repository | Summary |
| :-- | :-- |
| [**unit-testing-login**](https://github.com/Nikkilodeonee/unit-testing-login) | Console auth with account lockout — JUnit 5 and Mockito covering success, failure, and lockout paths |
| [**design-patterns-smart-home**](https://github.com/Nikkilodeonee/design-patterns-smart-home) | Smart home simulator — Strategy, Observer, Mediator, Factory, Command, Builder, Adapter |

### Systems & simulation

| Repository | Summary |
| :-- | :-- |
| [**page-replacement-algorithms**](https://github.com/Nikkilodeonee/page-replacement-algorithms) | OS memory management — FIFO, LRU, and optimal page replacement |
| [**os-scheduling-simulator**](https://github.com/Nikkilodeonee/os-scheduling-simulator) | CPU scheduling algorithms simulator |
| [**cats-and-mice**](https://github.com/Nikkilodeonee/cats-and-mice) | Agent-based simulation |

---

## Technologies

| | |
| :-- | :-- |
| **Language** | Java 17 |
| **Backend** | Spring Boot · Spring MVC · Spring Security · Spring Data JPA · REST |
| **Database** | PostgreSQL · H2 · Flyway |
| **Testing** | JUnit 5 · Mockito · MockMvc · Testcontainers |
| **Tools** | Maven · Docker · GitHub Actions · Git |

---

Feedback and issues are welcome on any repository.
