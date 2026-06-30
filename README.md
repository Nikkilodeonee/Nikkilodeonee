## [vulntrack](https://github.com/Nikkilodeonee/vulntrack) — Vulnerability Remediation API

[![Build and Test](https://github.com/Nikkilodeonee/vulntrack/actions/workflows/build.yml/badge.svg)](https://github.com/Nikkilodeonee/vulntrack/actions/workflows/build.yml)

Spring Boot backend for managing security findings across company assets — asset inventory, scan imports, remediation workflows, and audit history. Domain modeled on AppSec triage after vulnerability scans.

| | |
| :-- | :-- |
| **Architecture** | Multi-module Maven — `api` · `persistence` · `service` · `web` |
| **Security** | JWT authentication, RBAC — Admin · Security Analyst · Engineer · Viewer |
| **Domain** | Finding state machine, comments, accepted-risk handling, business-rule validation |
| **Risk & SLA** | CVSS × asset criticality scoring, SLA deadlines, hourly overdue escalation job |
| **Ops & quality** | PostgreSQL, Flyway, Docker Compose, OpenAPI, MockMvc + Testcontainers |

`Java 17` · `Spring Boot 3` · `Spring Security` · `JWT` · `PostgreSQL` · `Flyway` · `OpenAPI` · `Testcontainers` · `GitHub Actions`

---

## [spring-mvc-food-delivery](https://github.com/Nikkilodeonee/spring-mvc-food-delivery) — Food Ordering REST API

[![Build and Test](https://github.com/Nikkilodeonee/spring-mvc-food-delivery/actions/workflows/build.yml/badge.svg)](https://github.com/Nikkilodeonee/spring-mvc-food-delivery/actions/workflows/build.yml)

Multi-module backend for food browsing, cart management, and order placement — secured REST endpoints, transactional persistence, and production-style infrastructure.

| | |
| :-- | :-- |
| **Architecture** | `api` · `persistence` · `service` · `web` with OpenAPI-generated DTOs |
| **API & persistence** | JPA entities and repositories, transactional order and balance logic |
| **Reliability** | Request validation, centralized JSON error handling, optimistic locking on balances |
| **Ops & quality** | PostgreSQL, Flyway, Docker Compose, MockMvc + Testcontainers |

`Java 17` · `Spring Boot 3` · `Spring Security` · `JPA` · `PostgreSQL` · `Flyway` · `OpenAPI` · `Testcontainers` · `GitHub Actions`

---

## More repositories

### Backends

| Repository | Summary |
| :-- | :-- |
| [**spring-mvc-todo-rest**](https://github.com/Nikkilodeonee/spring-mvc-todo-rest) | REST todo API — CRUD, in-memory storage, validation, structured error responses |

### Testing & patterns

| Repository | Summary |
| :-- | :-- |
| [**unit-testing-login**](https://github.com/Nikkilodeonee/unit-testing-login) | Console auth service with account lockout — JUnit 5 and Mockito covering success, failure, and lockout paths |
| [**design-patterns-smart-home**](https://github.com/Nikkilodeonee/design-patterns-smart-home) | Smart home simulator — Strategy, Observer, Mediator, Factory, Command, Builder, Adapter |

### Systems & simulation

| Repository | Summary |
| :-- | :-- |
| [**page-replacement-algorithms**](https://github.com/Nikkilodeonee/page-replacement-algorithms) | OS memory management — FIFO, LRU, and optimal page replacement |
| [**os-scheduling-simulator**](https://github.com/Nikkilodeonee/os-scheduling-simulator) | CPU scheduling algorithms simulator |
| [**cats-and-mice**](https://github.com/Nikkilodeonee/cats-and-mice) | Agent-based simulation |
