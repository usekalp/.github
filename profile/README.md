# Kalp 🦋
### Deploy production-grade AI Agents in minutes.

Kalp is the **runtime for AI agents** — built to run persistent, stateful agents at the edge without the usual infrastructure overhead.

It bridges the gap between **writing agent logic** and **running it reliably in production**, with a developer experience focused on **type-safety, speed, and simplicity**.

---

## 🚀 Get Started

Spin up your first agent in seconds:

```bash
npx create-kalp@latest
```

Then deploy it globally:

```bash
kalp push
```

---

## 🛠️ Developer Workflow

**1. Initialize**  
Scaffold a new project and agent instantly.

**2. Develop**  
Write your logic in TypeScript with built-in primitives:
- `ctx.memory` → persistent SQLite storage  
- `ctx.vault` → secure secrets management  

**3. Deploy**  
Push to the edge. Kalp handles orchestration, state, and scaling.

---

## ✨ Key Features

**⚡ Edge-Native**  
Runs on top of Cloudflare Durable Objects for low-latency, stateful execution.

**🧠 Persistent by Default**  
Agents have built-in memory — no extra setup required.

**🧩 Code-First**  
No visual builders. Everything lives in your codebase.

**🔄 Migrations**  
Each deploy creates a versioned snapshot of your agent state.

**🗄️ Zero-Config Storage**  
SQLite comes out of the box via `ctx.memory`.

**🔐 Secure Secrets**  
Manage sensitive data easily with `ctx.vault`.

---

## 🌐 Links

- Website: https://usekalp.com  
- Docs: https://docs.usekalp.com  
- Twitter: https://twitter.com/usekalp  

---

## 🧭 Philosophy

Kalp is built on a simple idea:

> Agents shouldn’t be scripts. They should be **long-lived systems**.

No glue code. No infra headaches. Just write your agent and ship it.
