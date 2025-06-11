# 👋 Hi, I'm Leandro Baier

I'm a **Backend Developer** with nearly 5 years of experience in **Java + Spring Boot**, passionate about crafting maintainable systems and exploring clean architectures in both enterprise environments and game development.

---

## 💼 Professional Background

I specialize in backend development with a strong focus on robust architectures and performance optimization:

- ✅ **Java (8–17)**, **Spring Boot**, **Hibernate**, **JPA**
- 🧩 **Microservices architecture**, **Hexagonal & Domain-Driven Design**
- 💾 **Relational Databases** (Oracle, PostgreSQL)
- 🚀 **OpenShift**, **Docker**, and **CI/CD pipelines**
- 🔧 Server provisioning and deployment on **VPS** and cloud environments
- 🔍 Experience debugging complex systems and building **integration testing utilities**

My goal is to design backends that are not only scalable, but also maintainable, observable, and resilient in real-world environments.

---

## 🎮 Game Development

In my personal projects, I apply the same architectural principles used in enterprise systems to video games, using **Godot 4.4 + C#** and a modular architecture based on **DDD (Domain-Driven Design)** and **Hexagonal Architecture**.

### 🧠 Engineering-driven gameplay

I'm building *Final Fragment*, a dark-fantasy tactical roguelike with turn-based combat, branching narrative routes and evolving character cards. It's a solo project with clean design at its core.

Key engineering aspects:

- 🔄 **Strict separation between UI and domain**: all logic runs independently of Godot scenes.
- 🧩 **GameContext DI container** for managing shared state and dependencies.
- 🏗️ **Repositories + factories** build domain models (`Card`, `Ability`, `Mutation`) from structured Godot `Resources`.
- 💡 **Application layer** uses services like `GameFlowService` to coordinate gameplay actions.
- 🎴 **CardBase** scene is reused across enemies and players, rendering changes dynamically from domain state.

### 🎲 Gameplay + Systems

- 🗺️ **Route-based map exploration** with interactive nodes: combat, events, rewards.
- ⚔️ **Turn-based combat system** with energy points, status effects and synergy bonuses.
- 🧬 **Mutation system** with both mechanical bonuses and thematic drawbacks.
- 📚 **Narrative events** with symbolic consequences and persistent effects.

### ⚙️ Modular project structure

- `FinalFragment.Domain`: pure domain models and rules
- `FinalFragment.Application`: gameplay orchestration and game loop services
- `FinalFragment.Infrastructure`: resource loading and repository implementations
- `FinalFragment.Client.Godot`: UI, scenes, shaders, audio, and integration glue

All modules follow strict separation and communicate only through well-defined interfaces.

### 🎨 Visuals and UX

- 🎴 Tarot-style evolving cards that change with your decisions
- 🗺️ Scroll-animated maps with procedural visual routing
- 🖼️ UI styled as broken stained glass and arcane books
- 🔥 Custom shaders for aura effects, magical corruption, and ritual symbols

### 🧪 Testing & Maintainability

- 🧪 Manual and debug testing tools for each game feature
- 🛠️ Real-time logging of visual and gameplay state for easier debugging
- 📦 Resource catalog allows fully data-driven gameplay definitions

> *"Clean code isn't just for enterprise — it's for monsters, dungeons and magic, too."*

---

## 📌 Projects (coming soon)

I'm currently working on:

- 🎴 **Final Fragment** — Tactical card roguelike built with Godot + DDD

I’ll start publishing these projects gradually, including architecture diagrams, devlogs and implementation strategies.

---

## 📫 Let's connect

- 💼 [LinkedIn](https://www.linkedin.com/in/leandrobaier)
- 🧠 [GitHub](https://github.com/LeanBaier)

---

> *"I design domains that make sense — whether it's for users or monsters."*
