# GrowLocal

**Every Skill Counts. Every Resource Matters.**

GrowLocal is an open-source, AI-assisted, modular town and civilization simulation engine designed to model how real communities can sustainably develop using local skills, resources, and cooperative systems. It transforms real-world towns into living simulations where economy, environment, infrastructure, and human behavior interact dynamically.

Built under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**, GrowLocal is designed as a fully transparent, forkable, and community-driven simulation platform.

---

## 🌱 Vision

GrowLocal simulates what becomes possible when:
- Every local resource is recognized and utilized
- Every skill in a community has value
- Economic systems are cooperative rather than extractive
- Environmental systems are respected as active constraints, not background scenery

The goal is not just simulation—it is **systemic understanding of how towns survive and thrive**.

---

## 🧩 Core Philosophy

- Open source by default  
- Real-world data driven  
- AI-assisted but not AI-dependent  
- Modular and extensible architecture  
- Transparent simulation logic  
- Community-first economic modeling  
- Deterministic and reproducible systems  

---

## 🌍 Full Feature List

### 🧩 1. Core Modular Architecture
- Plugin-based simulation engine with hot-loadable modules  
- Standardized simulation API contracts  
- Independent systems for economy, environment, population, governance, and industry  
- Community-developed extensions under AGPL 3.0+  
- Deterministic simulation core for reproducible outcomes  

---

### 🏘️ 2. Town Simulation Core Module
- Import real-world towns using OpenStreetMap and GIS datasets  
- Procedural generation of missing infrastructure  
- Dynamic zoning:
  - Residential  
  - Commercial  
  - Industrial  
  - Agricultural  
  - Natural and public land  
- Time progression system (daily → seasonal → yearly cycles)  

---

### 🌍 3. Environmental Systems Module
- Forest growth and regeneration modeling  
- Water systems (rivers, lakes, groundwater flow, usage)  
- Soil health and agricultural viability  
- Climate and seasonal effects  
- Pollution tracking and ecological recovery  

---

### 🧠 4. Memory & Historical Simulation Layer
- Full chronological history of all simulation events  
- Replay system for entire town evolution  
- Generational simulation (families, institutions, skills)  
- Institutional memory (co-ops, businesses, governance bodies persist)  
- AI-generated historical explanations of outcomes  
- Branching timelines and simulation forks  

---

### 🤝 5. Cooperative Economy Module
- Community-owned production systems (co-ops, shared ventures)  
- Shared expense and resource pooling  
- Local trade networks between districts and towns  
- Supply and demand balancing based on real resources  
- Anti-monopoly and systemic stability balancing  

---

### 🧑‍🌾 6. Micro-Enterprise Emergence System
- Automatic detection of unmet local needs  
- Opportunity engine based on:
  - Skill distribution  
  - Resource availability  
  - Economic imbalance  
- Emergent business creation:
  - Repair shops  
  - Tool libraries  
  - Food co-ops  
  - Logistics services  
- Business lifecycle:
  - Formation → Growth → Failure → Reintegration  
- Innovation emergence from skill and resource clustering  
- Natural evolution into cooperative ownership models  

---

### 👷 7. Workforce & Skill Simulation Module
- Population modeled with skill trees and progression  
- Job matching system based on:
  - Skills  
  - Location  
  - Resource availability  
- Apprenticeship and training systems  
- Labor allocation for cooperative projects  

---

### 🌐 8. Federation of Towns (Meta Layer)
- Town-to-town trade and resource exchange  
- Regional economies across connected simulations  
- Migration based on opportunity and stability  
- Shared knowledge propagation across towns  
- Federated Town Nodes (independent or networked systems)  
- Optional decentralized global simulation network  

---

### 🏭 9. Industry & Production Module
- Convert vacant spaces into:
  - Workshops  
  - Micro-factories  
  - Food processing units  
  - Craft and manufacturing hubs  
- Full supply chain simulation (raw → processed → goods)  
- Industrial dependency tracking  

---

### 🌾 10. Food & Resource Production Module
- Backyard and urban agriculture systems  
- Fisheries and aquaculture simulation  
- Cooperative farming systems  
- Seasonal crop yield modeling  
- Local food security tracking  

---

### 🔍 11. Transparency & Debug Layer
- Full traceability of simulation decisions  
- “Why did this happen?” explanation engine  
- Live system graphs:
  - Economy flows  
  - Population changes  
  - Environmental impact  
- Rule inspector for simulation logic  
- Deterministic replay mode  
- Exportable audit logs for research  

---

### 🤖 12. AI Planning & Simulation Module
- AI-generated development suggestions  
- What-if scenario simulation engine  
- Resource optimization and forecasting  
- Risk detection (economic, environmental, social)  
- Cooperative planning assistance tools  

---

### 🎨 13. On-Demand Graphics Development Module
- Procedural generation of towns from simulation state  
- AI-assisted asset creation (buildings, infrastructure, landscapes)  
- Dynamic world evolution visuals  
- Multiple render modes:
  - Realistic  
  - Blueprint / planning  
  - Data visualization overlays  
- Level-of-detail system tied to simulation importance  

---

### 📊 14. Economic & Survival Simulation Module
- Local supply/demand-driven economy  
- Household-level cost-of-living simulation  
- Resource scarcity and abundance modeling  
- Survival based on skills and cooperation (not currency accumulation)  
- System balancing to prevent collapse loops  

---

### 🌐 15. Open Data Integration Module
- OpenStreetMap (geography and infrastructure)  
- USGS / NOAA (terrain, weather, water systems)  
- USDA / FAO (food systems, agriculture, fisheries)  
- Local government datasets (zoning, land use, buildings)  
- Continuous data ingestion pipelines  

---

### 🔓 16. Open Source Governance Layer (AGPL 3.0+)
- Licensed under GNU AGPL 3.0+  
- All network deployments must expose source modifications  
- Fully forkable and auditable simulation system  
- Community module registry  
- Designed as a public digital commons engine  

---

## 🛠️ Tech Stack (High Level)

- **Core Simulation:** Python (with optional Rust optimization modules)  
- **Backend:** FastAPI + Node.js (real-time systems)  
- **Database:** PostgreSQL + PostGIS, Redis  
- **Frontend:** Godot (primary) + optional React dashboard  
- **AI Layer:** LLaMA 3 / Mistral / Falcon (self-hosted capable)  
- **Geospatial:** OpenStreetMap, GDAL, GeoPandas  
- **Assets:** Blender + glTF pipeline  
- **Deployment:** Docker, Kubernetes, self-hostable Town Nodes  

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
  - [https://roxanneardary.com/growlocal/](https://roxanneardary.com/growlocal/)  

---

## 🔓 License & Notice Requirements

GrowLocal is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- GrowLocal specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.

---

## 🤝 Contributing

GrowLocal is fully open source and welcomes contributions in:

- Simulation systems  
- AI modules  
- Economic modeling  
- Environmental systems  
- UI/UX design  
- Geospatial integration  
- Documentation and research  

All contributions are subject to AGPL 3.0+ licensing.

---

## 🌱 Closing Vision

GrowLocal is not just a simulation—it is a framework for understanding how real communities function when every resource, skill, and decision is visible, connected, and meaningful.

**Build locally. Understand globally. Grow together.**
