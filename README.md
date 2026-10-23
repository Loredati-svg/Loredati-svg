# 👋 Hey, I'm Lorenzo Dati

I'm a 26-year-old **Analog IC Designer** specializing in **CMOS Image Sensors**. I hold a Master's degree in **Electronic Engineering for Intelligent Vehicles** from **MUNER**. I am passionate about designing integrated analog circuits, custom high-performance PCBs, and bridging the gap between chip-level design and board-level hardware.

---

### 🏆 Key Projects

🔹 **[TPA3116D2 Class-D Audio Amplifier](https://github.com/Loredati-svg/Class-D-Audio-Amplifier)** *(design complete - In Prodcution)*
- Designing an open-source stereo Class-D amplifier (TI TPA3116D2, 2 × 40 W) in KiCad 10.
- USB-C digital input via a driverless USB Audio DAC (PCM2704C), with ESD protection.
- Active Baxandall bass/treble tone control (OPA1678) and logarithmic volume control, tuned for deep bass.
- Anti-pop sequencing (MUTE/SDZ timing), LDO analog supply, LC output filter and EMI snubbers.
- Modular hierarchical schematics with custom symbol and footprint libraries.

🔹 **[RP2040-Macropad](https://github.com/Loredati-svg/Custom_Keyboard)** *(design complete - In Production)*
- 9-key mechanical macropad with two push-button rotary encoders and per-key RGB lighting, designed from scratch in KiCad 10.
- Bare RP2040 design (no module): QSPI flash, 12 MHz crystal, AP2112K 3.3 V LDO, USB-C with USBLC6 ESD protection and polyfuse.
- Hardware RC debouncing on the encoders; 9 reverse-mount SK6812MINI-E LEDs with a 3.3 V → 5 V level shifter on the data line.
- 4-layer PCB with a dedicated ground plane, single-sided SMD assembly on the bottom; designed for QMK/VIA firmware.

🔹 **[BLDC FOC Motor Driver](https://github.com/Loredati-svg/BLDC-FOC-Motor-Driver)** *(work in progress)*
- Single-motor BLDC/PMSM driver with sensored Field-Oriented Control, designed in KiCad 10 as the motor building block for a two-wheeled self-balancing robot.
- STM32G431 (170 MHz, CORDIC) driving a TI DRV8323RH smart gate driver and a 3-phase inverter with 60 V MOSFETs; 3S–6S LiPo input with TVS and bulk protection.
- 3-shunt low-side current sensing through the DRV8323 amplifiers, RC-filtered into simultaneous ADC sampling; MA730 14-bit magnetic encoder centred on the motor shaft.
- On-chip buck (5 V) + LDO (3.3 V) with ferrite-filtered analog supply; USB-C (CDC telemetry, diode-OR logic supply, ESD + polyfuse) and Tag-Connect SWD.
- Gate drive strength, overcurrent threshold and current-sense gain set by hardware straps; schematic complete, PCB layout in progress.

---

### 🔧 Areas of Interest

- Analog & Mixed-Signal IC Design
- CMOS Image Sensor Architecture
- Custom PCB Design & Hardware Engineering
- Open-Source Hardware Development

---

### 💻 Technical Skills

**Design & Simulation Tools:**  
![Siemens EDA](https://img.shields.io/badge/Siemens_S--Edit%2FL--Edit-009999?style=for-the-badge&logo=siemens&logoColor=white)
![Cadence Spectre](https://img.shields.io/badge/Cadence_Spectre-CC0000?style=for-the-badge&logo=cadence&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-EE3124?style=for-the-badge&logo=analogdevices&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad_10-314685?style=for-the-badge&logo=kicad&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)


### 🏢 Organization

<a href="https://github.com/L2-hardware">
  <img src="https://github.com/L2-hardware.png" width="60" align="left" style="margin-right:12px" alt="L2_hardware logo"/>
</a>

**[L2_hardware](https://github.com/L2-hardware)** — Founder & Owner  
Open-source hardware projects: custom PCBs, analog circuits and board-level design.

<br clear="left"/>

[![L2_hardware](https://img.shields.io/badge/GitHub-L2__hardware-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/L2-hardware)

---

### 🎓 Education

**M.Sc. Electronic Engineering for Intelligent Vehicles**  
*MUNER – Motorvehicle University of Emilia-Romagna*  
🏅 **Grade:** 110/110 Cum Laude

---

### 📫 Contact

- 📧 **Email:** lollodati46@gmail.com

---

### 🌐 Socials

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lorenzodati00)
