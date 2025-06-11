# 👋 Hola, soy Leandro Baier

Soy **Desarrollador Backend** con casi 5 años de experiencia en **Java + Spring Boot**, apasionado por crear sistemas mantenibles y explorar arquitecturas limpias tanto en entornos empresariales como en el desarrollo de videojuegos.

---

## 💼 Experiencia Profesional

Estoy especializado en desarrollo backend con un fuerte enfoque en arquitecturas robustas y optimización del rendimiento:

- ✅ **Java (8–17)**, **Spring Boot**, **Hibernate**, **JPA**
- 🧩 **Arquitectura de microservicios**, **Diseño Hexagonal y DDD**
- 💾 **Bases de datos relacionales** (Oracle, PostgreSQL)
- 🚀 **OpenShift**, **Docker** y **pipelines CI/CD**
- 🔧 Provisionamiento de servidores y despliegue en **VPS** y entornos cloud
- 🔍 Experiencia en debugging de sistemas complejos y en la construcción de **utilidades de testing de integración**

Mi objetivo es diseñar backends no solo escalables, sino también mantenibles, observables y resilientes frente a los desafíos del mundo real.

---

## 🎮 Desarrollo de Videojuegos

En mis proyectos personales aplico los mismos principios arquitectónicos que en sistemas empresariales, usando **Godot 4.4 con C#**, **.NET 8** y una arquitectura modular basada en **DDD (Domain-Driven Design)** y **Arquitectura Hexagonal**.

### 🧠 Gameplay impulsado por ingeniería

Estoy desarrollando *Final Fragment*, un roguelike táctico de fantasía oscura con combate por turnos, rutas narrativas ramificadas y tarjetas de personaje que mutan con cada decisión. Es un proyecto personal, donde el diseño limpio es la columna vertebral de la experiencia.

> *"Siempre creí que los nombres tienen poder. En este juego, no importa cómo te llames, sino la huella que dejes en la última carta que portas."*

Aspectos técnicos clave:

- 🔄 **Separación estricta entre dominio, aplicación y UI**. El dominio contiene las reglas del juego; la aplicación, los casos de uso; la infraestructura conecta todo con Godot.
- 📦 **La capa Application contiene solo casos de uso**, orquestando la lógica del dominio sin referencias a escenas ni nodos.
- 🧩 **La capa Client Godot maneja el flujo del juego**, la lógica de escena y los servicios como `GameFlowService`.
- 🧠 **Inyección de dependencias con `Microsoft.Extensions.DependencyInjection`**, integrada manualmente en Godot a través de un contenedor personalizado (`GodotGameProvider`).
- 🧱 **Repositorios y fábricas** que construyen modelos (`Card`, `Ability`, `Mutation`) a partir de `Resources` estructurados.

### 🎲 Gameplay y sistemas

- 🗺️ **Exploración de mapas por rutas** con nodos interactivos: combate, eventos, recompensas.
- ⚔️ **Sistema de combate por turnos** con puntos de energía, efectos de estado y bonificaciones por sinergia.
- 🧬 **Sistema de mutaciones** con ventajas mecánicas y consecuencias narrativas.
- 📚 **Eventos narrativos simbólicos** con decisiones persistentes.

> *"Cada partida es un susurro arrancado al vacío. No controlás a un héroe, sino a lo que queda de él."*

### ⚙️ Estructura modular del proyecto

- `FinalFragment.Domain`: modelos y reglas del dominio puras
- `FinalFragment.Application`: casos de uso y orquestación de reglas
- `FinalFragment.Client.Godot`: flujo de juego, integración de DI, carga de recursos, repositorios, UI, escenas, shaders, audio y lógica runtime

Cada módulo se comunica solo a través de interfaces bien definidas, manteniendo el dominio aislado y testeable.

### 🎨 Estilo visual y UX

- 🎴 Tarjetas tipo tarot que evolucionan visual y mecánicamente con cada decisión
- 🗺️ Mapas animados como pergaminos corruptos
- 🖼️ UI inspirada en vitrales rotos y grimorios arcanos
- 🔥 Shaders personalizados para efectos de aura, corrupción mágica y símbolos rituales

> *"Una tarjeta no es papel. Es memoria grabada en tinta y sangre. Cada decisión escribe una línea; cada línea redibuja tu destino."*

### 🧪 Testing y mantenibilidad

- 🧪 Herramientas de testing manual y debug para cada sistema del juego
- 🛠️ Logging visual y de gameplay en tiempo real para facilitar el debugging
- 📦 Un catálogo centralizado de recursos permite definir el gameplay completamente por datos

> *"El código limpio no es solo para empresas. También lo necesitan los monstruos, las mazmorras y la magia."*

---

## 📌 Proyectos (próximamente)

Actualmente estoy trabajando en:

- 🎴 **Final Fragment** — Roguelike táctico de cartas, construido en Godot con arquitectura DDD

Pronto comenzaré a publicar estos proyectos, incluyendo diagramas de arquitectura, devlogs y estrategias de implementación.

---

## 📫 Conectemos

- 💼 [LinkedIn](https://www.linkedin.com/in/leandrobaier)
- 🧠 [GitHub](https://github.com/LeanBaier)

---

> *"Diseño dominios que tienen sentido — ya sea para usuarios o para monstruos."*
