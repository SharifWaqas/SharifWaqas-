<p align="center">
  <img src="./assets/Banner.svg" width="100%" />
</p>

<br>



# Building software that scales.

Focused on backend engineering, distributed systems, and AI-powered applications.

I'm Sharif Waqas, a Computer Science & Mathematics student building production-ready backend systems and AI-powered applications.

## About

I enjoy building software that solves practical problems.

Whether it's designing authentication systems, processing thousands of log events, or building AI-powered applications, I'm most interested in creating systems that remain simple, reliable, and maintainable as they grow.



## Engineering Philosophy

> **Reliability before cleverness.**

> Simple systems scale.

> Measure before optimizing.

> Build for maintainability.

> Learn continuously by building.

## 🚀 Featured Systems
Production-ready systems focused on backend engineering, distributed architecture, and AI-powered applications.

## 🛡️ SafeStep

> AI-powered digital safety platform designed to help older adults recognize online scams, understand suspicious content, and confidently navigate the digital world.

SafeStep combines modern AI with accessible design to analyze screenshots, emails, text messages, and websites, providing clear explanations, risk assessments, and actionable guidance instead of confusing technical jargon.

### 🚧 Project Status

**Overall Progress**

```
████████░░ 80%
```

| Component | Progress |
|-----------|----------|
| Backend Architecture | ██████████ 100% |
| Authentication & Sessions | ██████████ 100% |
| Database Design | ██████████ 100% |
| File Upload Service | ██████████ 100% |
| Repository & Service Layer | ██████████ 100% |
| AI Analysis Engine | ███████░░░ 70% |
| Frontend | ████░░░░░░ 40% |
| Deployment | ██░░░░░░░░ 20% |
| Testing | ███░░░░░░░ 30% |

### ✨ Engineering Highlights

- AI-powered screenshot analysis
- JWT authentication with secure refresh token sessions
- Secure file upload and storage pipeline
- Modular Repository & Service Layer architecture
- PostgreSQL with SQLAlchemy ORM
- OpenAI Vision integration
- Risk scoring and personalized guidance generation
- Accessibility-focused design for older adults

### 🛠️ Tech Stack

`Python` • `FastAPI` • `PostgreSQL` • `SQLAlchemy` • `Docker` • `OpenAI API`

### 🎯 Why I Built It

SafeStep was inspired by the growing number of online scams targeting older adults. Rather than simply detecting scams, the platform focuses on helping users understand **why** something is suspicious, improving digital literacy while providing reassurance and practical guidance.

🔗 **[Explore the Repository →](https://github.com/SharifWaqas/safestep)**


## 📊 Log Analytics Engine

> High-throughput backend system designed to ingest, process, and analyze large volumes of application logs using asynchronous workers, batch processing, and a scalable service-oriented architecture.

Built to explore production backend patterns, this system focuses on throughput, reliability, and maintainability. Rather than simply storing logs, it demonstrates how modern backend services can efficiently process high-volume data while exposing analytics through clean APIs.

### 📈 Engineering Results

| Metric | Result |
|---------|--------|
| Peak Throughput | **921.43 logs/sec** |
| Baseline Throughput | **46.63 logs/sec** |
| Performance Improvement | **~20×** |
| Processing Model | **Queue-Based + Background Workers** |
| Batch Processing | **Enabled** |
| Deployment | **Docker** |

### ✨ Engineering Highlights

• Queue-based ingestion pipeline with background workers
• Batch database writes for higher throughput
• Shared in-memory buffering architecture
• Retry handling for failed database writes
• Cursor-based pagination for analytics endpoints
• REST analytics API
• Modular layered backend architecture
• Containerized deployment with Docker

### 🛠️ Tech Stack

`Python` • `FastAPI` • `PostgreSQL` • `SQLAlchemy` • `Docker` • `Threading`

### 🧠 Key Engineering Decisions

• Decoupled request handling from database writes using a shared queue
• Used batch insertion to reduce database transaction overhead
• Offloaded ingestion processing to a threaded background worker
• Benchmarked multiple ingestion strategies to quantify performance improvements
• Exposed analytics through dedicated REST endpoints

### 🎯 Why I Built It

This project was built to explore production backend engineering concepts beyond traditional CRUD applications.

The goal was to understand how modern ingestion systems improve throughput through asynchronous processing, batching, concurrency, and pipeline design while exposing operational analytics through clean APIs.

🔗 **[Explore the Repository →](https://github.com/SharifWaqas/log-analytics-backend)**
