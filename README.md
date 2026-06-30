# Hi, I'm Ashish 👋

**Backend & Systems Engineer** focused on networking, distributed systems, and infrastructure.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)

---

## 🚀 Currently Building

## Torus — High Performance Layer 7 Reverse Proxy & Edge API Gateway

Torus is my current long-term systems project.

I originally built it in Node.js/TypeScript, then rewrote the entire project in **Go** to better understand how production reverse proxies work internally. The goal isn't simply to proxy HTTP requests—it's to build the major components that power modern API gateways while relying primarily on Go's standard library.

Current capabilities include:

- Reverse proxying with `httputil.ReverseProxy`
- Longest-prefix route matching
- Atomic round-robin load balancing
- Active health checking with automatic recovery
- Graceful Shutdown
- Tuned HTTP transport for high connection reuse
- Request tracing via `X-Request-ID`
- Race-tested Go codebase

### Performance

Benchmarked on an **Intel i3-1115G4 (2C/4T)** using **wrk**.

| Scenario | Throughput |
|----------|-----------:|
| Production reverse proxying | **17,865 requests/sec** |
| Memory-path routing | **98,565 requests/sec** |

Compared to the original Node.js implementation, the Go rewrite delivers roughly:

- **10.8× higher throughput**
- **10x lower memory usage**
- Single-process goroutine architecture instead of clustered worker processes

### Current Roadmap

- TLS termination
- Rate Limiting
- Zero-downtime hot reloads
- Prometheus metrics
- Websocket proxying
- Middleware pipeline

**Repository →** https://github.com/Ashish-Barmaiya/torus-proxy

## 📦 Other Projects

## Candie

Turn your favorite movies into living wallpapers.

Candie is a Linux-first CLI that extracts beautiful frames from locally stored movies or videos and turns them into rotating desktop wallpapers. With just two commands, you can generate wallpaper-ready frames from any offline video and bring your desktop to life.

Tech: Go · FFmpeg · Linux

**Repository →** https://github.com/Ashish-Barmaiya/candie

---

## Attest

Tamper-evident audit logging built around cryptographic hash chains.

Instead of trusting database integrity, Attest allows historical logs to be independently verified even after database compromise.

**Tech:** TypeScript · PostgreSQL · Docker · Cryptography

**Repository →** https://github.com/Ashish-Barmaiya/attest

---

## Securevault

A zero-knowledge digital inheritance platform.

Files are encrypted entirely on the client before upload, hile the backend only manages encrypted blobs and lifecycle state transitions.

**Tech:** Next.js · TypeScript · PostgreSQL · Prisma · Web Crypto API

---

### Areas of Interest

- Distributed Systems
- Low-Level Systems
- Networking
- Backend Infrastructure
- Reverse Proxies
- System Design
- Perfomance Engineering

---

### Connect

- Email: ashishbarmaiya2908@gmail.com
- LinkedIn: https://www.linkedin.com/in/ashish-barmaiya-37a263152
