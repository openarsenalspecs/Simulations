# 🍃 Agility Ascension

**From practice fields to global trials.**

Agility Ascension is a 5+ friendly open-source dog agility training and competition simulation game where players form a **handler–dog team**, build agility skills, and progress through structured training, distraction environments, distance handling challenges, and multiplayer global trials.

Players can switch between:
- 🧑 Handler Mode — command timing, strategy, and distance control  
- 🐕 Dog Mode — movement execution, responsiveness, and focus under pressure  

---

## 🌱 Core Philosophy

Agility Ascension is built around a simple idea:

> Skill is not just speed—it is clarity, trust, timing, and control under increasing complexity.

The game simulates real agility training progression:
- learn fundamentals  
- train under distraction  
- master distance handling  
- compete in structured trials  
- evolve into multiplayer competition  

---

# 🎮 Core Features

## 🏁 Training System (Practice Fields)

- Structured beginner-friendly agility environments  
- Core obstacles:
  - jumps  
  - tunnels  
  - weave poles  
  - A-frames  
  - pause tables  
- Repetition-based skill learning  
- Treat-based XP reward system  
- Progressive unlock system for advanced mechanics  

---

## 🍃 Leaf Module (Environmental Distraction System)

A full environmental simulation system that introduces layered distractions.

### 🌿 Leaf System (Baseline Layer)
- wind-driven leaf simulation across all fields  
- deterministic physics for fairness  
- scalable density (calm drift → storm chaos)  
- obstacle interaction (bounce, redirect, cluster behavior)  

### 🐕 Animal Distractions
- parallel running dogs  
- squirrels, birds, edge movement  
- decoy agility animals  
- ambient barking/audio cues  

### 🎾 Object Distractions
- rolling balls across lanes  
- bouncing toys near obstacles  
- fluttering flags and fabric strips  
- wind-driven props  

### 👥 Human / Crowd Distractions
- cheering spectators  
- judges moving along field edges  
- camera flashes and motion  
- off-course handler noise  

### 🌪 Environmental Effects
- wind gust spikes  
- lighting and shadow shifts  
- surface noise variation  
- weather simulation (light rain, damp ground)  

---

## 📊 Leaf Pressure Rating (LPR)

Unified difficulty system controlling all environmental layers:

| Level | Description |
|------|-------------|
| 0 | No distractions |
| 1 | Leaves only |
| 2 | Leaves + objects |
| 3 | Animals added |
| 4 | Crowd + layered chaos |
| 5 | Championship-level simulation |

---

## 📡 Distance Training Module

Advanced handling system where the human remains stationary while guiding the dog remotely.

### Distance Levels
- 🟢 Close Range — full movement support  
- 🟡 Mid Range — partial separation control  
- 🔵 Long Range — stationary handler gameplay  
- 🔴 Extreme Range — full remote execution courses  

### Core Mechanics
- command chains (multi-step instructions)  
- anchor commands (focus zones)  
- delayed release timing  
- line-of-sight prediction tools  

### Dog Behavior Evolution
- increased independence at higher ranges  
- intent-completion behavior  
- stronger reliance on memory windows  
- trust-based execution systems  

---

## 🏁 Trial System (Competitive Progression)

Ranked agility progression system:

- Novice  
- Intermediate  
- Advanced  
- Excellent  
- Master  
- Champion  

### Scoring Factors
- completion time  
- accuracy  
- synchronization  
- distance performance  
- distraction resistance (LPR)  

---

## 🧑‍🤝‍🐕 Character System

### Handler
- customizable avatars  
- personality traits  
- training styles  

### Dog
- breed selection (real + stylized)  
- temperament traits:
  - eager  
  - cautious  
  - fast  
  - precise  

### Team System
- bond level  
- responsiveness rating  
- focus stability  
- distance trust rating  

---

## 🌐 Multiplayer Module (Future Expansion)

A scalable competitive and cooperative system built for shared agility experiences.

### Multiplayer Modes
- 🤝 Cooperative Training  
- 🏁 Competitive Trials  
- 🧠 Asynchronous Ghost Racing  
- 🌍 Community Hosted Servers  

### Multiplayer Features
- seeded identical environments  
- synchronized Leaf Module (LPR fairness)  
- ranked leaderboards  
- replay-based validation system  

---

## 🔁 Replay System

- fully deterministic run recording  
- ghost competition system  
- performance analysis tools  
- fairness verification via replay playback  

---

## ⚙️ Server Architecture (Planned)

- Match Orchestrator (course + rules + LPR)  
- Leaf Simulation Engine (deterministic environment)  
- Distance Controller Sync System  
- Score Validator (open algorithm)  
- Replay Recorder  

---

## ♿ Accessibility Features

- reduced motion Leaf mode  
- visual clarity overlays  
- optional training assistance tools  
- scalable difficulty for all ages  

---

## 🌱 Modularity

Agility Ascension is designed as a fully modular system:

- Leaf Module can be extended or modified  
- new distraction packs can be added  
- custom agility courses supported  
- multiplayer rulesets are configurable  
- open-source community expansion encouraged  

---

## Specification Branding License (SBL)

### Standard
- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/agility-ascension/](https://roxanneardary.com/agility-ascension/)

---

# ⚖️ License & Notice Requirements

Agility Ascension is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- Agility Ascension specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.

---

# 🌍 Project Vision

Agility Ascension is designed to evolve from:

> practice fields → distraction mastery → distance control → competitive trials → global multiplayer agility ecosystem

A system where skill is built through **focus, trust, and clarity under complexity**.
