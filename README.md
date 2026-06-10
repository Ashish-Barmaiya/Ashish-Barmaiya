# Hi, I'm Ashish 👋

**Backend & Systems Engineer** — I build correctness-first infrastructure, secure APIs, and resilient distributed systems.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)

---

### 🧠 Engineering Philosophy

I build systems that **fail loudly and verifiably**. I prefer simple, auditable architectures over magical abstractions. My focus is on the network and protocol layers — explicit trust boundaries, state machine invariants, cryptographic proofs, and designing for adversarial conditions.

---

### 🚀 Featured Engineering

#### ⚡ Torus Proxy — High‑Performance Multi‑Core API Gateway (now in Go)

A Layer 7 reverse proxy rewritten from scratch in Go after an initial Node.js prototype.  
Torus is built for raw speed and zero‑downtime operations, leveraging Go’s concurrency model and a zero‑allocation hot path.

**Performance (dual‑core i3‑1115G4, Linux, wrk):**
- **98,566 req/s** — short‑circuit memory path (HTTP parse + routing overhead only)
- **17,866 req/s** — full production proxying to Go mock backends
- **6.3× faster** than the original Node.js version on identical hardware

**Roadmap (features from the Node.js prototype being ported):**
- Native TLS termination (currently plain HTTP)
- Zero‑downtime hot reloads via IPC
- Atomic rate limiting with Redis‑backed Token Buckets
- Prometheus metrics and structured NDJSON loggin

**Tech:** Go, Node.js (history), Redis, Clustering, TCP/HTTP, Linux  
🔗 [github.com/Ashish-Barmaiya/torus-proxy](https://github.com/Ashish-Barmaiya/torus-proxy)

---

#### 🔐 Attest — Tamper‑Evident Audit Logging

An append‑only audit log with cryptographic verification, designed for zero‑trust environments.

- **Cryptographic Integrity:** Hash‑chained event log with external anchoring.
- **Immutability:** Detects history rewrites even after a total database compromise.
- **Verification:** Ships with offline verification tooling for independent audit proofs.

**Tech:** TypeScript, Node.js, PostgreSQL, Cryptography, Docker  
🔗 [github.com/Ashish-Barmaiya/attest](https://github.com/Ashish-Barmaiya/attest)

---

#### 🗝 SecureVault — Zero‑Knowledge Digital Inheritance

A digital asset handoff system built on explicit state machines and zero‑trust assumptions.

- **Zero‑Knowledge Architecture:** Strict client‑side encryption — the server sees nothing.
- **State Machine Routing:** `ACTIVE` → `GRACE` → `INHERITABLE` → `CLAIMED` lifecycle.
- **Adversarial Design:** Cryptographic challenge‑response prevents server/insider attacks.

**Tech:** TypeScript, Next.js, Node.js, PostgreSQL, Prisma, Redux, Web Crypto API  
🔗 [github.com/Ashish-Barmaiya/securevault](https://github.com/Ashish-Barmaiya/securevault)

---

### 🛠 Technical Skills

- **Languages:** Go, TypeScript, JavaScript, SQL  
- **Systems:** TCP/HTTP networking, reverse proxies, stream processing, multi‑process clustering  
- **Security:** TLS termination, hash‑chaining, key derivation, threat modeling, zero‑knowledge designs  
- **Infrastructure:** Linux, Docker, Node.js runtime, PostgreSQL, Redis  
- **Frameworks:** Next.js, React, Redux, Tailwind CSS  

---

### 📬 Contact

- **Email:** ashishbarmaiya2908@gmail.com  
- **LinkedIn:** [linkedin.com/in/ashish-barmaiya-37a263152](https://www.linkedin.com/in/ashish-barmaiya-37a263152)
