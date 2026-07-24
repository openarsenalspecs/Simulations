# StructIQ

**Tagline:** *Intelligence in Every Beam*  
**License:** AGPL 3.0+  
**Website:** [roxanneardary.com](https://www.roxanneardary.com/)  
**Repository:** Monolithic GitLab Repository  

---

## Overview

StructIQ is an open-source, AI-assisted structural engineering platform designed to **simulate, optimize, and innovate building designs** using classical FEM (Finite Element Method) while integrating **AI for real-time suggestions and predictive analysis**.  

Key goals:  

- Full **traditional FEM core** with AI support  
- **Global code compliance** (US codes included, modular for any country/local codes)  
- **Digital twin capabilities** for real-time simulation  
- **Predictive structural behavior**, including earthquakes, wind, and dynamic loads  
- **Education and research-friendly** platform  
- Fully **modular, future-proof, and scalable**  

StructIQ is licensed under **AGPL 3.0+**, requiring attribution to **Roxanne Ardary** and [roxanneardary.com](https://www.roxanneardary.com/) in all copies and derivative works.

---

## Features Checklist

The following is a comprehensive, modular feature checklist for StructIQ:  

### 1. Advanced Structural Analysis
- [ ] Linear Static Analysis  
- [ ] P-Delta Analysis  
- [ ] Nonlinear Static Analysis  
- [ ] Modal Analysis  
- [ ] Response Spectrum Analysis  
- [ ] Nonlinear Dynamic Time-History Analysis  
- [ ] Soil-Structure Interaction (SSI)  
- [ ] Progressive Collapse Analysis  
- [ ] Thermal & Fire Response Modeling  
- [ ] Construction Sequence Simulation  
- [ ] Seismic Retrofitting Modules  

### 2. AI & Optimization Enhancements
- [ ] Multi-Objective Optimization (cost, weight, strength, drift)  
- [ ] Automated Material Selection  
- [ ] Topology Optimization  
- [ ] Evolutionary Design Generation  
- [ ] Real-Time Design Suggestions  
- [ ] Knowledge Base Integration  

### 3. Digital Twin & Simulation Enhancements
- [ ] Real-Time Sensor Integration  
- [ ] Surrogate Model Acceleration (PINNs / fast approximations)  
- [ ] Scenario Analysis / “What-if” Simulations  
- [ ] Predictive Maintenance Modeling  
- [ ] VR/AR Visualization of Structural Responses  
- [ ] Multi-Scale Simulation  

### 4. Global Building Code & Regulatory Support
- [ ] Modular Code Plugins  
  - [ ] U.S. Codes (IBC, ASCE 7, AISC, ACI, NDS, TMS)  
  - [ ] EU / Eurocodes  
  - [ ] Japan / JIS  
  - [ ] Local / Municipal Codes  
- [ ] Automatic Compliance Checks  
- [ ] Code Update Notifications  
- [ ] Customizable Safety Margins  

### 5. Workflow, Collaboration & Reporting
- [ ] Integrated Project Management  
- [ ] Version Control of Designs (Git-friendly)  
- [ ] Export to BIM / IFC / CAD  
- [ ] Automated Reporting (PDF / HTML / Compliance Sheets)  
- [ ] Collaboration Layer (multi-engineer simultaneous editing)  

### 6. Accessibility & Scalability
- [ ] Desktop Version  
- [ ] Cloud-Based Platform  
- [ ] GPU Acceleration Support  
- [ ] Plugin API for Future Modules  
- [ ] Mobile Dashboard / Remote Monitoring  

### 7. Future-Proof / Advanced AI Features
- [ ] Autonomous “Design Checker” Mode  
- [ ] Cross-Domain Integration  
- [ ] Knowledge Sharing / Community Library  
- [ ] Adaptive Learning (AI learns from past projects)  
- [ ] Generative AI for Innovative Structural Forms  

### 8. Core FEM Engine
- [ ] Beam-Column 2D / 3D Elements  
- [ ] Shell Elements  
- [ ] Solid Elements  
- [ ] Timoshenko & Euler Beams  
- [ ] Nonlinear Hinges  
- [ ] Material Nonlinearity (Concrete, Steel, Wood, Composite)  
- [ ] Contact / Friction Modeling  
- [ ] Spring / Damper Elements  
- [ ] Multi-Surface Plasticity Models  

### 9. Earthquake & Hazard Response
- [ ] Nonlinear Dynamic Solvers  
- [ ] Time-Stepping Integrators  
- [ ] Rayleigh Damping Models  
- [ ] Ground Motion Records Integration (PEER Compatible)  
- [ ] Hinge Formation & Energy Dissipation Tracking  

### 10. AI Assistance Layer
- [ ] Design Innovation Suggestions  
- [ ] Optimization Assistance  
- [ ] Earthquake Performance Enhancements  
- [ ] Real-Time Digital Twin Integration  
- [ ] PINNs for Fast Approximate Simulations  
- [ ] GNNs for Structural Topology Analysis  
- [ ] LLM-Based Code Reasoning & Suggestions  
- [ ] Evolutionary Design Optimization  

### 11. Advanced Visualization & Interaction
- [ ] Real-time Interactive Dashboards  
- [ ] Multi-angle, Animated FEM Deformation Visualizations  
- [ ] AR Overlays for On-Site Engineers  
- [ ] WebGL-Based Browser Simulations for Lightweight Access  
- [ ] Heatmaps of Stress, Strain, Drift, and Safety Factor Zones  

### 12. Education & Training Mode
- [ ] Guided Tutorials for Students / Engineers  
- [ ] Interactive “Sandbox” Mode for Safe Experimentation  
- [ ] Step-by-Step Visualization of Load Distribution and Failure Mechanisms  
- [ ] Challenge Mode: AI Sets Structural Problems for Learning  

---

## Repository Structure
```text
atlasstruct/
fem_core/
codes/
ai_assistant/
geometry/
ui/
exporters/
examples/
docs/
tests/
License
README.md
docs/Workflow.md
```

---

## Contribution Guidelines

Contributions are welcome! Please follow standard GitLab fork, branch, and merge request workflows. Ensure:  

- Compliance with **AGPL 3.0+**  
- Attribution to **Roxanne Ardary, [roxanneardary.com](https://www.roxanneardary.com/)**  
- No inclusion of email addresses in files  

Refer to `docs/Workflow.md` for detailed contribution and coding standards.

---

## Disclaimer

StructIQ is provided **“as is”**, with **no warranty**. Users are responsible for:

- Verifying designs  
- Compliance with local building codes  
- Safe engineering practices  

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
  - [https://roxanneardary.com/structiq/](https://roxanneardary.com/structiq/)

---

## License & Notice Requirements

StructIQ is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- StructIQ Specificiations are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.
