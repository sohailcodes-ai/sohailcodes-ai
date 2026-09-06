# Sam

### Systems-focused developer · Backend · Realtime · Compilers · AI

I build software, break it, read the source, figure out why it broke — and then usually go one layer deeper.

I'm interested in what happens **underneath the abstraction**: state machines, concurrency, networking, persistence, queues, runtimes, execution, protocols, and the edge cases that show up when a prototype becomes a real system.

Some things become products.
Some become experiments.
Some become repositories containing questionable 3 AM decisions that somehow survived code review.

---

## What I Build

I gravitate toward software where the interesting problems aren't immediately visible from the UI.

* **Distributed & backend systems**
* **Realtime applications**
* **Compilers & runtimes**
* **Developer tooling**
* **AI systems**
* **Game systems**
* **Infrastructure**
* **Full-stack products**

I like taking something that looks simple from the outside and figuring out what it actually takes to make it work underneath.

---

# Selected Work

### ⚔️ Clutch

**Competitive coding infrastructure**

A competitive coding platform built around **server-authoritative matches, real code execution, and persistent player progression.**

**Built with:**

`TypeScript` `Next.js` `Fastify` `PostgreSQL` `Redis` `BullMQ` `Docker` `WebSockets`

**Systems:**

* Matchmaking & placement matches
* ELO, streaks & seasonal progression
* Tournaments & titles
* Asynchronous code evaluation
* WebSocket realtime state
* Docker-isolated execution
* Multi-language runtimes
* Persistent player state

**Runtimes:** Python · JavaScript · TypeScript · C++ · Java · Go · Rust

→ [View Clutch](https://github.com/sohailcodes-ai/clutch)

---

### 🧬 Vex-Lang

**Programming language + runtime**

A Hinglish-inspired programming language built from the ground up with its own **lexer, parser, AST pipeline, bytecode compiler, virtual machine, Python backend, and CLI tooling.**

```text
                    Vex Source
                         │
                       Lexer
                         │
                      Parser
                         │
                        AST
                       ╱   ╲
                      ╱     ╲
                 Python    Bytecode
                 Backend   Compiler
                    │          │
                 CPython     Vex VM
```

**Includes:**

* Custom lexer & parser
* AST generation
* Python code generation
* Bytecode compiler
* Virtual machine
* CLI tooling
* Token / AST / bytecode inspection
* Automated test suite
* PyPI distribution
* VS Code tooling

`Python` `Compilers` `Bytecode` `Virtual Machines` `CLI`

→ [Explore Vex-Lang](https://github.com/sohailcodes-ai/Vex-Lang)

---

### 🌐 Shadow Rooms

**Realtime social collaboration**

A room-based realtime application built around **private spaces, persistent state, presence, and event-driven communication.**

**Systems:**

* Realtime rooms
* Presence & typing state
* WebSocket event architecture
* Chat & polls
* Collaborative interactions
* HTTP / REST APIs
* Redis-backed transient state
* Database persistence
* Dockerized workloads

`React` `TypeScript` `Vite` `Node.js` `WebSockets` `Redis` `Docker`

→ [Explore Shadow Rooms](https://github.com/sohailcodes-ai/Shadow-Rooms)

---

## Other Work

### 🥗 NutriWise AI

AI-powered food analysis and nutrition tracking built as a full-stack application.

`Next.js` `React` `Tailwind` `Supabase` `Gemini`

---

### 🌑 LIMEN

An experimental interactive web experience focused on **3D, motion, sound, atmosphere, and cinematic UI.**

`React` `Three.js` `GSAP` `WebGL`

---

### 🎮 Game Development

Roblox systems, gameplay architecture, networking, UI, combat systems, world building, and interactive experiences.

`Roblox` `Lua` `Blender`

---

# Engineering Interests

```text
┌─────────────────────────────────────────────────┐
│                                                 │
│  Compilers              Distributed Systems     │
│  Networking             Concurrency             │
│  Databases              Backend Architecture    │
│  Realtime Systems       Developer Tooling       │
│  Infrastructure         AI Systems              │
│  Game Systems            Graphics               │
│  Protocols              Performance             │
│                                                 │
└─────────────────────────────────────────────────┘
```

# Stack

### Languages

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,js,py,cpp,cs,lua" />
</p>

### Web

<p align="left">
  <img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,threejs" />
</p>

### Backend

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,fastapi,django" />
</p>

<p align="left">
  <img src="https://skillicons.dev/icons?i=express" />
</p>

`REST` · `WebSockets`

### Databases

<p align="left">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis" />
</p>

### Infrastructure & Systems

<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,linux,git,github,githubactions" />
</p>

### Game Development

<p align="left">
  <img src="https://skillicons.dev/icons?i=robloxstudio,blender" />
</p>

---

# Beyond the Stack

I don't want to be defined by a list of technologies.

Frameworks change. Languages change. Infrastructure changes.

The underlying problems don't.

I'm particularly interested in:

```text
                    SYSTEMS
                       │
        ┌──────────────┼──────────────┐
        │              │              │
     Runtime        Network        Storage
        │              │              │
    Compilers      Protocols      Databases
        │              │              │
       VM          Realtime       Persistence
        │              │              │
        └──────────────┼──────────────┘
                       │
                  Architecture
                       │
                  Applications
```

The goal isn't to know every tool.

It's to understand the machine well enough that the tool becomes secondary.

---

# What I'm Working On

Currently going deeper into:

**Distributed Systems · Networking · Compilers · Concurrency · Databases · Infrastructure · Backend Architecture · AI Engineering · Performance**

And building things that force me to actually understand them.

---

# A Few Things I Believe

> **Abstractions are useful. Understanding what they hide is better.**

> **If you can't explain why it works, you probably don't understand it yet.**

> **Production is where assumptions go to die.**

> **Read the source before blaming the framework.**

---

# Connect

<p align="left">
  <a href="https://github.com/sohailcodes-ai">
    <img src="https://skillicons.dev/icons?i=github" width="48" />
  </a>
  &nbsp;
  <a href="https://samx-portfolio.vercel.app/">
    <img src="https://skillicons.dev/icons?i=vercel" width="48" />
  </a>
</p>

---

### Currently building.

### Currently breaking.

### Currently learning why.

<br>

**Build things. Read the source. Understand the system.**


# How I Think About Engineering

I generally work from the **inside out**.

```text
Requirements
     ↓
Architecture
     ↓
Implementation
     ↓
Failure modes
     ↓
Bottlenecks
     ↓
Question the abstraction
     ↓
Prove the smallest viable idea
     ↓
Harden the system
```

If something works, I want to know **why**.

If something fails, I want to know **which assumption was wrong**.

I have very little interest in cargo-cult engineering.

---

# Currently

Going deeper into:

**distributed systems · networking · compilers · concurrency · databases · infrastructure · backend architecture · AI engineering · performance**

And, inevitably, overengineering something that absolutely did not need to be overengineered.

---

# Find Me

**Portfolio** → https://samx-portfolio.vercel.app/
**GitHub** → https://github.com/sohailcodes-ai
**Astra AI** → https://astra-ai.co/en

---

> **Build things. Read the source. Understand the system.**
