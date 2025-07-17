# 📘 Learning Path for Junior .NET (C#) Software Engineer

You don’t need to become an expert in every topic listed below, but it’s crucial to understand:

- **What**: What the topic is and what problem it solves.
- **Why & When**: Why and when to use it—and when it doesn’t make sense.
- **How**: Theory is good, but hands-on practice (e.g., mini-projects) is strongly recommended.

> 💡 **Tip**: While studying prefer consistent progress over random volume. Bad example would be studying everyday for a week and then don't do nothing for a month.

> 💡 **Tip**: You don’t need to memorize everything—just know how to find the right information and apply it effectively.

### 📚 Learning Resources

- **Video**: `YouTube` (very good for quick intro/overviews, but also has extensive tutorials)
- **Documentation**: `Official Docs` ([.NET documentation](https://learn.microsoft.com/en-us/dotnet/), [.NET Learning Center](https://dotnet.microsoft.com/en-us/learn))
- **Community**: `Stack Overflow`, `Blog Posts`, `LinkedIn Dev Groups`
- **Courses**: `Pluralsight` (paid), `Udemy` (paid)  
- **Practice**: `LeetCode`, `HackerRank` or similar

---

## 🔧 **Git**

- **Basic Workflow**: `init`, `add`, `commit`, `status`, `log`
- **Repositories**: Creating, cloning, pushing
- **Branching & Merging**: Creating/switching branches, resolving merge conflicts
- **Collaboration**: Forking, pull requests, code reviews
- **Best Practices**: Small and focused commits, meaningful commit messages
- **Github**: a platform for version control and collaborative software development using Git

---

## 💻 **C#**

- **Basics**: Variables, data types, properties, methods, collections, control flow (conditional operators and loops)
- **OOP**: Classes, inheritance, interfaces, polymorphism, encapsulation
- **Useful**: LINQ, async/await, exception handling
- **Advanced**: Memory management (garbage collection/memory allocation), delegates, generics, lambda expressions, reflection

---

## 🌐 **.NET**

- **.NET Core vs .NET Framework**: Differences, pros/cons, LTS
- **ASP.NET Core Web API**: Building RESTful services
- **Middleware Pipeline**: Request handling, middleware order
- **Auth**: OAuth2, JWT
- **API Docs**: Swagger, OpenAPI
- **Error Handling**: Action results, model state, custom/global exceptions
- **Hosted Services**: `IHostedService`, `BackgroundService`
- **Dependency Injection**: Purpose, lifetimes, libraries
- **Configuration Management**: Manage application settings using `appsettings.json` and `environment variables`

---

## 🏗️ **Architecture & Code Structure**

- **Solution Structure**: Organizing multiple projects
- **Project Types**: Class Library, Console App, Web App, Test Project
- **Folder Structure**
- **Monolith** vs **Modular Monolith** vs **Microservices**
- **Layered Architecture (N-Tier)**
- **Onion / Clean Architecture**
- **CQRS** (Command Query Responsibility Segregation)

---

## 🧪 **Automated Testing**

- **Why it matters?**
- **Test Pyramid vs Testing Trophy**
- **Unit Testing**:
  - Frameworks: xUnit, NUnit
  - Tools: Moq, AutoFixture
  - Patterns: Avoid magic values, use AAA (Arrange-Act-Assert)
- **Integration Testing**:
  - [Microsoft Docs Guide](https://learn.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-9.0&pivots=xunit)
  - WireMock: popular open-source tool for API mock testing
- **Performance Testing**: JMeter, k6
- **Behaviour-Driven Development (BDD) Testing**: Natural language for writing automated tests
---

## 🌐 **REST API Principles**

- **Statelessness**
- **Client-Server Architecture**
- **Uniform Interface**
- **Resource-Based Structure**
- **JSON Representation**
- **Cacheability**
- **Idempotency**
- **HTTP Methods & Status Codes**
- **Error Handling & Security**
- **Best Practices**: Use nouns for endpoints, Hierarchical structure, JSON, Versioning, Filtering/Pagination/Sorting, Rate Limiting, Security, etc.

---

## 🍇 **GraphQL**

- **What it is and what problem it solves?**
- **Schema Definition**
  - Types
  - Relations
- **Resolvers**
- **Queries**
- **Mutations**
- **GraphQL Server**
- **Playground**
- **Extra**: Directives, Subscriptions, N+1 problem, Interfaces, Unions

---

## 🔄 Background Workers

- **Problems They Solve**: Service-to-service communication, event handling, cron jobs
- **RabbitMQ**: Message broker for asynchronous communication
- **Kafka**: Distributed event streaming platform
- **HangFire / Quartz.NET**: Libraries for scheduling and executing background jobs

---

## 🗄️ **Databases**

### 📊 **Relational (PostgreSQL)**

- **Basics**: Schemas, tables, columns, constraints
- **CRUD**: Insert, select, update, delete
- **Joins**: INNER, LEFT, UNION, CROSS
- **More**: Subqueries, functions, stored procedures, views, triggers
- **Performance**: Indexing, query optimization, partitioning, sharding, materialized views
- Advanced PostgreSQL **Data Types** (JSON/JSONB/Arrays)

### 📂 **NoSQL (MongoDB)**

- **Concepts**: Document DB vs SQL DB
- **Basics**: Collections, documents, BSON, CRUD operations, aggregations
- **Performance**: Indexing, query optimization

---

## 🧭 **Best Practices**

- **Consistent naming & formatting**
- **Avoid hard-coding**
- **KISS principle**: Keep It Simple, Stupid
- **YAGNI principle**: You Aren’t Gonna Need It
- **SOLID Principles**:
  - **Single Responsibility**
  - Open/Closed
  - Liskov Substitution
  - Interface Segregation
  - Dependency Inversion

---

## 📦 **Containers**

### 🧱 **Container Basics**

- **What is a container?**
- **Container vs Virtual Machine**
- **Container lifecycle**

### 🐳 **Docker**

- **Docker architecture**
- **Basic commands**
- **Dockerfile**
- **Networking & volumes**

### 🧩 **Docker Compose**

- **What it is and when to use it**
- **Commands & file structure**

---

## 🔁 **CI/CD**

- **CI**: Continuous Integration
- **CD**: Continuous Delivery
- **GitHub Actions (GHA)**:
  - Runner, Workflow, Event, Job, Step, Action, Secrets, Artifact

---

## 📈 **Monitoring & Logging**

### 📊 **Monitoring**

- **What is monitoring & alerting?**
- **Tools**:
  - OpenTelemetry
  - Grafana
  - Prometheus

### 📋 **Logging**

- **What is logging?**
- **Tools**:
  - Serilog
  - ELK Stack (Elasticsearch, Logstash, Kibana)
  - Grafana Loki 
  
