# 🌱 Organic Waste Shredding and Selection System — Scale Prototype

<div align="center">

![Universidad Mariana](https://img.shields.io/badge/University-Mariana-green?style=for-the-badge)
![Mechatronics Engineering](https://img.shields.io/badge/Program-Mechatronics%20Engineering-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed%202025-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-orange?style=for-the-badge)

**Undergraduate thesis to obtain the degree of Mechatronics Engineer**

 · [🔧 Hardware](hardware/) · [🧪 Results](tests/) · [📸 Gallery](media/)

</div>

---

## 📋 Project Overview

This repository contains all technical documentation, design files, electrical control , and experimental results for the **1:4 scale prototype** of an organic waste shredding and selection system. The prototype was developed for the **pilot composting plant of the La Mesa community**, municipality of Samaniego, department of Nariño, Colombia.


<!-- The project is part of the **Biocompost2** program, funded by **Minciencias** (Colombia's Ministry of Science) with COP $100,000,000 through the *Ciencia Cierta* competition, with an additional COP $2,000,000 contribution from **Universidad Mariana** for prototype construction. -->

### Problem Context

- 🌍 Over **2 billion tonnes** of waste are produced globally each year — 50% of which is organic
- 🇨🇴 Colombia generates ~**12 million tonnes** of waste annually, recycling only 17%
- 📍 The municipality of Samaniego (Nariño) registers over **2,000 tonnes/year** of solid waste with inadequate management, resulting in environmental sanctions from Corponariño

---

## 🎯 Objectives

**General Objective:** Develop a 1:4 scale prototype of the shredding and waste selection process for the Biocompost2 pilot composting plant of the La Mesa community, Samaniego, Nariño.

**Specific Objectives:**
1. Research biocomposting technologies to identify performance specifications that guide prototype construction
2. Design and build the 1:4 scale prototype of the shredding, selection, and control systems
3. Verify prototype performance through experimental testing

---

## ⚙️ Prototype Components

The system consists of two main subsystems:

### 🔪 Shredder Mill (1:4 Scale)

| Parameter | Full-Scale Design | Prototype (1:4) |
|---|---|---|
| Type | Double-shaft blade mill | Double-shaft blade mill |
| Blade material | Stainless steel AISI 304 | PLA (3D printed) |
| Frame material | Steel | MDF + Plywood + PLA |
| Transmission | Gear system | Gear system (PLA) |
| Motor | — | Gearmotor 6 RPM, 91 kg·cm |
| Target mass flow | 1,732 kg/h | Scaled proportionally |
| Number of blades | — | 28 blades, 15° offset each |

**Material specifications for shredding:**
- Type: Wet organic waste (fruits, vegetables, food scraps, dry leaves)
- Density: 200 kg/m³
- Shear strength: 0.7 MPa
- Waste thickness: ~30 mm

### 🏭 Conveyor Belt (1:4 Scale)

| Parameter | Full-Scale Design | Prototype (1:4) |
|---|---|---|
| Belt width | 1.0 m | 0.4 m |
| Belt length | 6.0 m | 0.75 m |
| Belt speed | 0.2 m/s | 0.01 m/s |
| Drive system | Chain transmission | Chain transmission |
| Tensioner | Screw tensioner | Screw tensioner |
| Rollers | Flat support rollers | Flat support rollers |
| Full-scale efficiency | 8,475.84 kNem/hr | 26.49 kNem/hr |

---

## 🏗️ Repository Structure

```
shredding-waste-thesis/
│
├── 📄 docs/                          # Academic and technical documentation
│   ├── thesis/
│   │   ├── thesis_final.pdf          # Full thesis document
│   │   └── chapters/                 # Chapters in Markdown
│   ├── technical/
│   │   ├── tech_report.pdf           # Prototype technical report
│   │   ├── design_calculations.pdf   # Engineering calculations
│   │   └── system_specs.md           # Technical specifications
│   ├── regulatory/
│   │   ├── standards.md              # Applicable technical standards
│   │   └── environmental_norms.md    # Colombian environmental regulations
│   ├── presentations/
│   │   ├── proposal_presentation.pptx
│   │   └── final_presentation.pptx
│   └── references/
│       ├── bibliography.bib
│       └── literature_review.md
│
├── 🔧 hardware/                      # Physical prototype design
│   ├── cad_designs/
│   │   ├── shredder/                 # 3D designs — shredder mill
│   │   └── conveyor_belt/            # 3D designs — conveyor belt
│   ├── electrical/
│   │   ├── shredder_circuit.pdf      # Shredder electrical diagram
│   │   └── conveyor_circuit.pdf      # Conveyor belt electrical diagram
│   ├── BOM.xlsx                      # Bill of materials and costs
│   └── assembly.md                   # Assembly manual
│
<!-- ├── 💻 software/                      # Control code
│   ├── control/                      # System control logic
│   ├── hmi/                          # Control panel (buttons & interface)
│   └── requirements.txt -->
│
├── 🧪 tests/                         # Testing and validation
│   ├── raw_data/                     # Raw experimental data
│   ├── analysis/                     # Statistical analysis
│   ├── protocols.md                  # Testing protocols
│   └── results_charts/               # Result graphs and plots
│
├── 🖼️ media/                         # Visual assets
│   ├── photos/                       # Prototype photographs
│   ├── videos/                       # Operation videos
│   └── diagrams/                     # System diagrams
│
├── README.md                         # This file
├── LICENSE                           # CC BY-NC 4.0
└── CHANGELOG.md                      # Version history
```

---

## 🧑‍🔬 Methodology

The project followed three development phases:

**Phase 1 — Research & Analysis**
Literature review of biocomposting technologies, shredder types, and conveyor systems. Selection through weighted decision matrices: the **double-shaft blade mill** (Design 4, score 7.9/10) and the **chain-driven flat conveyor belt** (Alternative 3, score 43/52) were selected as the optimal designs.

**Phase 2 — Design & Construction**
Full mechanical engineering calculations (mass flow rate, volumetric flow, shear forces, torque, motor power, shaft diameter, static analysis), 3D CAD design, and PLA 3D printing of all prototype components.

**Phase 3 — Testing & Evaluation**
Functional verification of the full system — organic waste shredding and conveyor transport — with parameter adjustments based on experimental results.

---

## 📊 Key Results

- ✅ Justified selection of the three-level system architecture (cost < benefit) as optimal configuration
- ✅ Full 3D CAD design of the real shredder mill and 1:4 scale prototype
- ✅ Full 3D CAD design of the real conveyor belt and 1:4 scale prototype
- ✅ Electrical diagrams for both subsystems
- ✅ Functional prototype built with PLA, MDF, and plywood
- ✅ Prototype validated through experimental trials

---

## 👥 Authors

| Name | Role |
|---|---|
| **Carlos Andrés Bernal Carvajal** | Author |
| **Manuel Felipe Bastidas Díaz** | Author |
| **Steven Alexander Pérez Yela** | Author |

**Advisors:**
- Dr. Ing. Richard Geovanni Morán Perafán
- Mg. Fabio Camilo Gómez Meneses

**Institution:** Universidad Mariana — Faculty of Engineering, Mechatronics Engineering Program  
**City:** San Juan de Pasto, Nariño, Colombia  
**Year:** 2025

---

## 🤝 Affiliated Organizations

| Organization | Role |
|---|---|
| **Minciencias** | Primary funder — *Ciencia Cierta* program (COP $100,000,000) |
| **Universidad Mariana** | Research group & additional funding (COP $2,000,000) |
| **La Mesa Community, Samaniego** | Beneficiary — Biocompost2 project |

---

## 📑 Regulatory Framework

| Regulation | Description |
|---|---|
| Resolution 1407 / 2018 | Management of packaging waste (Colombia) |
| Decree 2981 / 2013 | Public solid waste collection service |
| Law 99 / 1993 | National Environmental System (SINA) |
| Applicable NTC | Colombian technical standards for solid waste |

---

## 📄 License

This work is distributed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.  
You are free to share and adapt the material with attribution, provided it is not used for commercial purposes.

---

## 📬 Contact

For academic or technical inquiries related to this project, please contact the **Faculty of Engineering, Universidad Mariana**, San Juan de Pasto, Nariño, Colombia.

---

<div align="center">
<sub>Undergraduate Thesis — Mechatronics Engineering — Universidad Mariana — 2025</sub><br>
<sub>Biocompost2 Project — La Mesa Community, Samaniego, Nariño, Colombia</sub>
</div>
