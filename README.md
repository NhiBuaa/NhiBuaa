<p align="center">
  <img src="./assets/cozy-header.svg" alt="NhiBuaa — Software Engineering student focused on Backend & AI Systems" width="100%" />
</p>

<h1 align="center">Hey, I'm Nhi 👋</h1>

<p align="center">
  <strong>Software Engineering student focused on Backend & AI Systems.</strong>
</p>

<p align="center">
  Building production-oriented backend systems, distributed realtime applications,
  and applied AI systems with an emphasis on correctness, reliability, and reproducible engineering evidence.
</p>

<p align="center">
  <a href="https://nhibuaa.space">Portfolio</a>
  ·
  <a href="https://www.linkedin.com/in/nhibuaa/">LinkedIn</a>
  ·
  <a href="mailto:nhihuynh210905@gmail.com">Email</a>
</p>

---

## Featured Engineering Work

### 💬 KittaChat — Realtime Communication Platform

<a href="https://github.com/NhiBuaa/kitta-chat">
  <img src="./assets/kittachat-card.svg" alt="KittaChat realtime communication platform" width="100%" />
</a>

A production-oriented realtime communication system built to explore **distributed backend design, reliable messaging, asynchronous processing, and WebRTC communication**.

**Engineering highlights**

- Runs multiple Express + Socket.IO replicas behind nginx with Redis-based cross-instance event propagation.
- Keeps MongoDB as durable state while using Redis only for presence, fan-out, caching, and short-lived coordination.
- Uses idempotency-aware persistence to make optimistic message retries safe.
- Handles competing call termination events through conditional durable-state transitions.
- Uses RabbitMQ-backed retry and dead-letter flows for asynchronous notification, image, and audit work.
- Includes Prometheus/Grafana observability, CI/security workflows, ADRs, integration tests, and reproducible performance evidence.

**Stack:** Node.js · Express · Socket.IO · MongoDB · Redis · RabbitMQ · React · WebRTC · nginx · Docker

**Explore:**  
[Repository](https://github.com/NhiBuaa/kitta-chat) ·
[Architecture](https://github.com/NhiBuaa/kitta-chat/blob/main/docs/ARCHITECTURE.md) ·
[Engineering Decisions](https://github.com/NhiBuaa/kitta-chat/tree/main/docs/adr) ·
[Watch Demo](https://drive.google.com/file/d/1qqE7t2oZpm36_EXk7Y98evX5B2TUkoW0/view)

---

### 🧠 Knora Agent — Cited Knowledge & Support Agent

<a href="https://github.com/NhiBuaa/knora-agent">
  <img src="./assets/knora-card.svg" alt="Knora Agent cited knowledge and support system" width="100%" />
</a>

A workspace-scoped AI knowledge and support system for answering questions from uploaded documents with **traceable citations and controlled retrieval/tool execution**.

**Engineering highlights**

- Implements cited retrieval over workspace-isolated document collections.
- Processes PDFs through durable asynchronous ingestion jobs with polling, retry, reprocessing, and idempotency semantics.
- Uses PostgreSQL + pgvector with versioned embedding configurations and hybrid retrieval.
- Separates provider integrations behind adapters rather than coupling the application to one model vendor.
- Records evaluation provenance so retrieval and semantic-quality claims remain tied to reproducible evidence.
- Introduces controlled support-tool execution through proposal → human approval → execution/reconciliation boundaries.

**Stack:** Python · FastAPI · PostgreSQL · pgvector · Docker · RAG · Hybrid Retrieval · LLM Providers

**Explore:**  
[Repository](https://github.com/NhiBuaa/knora-agent) ·
[Project Overview](https://github.com/NhiBuaa/knora-agent/blob/main/docs/PROJECT_OVERVIEW.md) ·
[Evaluation](https://github.com/NhiBuaa/knora-agent/blob/main/docs/evaluation.md)

---

## Engineering Focus

**Backend & APIs**  
Node.js / Express · Python / FastAPI · REST APIs

**Data & State**  
PostgreSQL / pgvector · MongoDB · Redis

**Messaging & Realtime**  
Socket.IO · RabbitMQ · WebRTC

**Applied AI**  
Retrieval-Augmented Generation · Hybrid Retrieval · Embeddings · Evaluation & Citation Provenance

**Infrastructure**  
Docker / Docker Compose · nginx · GitHub Actions · Prometheus / Grafana

**Frontend**  
React

---

## How I Like to Build

I enjoy projects where the interesting part begins **after the happy path works**:

- What happens when a request is retried?
- What happens when two processes race?
- Which system owns durable truth?
- What should remain disposable?
- How can a reviewer reproduce a claim instead of simply trusting it?
- Where should an AI system stop and ask for human approval?

That usually leads me somewhere between backend systems, realtime applications, infrastructure, and applied AI.

> **Build it → break it → understand it → make it better.**

---

## A Little Outside the Code

When I'm not debugging something that worked yesterday, I'm usually around coffee, chill music, or exploring another engineering rabbit hole that looked simpler before I opened it.

<p align="center">
  <img src="./assets/currently-board.svg" alt="What Nhi is currently exploring" width="100%" />
</p>

---

## Find Me Elsewhere

<table>
  <tr>
    <td width="33.33%" align="center">
      <a href="https://nhibuaa.space">
        <img src="./assets/social-portfolio.svg" alt="Visit Nhi's portfolio" width="100%" />
      </a>
    </td>
    <td width="33.33%" align="center">
      <a href="https://www.linkedin.com/in/nhibuaa/">
        <img src="./assets/social-linkedin.svg" alt="Visit Nhi's LinkedIn" width="100%" />
      </a>
    </td>
    <td width="33.33%" align="center">
      <a href="mailto:nhihuynh210905@gmail.com">
        <img src="./assets/social-email.svg" alt="Email Nhi" width="100%" />
      </a>
    </td>
  </tr>
</table>

<br />

<p align="center">
  <sub>🌿 Thanks for wandering by — see you around.</sub>
</p>
