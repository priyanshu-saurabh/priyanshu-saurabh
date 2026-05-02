<div align="center">
  <img src="./banner.svg" width="100%" alt="Priyanshu Saurabh — Analog & Mixed-Signal IC Designer" />
</div>

<br/>

```
  001 ──────────────────────────────────────── CURRENT TRANSMISSION
```

Designing **analog front-end OTA architectures** for next-generation sensing systems. Present focus: gain-bandwidth optimization, noise floor suppression, and continuous-time analog integration with digital back-ends.

Simultaneously building a custom **Python bitstream analysis toolchain** — FFT-based SNDR/ENOB extraction, noise floor characterization, and autocorrelated BPM detection for sigma-delta output verification.

<br/>

```
  002 ──────────────────────────────────────── SELECTED TRANSMISSIONS
```

| Signal | Band | Description |
|---|---|---|
| **2nd-Order Σ-Δ Modulator** | `ADC · AMS` | Full architecture — loop filter, 1-bit quantizer, DAC feedback. SNDR/ENOB via custom Python tooling. Validated against MATLAB behavioral model. |
| **Analog Front-End Chain** | `AFE · Sensor` | Instrumentation-grade input, PGA, anti-alias filter. Low-frequency, high-resolution sensing. |
| **OTA Design** | `Amplifier · Cadence` | Differential OTA across gain, phase margin, slew rate. Full PVT corner simulation in Spectre. |
| **Latched Comparator** | `Mixed-Signal` | Strong-arm latch. Offset, regeneration time, metastability window characterized. Σ-Δ quantizer block. |
| **FFT Processor — FPGA** | `Digital · Xilinx` | Fixed-point pipelined butterfly stages on ARTY A7. Real-time spectral analysis of ADC bitstreams. |

<br/>

```
  003 ──────────────────────────────────────── RESEARCH FREQUENCIES
```

```
  1420.4 MHz  ·  Σ-Δ Modulators        —  continuous-time, high-order, multi-bit
  2695.0 MHz  ·  OTA Topologies        —  folded-cascode, recycling, current-mirror
  4860.0 MHz  ·  Bandgap References    —  curvature-corrected, low-noise
  8448.0 MHz  ·  AMS Co-Simulation     —  Verilog-AMS, mixed-domain verification
  10650  MHz  ·  Compute-in-Memory     —  mixed-signal ML accelerators
  22235  MHz  ·  Intelligent Sensing   —  edge inference, ADC-DSP co-design
```

<br/>

```
  004 ──────────────────────────────────────── INSTRUMENT ARRAY
```

```
  SCHEMATIC / SIM   ·  Cadence Virtuoso  ·  Spectre  ·  LTSpice  ·  Xschem
  LAYOUT / VERIFY   ·  Virtuoso Layout   ·  Assura DRC/LVS  ·  Magic VLSI
  HDL / FPGA        ·  Verilog  ·  SystemVerilog  ·  VHDL  ·  Xilinx Vivado
  ANALYSIS          ·  MATLAB  ·  Simulink  ·  Python
  EMBEDDED          ·  STM32  ·  ARM Assembly  ·  TI DSP
```

<br/>

```
  005 ──────────────────────────────────────── TELEMETRY
```

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=priyanshu-saurabh&theme=dark&hide_border=true&bg_color=030a14&title_color=4a8ad8&text_color=2a5a8a&icon_color=7ab0ef&include_all_commits=true&count_private=false&hide=issues&show_icons=true)

![Streak](https://nirzak-streak-stats.vercel.app/?user=priyanshu-saurabh&theme=dark&hide_border=true&background=030a14&ring=4a8ad8&fire=7ab0ef&currStreakLabel=4a8ad8)

</div>

<br/>

---

<div align="center">

```
  "The analog designer's job is not to fight physics.
   It is to understand it well enough to bend the tradeoffs in your favor."
```

`SIG STRENGTH ▮▮▮▮▯  ·  LOCK  ·  Bengaluru, India`

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-030a14?style=flat-square&logo=linkedin&logoColor=4a8ad8)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-030a14?style=flat-square&logo=gmail&logoColor=4a8ad8)](mailto:)
[![GitHub](https://img.shields.io/badge/GitHub-030a14?style=flat-square&logo=github&logoColor=4a8ad8)](https://github.com/priyanshu-saurabh)

</div>
