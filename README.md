# 🪓 VikingSurvivors

**VikingSurvivors** is a high-performance, top-down "Survivor" style action-roguelike built with **Unity**. Set in a Norse-inspired world, players control a Viking warrior fending off endless swarms of Draugrs, Golems, and Ice Goblins. The project focuses on scalable AI systems, efficient projectile management, and dynamic character progression.

## 🎮 Core Gameplay Mechanics
* **Endless Swarm Survival:** Fight against escalating waves of diverse enemies with unique behaviors.
* **Dynamic Skill System:** Level up and choose from various upgrades like Fireballs, Sword Effects, and Crow Shields to enhance your combat capabilities.
* **Auto-Combat & Movement:** Optimized for a fluid experience using the **Unity Input System** for responsive movement.
* **Progression & Loot:** Collect XP and Health items dropped by enemies to survive and grow stronger.

## 🛠 Technical Features & Architecture
This project showcases clean and scalable game engineering principles:
* **Modular AI System:** Implements distinct AI logics (Draugr, Rock Golem, Ice Goblin) using a shared base for optimized performance and variety.
* **Projectile & VFX Optimization:** Efficient handling of multiple active projectiles and particle effects using optimized spawning systems.
* **Event-Driven UI:** Decoupled Level Up and Health UI systems that react to game state changes without tight coupling to core logic.
* **Physics & Tiling:** Integrated **SimpleTileManager** for efficient environment rendering and collision layers.

## 📁 Project Structure
```text
VikingSurvivors/
├── Assets/
│   ├── Scripts/        # Core gameplay, AI Controllers, and Skill Systems
│   ├── Prefabs/        # Reusable enemies, projectiles, and UI elements
│   ├── Sprites/        # Visual assets for Viking, enemies, and skills
│   └── Settings/       # URP profiles and input configurations
