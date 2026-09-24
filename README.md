# Alexander · dobropalm

Independent software engineer building personal AI assistants, research platforms,
offline-first field software and resilient communications. I take products from
architecture through implementation, release and day-to-day operations.

**[Portfolio](https://dobropalm.tech)** · [Email](mailto:hello@dobropalm.tech) · [Telegram](https://t.me/dobropalm)

Available for contract engineering, technical partnerships and long-term product ownership.

## Selected work

### [DOBROPALM Agent](https://github.com/kevinscott66/ai-agents)

A Russian-first personal AI assistant with twelve specialist roles sharing a
Telegram bot, a native iPhone client and browser chat. Shared conversation history,
project-scoped memory, bounded delegation and audited tools connect the interfaces.
Voice input, spoken replies and in-chat approvals support everyday conversations;
permissions and human approval gates control external actions.

A 2D/3D virtual office, cross-client role routing and a scoped read-only GitHub MCP
adapter are available on the [development branch](https://github.com/kevinscott66/ai-agents/tree/codex/virtual-office-live).
These office changes are not yet merged into the default branch. App distribution
and account setup are separate steps; personal banking execution remains planned.

Bun · TypeScript · Claude Agent SDK · SQLite WAL · SwiftUI · Preact · React Three Fiber · MCP

### [AirChat](https://github.com/kevinscott66/airchat)

A messenger with a seed-phrase identity: no phone number or sign-up. Encrypted
account sync restores conversations on another device, while servers still see
routing and sync metadata. Posts shared by public link are unencrypted.

The browser supports internet connectivity and WebRTC; native builds add LAN
messaging. Your seed phrase is your account: no operator can issue or recover it,
and the same identity unlocks your encrypted history on another device. Browser
key storage offers weaker protection than native secure storage; sync and calls
require connectivity.

React Native · Expo 55 · TypeScript · libp2p · WebRTC · LAN · `@noble` cryptography

[Open the web app](https://air.dobropalm.tech)

### [VahtaHoz](https://github.com/kevinscott66/bazahoz)

Warehouse and task management for rotational crews, with offline workflows for
unreliable connections. Stable and beta releases use separate service-worker
caches; changes reach the stable channel through an explicit promotion. Supabase
provides row-level access controls and account administration, with Capacitor and
Tauri packaging for mobile and desktop.

PWA · Supabase · PostgreSQL · Edge Functions · Capacitor · Tauri

[Open the stable app](https://vahta.razvedchick.ru/vahtahoz.html)

### [KOM17](https://github.com/kevinscott66/kom17)

A Telegram community platform with invites, moderation, an in-chat economy,
payment integrations, games, statistics and AI text and voice assistance.
The migration from a single-file bot to a typed aiogram 3 application completed
in May 2026. FastAPI webhooks, dependency injection and five independently
versioned SQLite databases support the modular service. The public repository
is a source snapshot; the legacy monolith remains as evidence for parity tests.

Python · aiogram 3 · FastAPI · SQLAlchemy 2 · Alembic · SQLite

[Open the bot](https://t.me/kom17bot)

### [DeLabs](https://delabs.space)

A Russian-language crypto and AI research platform combining daily briefs,
activity guides, airdrop tracking and token unlocks in a searchable project
catalog. Source links accompany reporting, editorial corrections survive data
refreshes, and a protected editor separates revisions from source snapshots.

As of **24 September 2026**: **536 research briefs**, **181 activity guides** and
**315 project profiles**, with 22 airdrop programs tracked and 132 token unlock
entries. Server-rendered pages, locally served project logos, RSS and search
support the archive.

Next.js · React · TypeScript · Editorial data pipelines · Search & RSS

[Explore activity guides](https://delabs.space/activities) · [Browse projects](https://delabs.space/projects)

## Engineering focus

- AI orchestration, scoped memory, human approvals and audited execution
- TypeScript, JavaScript, Python, Bun and Node.js
- SwiftUI, React Native, React, Next.js, Preact and progressive web apps
- SQLite, PostgreSQL, Supabase and offline data flows
- Telegram integrations, WebRTC, background workers and real-time interfaces
- Permission boundaries, CI/CD, observability and production operations

## How I work

- Design for network failure, partial execution and recovery.
- Keep permissions explicit and external actions auditable.
- Ship in small, reviewable increments with a rollback path.
- Leave code and documentation another engineer can maintain.

_Last reviewed: 24 September 2026. Project capabilities and availability are described separately from development work._
