<h1 align="center">Pablo Villanueva</h1>
<p align="center">
  Gameplay Programmer · C++ · Unreal Engine 4 & 5
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Engine-Unreal%20Engine%205-black?style=flat-square&logo=unrealengine" />
  <img src="https://img.shields.io/badge/Language-C%2B%2B-00599C?style=flat-square&logo=c%2B%2B" />
</p>

---

## About

C++ Gameplay Programmer with 2+ years of professional experience shipping games in Unreal Engine 4 and 5. Generalist by nature — across my professional work I've covered GAS architecture, multiplayer networking, performance optimization, UI, and tooling depending on what the project needed.

Currently building low-level depth beyond the engine: custom memory allocators, a dynamic array with manual memory management, and a simplified ECS — driven by a genuine interest in understanding the systems underneath UE5's abstractions. I integrate AI-assisted development as a deliberate practice: using LLMs to accelerate iteration while critically reviewing and owning every line of generated code.

Targeting an entry-level role at an AA or AAA studio. Open to relocation.

---

## Professional Experience

**Scubalight Studios — Junior Gameplay Programmer** (2+ years, 2021–2023)

Shipped two titles across UE4 and UE5 in a 3-person programming team.

- Sole architect of the GAS foundation on *Don't Kill Rumble*: base character, attributes, ability pipeline, and ability examples from scratch
- Led multiplayer networking foundations, establishing replication patterns used across the project
- Promoted to lead programmer after demonstrating end-to-end project ownership
- Inherited a shipping game (*Junior Solutions*) running at 25–30 FPS; profiled and optimized CPU, GPU, and RAM usage to reach a stable 60 FPS
- Reduced Blueprint Tick calls by an estimated 80%+ through profiling, refactoring, and event-driven replacements
- Built an in-game developer menu for runtime testing and QA tooling

---

## Low-Level Projects

These projects exist to build understanding of systems that engines abstract away — not to reinvent them, but to reason about them clearly.

**[Simple-ECS](https://github.com/Pablyco/Simple-ECS)**
A simplified Entity Component System implemented in C++. Built to understand data-oriented architecture and how component-based design works at the memory level.

**[Allocators](https://github.com/Pablyco/Allocators)**
Custom memory allocators in C++: linear/bump, pool, and stack. Built to understand allocation strategies, fragmentation tradeoffs, and manual memory management patterns used in game engines.

**[Custom-Vector](https://github.com/Pablyco/Custom-Vector)**
A dynamic array container implemented in C++20 with manual memory management. Built to understand how contiguous storage, growth strategies, and move semantics work beneath STL abstractions.

---

## Shipped Games

**[Chester the Chest](https://store.steampowered.com/app/2506390/)**
<div align="center">
  <a href="https://store.steampowered.com/app/2506390/">
    <img src="https://cdn.akamai.steamstatic.com/steam/apps/2506390/header.jpg" width="600">
  </a>
</div>

- Decoupled reactive inventory system using Delegates, allowing multiple systems to respond to state changes without circular dependencies
- Dynamic attribute modifier architecture to alter Character Controller parameters in real time

**[Through His Eyes](https://store.steampowered.com/app/3520830/)**
<div align="center">
  <a href="https://store.steampowered.com/app/3520830/">
    <img src="https://cdn.akamai.steamstatic.com/steam/apps/3520830/header.jpg" width="600">
  </a>
</div>

- Interaction system using Constraints and Linear Drives for realistic player-controlled mechanical manipulation
- Async Level Streaming pipeline managing memory across secondary threads to eliminate transition latency
- Data-driven inspection pipeline using Data Assets, allowing designers to integrate objects without code changes
- Context-aware narrative system using a priority queue and Gameplay Tags to trigger dialogue based on player state

---

## Tech Stack

| Area            | Tools                                          |
| --------------- | ---------------------------------------------- |
| Language        | C++                                            |
| Engine          | Unreal Engine 4 & 5                            |
| Version Control | Git, Perforce                                  |
| Audio           | FMOD                                           |
| Patterns        | GAS, Data-Driven Design, ECS, OOP              |

---

## Contact

[pablofvillanueva@outlook.com](mailto:pablofvillanueva@outlook.com)
[linkedin.com/in/pablofvillanueva](https://linkedin.com/in/pablofvillanueva)
[pablyco.github.io/portfolio](https://pablyco.github.io/portfolio)
