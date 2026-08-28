<div align="center">

# Hi, I'm Muppidi Varun 👋

### ECE undergrad working in VLSI and FPGA design — RTL, verification, and timing closure

[![GitHub](https://img.shields.io/badge/GitHub-varunmhub-181717?style=for-the-badge&logo=github)](https://github.com/varunmhub)
[![Email](https://img.shields.io/badge/Email-Contact_Me-2783DE?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ugs23047_ece.varun@cbit.org.in)

</div>

---

## About me

- 🎓 Electronics and Communication Engineering student at CBIT
- 🔧 **Digital design in Verilog** — RTL, self-checking testbenches, synthesis, place-and-route, static timing analysis
- 🧩 **FPGA** — Xilinx Artix-7 on a Digilent Basys 3, full flow through to bitstream and on-board bring-up
- 🔬 **Analog and custom IC** — schematic entry and simulation in Cadence Virtuoso
- 🎛️ **Embedded** — 8051 and ARM firmware in embedded C using Keil µVision
- 🔊 Also build practical tools for array signal processing and acoustic source localization

## Current focus

```text
Verilog RTL        ████████████████████  Datapath design, pipelining, verification
FPGA / Vivado      ██████████████████░░  Synthesis, implementation, timing closure
Cadence Virtuoso   ████████████░░░░░░░░  Schematic capture and analog simulation
Embedded C / Keil  ████████████░░░░░░░░  8051 and ARM peripheral firmware
Signal Processing  ██████████████░░░░░░  Beamforming and source localization
```

## Technical toolkit

**Hardware design and EDA**

![Verilog](https://img.shields.io/badge/Verilog--2001-CC342D?style=flat-square)
![Vivado](https://img.shields.io/badge/Xilinx_Vivado_ML_2024.1-0071C5?style=flat-square&logo=xilinx&logoColor=white)
![XSim](https://img.shields.io/badge/XSim-0071C5?style=flat-square)
![Cadence Virtuoso](https://img.shields.io/badge/Cadence_Virtuoso-006EB6?style=flat-square)
![Keil](https://img.shields.io/badge/Keil_µVision-B4292A?style=flat-square&logo=arm&logoColor=white)
![Artix-7](https://img.shields.io/badge/Artix--7_%7C_Basys_3-76B900?style=flat-square)

RTL design · testbench-driven verification · synthesis and utilization analysis · static timing
analysis and timing closure · XDC constraints · power estimation · UART bridging and host tooling

**Languages**

![Verilog](https://img.shields.io/badge/Verilog-CC342D?style=flat-square)
![C](https://img.shields.io/badge/Embedded_C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)

**Frameworks and tools**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Featured work

### 🧮 [Edge Vision Accelerator](https://github.com/varunmhub/edge-vision-accelerator) — DSP-free 3x3 convolution on Artix-7

A convolution accelerator that quantizes 8-bit sensor pixels on-chip to 4-bit sign-magnitude codes
and replaces every multiply with a shift-and-decode operation.

| | |
| --- | --- |
| Accuracy | **640 / 640** outputs bit-exact vs a NumPy golden model |
| DSP48 / BRAM | **0** / 90 and **0** / 50 |
| Timing | **+3.788 ns** worst negative slack at 100 MHz, 0 of 675 endpoints failing |
| Area | 141 slice LUTs, 103 registers, 3 bonded IOB |
| Power | 0.015 W core dynamic |
| Versus a multiplier baseline | **1.84x fewer LUTs, 2.29x less carry logic** at identical register count |

`Verilog-2001` · `Vivado` · `XSim` · `Artix-7` · `Static Timing Analysis` · `Python/NumPy`

### 🔊 [Aeroacoustic Beamforming Suite](https://github.com/varunmhub/beamforming-app)

A Streamlit application for localizing noise sources from multichannel microphone-array recordings.
It explores DAS, MVDR, CMF, and SODIX beamforming algorithms with comparison views and acoustic maps.

`Python` · `Streamlit` · `Acoular` · `NumPy` · `Signal Processing`

### 🎬 [AutoClip MVP — exploration fork](https://github.com/varunmhub/autoclip_mvp)

Exploring an AI-assisted workflow for video analysis, automatic clipping, subtitle processing, and
collection generation.

`Python` · `FastAPI` · `React` · `TypeScript` · `Docker`

## GitHub dashboard

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=varunmhub&show_icons=true&hide_border=true&theme=transparent" alt="Varun's GitHub statistics" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=varunmhub&layout=compact&hide_border=true&theme=transparent" alt="Varun's most used languages" />

</div>

---

<div align="center">

**Open to collaborating on VLSI, FPGA, and signal-processing projects.**

</div>
