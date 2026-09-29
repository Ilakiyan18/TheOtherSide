# 🌒 THE OTHER SIDE

> **Reality has another side.**
>
> *A realistic atmospheric exploration game built in Unreal Engine.*

![Status](https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-8A2BE2?style=for-the-badge)
![Engine](https://img.shields.io/badge/UNREAL%20ENGINE-5.8-0E1128?style=for-the-badge&logo=unrealengine)
![Platform](https://img.shields.io/badge/PLATFORM-PC-111111?style=for-the-badge&logo=windows)
![Language](https://img.shields.io/badge/C%2B%2B%20%2B%20BLUEPRINTS-00599C?style=for-the-badge&logo=cplusplus)
![Multiplayer](https://img.shields.io/badge/MULTIPLAYER-UP%20TO%204-6E40C9?style=for-the-badge)

---

## ◼︎ THE PROJECT

**The Other Side** is a realistic atmospheric exploration game built around a simple question:

> **What if the world we know isn't the only version of reality?**

Explore a large European-inspired world made of cities, suburbs, islands and abandoned places.

Drive.

Sail.

Explore.

Discover.

And eventually cross to **the other side**.

The game focuses on **atmosphere, exploration, environmental storytelling and mystery** rather than traditional horror formulas.

There are no endless jumpscares.

No artificial corridors designed to scare you every five minutes.

The world itself is the mystery.

---

## 🌍 THE WORLD

The game takes place in a large interconnected world containing:

- 🏙️ European-inspired cities
- 🏘️ Suburban areas
- 🌲 Natural environments
- 🏚️ Abandoned locations
- 🏝️ Large islands
- 🚗 Roads and vehicles
- 🚤 Boats and waterways
- 🌫️ Atmospheric environments
- 🌀 Portals
- 🌒 A parallel world
- ⚠️ Anomalies and unexplained phenomena

The world is designed to feel **believable first, mysterious second**.

Buildings should feel like real buildings.

Roads should make sense.

Geography should be coherent.

Transportation should have a purpose.

Every location should feel like it exists for a reason.

---

# 🌀 THE OTHER SIDE

At some point, the player discovers that reality is not as stable as it appears.

A second version of the world exists.

A world that follows different rules.

The transition between the two worlds is not simply a level change.

It is part of the game's core identity.

The two realities may share the same physical space while behaving differently.

Objects may change.

Locations may become inaccessible.

The environment may transform.

Events may occur differently.

And some things may exist on **only one side**.

---

## 🎮 GAMEPLAY

The experience is built around **exploration and discovery**.

### 🚶 Exploration

Move through large environments and discover places without being constantly guided.

### 🚗 Vehicles

Travel through the world using cars and other vehicles.

### 🚤 Boats

Explore waterways and reach areas inaccessible by road.

### 🌀 Portals

Discover and interact with gateways between realities.

### ⚠️ Anomalies

Encounter strange events and environmental changes that challenge the player's understanding of the world.

### 🔎 Environmental Storytelling

The world itself tells the story.

Details, locations, objects and changes in the environment may reveal information without relying entirely on exposition.

---

# 👥 MULTIPLAYER

**The Other Side** is designed with multiplayer in mind.

The long-term target is:

> **1–4 players**

Players should be able to explore the world together and experience the game's environments and anomalies as a group.

Multiplayer architecture is being considered from the beginning so that major systems do not need to be completely rewritten later.

---

# 🎨 VISUAL DIRECTION

The target is a **realistic modern visual style**.

### Visual principles

- Realistic materials
- Physically plausible environments
- Cinematic lighting
- Natural environments
- Believable architecture
- Atmospheric weather
- Controlled color grading
- Consistent asset quality

The goal is **not** to look like a generic indie horror game.

The world should feel like a real place.

Until something starts feeling wrong.

---

# 🧠 TECHNICAL FOUNDATION

The project is being developed with:

| Technology | Usage |
|---|---|
| **Unreal Engine 5.8** | Game engine |
| **C++** | Core gameplay architecture |
| **Blueprints** | Gameplay scripting & designer iteration |
| **Enhanced Input** | Input system |
| **World Partition** | Large-world streaming |
| **Git** | Version control |
| **Git LFS** | Unreal binary assets |

The project is being built progressively rather than attempting to create the entire game at once.

---

# 🏗️ DEVELOPMENT PHILOSOPHY

The project follows a simple rule:

> **Build the foundation before building the world.**

Development follows:

```text
ANALYZE
   ↓
PLAN
   ↓
IMPLEMENT
   ↓
BUILD
   ↓
TEST
   ↓
FIX
   ↓
DOCUMENT
   ↓
COMMIT
```

A feature is not considered complete simply because its code exists.

It must **build, run and be tested**.

---

# 🗺️ ROADMAP

### `M0` — Environment Foundation
- [x] Unreal Engine project
- [x] Git repository
- [x] Git LFS
- [x] C++ toolchain
- [x] Development documentation

### `M1` — C++ Core Framework
- [ ] GameMode
- [ ] GameState
- [ ] PlayerState
- [ ] Character foundation
- [ ] PlayerController foundation
- [ ] Core multiplayer architecture

### `M2–M5` — Core Systems
- [ ] Player movement
- [ ] Enhanced Input
- [ ] Interaction framework
- [ ] Inventory architecture
- [ ] Save / Load system

### `M6–M7` — Vertical Slice
- [ ] Test environment
- [ ] Player movement
- [ ] Interaction
- [ ] Inventory
- [ ] Save / Load
- [ ] Audio
- [ ] Lighting
- [ ] First atmospheric gameplay loop

### `M8–M10` — The Other Side
- [ ] World Partition
- [ ] Dimension system
- [ ] Portal system
- [ ] Parallel-world environment
- [ ] Anomalies
- [ ] Environmental transformations

### `M11–M12` — Multiplayer & Vehicles
- [ ] Multiplayer foundations
- [ ] Player replication
- [ ] Vehicle system
- [ ] Cars
- [ ] Boats
- [ ] Multiplayer testing

### `M13` — World Assembly
- [ ] Main city
- [ ] Suburbs
- [ ] Islands
- [ ] Roads
- [ ] Waterways
- [ ] Environmental storytelling

### `M14–M16` — Optimization & Testing
- [ ] Performance optimization
- [ ] Packaging
- [ ] Internal Alpha
- [ ] Private Beta
- [ ] First external testers

---

# 💻 PERFORMANCE TARGET

The game is being developed with realistic hardware constraints in mind.

Current development target:

```text
GPU     → RTX 3050 6GB
CPU     → Ryzen 5 5600
RAM     → 16GB
Display → 2560 × 1440
```

Performance is considered from the beginning.

Large environments will rely on techniques such as:

- World Partition
- Spatial streaming
- Level-of-detail systems
- Texture streaming
- Efficient replication
- Controlled runtime object creation
- Scalable lighting

Visual quality should never come at the cost of an unnecessarily inefficient architecture.

---

# 📁 PROJECT STRUCTURE

```text
TheOtherSide/
│
├── Unreal/
│   └── TheOtherSide/
│       ├── Config/
│       ├── Content/
│       ├── Source/
│       └── TheOtherSide.uproject
│
├── Assets/
│
├── Docs/
│
├── AI/
│   ├── PROJECT_RULES.md
│   ├── PROJECT_ANALYSIS.md
│   └── DEVELOPMENT_ROADMAP.md
│
├── Backups/
│
├── .gitattributes
├── .gitignore
└── README.md
```

---

# 🤖 AI-ASSISTED DEVELOPMENT

**The Other Side** is being developed with AI-assisted engineering workflows.

AI agents are used for:

- Code generation
- Architecture analysis
- Debugging
- Documentation
- Build diagnostics
- Refactoring
- Testing assistance
- Development planning

AI does **not** replace design decisions.

The project's creative direction remains human-driven.

---

# 🔐 DEVELOPMENT STATUS

> **This project is currently in early development.**

The repository is **not a finished game**.

Systems, mechanics, environments and visual direction are expected to evolve throughout development.

Expect:

- unfinished features
- placeholder assets
- experimental systems
- breaking changes
- performance issues
- incomplete environments

That's part of the process.

---

# 📸 SCREENSHOTS

*Screenshots will be added as the project develops.*

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│                     THE OTHER SIDE                           │
│                                                              │
│                  SCREENSHOTS COMING SOON                     │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

# 🧭 PROJECT PRINCIPLES

### 01 — Atmosphere over noise

The world should create tension without constantly forcing it.

### 02 — Believability over scale

A smaller believable world is better than a massive empty one.

### 03 — Discovery over exposition

Let players notice things themselves.

### 04 — Quality over quantity

Every asset, system and location should have a reason to exist.

### 05 — Architecture before content

Build systems that can support the final game before creating massive amounts of content.

### 06 — Progressive development

Never attempt to build the entire game in one operation.

---

# 🌒 THE QUESTION

The player begins on one side.

They believe they understand the world.

Then something changes.

A place is different.

A road leads somewhere it shouldn't.

A building exists where it didn't before.

A familiar location becomes unfamiliar.

And eventually, the player discovers:

> **There is another side.**

---

## ⚙️ CURRENT BUILD

**Development phase:** `M1 — C++ Core Framework`

**Engine:** `Unreal Engine 5.8.3`

**Status:** `🟣 ACTIVE DEVELOPMENT`

---

<p align="center">

### 🌒 THE OTHER SIDE

*Reality is only one version of the story.*

</p>
