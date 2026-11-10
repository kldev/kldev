# Krzysztof Łopuch

**Senior Developer & Architect** · building on .NET 10, Java, Kotlin

<p>
  <img alt=".NET 10" src="https://img.shields.io/badge/.NET%2010-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img alt="C# 14" src="https://img.shields.io/badge/C%23%2014-239120?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAxLjUgMjEuMSA2Ljc1djEwLjVMMTIgMjIuNSAyLjkgMTcuMjVWNi43NXoiLz48dGV4dCB4PSIxMiIgeT0iMTYiIGZvbnQtZmFtaWx5PSJBcmlhbCxzYW5zLXNlcmlmIiBmb250LXNpemU9IjkuNSIgZm9udC13ZWlnaHQ9IjcwMCIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZmlsbD0iIzIzOTEyMCI%2BQyM8L3RleHQ%2BPC9zdmc%2B" />
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
  <img alt="PostgreSQL 18" src="https://img.shields.io/badge/PostgreSQL%2018-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

I help businesses solve real problems with modern web technologies: backend systems, architecture and legacy
modernization, from the code all the way to the business decisions behind it.

## About me

For over 18 years I've been designing and building software that companies rely on every day: from VoIP and unified
communications platforms, through HR, recruitment and payroll systems, to ERP modernization.

I've worked as a sole developer in a startup, a full stack engineer, a team lead and an architect, so I understand both
the code and the business behind it. Great products are built by strong teams, not individuals: I work closely with
specialists and the business to deliver reliable systems, and I've built and led teams that ship.

## What I do

- **Scalable backend systems**: C#, .NET, Java, Spring Boot, Kotlin
- **Databases and performance**: PostgreSQL, SQL Server, MySQL, Oracle
- **Modern architectures**: microservices, CQRS, DDD and event-driven systems (RabbitMQ, MassTransit, Kafka)
- **Containers and GitOps**: Docker, Kubernetes, Helm, Argo CD, Flux
- **Frontend and mobile**: React, TypeScript, Vue, Flutter
- **Legacy modernization**: step by step, without stopping the business (strangler pattern, incremental migration)
- **Modernizing** I can work on a large legacy ERP and rewrite into .NET 10 event-driven services running on Kubernetes.

## Tools
- AI-assisted development (Claude Code, custom MCP servers).
- JetBrains **jd** (cli/CI tool)

## This account

This account is for side projects:

- [**shipment.app.ef**](https://github.com/kldev/shipment.app.ef): a delivery operator's back office (Glovo-style). A
  .NET 10 modular monolith with DDD bounded contexts, EF Core on PostgreSQL, an outbox and Wolverine runner, and the
  Blazor UI and REST API in one host.
- [**own.sso.app**](https://github.com/kldev/own.sso.app): Great SSO, one sign-in for a team's applications through
  GitHub, Google or a work Microsoft account, with no passwords and no registration. Its own narrow OpenID Connect
  provider (code + PKCE, rotating refresh tokens), a Blazor admin panel, a REST API and an MCP server for Claude Code;
  .NET 10, EF Core on PostgreSQL 18 with Liquibase, RabbitMQ and Wolverine.
- [**fitness.app.ef**](https://github.com/kldev/fitness.app.ef): the back office of gyms and fitness clubs: members,
  versioned price lists and passes, a front desk with QR check-ins, classes with bookings and a waitlist, and a member
  portal. A multi-tenant .NET 10 modular monolith with Blazor Server, EF Core on PostgreSQL 18 and an MCP server.
- [**delivery.platform.app**](https://github.com/kldev/delivery.platform.app): an event-driven microservices platform
  for deliveries, payments, driver settlements and financial reconciliation. Independent services in Kotlin (JVM 25,
  Spring Boot, Quarkus) and C# (ASP.NET Core) cooperate through REST and Apache Kafka events, each with its own
  PostgreSQL database, behind a YARP gateway and a Blazor operations portal.

- [**crm.kotlin.db.app**](https://github.com/kldev/crm.kotlin.db.app): a small CRM (clients, teams, projects with
  stages and comments) and a service desk with one event stream per ticket. Kotlin + Spring Boot 4 for the API and
  identity, all data logic in plain T-SQL procedures on SQL Server 2025, no ORM; a React front end (TanStack + HeroUI).
- [**fixer.ef.app**](https://github.com/kldev/fixer.ef.app): WeFix, maintenance requests for residential buildings:
  residents report, company admins assign, technicians fix. .NET 10 Minimal API with vertical slices and a DDD status
  machine, EF Core 10 on PostgreSQL 18, JWT, Angular 22 + Clarity.
- [**marten.task.event.store**](https://github.com/kldev/marten.task.event.store): Halcyon, an internal service desk
  built on an event store: requests to IT, legal, HR and other teams in one pool, deadlines by priority, attachments in
  S3 and every change as an event in the ticket's stream. .NET 10, Blazor Server, Marten.
- [**server.swarm.setup**](https://github.com/kldev/server.swarm.setup): one Ubuntu server running the demo
  applications above on a one-node Docker Swarm, each at its own HTTPS address, built from its repository on the server,
  with a local image registry and Mailpit.
