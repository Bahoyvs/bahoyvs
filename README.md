<h1 align="center">İlhan Bahadır Yavaş</h1>
<p align="center">
  <strong>Software Engineer &amp; Game Developer</strong><br>
  I build the two halves of a modern product: the millisecond-sensitive gameplay layer, and the backend that keeps it running.
</p>

<p align="center">
  <a href="https://bahoyvs.github.io"><img src="https://img.shields.io/badge/Portfolio-bahoyvs.github.io-64ffda?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/bahoyvs"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ilhanbahadiryavas@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### 👋 About

Most engineers pick a side of the stack. I work deliberately across the seam between them.

On the **gameplay** side I care about the frame budget: data-driven ability systems that collapse hundreds of near-duplicate classes into composable assets, server-authoritative netcode, spatial partitioning, object pooling, and rendering close to the metal. On the **systems** side I care about the architecture that keeps a product alive: containerised services, job queues, indexed databases, CI/CD, and AI models served as dependable components rather than demos.

Final-year **Information Systems and Technologies** student at **Bilkent University** (2021–2026), with a year of industry experience shipping Unreal Engine work at **INFINIA Engineering**.

---

### 🛠 Tech Stack

**Game Development**

![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Unreal Engine 5](https://img.shields.io/badge/Unreal%20Engine%205-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PixiJS](https://img.shields.io/badge/PixiJS-E72264?style=flat-square&logo=pixiv&logoColor=white)

`Netcode for GameObjects` · `UGS Relay/Lobby` · `URP` · `Blueprints` · `WebGL / HTML5 Canvas` · `VR` · `Object Pooling`

**Systems &amp; AI**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

`REST API Design` · `BullMQ` · `Qdrant` · `GitHub Actions` · `SQL` · `Applied LLMs` · `Agile / Scrum`

---

### 📌 Featured Work

#### 🎮 Project C-Building — Unity Co-op Action Roguelite
*Systems Programmer · Unity, C#, Netcode for GameObjects, UGS Relay/Lobby, URP*

A 4-player co-op isometric action roguelite spanning **5 biomes** and **8 playable heroes** with fully composable ability kits. I architected a data-driven combat framework (the `ComposedAbilitySO` pipeline) that replaced hardcoded per-hero logic with reusable Effect/Delivery primitives, so designers compose abilities from assets while bespoke hero mechanics keep their hooks. I also built the multiplayer foundation on NGO and UGS Relay/Lobby — session state machine, additive scene loading, per-client camera isolation across 4 players — plus a dual-camera system driving the game's asymmetric finale and a DSP-time-anchored branching music system that switches bar-aligned layers without desync.

#### 🫧 Bubbles — AI-Powered Turkish News Platform 🏆
*Senior Capstone · Backend Lead &amp; Scrum Master · Node.js, Docker, MongoDB Atlas, Qdrant, Redis + BullMQ, Modal Labs*

> 🏆 **Best Senior Project** (System Development Award), CTIS Awards 2026
> 🏆 **Best Presentation**, Startup Studio Demo Day '26

A production news platform that ingests Turkish news feeds and enriches them with AI. I architected and operated the backend: containerised microservices on Railway, PM2 workers for RSS ingestion and AI processing, and a Redis + BullMQ job queue. I built the GitHub Actions CI/CD pipeline and added health checks and external uptime monitoring after diagnosing a production outage; managed MongoDB Atlas (indexing, TTL policies, tuning) and a Qdrant vector database powering multilingual semantic search; and put a fine-tuned mBART Turkish summarizer plus perspective-scoring models into production on Modal Labs GPUs, with LLM taggers for enrichment. I also led the team's Agile/Scrum process across frontend, backend, and AI/ML developers.

#### 🌊 BloomWake &amp; AeroDrop — Browser Games (CrazyGames)
*Solo Developer · JavaScript, TypeScript, Canvas/WebGL, Vector Math*

**BloomWake** is a "Vampire Survivors" style bounded-swarm game engineered to hold hundreds of on-screen entities without frame drops — spatial partitioning, pooling, and an allocation-free hot path. **AeroDrop** is a physics-based cell-growing game built on integrated water physics, a mass-based "Jet Boost" movement system, and dynamic bot AI.

<sub>Several of these projects live in private repositories. I'm happy to walk through the code or give a demo on request — the write-ups above describe systems I designed and shipped.</sub>

---

### 💼 Experience

- **INFINIA Engineering** — Unreal Engine Game Developer *(Intern → Part-Time → Full-Time, Jul 2024 – May 2025, Ankara)*
  VR and 3D interactive environments in UE5 and C++: interaction systems, custom blueprint systems, MQTT-driven room-scale experiences, and Lumen/Nanite/LOD optimisation passes.
- **BTC Bilişim Hizmetleri** — Intern *(Jun 2024 – Jul 2024, İstanbul)*
  SQL data operations and SAP ERP: query optimisation, database design, and operational reporting for internal business units.

---

### 🔭 Currently Building

- **Game loop optimisation** — profiling frame budgets, allocation-free hot paths, and benchmarks that catch regressions before they reach a device.
- **Multiplayer networking** — authority splits, client prediction and reconciliation, and keeping replicated state consistent without sacrificing input responsiveness.
- **AI-native architecture** — designing systems where a model is a dependable component with real boundaries, not a black box glued to the edge.

---

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

---

<p align="center">
  <sub>Open to Game Developer (Unity / Unreal) and Backend / Full-Stack Engineering roles.</sub>
</p>
