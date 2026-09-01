# kevinscott66

Full-stack engineer focused on secure, production-oriented software for real
operational workflows.

I build systems that combine product engineering, backend automation, mobile and
web clients, and pragmatic infrastructure. My recent work includes offline-first
field software, encrypted peer-to-peer communication, Telegram platforms, and
multi-agent operations tooling.

**[dobropalm.tech](https://dobropalm.tech)** · hello@dobropalm.tech · [@dobropalm](https://t.me/dobropalm)

## Selected work

### [AirChat](https://github.com/kevinscott66/airchat)

A decentralised mobile messenger that keeps working when the network does not.
Multi-transport mesh routing across WebRTC, IPFS pubsub, LAN discovery and
long-range radio, with store-and-forward delivery for peers that are never
online at the same time. Self-owned `did:key` identity derived from a BIP39
seed phrase, end-to-end encryption, and an encrypted local database.

React Native · Expo · libp2p · `@noble` cryptography

### [Multi-agent operations platform](https://github.com/kevinscott66/ai-agents)

A production platform coordinating twelve role-scoped agents inside a Telegram
group: tiered autonomy per role, a fail-closed permission gate, human approval
for risky actions, audited tool execution, persistent task queues and a
six-view operator dashboard.

Bun · TypeScript · Claude Agent SDK · SQLite · Preact

### [KOM17](https://github.com/kevinscott66/kom17)

A Telegram community platform and a strangler-fig refactor carried out in
production: a 45k-line single-file monolith replaced module by module with a
typed, dependency-injected aiogram 3 application, both pipelines sharing one
database and one webhook. Invites, moderation, an in-chat economy with real
payment providers, games, AI assistants and an admin panel.

Python · aiogram 3 · FastAPI · SQLAlchemy 2 · Alembic

### [VahtaHoz](https://github.com/kevinscott66/bazahoz)

Offline-ready warehouse and task management for distributed field teams. A PWA
with Supabase-backed authorization and row-level security, native packaging,
and resilient synchronization for unreliable networks.

[Live application](https://vahta.razvedchick.ru)

## Engineering focus

- TypeScript, JavaScript, Python, Bun, Node.js
- React Native, Preact, progressive web applications
- SQLite, PostgreSQL, Supabase, offline-first data flows
- Telegram Bot API, real-time systems, background workers
- Application security, authorization boundaries, audit trails
- Linux services, CI/CD, observability, production operations

## Working principles

- Security boundaries belong in code and tests, not only in documentation.
- Operational software should remain usable under partial failure.
- Automation needs explicit permissions, auditability, and recovery paths.
- A portfolio should show finished decisions and verified behavior, not internal noise.
