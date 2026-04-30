# MAT-Control-System

> ⚠️ **Status: Active Development** — This repository is currently under continuous development. New systems, simulations, and control strategies are being added progressively.

---

## Overview

This repository presents the implementation and simulation of classical and modern control systems using **MATLAB/Simulink**. The primary objective is to model, analyze, and control various dynamic systems by applying foundational and advanced control strategies — with an emphasis on academic rigor, simulation accuracy, and systematic performance evaluation.

The work here is intended as a structured learning and experimentation framework, progressing from basic motor control to complex multi-body system stabilization.

---

## Objectives

- Model dynamic systems using transfer functions and state-space representations
- Design and tune controllers (PID, LQR) for real and simulated physical systems
- Perform stability analysis using Bode plots and Root Locus techniques
- Simulate system responses and validate controller performance in MATLAB/Simulink

---

## Repository Structure

```
MAT-Control-System/
│
├── DC Motor Control/          # Speed and position control of a DC motor using PID
├── Rhino 300 RPM Motor/       # Transfer function modeling and control of Rhino motor
├── Trial/                     # Experimental scripts and sandbox simulations
└── README.md
```

---

## Systems Under Study

| System | Description | Status |
|---|---|---|
| DC Motor | Speed/position control via PID tuning | ✅ In Progress |
| Rhino 300 RPM Motor | Transfer function modeling & response analysis | ✅ In Progress |
| Bipad Bot | Stability control of a bipedal robot using LQR & State-Space | 🔄 Planned |
| Industrial Robotic Arm | Joint-level control using PID and trajectory analysis | 🔄 Planned |

---

## Control Techniques Covered

### Classical Control
- **PID Controller** — Proportional-Integral-Derivative tuning for motor systems
- **Bode Plot Analysis** — Frequency domain analysis for gain/phase margin evaluation
- **Root Locus** — Pole-zero placement for transient response shaping

### Modern Control
- **State-Space Representation** — Full system modeling using state variables
- **LQR (Linear Quadratic Regulator)** — Optimal control for multi-state systems (applied to Bipad Bot stability)

---

## Tools & Requirements

| Tool | Purpose |
|---|---|
| MATLAB R2021a or later | Core simulation environment |
| Simulink | Block diagram-based dynamic modeling |
| Control System Toolbox | Transfer functions, Bode, Root Locus |
| Symbolic Math Toolbox | Analytical derivations (where applicable) |

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ShashiBhushanSharma-debug/MAT-Control-System.git
   ```
2. Open MATLAB and navigate to the desired system folder.
3. Run the `.m` scripts or open the `.slx` Simulink models.
4. Modify plant parameters or controller gains to observe system behavior.

---

## Upcoming Work

- [ ] Bipad Bot dynamic modeling and LQR-based stabilization
- [ ] Industrial Robotic Arm joint control simulation
- [ ] Lead/Lag compensator design
- [ ] Comparative analysis of PID vs LQR on same plant
- [ ] Documented simulation results with plots for each system

---

## Author

**Shashi Bhushan Sharma**
B.Tech — Mechanical/Control Systems Engineering
GitHub: [@ShashiBhushanSharma-debug](https://github.com/ShashiBhushanSharma-debug)

---

## License

This project is licensed under the [Apache-2.0 License](LICENSE).

---

> *This repository is part of an ongoing academic exploration of control systems theory and its practical simulation using MATLAB. Contributions, feedback, and suggestions are welcome.*