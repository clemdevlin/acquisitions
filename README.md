<div align="center">
  <br />
    <a href="https://youtu.be/H5FAxTBuNM8" target="_blank">
      <img src="public/readme/hero.webp" alt="Project Banner">
    </a>
  <br />

  <div>
<img src="https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/-Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/-Neon%20Postgres-2496ED?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/-Drizzle%20ORM-FFDF00?style=for-the-badge&logo=drizzle&logoColor=black"/>

  </div>

  <h3 align="center">Build a Scalable Production Ready API</h3>

   <div align="center">
     Build this project step by step with our detailed tutorial on <a href="https://www.youtube.com/watch?v=XUkNR-JfHwo" target="_blank"><b>JavaScript Mastery</b></a> YouTube. Join the JSM family!
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔗 [Assets](#links)
6. 🚀 [More](#more)

## 🚨 Tutorial

This repository contains the code corresponding to an in-depth tutorial available on our YouTube channel, <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a>.

If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects like these step-by-step in a beginner-friendly manner!

<a href="https://youtu.be/H5FAxTBuNM8" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" /></a>

## <a name="introduction">✨ Introduction</a>

Master DevOps by taking an API from code to production with Docker, Kubernetes, Git & GitHub, Warp, and CI/CD Actions! Build a scalable backend using Node.js, Express.js, Neon Postgres, and Drizzle ORM, while testing ensures reliability at every step. Learn to containerize services, orchestrate deployments, automate pipelines, and monitor applications—perfect for developers who want hands-on experience shipping robust, production-ready systems.

If you're getting started and need assistance or face any bugs, join our active Discord community with over **50k+** members. It's a place where people help each other out.

<a href="https://discord.com/invite/n6EdbFJ" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/618f4872-1e10-42da-8213-1d69e486d02e" /></a>

## <a name="tech-stack">⚙️ Tech Stack</a>

- **[Arcjet](https://jsm.dev/dops25-arcjet)** is a developer-first security layer that enables you to protect your applications with minimal code. It offers features like bot protection, rate limiting, email validation, and defense against common attacks. Arcjet's SDK integrates seamlessly into your application, providing real-time security decisions without the need for additional infrastructure.

- **[Docker](https://www.docker.com/)** is a leading containerization platform that allows you to package applications along with all their dependencies into portable, lightweight containers. This ensures consistent behavior across different environments, simplifies deployment, and makes scaling applications more efficient.

- **[Kubernetes](https://kubernetes.io/)** is an open-source orchestration system designed to automate the deployment, scaling, and management of containerized applications. It handles tasks like load balancing, self-healing, and rolling updates, making it essential for running applications reliably at scale.

- **[Warp](https://jsm.dev/dops25-warp)** is a modern terminal built in Rust, optimized for developer productivity. It offers features like AI-assisted commands, easy collaboration, command history search, and a faster, more intuitive interface compared to traditional terminals.

- **[Node.js](https://nodejs.org/)** is a fast, event-driven JavaScript runtime built on Chrome’s V8 engine. It enables developers to build scalable, high-performance server-side applications and APIs using JavaScript on both the client and server side.

- **[Express.js](https://expressjs.com/)** is a minimal and flexible Node.js web application framework. It provides robust features for building APIs and server-side applications, including routing, middleware support, and simplified request/response handling.

- **[Neon Postgres](https://jsm.dev/dops25-neon)** is a fully managed, serverless Postgres database designed for modern cloud applications. It offers autoscaling, branching for development workflows, and simplifies database management without compromising performance.

- **[Drizzle ORM](https://orm.drizzle.team/)** is a TypeScript-first, lightweight ORM for SQL databases. It provides type safety, schema migrations, and an intuitive API for building reliable and maintainable database queries.

- **[Zod](https://zod.dev/)** is a TypeScript-first schema validation library that ensures runtime type safety. It helps developers validate data structures, enforce strict type checks, and catch errors early in the development process.

## <a name="features">🔋 Features</a>

👉 **Absolute Imports**: Clean import paths using `#` prefix aliases for more organized and readable code.

👉 **Business Listings**: Create, update, delete, and browse business listings efficiently.

👉 **Database Integration**: Integrate PostgreSQL with Drizzle ORM, including migrations for schema management.

👉 **Deal Management**: Create deals on listings, accept or reject offers, and track deal status.

👉 **Docker Support**: Full containerization with development and production environments for consistent deployment.

👉 **ESLint + Prettier**: Enforce code linting and formatting rules for cleaner, consistent code.

👉 **Health Monitoring**: Endpoint to check system health and monitor overall application status.

👉 **Hot Reload**: Development server automatically restarts on file changes for faster iteration.

👉 **Jest Testing**: Framework for unit and integration testing with SuperTest for HTTP endpoints.

👉 **Request Validation**: Validate all API inputs using Zod schemas to ensure data integrity.

👉 **Role-Based Access Control**: Implement admin and user roles with permission middleware for secure operations.

👉 **Structured Logging**: Winston-based logging throughout the application for better monitoring and debugging.

👉 **User Authentication & Authorization**: JWT-based authentication supporting signup, signin, and signout workflows.

👉 **User Management**: CRUD operations for user accounts, enabling easy administration and management.

And many more, including code architecture and reusability.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/acquisitions.git
cd acquisitions
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
# Server Configuration
PORT=3000
NODE_ENV=development
LOG_LEVEL=info

# Database Configuration
DATABASE_URL=

# Arcjet
ARCJET_KEY=
```

Replace the placeholder values with your real credentials. You can get these by signing up at: [**Arcjet**](https://jsm.dev/dops25-arcjet), [**Neon**](https://jsm.dev/dops25-neon).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## <a name="links">🔗 Assets</a>

Assets and snippets used in the project can be found in the **[video kit](https://jsm.dev/dops25-kit)**.

<details>
  <summary>Codebase Architect Explainer</summary>

    An AI prompt that studies any codebase and produces a clear, structured explanation of its architecture and how it works
    You are an expert software architect and senior developer. Your task is to deeply study the entire provided codebase and then produce a clear, structured explanation of its architecture and how it works.
    When analyzing the codebase, follow these steps:

    1. **Identify the Big Picture**

      - What type of project is this (web app, API, CLI tool, etc.)?
      - What problem does it solve?

    2. **Core Architecture**

      - Explain the high-level structure (monolith, microservices, layered, event-driven, etc.).
      - Describe how the major parts of the system are organized (folders, modules, services).

    3. **Key Components**

      - Break down each major component/module.
      - Explain its purpose and how it fits into the system.

    4. **Data Flow & Communication**

      - How does data move through the system?
      - Which functions, APIs, or services interact with each other and how?

    5. **Tech Stack & Dependencies**

      - What frameworks, libraries, and databases are used?
      - Why are they important in this architecture?

    6. **Execution Flow**

      - Walk through a typical request or workflow step by step (e.g., "User clicks button → API call → DB query → response returned").

    7. **Strengths & Tradeoffs**

      - What are the advantages of this design?
      - Any notable limitations or things to watch out for?

    8. **Final Summary**

      - Provide a concise explanation I could give to a teammate in 2–3 sentences to understand the whole system quickly.

    Write the explanation in a friendly but professional tone, with clear sections, diagrams/ASCII flowcharts if useful, and examples of request/response flows when possible.

</details>

<details>
  <summary>Dockerization Prompt</summary>

You are a senior DevOps engineer. Your task is to dockerize my application that uses Neon Database. The setup must work differently for development and production:

1. **Development Environment (Local):**
   - Use **Neon Local** via Docker.
   - Configure `docker-compose.yml` to run the Neon Local proxy alongside my application. Learn more about Neon Local here: <https://neon.com/docs/local/neon-local>
   - The application should connect to Postgres at `postgres://user:password@neon-local:5432/dbname` (or equivalent `localhost` inside the compose network).
   - Neon Local should automatically create ephemeral branches for dev and testing.
   - Ensure `.env.development` or equivalent config points to this Neon Local connection string.
2. **Production Environment:**
   - Use the actual **Neon Cloud Database URL** (e.g., `DATABASE_URL=postgres://...neon.tech...`).
   - No Neon Local proxy should be used in production.
   - Ensure secrets and URLs are injected via environment variables, not hardcoded.
   - Create a separate `.env.production` for production environments
3. **General Requirements:**
   - Write a `Dockerfile` for the app.
   - Write a `docker-compose.dev.yml` that runs both the app and Neon Local for development.
   - Write a `docker-compose.prod.yml` that runs both the app and serverless neondb for production.
   - Show how environment variables (`DATABASE_URL`) switch between dev and prod.
   - Provide documentation (in `README.md` style) for how a developer should start the app locally with Neon Local, and how the same app deploys with production Neon DB.

</details>

<a href="https://jsm.dev/dops25-kit" target="_blank">
  <img src="public/readme/videokit.webp" alt="Video Kit Banner">
</a>

## <a name="more">🚀 More</a>

**Advance your skills with Next.js Pro Course**

Enjoyed creating this project? Dive deeper into our PRO courses for a richer learning adventure. They're packed with
detailed explanations, cool features, and exercises to boost your skills. Give it a go!

<a href="https://jsm.dev/dops25-jsm" target="_blank">
  <img src="public/readme/jsmpro.webp" alt="Project Banner">
</a>
