# PCB_asurt — Altium PCB Design & Manufacturing Deliverables

This repository contains the design source files, schematic diagrams, PCB layouts, and manufacturing outputs (Gerber/NC Drill files) for the **PCB_asurt** hardware project.

---

## 📌 Project Overview


* **Project File:** `pcb_asurt.PrjPcb`
* **Schematic File:** `pcb_asurt.SchDoc`
* **PCB File:** `PCB1.PcbDoc`
*  **Screenshots:** `Screenshot 2026-09-08 181827.png` `Screenshot 2026-09-08 181838.png` `Screenshot 2026-09-08 181902.png` `Screenshot 2026-09-08 181911.png` 
---

## 📁 Repository Structure

```text
├── pcb_asurt.PrjPcb            # Main Altium Designer Project file
├── pcb_asurt.SchDoc            # Circuit schematic design sheet
├── PCB1.PcbDoc                 # PCB layout and routing file
├── Project Outputs for PCB_asurt/
│   ├── pcb1_copper_signal_top.gbr    # Top Copper Signal Layer
│   ├── pcb1_copper_signal_bot.gbr    # Bottom Copper Signal Layer
│   ├── pcb1_soldermask_top.gbr       # Top Solder Mask
│   ├── pcb1_soldermask_bot.gbr       # Bottom Solder Mask
│   ├── pcb1_paste_top.gbr            # Top Solder Paste Mask (Stencil)
│   ├── pcb1_legend_top.gbr           # Top Silkscreen / Legend
│   ├── pcb1_pads_top.gbr             # Top Component Pads
│   ├── pcb1_pads_bot.gbr             # Bottom Component Pads
│   ├── pcb1_pth_drill.gbr            # Plated Through-Hole (PTH) Drill File
│   ├── pcb1_npth_drill.gbr           # Non-Plated Through-Hole (NPTH) Drill File
│   ├── pcb1_profile.gbr              # Board Edge / Profile Outline
│   ├── pcb1_top_assembly.gbr         # Assembly Drawing (Top)
│   ├── pcb1_top_courtyard.gbr        # Component Courtyard Boundary
│   ├── pcb1_top_component_center.gbr # Pick and Place / Centroid Data
│   └── pcb1_top_3d_body.gbr          # 3D Component Projection Layer
└── README.md                   # Project documentation
