# Charles Agyeman — A-Dagaate

**Full-stack Java developer · Spring Boot · Security-minded**

I build and operate backend systems — auth flows, async pipelines, batch jobs, REST integrations — and I run them in production rather than only building them. A test-engineering background means the systems I ship come with the evidence that they work.

Currently studying for **ISTQB Security Test Engineer** (STE v1.0.1) and building a RAG-powered tutor to do it.

📝 **[Engineering notes →](https://a-dagaate.github.io/)** — what I find while building and operating the projects below. Every post is grounded in real code, real logs and measured numbers.

---

## What I'm working on

| Project | Stack | What it does |
|---|---|---|
| [pdf-classifier-app](https://github.com/A-Dagaate/pdf-classifier-app) — **[live ↗](https://ashtvkr.up.railway.app)** | Spring Boot · Python FastAPI · Docker · Postgres | Secure PDF upload + ML classification + RAG study sidecar (ChromaDB · Claude AI). 128 tests, CI on every push, deployed on Railway |
| OpenClaw | Python · Claude API | Automated chess game analyser with LLM commentary |
| RideGhana | React · Node | Ride-hailing UI prototype |

---

## Tech I reach for first

```
Backend:     Java 17 · Spring Boot 3 · Spring Data JPA · Spring Batch 5 · Spring Security
Data:        PostgreSQL · H2 · Hibernate · ChromaDB
Services:    REST · multipart uploads · FastAPI sidecar · RestTemplate clients
Frontend:    Thymeleaf server-side rendering · JavaScript · React (learning)
Security:    Spring Security filter chain · TOTP 2FA · CSRF · BCrypt · Snyk
Infra:       Docker multi-stage · Docker Compose · Railway · Maven · GitHub Actions
Testing:     JUnit 5 · Mockito · MockMvc · WireMock · Spring test slices
AI / ML:     Anthropic Claude API · sentence-transformers · RAG pipelines
```

---

## How I build

I ship features with the evidence that they work, and I go looking for the ways they do not.

- **Layered by cost** — 128 tests across Mockito units, `@DataJpaTest` and `@WebMvcTest` slices, `@SpringBootTest` smoke, and WireMock against a real HTTP wire. Cheapest test that can still fail for the right reason
- **Deterministic async** — `@Async` services tested by substituting a `SyncTaskExecutor`, so the proxy and interceptor stay real while execution becomes predictable. No sleeps, no polling
- **Operated, not just built** — deployed on Railway with Postgres, actuator health, profile-based config, and a Docker image CI rebuilds on every push
- **Debugged at the source** — I read framework code and attach a debugger to a running JVM when the logs are not enough
- **Dependency scanning** — Snyk bound to the Maven `verify` phase in CI; a high-severity finding fails the build

---
## Certifications
- CompTIA Security + CE
- ISTQB CTFL (foundation)
- ISTQB CTAL-TAE (advanced test automation engineer)
- Scrum Alliance Certified Scrum Master

## Certifications in progress

- ISTQB STE v1.0.1 (security test engineer)

- AWS Cloud Security Architecture

## Let's talk

`ze2@hotmail.com` · [GitHub](https://github.com/A-Dagaate) · [Engineering notes](https://a-dagaate.github.io/)

Open to full-stack and backend Java / Spring Boot roles.
