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

In my personal projects, I apply the same architectural principles used in enterprise systems to video games, using **Godot 4.4 + C#**, **.NET 8** and a modular architecture based on **DDD (Domain-Driven Design)** and **Hexagonal Architecture**.

### 🧠 Engineering-driven gameplay

I'm building *Final Fragment*, a dark-fantasy tactical roguelike with turn-based combat, branching narrative routes and evolving character cards. It's a solo project with clean design at its core.

Key engineering aspects:

- 🔄 **Strict separation between domain, application, and UI**. The domain contains the game rules; the application holds use cases; infrastructure connects everything to Godot.
- 📦 **Application layer only contains use cases**, purely orchestrating domain logic without referencing scenes or runtime objects.
- 🧩 **Infrastructure layer handles orchestration**, Godot scene logic and flow via services like `GameFlowService`.
- 🧠 **Dependency Injection with `Microsoft.Extensions.DependencyInjection`**, manually integrated in Godot through a `GodotGameProvider` bootstrapper.
- 🧱 **Repositories + factories** build domain models (`Card`, `Ability`, `Mutation`) from structured Godot `Resources`.

### 🎲 Gameplay + Systems

- 🗺️ **Route-based map exploration** with interactive nodes: combat, events, rewards.
- ⚔️ **Turn-based combat system** with energy points, status effects and synergy bonuses.
- 🧬 **Mutation system** with both mechanical bonuses and thematic drawbacks.
- 📚 **Narrative events** with symbolic consequences and persistent effects.

### ⚙️ Modular project structure

- `FinalFragment.Domain`: pure domain models and rules
- `FinalFragment.Application`
