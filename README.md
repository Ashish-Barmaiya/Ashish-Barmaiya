# Hi, I'm Ashish 👋

**Backend & Systems Engineer** Building correctness-first infrastructure, secure APIs, and resilient distributed systems.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)

---

### 🧠 Engineering Philosophy

I build systems that **fail loudly and verifiably**. I prefer simple, auditable architectures over magical abstractions. My focus is on the network and protocol layers—explicit trust boundaries, state machine invariants, cryptographic proofs, and designing for adversarial conditions. 

---

### 🚀 Featured Engineering

#### 🛡️ Torus Proxy — Multi-Core Edge API Gateway
> A Layer 7 reverse proxy built entirely from scratch using Node.js core modules (`node:net`, `node:cluster`, `node:stream`), bypassing bloated frameworks.

- **Zero-Downtime Hot Reloads:** Master process updates routing tables across clustered worker processes via IPC without dropping active TCP sockets.
- **Enterprise Security:** Native TLS termination and atomic Token Bucket rate limiting executed via Lua scripts in Redis.
- **Zero Memory Leaks:** Bypasses the V8 heap entirely for payload transfer using native OS stream piping.
- **Observability:** Built-in Prometheus metrics and structured Pino NDJSON logging.

Tech: TypeScript, Node.js Core, Redis, Clustering, IPC, Network Streams  
🔗 https://github.com/Ashish-Barmaiya/torus-proxy

#### 🔐 Attest — Tamper-Evident Audit Logging
> An append-only audit log with cryptographic verification, designed for zero-trust environments.

- **Cryptographic Integrity:** Hash-chained event log with external anchoring.
- **Immutability:** Detects history rewrites and malicious tampering even after a total database compromise.
- **Verification:** Ships with offline verification tooling for independent audit proofs.

Tech: TypeScript, Node.js, PostgreSQL, Cryptography, Docker
🔗 https://github.com/Ashish-Barmaiya/attest

#### 🗝 SecureVault — Zero-Knowledge Digital Inheritance
> A digital asset handoff system built on explicit state machines and zero-trust assumptions.

- **Zero-Knowledge Architecture:** Strict client-side encryption ensures the server has absolutely zero visibility into the stored assets.
- **State Machine Routing:** Explicit lifecycle transitions: `ACTIVE` → `GRACE` → `INHERITABLE` → `CLAIMED`.
- **Adversarial Design:** Cryptographic challenge-response mechanisms protect against malicious servers and insider threats.

Tech: Javascript, Next.js, Node.js, PostgreSQL, Prisma, Redux, Web Crypto API 
🔗 https://github.com/Ashish-Barmaiya/securevault

---

### 🛠 Technical Skills

- **Languages:** TypeScript, JavaScript, SQL
- **Architecture:** TCP/HTTP Networking, Reverse Proxies, Stream Processing, Multi-Process Clustering
- **Security:** TLS Termination, Hash-chaining, Key Derivation, Threat Modeling, Zero-Knowledge Proofs
- **Infrastructure:** Node.js Core, PostgreSQL, Redis, Docker, Linux
- **Frameworks:** Nextjs, React, Redux, TailwindCss

---

### 📬 Contact

- **Email:** ashishbarmaiya2908@gmail.com
- **LinkedIn:** [linkedin.com/in/ashish-barmaiya-37a263152](https://www.linkedin.com/in/ashish-barmaiya-37a263152/)
