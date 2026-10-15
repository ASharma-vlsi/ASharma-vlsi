<div align="center">

<img src="assets/vlsi-header.svg" alt="VLSI and ASIC design header" width="100%"/>

# Ayushmaan Sharma

### Electronics & Communication Engineering | VLSI • RTL Design • FPGA • ASIC Physical Design

*Building digital systems from RTL to silicon — one block at a time.*

<p>
  <a href="https://github.com/USERNAME"><img src="https://img.shields.io/badge/GitHub-Profile-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Focus-Digital%20VLSI-2563eb?style=for-the-badge" alt="Digital VLSI"/>
  <img src="https://img.shields.io/badge/Interests-ASIC%20%7C%20FPGA%20%7C%20RISC--V-0f766e?style=for-the-badge" alt="Interests"/>
</p>

</div>

---

## `01` · About Me

I'm an ECE student interested in **digital VLSI design, computer architecture, FPGA prototyping, and ASIC implementation**. I enjoy connecting RTL-level logic to real hardware and exploring how a design moves through synthesis, floorplanning, placement, clock-tree synthesis, routing, and physical verification.

- **Digital design:** Verilog HDL, RTL simulation, custom IP integration
- **SoC & architecture:** RISC-V, memory-mapped peripherals, GPIO and timer IP
- **ASIC physical design:** OpenLane, OpenROAD, Sky130, Yosys, Magic, Netgen, OpenSTA
- **Hardware platforms:** FPGA boards, microcontrollers, embedded systems
- **Currently exploring:** reusable RTL blocks, timing-aware design, and RTL-to-GDSII workflows

> Physical-design work is presented here as project/workshop learning, separate from my VLSI internship experience.

## `02` · IC Layout Lab

A small visual index of the kinds of standard-cell and block-level layouts I’m interested in studying and documenting. These are **illustrative conceptual layouts**, not foundry-qualified or tapeout-ready layouts.

<p align="center">
  <img src="assets/asic-layouts.svg" alt="Conceptual IC layouts: inverter, NAND, 2-to-1 multiplexer and SRAM bitcell" width="100%"/>
</p>

| Layout study | Design focus | What to document |
|---|---|---|
| **CMOS Inverter** | PMOS/NMOS pull-up and pull-down network | Schematic, transient response, sizing and layout |
| **2-input NAND** | Series NMOS, parallel PMOS | Truth table, stick diagram, DRC/LVS |
| **2:1 MUX** | Select-controlled data path | Logic implementation, transistor count, delay |
| **6T SRAM bitcell** | Cross-coupled inverters + access transistors | Read/write concept, stability and cell layout |

## `03` · Featured Work

### Digital VLSI SoC Design & Planning
Learning and documenting an open-source RTL-to-GDSII flow using **Sky130, OpenLane/OpenROAD, Yosys, Magic, Netgen and OpenSTA**. Topics include floorplanning, placement, CTS, routing, STA, DRC/LVS and GDSII generation.

### RISC-V SoC & Custom Peripheral IP
Worked with a RISC-V SoC workflow and developed/integrated **GPIO and timer IP** through memory-mapped interfaces, with RTL simulation and FPGA validation.

### FPGA & RTL Experiments
Verilog-based digital logic experiments, peripheral integration, simulation, and board-level bring-up using open-source FPGA tools.

> Replace the project titles above with direct links to your actual repositories once you confirm the repository URLs.

## `04` · Contribution Activity

<div align="center">

<!-- Contribution heatmap from GitHub -->
<img src="https://ghchart.rshah.org/2563eb/USERNAME" alt="GitHub contribution graph for USERNAME" width="100%"/>

<table>
<tr>
<td>
<img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" alt="GitHub stats"/>
</td>
<td>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&hide_border=true&theme=transparent" alt="Top languages"/>
</td>
</tr>
</table>

</div>

### Contribution Snake (optional)

To show an animated snake eating your contribution graph, add the workflow below to your profile repository at `.github/workflows/snake.yml`. It publishes an SVG to the `output` branch.

```yaml
name: Generate contribution snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: USERNAME
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

After the workflow runs, add this image where you want the animation to appear:

```markdown
![Contribution snake](https://raw.githubusercontent.com/USERNAME/USERNAME/output/github-contribution-grid-snake.svg)
```

## `05` · Tools & Technologies

<p align="center">
  <img src="https://img.shields.io/badge/Verilog-RTL-7c3aed?style=flat-square" alt="Verilog"/>
  <img src="https://img.shields.io/badge/RISC--V-Architecture-2563eb?style=flat-square" alt="RISC-V"/>
  <img src="https://img.shields.io/badge/Yosys-Synthesis-0f766e?style=flat-square" alt="Yosys"/>
  <img src="https://img.shields.io/badge/OpenLane-RTL--to--GDSII-334155?style=flat-square" alt="OpenLane"/>
  <img src="https://img.shields.io/badge/OpenROAD-Physical%20Design-334155?style=flat-square" alt="OpenROAD"/>
  <img src="https://img.shields.io/badge/Sky130-PDK-0f766e?style=flat-square" alt="Sky130"/>
  <img src="https://img.shields.io/badge/Magic-Layout-7c3aed?style=flat-square" alt="Magic"/>
  <img src="https://img.shields.io/badge/Netgen-DRC%20%2F%20LVS-2563eb?style=flat-square" alt="Netgen"/>
  <img src="https://img.shields.io/badge/OpenSTA-Timing-0f766e?style=flat-square" alt="OpenSTA"/>
  <img src="https://img.shields.io/badge/FPGA-Prototyping-f59e0b?style=flat-square" alt="FPGA"/>
  <img src="https://img.shields.io/badge/C%20%2F%20Embedded-Systems-334155?style=flat-square" alt="Embedded C"/>
</p>

## `06` · What I’m Building Toward

- Reusable, well-tested RTL blocks and small SoC subsystems
- Better understanding of timing, area, power, and physical-design trade-offs
- Documented standard-cell layouts with schematic, simulation, and verification evidence
- Practical open-source ASIC workflows from RTL through GDSII

---

<div align="center">

**Thanks for visiting — explore the repositories to see what I’m learning and building.**

<sub>Template structure inspired by <a href="https://github.com/creativetimofficial/github-profile-template">Creative Tim’s GitHub Profile Template</a>. Visual assets in this bundle are original conceptual illustrations.</sub>

</div>
