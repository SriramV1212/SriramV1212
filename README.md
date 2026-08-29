<div align="center">

<!-- <img src="./profile.jpg" width="180" style="border-radius: 50%;" alt="Sriram Vivek" /> -->

# Sriram Vivek

### Software Engineer · Backend & Distributed Systems

I build backend systems with a focus on reliability, distributed processing, and the things that happen when the happy path breaks.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sriram_Vivek-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/sriram-vivek/)
[![GitHub](https://img.shields.io/badge/GitHub-SriramV1212-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/SriramV1212)
[![Email](https://img.shields.io/badge/Email-sriramv1202%40gmail.com-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:sriramv1202@gmail.com)

</div>

---

## About Me

I'm a software engineer interested in backend engineering, distributed systems, and financial infrastructure.

A lot of the systems I build start with a simple question and then get more interesting once I begin asking what can go wrong.

What happens if a Kafka message is delivered twice?
What happens if a service crashes halfway through a request?
What happens when a downstream dependency becomes unavailable?
How do I know which service actually caused the latency spike?

Those questions have led me to work with event-driven architectures, gRPC microservices, idempotent processing, retries, circuit breakers, distributed tracing, dead-letter queues, and CI/CD.

Some things I've built:

* A Kafka-based payment processing backend with idempotent consumers, manual offset management, PostgreSQL state transitions, and failure recovery through a DLQ
* A distributed gRPC backend with server-side streaming, exponential backoff, circuit breaking, mutual TLS, and end-to-end observability
* A deployed RAG system with a custom MCP server, Qdrant, FastAPI, Next.js, Docker, Nginx, TLS, and automated deployments through GitHub Actions
* A retrieval pipeline during my software engineering internship at Galatea Associates for a financial-services AI proof of concept

I'm especially interested in going deeper into **reliable backend systems, concurrency, distributed-system failure modes, testing, and financial infrastructure**.

Outside of code, I'm usually watching football, playing games, experimenting with something in the kitchen, or listening to music while convincing myself that one more song will not turn into another hour.

---

## Technologies I Work With

### Languages

* **Python**: primary language for backend services, distributed systems, data pipelines, and AI applications
* **SQL**: PostgreSQL, MS SQL Server, relational data modeling, queries, and application persistence
* **TypeScript**: frontend and full-stack development with Next.js
* **Linux / Shell**: deployment, service management, debugging, and development workflows

### Backend & Distributed Systems

* **FastAPI**: REST APIs and backend services
* **Apache Kafka**: event-driven processing, partitioning, consumer groups, offset management, and DLQs
* **gRPC**: service-to-service communication, Protocol Buffers, and server-side streaming
* **PostgreSQL**: transactional application state and relational persistence
* **Redis**: caching and backend data access
* **MySQL**
* **MongoDB**
* **REST APIs**
* **Protocol Buffers**

### Reliability & Observability

* **OpenTelemetry**: distributed tracing and service instrumentation
* **Prometheus**: metrics collection
* **Grafana**: dashboards and operational visibility
* **Jaeger**: distributed trace inspection
* **Circuit Breakers**
* **Exponential Backoff & Retries**
* **Idempotent Processing**
* **Dead-Letter Queues**
* **Failure Simulation**

### Infrastructure & Delivery

* **Docker**
* **Docker Compose**
* **GitHub Actions**
* **Nginx**
* **systemd**
* **TLS / HTTPS**
* **Git**
* **Linux**
* **Vercel**

### AI & Retrieval Systems

* **Retrieval-Augmented Generation (RAG)**
* **Model Context Protocol (MCP)**
* **LangChain**
* **Qdrant**
* **PGVector**
* **OpenAI Embeddings**
* **LLM API Integration**
* **Retrieval Pipelines**
* **Chunking & Vector Search**

### Frontend

* **Next.js**
* **TypeScript**
* **React**

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [Event-Driven Payment Processing Backend](https://github.com/SriramV1212/Real-Time-Event-Driven-Payment-Processing-Backend)

An event-driven payment backend built to explore asynchronous processing, reliability, and failure handling with Kafka.

**Engineering problems explored**

* Idempotent event processing using unique event IDs
* Manual Kafka offset commits after successful database work
* PostgreSQL-backed payment state transitions
* Dead-letter queue for failed events
* Kafka partitioning and consumer-group parallelism
* Load testing with 1,000 simulated payment events
* Failure scenarios around duplicate processing and partial failures

**Built with**

`Python` · `FastAPI` · `Apache Kafka` · `PostgreSQL` · `Docker`

</td>

<td width="50%" valign="top">

### [Distributed Microservices Orchestration](https://github.com/SriramV1212/Distributed-Microservices-Orchestration-using-gRPC)

A 3-service distributed backend built to explore service communication, resilience, security, and observability.

**Engineering problems explored**

* gRPC service orchestration
* Server-side streaming
* Circuit breaking
* Exponential backoff and retries
* Mutual TLS between services
* Distributed tracing
* Metrics and dashboards
* Injected service failures

**Built with**

`Python` · `gRPC` · `Protocol Buffers` · `OpenTelemetry` · `Prometheus` · `Grafana` · `Jaeger` · `Docker`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Agentic RAG System with Custom MCP Server](https://github.com/SriramV1212/Agentic-RAG-System)

A full-stack retrieval system where a custom MCP server acts as the only interface between the application and its knowledge base.

**Engineering work**

* Indexed 3,100+ document chunks
* Built a custom MCP server exposing four retrieval tools
* Designed a markdown-aware chunking pipeline
* Self-hosted Qdrant vector database
* FastAPI backend
* Retrieval inspector built with Next.js
* Dockerized deployment
* Nginx reverse proxy with TLS
* Automated deployment through GitHub Actions

**Built with**

`Python` · `MCP` · `Qdrant` · `FastAPI` · `Next.js` · `TypeScript` · `Docker` · `Nginx` · `GitHub Actions`

</td>

<td width="50%" valign="top">

### Financial Services RAG Pipeline

Built during my software engineering internship at **Galatea Associates** for a financial-services AI proof of concept.

**What I worked on**

* Parsed text and tables from a 600-page optimizer specification
* Built a recursive document chunking pipeline
* Generated embeddings for semantic retrieval
* Stored and queried vectors through PGVector
* Exposed retrieval through a query service
* Used SQL to prepare portfolio positions, constraints, and trade data for downstream LLM prompts
* Documented the system and development workflow for the team

**Built with**

`Python` · `LangChain` · `PGVector` · `PostgreSQL` · `SQL` · `RAG`

</td>
</tr>
</table>

---

## What I'm Working On

Right now I'm deliberately going deeper rather than collecting more frameworks.

My current focus is on:

```text
Backend Engineering
├── Testing
│   ├── Unit tests
│   ├── Integration tests
│   └── End-to-end tests
│
├── Distributed Systems
│   ├── Idempotency
│   ├── Concurrency
│   ├── Message delivery semantics
│   ├── Partial failures
│   └── Recovery
│
├── Databases
│   ├── Transactions
│   ├── Isolation
│   ├── Locking
│   └── PostgreSQL internals
│
└── Financial Infrastructure
    ├── Payments
    ├── Ledgers
    ├── Reconciliation
    └── Correctness
```

I'm also spending more time understanding the fundamentals underneath the tools I use, especially operating systems, networking, databases, and concurrency.

---

## How I Like to Build

I care less about adding another framework to a README and more about understanding why a system behaves the way it does.

A few principles I try to follow:

```text
Build the happy path.
        ↓
Ask how it fails.
        ↓
Make the failure reproducible.
        ↓
Understand why it happened.
        ↓
Add the right safeguard.
        ↓
Test it.
        ↓
Measure it.
```

Still learning. Still breaking things. Ideally breaking them intentionally.

---

## GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=SriramV1212&show_icons=true&hide_border=true&rank_icon=github" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SriramV1212&layout=compact&hide_border=true&langs_count=8" />

</div>

---

## Education

**Stony Brook University**
M.S. Computer Science and Applied Mathematics, 2024–2026

**SSN College of Engineering**
B.E. Electrical and Electronics Engineering, 2020–2024

---

## Away From the Keyboard

⚽ **Football**
Huge football fan. If there's a good match on, there is a very good chance I'm watching it.

🎮 **Gaming**
One of my favorite ways to switch my brain off after staring at logs for too long.

🍳 **Cooking**
I enjoy trying new recipes and occasionally discovering that the recipe was right and I was the problem.

🎧 **Music**
Almost always playing in the background while I work, cook, or do pretty much anything else.

---

<div align="center">

### Let's Connect

I'm currently interested in **Software Engineering and Backend Engineering** opportunities, particularly teams working on distributed systems, financial infrastructure, developer infrastructure, or reliability-heavy backend problems.

If you're working on something interesting in that space, I'd be happy to connect.

<br/>

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/sriram-vivek/)
[![GitHub](https://img.shields.io/badge/Explore_my_projects-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/SriramV1212?tab=repositories)

</div>
