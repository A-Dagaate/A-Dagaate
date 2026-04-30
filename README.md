# Charles Agyeman — A-Dagaate

**Lead SDET · Security-minded · Building things that work under pressure**

I test systems at the seams — auth flows, async pipelines, PDF classifiers, RAG endpoints. When I find a gap I patch it, document it, and automate the regression.

Currently studying for **ISTQB Security Test Engineer** (STE v1.0.1) and building a RAG-powered tutor to do it.

---

## What I'm working on

| Project | Stack | What it does |
|---|---|---|
| [pdf-classifier-app](https://github.com/A-Dagaate/pdf-classifier-app) | Spring Boot · Python FastAPI · Docker | Secure PDF upload + ML classification + RAG study sidecar (ChromaDB · Claude AI) |
| OpenClaw | Python · Claude API | Automated chess game analyser with LLM commentary |
| RideGhana | React · Node | Ride-hailing UI prototype |

---

## Tech I reach for first

```
Languages:   Java · Python · C# · JavaScript
Frameworks:  Spring Boot · FastAPI · Playwright · JUnit 5
AI / ML:     Anthropic Claude API · ChromaDB · sentence-transformers · RAGAs
Security:    Spring Security · TOTP · JWT · Snyk
Infra:       Docker · Docker Compose · Maven · Git
Testing:     Contract testing (PACT) · MockMvc · Mockito · WireMock
```

---

## How I test

I write tests that catch real failures, not tests that pass by definition. That means:

- **Contract tests** before integration — PACT consumer/provider pacts on REST APIs
- **RAG evaluation** with RAGAs — faithfulness, answer relevance, context precision scored against ground truth
- **Async-safe assertions** — `@Async` services tested with `CountDownLatch`, not `Thread.sleep`
- **Dependency scanning** — Snyk wired into Maven; high-severity findings block the build

---

## Certifications in progress

- ISTQB CTFL (foundation)
- ISTQB CTAL-TAE (advanced test automation engineer)
- ISTQB STE v1.0.1 (security test engineer)

---

## Let's talk

`ze2@hotmail.com` · [GitHub](https://github.com/A-Dagaate)

Open to SDET, QE lead, and backend engineering roles.
