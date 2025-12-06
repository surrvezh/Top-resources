# Moderate to Very Tough VLSI Projects

Curated set of analog, mixed‑signal, digital, and verification VLSI projects suitable for advanced students and enthusiasts. 

## How to Use This List

- Pick **1–2 projects** per domain (analog, mixed‑signal, digital, verification).  
- For each project, maintain folders: `docs/`, `rtl_or_schematics/`, `sim/`, `layout/`, `scripts/`. 

---

## Project Table

| # | Project Title | Domain | Difficulty | Short Description |
|---|---------------|--------|------------|-------------------|
| 1 | Rail‑to‑Rail Low‑Noise Op‑Amp (SKY130) | Analog IC | Hard | Design and simulate a two‑stage or folded‑cascode CMOS op‑amp with rail‑to‑rail I/O, high gain, and low noise, then create layout in SKY130.  |
| 2 | Fast Transient LDO Regulator | Analog IC | Hard | Implement an LDO with <50 mV dropout, fast load‑step response, and stability over PVT corners using open‑source analog tools.  |
| 3 | Continuous‑Time Sigma‑Delta ADC Front‑End | Mixed‑Signal | Very Hard | Design OTA + Gm‑C loop filter and quantizer, target audio‑band resolution, and verify stability and SNR via transient simulations.  |
| 4 | Digital PLL (DPLL) Based ADC | Mixed‑Signal | Very Hard | Build an all‑digital PLL where the DCO control encodes analog input; combine Verilog RTL with behavioral models for verification.  |
| 5 | Time‑Interleaved SAR ADC with Calibration | Mixed‑Signal | Very Hard | Implement multi‑channel SAR ADC with digital background calibration for offset and gain mismatches.  |
| 6 | High‑Speed SERDES Front‑End (CDR + EQ) | Mixed‑Signal | Very Hard | Create clock‑data recovery and equalizer blocks for multi‑Gb/s links, focusing on jitter tolerance and channel loss.  |
| 7 | 32‑bit Pipelined RISC‑V Core (RTL to GDSII) | Digital RTL/PD | Hard | Implement a 5–7 stage RISC‑V pipeline and take it through OpenLANE/OpenROAD to GDSII in SKY130.  |
| 8 | Multi‑Core RISC‑V SoC with AXI/AHB Interconnect | Digital RTL/PD | Very Hard | Build a small multi‑core SoC with shared bus/interconnect, basic caches, and memory map.  |
| 9 | AES or SHA256 Crypto Accelerator | Digital RTL | Hard | Implement a parameterized hardware crypto core and integrate it as a coprocessor to a CPU.  |
| 10 | Network‑on‑Chip (NoC) Router Mesh | Digital RTL | Very Hard | Design wormhole‑routed NoC routers with virtual channels, flow control, and QoS.  |
| 11 | UVM‑Based Verification of RISC‑V Core | Verification | Hard | Develop a UVM environment with scoreboards, coverage, and constrained‑random tests for a CPU core.  |
| 12 | Formal + ABV for Bus Bridge (AHB–APB) | Verification | Hard | Use SystemVerilog Assertions and formal tools to prove protocol correctness of a complex bus bridge.  |
| 13 | RTL‑to‑GDS Flow of 64‑bit MAC Unit | Physical Design | Hard | Synthesize, place, route, and sign‑off a 64‑bit multiply–accumulate unit in SKY130, closing timing and fixing DRC/LVS. |
| 14 | Clock‑Tree and Power‑Grid Design Study | Physical Design | Very Hard | Explore clock‑tree synthesis and power‑grid design on a mid‑size SoC, analyzing skew, IR‑drop, and EM.  |
| 15 | Low‑Power Multi‑Voltage SoC Experiment | Physical Design | Very Hard | Implement power‑gated domains, isolation cells, and level shifters in an SoC using open or academic PD flows. |

---

## Recommended Tool Stack

- **Analog / Mixed‑Signal:** Ngspice or Xyce, Xschem, Magic, SKY130 PDK.  
- **Digital / RTL & PD:** Verilog/SystemVerilog, OpenLANE/OpenROAD, Yosys, SKY130 PDK. 
- **Verification:** SystemVerilog/UVM, formal tools (SymbiYosys or commercial), plus Python for scripting. 

---

