<div align="center">
  <img src="assets/quiet-altitude.png" width="100%" alt="" />

  <br />
  <br />

  <samp>
    K A R A N &nbsp; L A L W A N I<br />
    BACKEND SYSTEMS &nbsp;·&nbsp; DISTRIBUTED DESIGN &nbsp;·&nbsp; APPLIED AI
  </samp>

  <br />
  <br />

  <a href="https://github.com/KaranLalwani-dev">github</a>
  &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/karan-lalwani-profile">linkedin</a>
  &nbsp;·&nbsp;
  <a href="mailto:karanlalwani2086@gmail.com">email</a>
</div>

<br />

> Build quietly. Measure carefully. Keep the system clear.

I am a Computer Science student specialising in Cybersecurity at Manipal Institute of Technology, Bengaluru. I work on backend services and AI-enabled platforms - the less visible parts of a product where routing, data access, retries, and service boundaries decide whether it stays dependable.

---

## The line I keep clear

I am interested in systems that have to coordinate under real constraints: distributed workflows, reliable state changes, useful AI integrations, and performance work that can be measured rather than assumed.

The question behind most of my work is simple: **when the load rises or a dependency fails, does the path through the system still make sense?**

---

## Systems in focus

### Design Forge

`AI-powered distributed code generation platform` &nbsp; `Nov 2025 - Jul 2026`

A platform that generates frontend web applications from natural-language prompts. I designed the infrastructure behind the generated result:

- Built microservices with Spring Boot, Spring AI, Kafka, PostgreSQL, Redis, MinIO, Docker, Kubernetes, and Google Kubernetes Engine.
- Built a custom reverse proxy for wildcard subdomain routing, sending ephemeral generated apps to their internal services.
- Designed a choreography-based Saga flow over Kafka to persist generated files with failure handling and idempotent retries.
- Used LLM tool calling to reduce prompt context and improve code-generation latency.
- Wrote JUnit tests for core service logic and validated inter-service APIs with Postman.

### Unicircle

`Campus activity discovery platform` &nbsp; `Mar 2026 - May 2026`

A platform for students to create activity-based groups, request membership, and find people through focused filters.

- Designed a 3NF relational schema and dynamic filtering by keyword, tags, and creator profile.
- Secured endpoints with stateless JWT authentication.
- Investigated an N+1 query path that caused more than 40 database round-trips per request; reduced it to 6 through batching and eager loading while keeping database-level pagination.
- Load-tested from 5 to 1,000 virtual users. At 400 concurrent users, the fix reduced p95 latency from **2.02s to 39ms**.

---

## Instruments, not decoration

```text
language         Java

backend          Spring Boot · Spring AI · PostgreSQL · Redis · Kafka
AI systems       Tool Calling · RAG · Vector Stores · OpenRouter
infrastructure   Docker · Kubernetes · Google Cloud · MinIO
workflow         JUnit · Postman · Git · Maven · Netlify · Render
```

---

## Ground

```text
B.Tech, Computer Science - Cybersecurity
Manipal Institute of Technology, Bengaluru
Expected May 2028 · GPA 8.54
```

The foundation underneath my work: operating systems, database systems, computer networks, data structures and algorithms, and object-oriented programming.

<br />

<div align="center">
  <sub>Less noise. Better boundaries. Systems that hold their shape.</sub>
</div>
