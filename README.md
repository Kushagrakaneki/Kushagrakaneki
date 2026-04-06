<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,30:1a0533,60:302b63,100:24243e&height=220&section=header&text=KUSHAGRA%20TRIVEDI&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=🐼%20Backend%20Systems%20Engineer%20&descSize=20&descAlignY=60&descColor=a78bfa&animation=fadeIn" width="100%"/>

</div>

<div align="center">

 ### *✦ "Solving the unsolvable is the way to go." ✦*

</div>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&lines=Architecting+Real-Time+WebSocket+Pipelines;Building+Distributed+Event-Driven+Systems;Shipping+Production-Grade+Backend+Code;Sub-100ms+Latency+%E2%80%A2+100%2B+Concurrent+Clients;From+NASA+APIs+to+Collaborative+Editors)](https://git.io/typing-svg)

</div>


<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kushagratrivedi17/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:trivedikushagra17@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kushagrakaneki)
[![Codolio](https://img.shields.io/badge/Codolio-7c3aed?style=for-the-badge&logo=code&logoColor=white)](https://codolio.com/profile/kushagrakaneki)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/)

</div>

<br/>

---

<div align="center">

## ░▒▓ `> whoami` ▓▒░

<br/>

### _"I build backends that don't just work — they work_ **at scale, under failure, under load.**

_I believe the best engineers aren't the ones who know the most — they're the ones who use AI to write their code. <br/>
Just kidding. The best are those who squeeze every last bit of brain juice to solve the problem themselves. I always do the same._

_I'm a backend systems engineer focused on the hard stuff:_ **distributed state, real-time communication, systems** _that don't fail when the network does. I've built WebSocket pipelines, event-driven architectures, and full-stack platforms that mirror how real products are built in the industry — not because someone assigned them, but because I wanted to know if I could.<br/>_

_I'm making real architectural decisions:<br/>_
**fault tolerance · eventual consistency · low latency · real-time systems**<br/>

_I pick up a problem, go deep, and ship it right._
<br/>
**I'm looking for problems hard enough to be worth solving."**

</div>

<br/>

---

<div align="center">

## ░▒▓ `> ./projects --highlight` ▓▒░

</div>

<br/>

---

### 🛰️ NeoWatch &nbsp;·&nbsp; *Near-Earth Object Threat Intelligence*

> **Real-time asteroid threat pipeline powered by NASA NeoWS API**

<table>
<tr>
<td width="50%">

**What it does**
- Pulls live asteroid data from NASA NeoWS API every 6 hours via `node-cron`
- Runs a custom **0–100 hazard scoring algorithm** (miss distance · velocity · diameter · PHA classification)
- Broadcasts real-time threat alerts to **100+ concurrent clients** via WebSocket
- Sends **Nodemailer** email notifications on HIGH_THREAT_DETECTED events

</td>
<td width="50%">

**How it's built**
- Event-driven layer: PostgreSQL mutations → WebSocket broadcasts
- Background jobs run independently without blocking the main event loop
- **Three.js + React Three Fiber** for 60fps orbital 3D visualizations
- **Recharts** live telemetry dashboards · **Framer Motion** threat-ring animations

</td>
</tr>
</table>

**Stack:** `Node.js` `Express` `PostgreSQL` `WebSocket` `Three.js` `React 18` `Vite` `Docker` `Nodemailer` `node-cron`

[![View on GitHub](https://img.shields.io/badge/⭐_View_on_GitHub-NeoWatch-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kushagrakaneki/NeoWatch---Space-Watcher)

---

### ⚡*KamiDB  ·  Distributed Consensus Database Engine*

> **Fault-tolerant, multi-node cluster with zero-downtime architecture**

<table>
<tr>
<td width="50%">

**What it does**
- Supports a self-healing cluster that automatically handles leader elections and hardware failures
- Achieves zero-downtime data ingestion by dynamically routing around dead nodes and network partitions
- Maintains absolute data consistency across all connected servers using the Raft consensus algorithm
- Visualizes real-time cluster telemetry and log replication via a dedicated monitoring dashboard

</td>
<td width="50%">

**How it's built**
- Microsecond-latency networking layer using strictly typed Protocol Buffers (proto3) over gRPC
- Custom Log-Structured Merge-Tree (LSM-Tree) storage engine with an append-only Write-Ahead Log (WAL)
- Deterministic state machine replication ensuring Follower nodes perfectly mirror the Leader's physical disk
- Decoupled architecture featuring an internal gRPC consensus network and an external Javalin HTTP REST bridge

</td>
</tr>
</table>

**Stack:** `Java 21+` `Raft` `gRPC` `Protocol Buffers` `Javalin` `React`

[![View on GitHub](https://img.shields.io/badge/⭐_View_on_GitHub-KamiDB-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kushagrakaneki/Kamidb---Distributed-Consensus-Database-Engine-in-Java)

---

### 🧠 GoZen · StudyFlow &nbsp;·&nbsp; *Cross-Platform Productivity Monorepo*

> **SaaS-architected learning platform across web + mobile from a single codebase**

<table>
<tr>
<td width="50%">

**What it does**
- Delivers a **Next.js 14** web app and **React Native** mobile app from one repo
- Tracks study sessions with real-time **heatmaps and progress benchmarking**
- Manages authentication, sessions, and data caching end-to-end
- Visualizes telemetry via **Recharts + SVG** without dropping frame rates

</td>
<td width="50%">

**How it's built**
- **Turborepo monorepo** — shared DB schemas, strict TypeScript types, UI components
- **Prisma ORM** over PostgreSQL with strict type safety end-to-end
- **NextAuth.js** for session management · **SWR** for aggressive data caching
- **Zustand** client state synced with server via auto-revalidation

</td>
</tr>
</table>

**Stack:** `Next.js 14` `TypeScript` `React Native` `PostgreSQL` `Prisma` `Turborepo` `Zustand` `NextAuth.js` `SWR`

[![View on GitHub](https://img.shields.io/badge/⭐_View_on_GitHub-GoZen·StudyFlow-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kushagrakaneki/GoZen-Codex)

<br/>

---

<div align="center">

## ░▒▓ `> cat tech_stack.json` ▓▒░

<br/>

**⚙️ — Backend & Runtime —**

![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**🗄️ — Databases & ORM —**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**🎨 — Frontend & Frameworks —**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**🚀 — DevOps & Cloud —**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**🧪 — Testing & Tools —**

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)

</div>

<br/>

---
