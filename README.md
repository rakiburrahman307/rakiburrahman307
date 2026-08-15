![Header Banner](Black%20and%20%20White%20Gradient%20Personal%20LinkedIn%20Banner%20(2).png)

# Md. Rakibur Rahman

**Backend Engineer | Full Stack Engineer | Node.js & TypeScript Specialist**

Building scalable server-side systems, resilient API architectures, and maintainable web applications with a focus on performance, security, and production readiness.

---

### 👨‍💻 About

I am a Backend and Full Stack Engineer specializing in Node.js and TypeScript ecosystems, currently building production APIs at **Spark Tech Agency**. My core focus is designing structured server-side systems, efficient database schemas, secure authentication mechanisms, and reliable real-time communication channels.

I emphasize building software with clear boundaries, predictable state management, comprehensive runtime validation, and scalable database design—ensuring applications remain maintainable as system complexity grows.

---

### 💡 Engineering Principles

- **Clean Architecture & Separation of Concerns**: Decoupling HTTP handlers, business logic, and database access layers using service abstractions to ensure testability and maintenance clarity.
- **Defensive Validation & Type Safety**: Enforcing strict type boundaries with TypeScript and validating incoming requests at the API edge using Zod schema definitions.
- **Security-First Design**: Implementing robust authentication pipelines with short-lived JWTs, token rotation, password hashing, and granular Role-Based Access Control (RBAC).
- **Data Modeling & Query Optimization**: Designing normalized relational tables (PostgreSQL) and optimized document schemas (MongoDB), backed by Redis caching strategies for high-frequency operations.
- **Resilient Integration & Fail-Safe Workflows**: Handling third-party webhooks (e.g., Stripe, PayFast) idempotently, managing connection lifecycles, and centralizing error handling across all API routes.

---

### ⚙️ Backend Engineering

My backend work centers on core system infrastructure and API design, including:

- **RESTful & gRPC API Architecture**: Designing consistent API contracts, custom route middleware, gRPC protocol buffers, pagination, and standardized error payloads.
- **Authentication & Authorization**: Multi-tier auth pipelines using JWT access tokens, HTTP-only refresh cookies, role hierarchy enforcement, and session revocation.
- **Database Architecture**: PostgreSQL relational modeling, indexing, and transaction management; MongoDB schema validation, compound indexing, and aggregation pipelines.
- **Caching & Rate Limiting**: In-memory caching with Redis to reduce database read pressure and sliding-window rate limiting to prevent API abuse.
- **Payment & Subscription Infrastructure**: Integration with Stripe and PayFast APIs, secure webhook verification, event signature checking, and recurring billing handlers.
- **Real-Time Communication**: Bidirectional messaging and event streaming via Socket.IO, structured into dedicated server rooms and channel broadcast patterns.
- **Media & Storage Engineering**: Video transcribing (`fluent-ffmpeg`), asynchronous multi-part uploads, AWS S3 presigned transfers, and BunnyCDN CDN integration.
- **Reliability & Validation**: Asynchronous background task processing (BullMQ), centralized exception middleware, operational logs (Winston), and Zod request validation.

---

### 🛠️ Tech Stack

#### Languages & Core
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=node.js&logoColor=white)

#### Backend & Frameworks
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-0055E6?style=flat-square&logo=json&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-CC3534?style=flat-square&logo=redis&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

#### Databases & In-Memory Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

#### DevOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

#### Cloud & Third-Party Services
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white)

---

### 🚀 Featured Projects

#### 🧘 Yoga With Jen
**On-Demand Fitness Platform & Media Streaming Backend**
- **Focus**: High-volume video delivery, subscription engine, Apple receipt validation, and background queues.
- **Stack**: Node.js, Express.js, TypeScript, MongoDB, Redis, BullMQ, AWS S3, BunnyCDN, Stripe, Twilio
- **Engineering Highlights**:
  - Engineered scalable media storage and video streaming delivery integration using BunnyCDN and AWS S3 signed URLs.
  - Implemented multi-channel subscription lifecycle handling with Stripe webhook listeners and Apple receipt verification.
  - Offloaded async notification dispatches and background user sessions using BullMQ worker queues and Redis adapters.

#### ⚙️ ENG Backend System
**Enterprise Microservices & Media Processing Infrastructure**
- **Focus**: Multi-protocol API services (gRPC & REST), video encoding pipelines, S3 transfers, and email automation.
- **Stack**: Node.js, Express.js (v5), TypeScript, gRPC, Mongoose, Redis, BullMQ, AWS S3, Stripe, Fluent-FFmpeg, Brevo
- **Engineering Highlights**:
  - Architected dual REST and gRPC communication layers (`@grpc/grpc-js`, `protobufjs`) for high-speed inter-service requests.
  - Developed automated media processing pipelines utilizing `fluent-ffmpeg` for video encoding paired with AWS S3 presigned uploads.
  - Configured distributed background queues via BullMQ and Redis for event telemetry, email delivery (Brevo), and transactional billing.

#### 🧟 Creepy Backend
**Real-Time Event & Interactive Streaming Engine**
- **Focus**: High-throughput Socket.IO rooms, token security, rate limiting, and modular service patterns.
- **Stack**: Node.js, Express.js, TypeScript, MongoDB, Redis, Socket.IO, JWT, Zod
- **Engineering Highlights**:
  - Developed bidirectional event streaming channels utilizing Socket.IO room namespaces and Redis socket adapters.
  - Enforced defensive payload validation middleware with Zod alongside sliding-window rate limiting for protection against abuse.
  - Structured modular Controller-Service-Repository architecture ensuring clean separation of business logic and transport protocols.

#### 💳 Corniel Swanepoel Backend
**Multi-Gateway Recurring Billing & Subscription Infrastructure**
- **Focus**: Multi-gateway payment handling (PayFast & Stripe), job scheduling, telemetry dashboards, and Docker deployment.
- **Stack**: Node.js, Express.js, TypeScript, MongoDB, Redis, BullMQ, PayFast, Stripe, Resend, Docker
- **Engineering Highlights**:
  - Integrated dual payment processing gateways (PayFast & Stripe) with signature verification and idempotent webhook handlers.
  - Configured real-time queue monitoring dashboards using BullMQ and `@bull-board/express` for worker health metrics telemetry.
  - Containerized Redis cache and task queue infrastructure with Docker Compose for consistent local and production parity.

---

### 📊 GitHub Activity

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=rakiburrahman307&theme=react-dark&bg_color=0D1117&hide_border=true)

<p align="left">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=rakiburrahman307&show_icons=true&theme=dark&hide_border=true" alt="Rakibur's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=rakiburrahman307&layout=compact&theme=dark&hide_border=true" alt="Top Languages" width="48%" />
</p>

---

### 📬 Contact & Links

- **LinkedIn**: [linkedin.com/in/rakibur-rahman-14b33a2a4](https://www.linkedin.com/in/rakibur-rahman-14b33a2a4)
- **Email**: [rakiburrahman.dev@gmail.com](mailto:rakiburrahman.dev@gmail.com)
- **GitHub**: [github.com/rakiburrahman307](https://github.com/rakiburrahman307)
- **Facebook**: [facebook.com/rakiburrahman305](https://fb.com/rakiburrahman305)
- **Instagram**: [instagram.com/rakibur_rahman_305](https://instagram.com/rakibur_rahman_305)
