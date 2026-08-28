<div align="center">

# Hi, I'm Muppidi Varun 👋

### ECE undergrad · VLSI & FPGA · Verilog RTL, Vivado, Cadence Virtuoso, Keil · building a DSP-free 4-bit CNN accelerator on Artix-7

[![GitHub](https://img.shields.io/badge/GitHub-varunmhub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/varunmhub)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ugs23047_ece.varun@cbit.org.in)

</div>

---

<img align="right" width="300" src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" alt="" />

### 👨🏻‍💻 &nbsp;About me

🎓 &nbsp;Electronics and Communication Engineering student at CBIT\
🔧 &nbsp;**Digital design in Verilog** — RTL, self-checking testbenches, synthesis, place-and-route, static timing analysis\
🧩 &nbsp;**FPGA** — Xilinx Artix-7 on a Digilent Basys 3, full flow through to bitstream and on-board bring-up\
🔬 &nbsp;**Analog and custom IC** — schematic entry and simulation in Cadence Virtuoso\
🎛️ &nbsp;**Embedded** — 8051 and ARM firmware in embedded C using Keil µVision\
🔊 &nbsp;Also build practical tools for array signal processing and acoustic source localization

<br clear="right" />

### 🎯 &nbsp;Current focus

| Area | What I'm working on |
| --- | --- |
| **Verilog RTL** | Datapath design, pipelining, testbench-driven verification |
| **FPGA / Vivado** | Synthesis, implementation, timing closure on Artix-7 |
| **Cadence Virtuoso** | Schematic capture and analog simulation |
| **Embedded C / Keil** | 8051 and ARM peripheral firmware |
| **Signal processing** | Beamforming and acoustic source localization |

### 🛠 &nbsp;Technical toolkit

**Hardware design and EDA**

![Verilog-2001](https://img.shields.io/badge/-Verilog--2001-0D1117?style=flat)&nbsp;
![Vivado](https://img.shields.io/badge/-Xilinx_Vivado_ML_2024.1-0D1117?style=flat&logo=xilinx&logoColor=0071C5)&nbsp;
![XSim](https://img.shields.io/badge/-XSim-0D1117?style=flat)&nbsp;
![Cadence Virtuoso](https://img.shields.io/badge/-Cadence_Virtuoso-0D1117?style=flat)&nbsp;
![Keil](https://img.shields.io/badge/-Keil_µVision-0D1117?style=flat&logo=arm&logoColor=0091BD)&nbsp;
![Artix-7](https://img.shields.io/badge/-Artix--7_%7C_Basys_3-0D1117?style=flat)

RTL design · testbench-driven verification · synthesis and utilization analysis · static timing
analysis and timing closure · XDC constraints · power estimation · UART bridging and host tooling

**Languages**

![Verilog](https://img.shields.io/badge/-Verilog-0D1117?style=flat)&nbsp;
![Embedded C](https://img.shields.io/badge/-Embedded_C-0D1117?style=flat&logo=c&logoColor=A8B9CC)&nbsp;
![Python](https://img.shields.io/badge/-Python-0D1117?style=flat&logo=python&logoColor=3776AB)&nbsp;
![TypeScript](https://img.shields.io/badge/-TypeScript-0D1117?style=flat&logo=typescript&logoColor=3178C6)&nbsp;
![Solidity](https://img.shields.io/badge/-Solidity-0D1117?style=flat&logo=solidity&logoColor=FFFFFF)

**Frameworks and tools**

![NumPy](https://img.shields.io/badge/-NumPy-0D1117?style=flat&logo=numpy&logoColor=4DABCF)&nbsp;
![Streamlit](https://img.shields.io/badge/-Streamlit-0D1117?style=flat&logo=streamlit&logoColor=FF4B4B)&nbsp;
![React](https://img.shields.io/badge/-React-0D1117?style=flat&logo=react&logoColor=61DAFB)&nbsp;
![FastAPI](https://img.shields.io/badge/-FastAPI-0D1117?style=flat&logo=fastapi&logoColor=009688)&nbsp;
![Git](https://img.shields.io/badge/-Git-0D1117?style=flat&logo=git&logoColor=F05032)

### 📂 &nbsp;Featured work

#### 🧮 [Edge Vision Accelerator](https://github.com/varunmhub/edge-vision-accelerator) — DSP-free 3x3 convolution on Artix-7

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

#### 🔐 [Random Password Generator on 8051](https://github.com/varunmhub/8051-random-password-generator) — AT89S52 firmware with 16x2 LCD

A standalone, fully offline hardware password generator. A debounced button press samples the
free-running Timer 0 registers to index a 68-character alphabet and prints an 8-character password
to a 16x2 LCD in roughly 400 ms. Includes the full firmware, hardware wiring reference, and the
academic project report.

| | |
| --- | --- |
| Microcontroller | AT89S52, 11.0592 MHz crystal |
| Entropy source | Free-running Timer 0, ~921,600 ticks/s, sampled at press time |
| Output | 8 characters from A–Z, a–z, 0–9, `@#$%&*` on an HD44780 16x2 LCD |
| Latency | **~400 ms** press-to-full-password |
| Interfaces | 8-bit LCD data bus on Port 1, control on P2.4–P2.6, button on P0.0 |

`Embedded C` · `AT89S52 / 8051` · `Keil µVision C51` · `HD44780 LCD` · `Timer 0` · `7805 power supply`

#### 🔊 [Aeroacoustic Beamforming Suite](https://github.com/varunmhub/beamforming-app)

A Streamlit application for localizing noise sources from multichannel microphone-array recordings.
It explores DAS, MVDR, CMF, and SODIX beamforming algorithms with comparison views and acoustic maps.

`Python` · `Streamlit` · `Acoular` · `NumPy` · `Signal Processing`

### ⚙️ &nbsp;GitHub dashboard

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=varunmhub&show_icons=true&hide_border=true&theme=github_dark&include_all_commits=true&count_private=true" alt="Varun's GitHub statistics" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=varunmhub&layout=compact&hide_border=true&theme=github_dark&langs_count=8" alt="Varun's most used languages" />
</p>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=varunmhub&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FFFFFF&area=true&area_color=1F6FEB&hide_border=true&custom_title=Contribution%20activity" width="100%" alt="Contribution activity graph" />

---

<div align="center">

**Open to collaborating on VLSI, FPGA, and signal-processing projects.**

</div>
