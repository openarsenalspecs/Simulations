# Pelagia

## The Open Specification for Living Ocean Worlds

### The Ocean Lives Beyond the Player.

Pelagia is an open, modular specification for creating living underwater worlds focused on exploration, spearfishing, diving, marine ecosystems, ocean discovery, research, conservation, and multiplayer aquatic experiences.

Unlike traditional underwater games where the environment exists only as a backdrop for the player, Pelagia defines the ocean as a persistent, evolving ecosystem. Marine life migrates, habitats change, weather affects conditions, discoveries remain, and the world continues to exist whether the player is present or not.

Pelagia provides a standardized architecture for developers to create underwater simulations ranging from realistic diving experiences to expansive ocean exploration worlds.

The specification is designed around modular systems, allowing individual features to be implemented independently while maintaining compatibility with the larger Pelagia ecosystem.

---

# Vision

Pelagia aims to establish an open standard for creating immersive ocean environments where players can:

- Explore unknown waters
- Become skilled divers
- Master spearfishing techniques
- Discover hidden underwater locations
- Map unexplored regions
- Recover lost treasures
- Study marine life
- Photograph wildlife
- Conduct research
- Restore ecosystems
- Build underwater businesses
- Compete with other explorers

The ocean is not a level.

The ocean is a living world.

---

# Design Principles

## Modular Architecture

Every major feature is designed as an independent module.

Developers can:

- Enable only required systems
- Replace individual components
- Create custom extensions
- Share compatible content
- Expand implementations without modifying the core specification

---

## Living Environment

The world continues operating beyond player interaction.

Systems simulate:

- Migration
- Feeding
- Breeding
- Population changes
- Weather patterns
- Ecosystem recovery
- Environmental changes

---

## Skill-Based Progression

Player advancement is based on:

- Training
- Knowledge
- Exploration
- Experience
- Equipment mastery
- Research accomplishments

---

## Open Interoperability

Pelagia defines shared formats for:

- Species data
- Equipment
- Maps
- Biomes
- Missions
- Environmental states
- Player progression
- Community extensions

---

# Core Modules

---

# CharacterCore

CharacterCore provides player identity and avatar management.

Features:

- Character creation
- Facial customization
- Body customization
- Hairstyles
- Skin customization
- Tattoos
- Scars
- Accessories
- Multiple character profiles
- Animation standards
- Multiplayer synchronization

Character appearance remains separate from gameplay advantages.

---

# ApparelCore

ApparelCore manages land-based clothing.

Supported clothing:

- Shirts
- Jackets
- Hoodies
- Pants
- Shorts
- Fishing apparel
- Outdoor clothing
- Hats
- Sunglasses
- Backpacks
- Accessories

Players may create outfit presets:

- Casual
- Expedition
- Research
- Charter
- Tournament
- Exploration

---

# SwimwearCore

SwimwearCore manages surface and swimming apparel.

Supported items:

- Swim trunks
- Board shorts
- Rash guards
- One-piece suits
- Two-piece suits
- Thermal swimwear
- UV protection clothing
- Water shoes

---

# DiveGearCore

DiveGearCore defines diving equipment customization.

## Masks

Supports:

- Standard masks
- Low-volume masks
- Prescription lenses
- Custom designs

## Snorkels

Supports:

- Traditional snorkels
- Dry snorkels
- Flexible systems

## Fins

Supports:

- Freediving fins
- Split fins
- Carbon fiber fins
- Fiberglass fins

## Wetsuits

Supports:

- Full suits
- Short suits
- Hooded suits
- Thermal systems
- Custom patterns

## Accessories

Supports:

- Gloves
- Boots
- Weight systems
- Dive computers
- Safety equipment

---

# EquipmentCore

EquipmentCore manages functional diving equipment.

Supported equipment:

- Pole spears
- Hawaiian slings
- Beginner spearguns
- Advanced spearguns
- Roller spearguns
- Pneumatic spearguns
- Blue-water spearguns
- Spear shafts
- Reels
- Float systems
- Recovery equipment

Equipment progression depends on:

- Certification
- Materials
- Player skill
- Maintenance
- Experience

---

# ProgressionCore

ProgressionCore manages player advancement.

Tracks:

- Diving experience
- Certifications
- Equipment mastery
- Exploration achievements
- Research reputation
- Competition rankings

---

# TrainingCore

TrainingCore provides certification paths.

## Freediver Certification

Unlocks:

- Longer dives
- Breath control
- Improved recovery

## Spearfishing Certification

Unlocks:

- Advanced spears
- Species knowledge
- Hunting techniques

## Cave Diver Certification

Unlocks:

- Cave exploration
- Tunnel navigation
- Specialized equipment

## Technical Diver Certification

Unlocks:

- Extreme depth exploration
- Advanced systems

## Research Diver Certification

Unlocks:

- Scientific missions
- Marine surveys

## Salvage Diver Certification

Unlocks:

- Wreck exploration
- Recovery operations

---

# PhysiologyCore

PhysiologyCore simulates diver condition.

Tracks:

- Oxygen
- Carbon dioxide buildup
- Heart rate
- Stress
- Fatigue
- Cold exposure
- Hydration
- Recovery

---

# Ocean Simulation Modules

---

# WorldGenCore

Procedural ocean generation.

Creates:

- Oceans
- Islands
- Reefs
- Kelp forests
- Mangroves
- Trenches
- Caves
- Volcanic areas
- Deep-water environments

Generation factors:

- Climate
- Temperature
- Currents
- Depth
- Geological history
- Biodiversity

---

# OceanLifeCore

Creates persistent marine ecosystems.

Simulates:

- Migration
- Feeding cycles
- Breeding
- Predator relationships
- Population movement
- Habitat changes

---

# EcologyCore

Manages environmental balance.

Tracks:

- Coral health
- Biodiversity
- Species populations
- Habitat quality
- Environmental damage

Players can:

- Restore reefs
- Clean pollution
- Protect habitats
- Support conservation

---

# FishCore

Provides the marine species database.

Each species contains:

- Common name
- Scientific name
- Habitat
- Depth range
- Temperature preference
- Behavior profile
- Feeding patterns
- Migration patterns
- Rarity
- Value

---

# Fish Elusiveness System

Higher-value species become increasingly difficult.

Factors:

- Detection difficulty
- Swimming speed
- Awareness
- Habitat difficulty
- Camouflage
- Rarity
- Behavior

---

# WildlifeCore

Supports marine animals.

Includes:

- Sharks
- Dolphins
- Whales
- Rays
- Turtles
- Seals
- Octopus
- Crustaceans
- Jellyfish

---

# OceanAI

Provides adaptive marine behavior.

Animals respond to:

- Player activity
- Hunting pressure
- Environment
- Weather
- Habitat changes

---

# Exploration Modules

---

# MapCore

Creates underwater mapping systems.

Features:

- Sea floor mapping
- Depth charts
- Reef mapping
- Cave mapping
- Secret entrances
- Tunnel discovery
- Waypoints
- Exploration tracking

---

# CaveCore

Procedural underwater cave systems.

Features:

- Hidden entrances
- Underground tunnels
- Caverns
- Air pockets
- Underground lakes
- Rare discoveries

---

# TreasureCore

Underwater treasure discovery.

Find:

- Gold
- Silver
- Gems
- Pearls
- Jewelry
- Artifacts
- Lost cargo
- Crafting materials

---

# WreckCore

Shipwreck exploration.

Supports:

- Cargo ships
- Fishing vessels
- Military wrecks
- Aircraft
- Submarines
- Ancient vessels

Features:

- Interior exploration
- Salvage
- Historical discoveries
- Hidden compartments

---

# ArchaeologyCore

Underwater archaeology.

Discover:

- Ruins
- Fossils
- Ancient artifacts
- Lost technology
- Historical objects

---

# ResearchCore

Scientific exploration.

Activities:

- Species identification
- Water sampling
- Marine surveys
- Fish tagging
- Reef monitoring

---

# PhotographyCore

Underwater photography.

Features:

- Wildlife photography
- Documentation
- Research photography
- Image sales
- Photo competitions

---

# Gameplay Modules

---

# BaitCore

Advanced bait and chum system.

Features:

- Bait shops
- Natural bait
- Fish oils
- Species attractants
- Custom chum recipes

Advanced divers unlock:

- Premium chum
- Deep-water attractants
- Rare species formulas

---

# CraftingCore

Resource-based crafting.

Create:

- Spears
- Speargun components
- Equipment upgrades
- Tools
- Custom gear

---

# EconomyCore

Dynamic economy.

Supports:

- Fish sales
- Treasure markets
- Gem trading
- Equipment purchases
- Regional pricing

---

# TradeCore

Player commerce.

Supports:

- Dive shops
- Charter businesses
- Research companies
- Equipment stores
- Salvage operations

---

# BoatCore

Ocean transportation.

Supports:

- Kayaks
- Fishing boats
- Charter boats
- Research vessels
- Offshore vessels

Features:

- Storage
- Navigation
- Equipment transport
- Crew support

---

# MissionCore

Dynamic missions.

Examples:

- Species surveys
- Treasure recovery
- Mapping expeditions
- Conservation tasks
- Research projects
- Rescue missions

---

# ExpeditionCore

Procedural adventures.

Generates:

- Unknown reefs
- Rare species encounters
- Hidden caves
- Lost wrecks
- Scientific discoveries

---

# CompetitionCore

Competitive events.

Supports:

- Spearfishing tournaments
- Photography contests
- Mapping challenges
- Discovery rankings

---

# MultiplayerCore

Multiplayer support.

Features:

- Cooperative diving
- Shared maps
- Team expeditions
- Trading
- Clubs
- Community events

---

# BaseCore

Player-owned locations.

Create:

- Dive shops
- Research stations
- Marinas
- Beach homes
- Underwater habitats

Display:

- Trophies
- Maps
- Photos
- Artifacts
- Collections

---

# SurvivalCore

Optional survival mechanics.

Tracks:

- Food
- Water
- Supplies
- Equipment condition
- Emergency resources

---

# Developer Modules

---

# OceanDataCore

Standardized data exchange.

Defines formats for:

- Fish libraries
- Equipment
- Maps
- Missions
- Biomes
- Environmental states

---

# ModdingCore

Community extension framework.

Supports:

- New species
- New regions
- New equipment
- New missions
- New ecosystems
- Cosmetic content

---

# Intended Applications

Pelagia can support:

- Spearfishing games
- Diving simulators
- Ocean exploration games
- Marine research simulations
- Educational platforms
- Conservation experiences
- Survival games
- Multiplayer ocean worlds

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
  - [https://roxanneardary.com/pelagia/](https://roxanneardary.com/pelagia/)  

---

## License & Notice Requirements

Pelagia is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to any Open Arsenal project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.
- Pelagia specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.
