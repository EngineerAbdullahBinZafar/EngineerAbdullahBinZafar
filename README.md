<div align="center">

# ⚡ ABDULLAH BIN ZAFAR
### **Autonomous Systems, Mechatronics & Control Systems Engineer**
*Robotics • Deterministic Safety Gateways • Embedded Firmware • Industrial Automation*

[![GitHub Followers](https://img.shields.io/github/followers/EngineerAbdullahBinZafar?label=Followers&style=for-the-badge&logo=github&color=181717)](https://github.com/EngineerAbdullahBinZafar)
[![GitHub Stars](https://img.shields.io/github/stars/EngineerAbdullahBinZafar?label=Total%20Stars&style=for-the-badge&logo=apachespark&color=f59e0b)](https://github.com/EngineerAbdullahBinZafar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/abdullah-bin-zafar)
[![Email](https://img.shields.io/badge/Email-abz.king.1.9.2003%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abz.king.1.9.2003@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B92%20336%201919709-25d366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/923361919709)

---

```
"Safety is not a feature or a soft prompt. It is a deterministic mathematical law."
```

</div>

<br/>

## 🎯 Executive Engineering Profile

**Mechatronics & Control Systems Engineer** (UET Lahore, Top Merit Scholar, 20 A/A+ grades) bridging the critical gap between **deterministic control theory, physical hardware realization, and modern embodied AI**.

- **Proven Physical Engineering Track Record:** 100% physical hardware build rate across 6 engineering semesters spanning CNC machining (GD&T $\pm0.05$ mm), STM32/ESP32 bare-metal & RTOS firmware, multi-layer KiCad PCB routing, and high-frequency power electronics.
- **Industrial Automation Experience:** Industrial engineering internship at **Interloop Limited** (Textile & Advanced Manufacturing), optimizing industrial automation line reliability, pneumatic valve sequencing, PLC/sensor telemetry, and environmental control loops.
- **Pioneering Embodied AI Safety:** Creator of **Principia Robotica**, the world's first unified MCP gateway + Control Barrier Function (CBF-QP) real-time safety engine enforcing forward invariance ($\forall t \ge 0: h(x(t)) \ge 0$) on physical robots at $>12,000\text{ Hz}$.

---

## ⚙️ Core Technical Competency Matrix

<table>
  <tr>
    <td width="30%"><b>🧠 Autonomous Systems & AI Safety</b></td>
    <td><code>Control Barrier Functions (CBF-QP)</code> <code>Lyapunov Stability (CLF)</code> <code>Model Context Protocol (MCP)</code> <code>ROS 2 Humble / Jazzy</code> <code>Nav2</code> <code>Kalman Filtering (EKF)</code> <code>Forward/Inverse Kinematics (DH)</code></td>
  </tr>
  <tr>
    <td><b>⚡ Embedded Firmware & Protocols</b></td>
    <td><code>STM32 (C/C++ HAL & LL)</code> <code>ESP32 (FreeRTOS)</code> <code>CAN Bus 2.0B / CAN-FD</code> <code>SPI & I²C (DMA)</code> <code>UART (CRC8 Protocol)</code> <code>PWM Timing & Timers</code> <code>ADC Conditioning</code></td>
  </tr>
  <tr>
    <td><b>🏭 Industrial Automation & Controls</b></td>
    <td><code>Industrial Pneumatics & Electro-Pneumatics</code> <code>PLC Ladder Logic & Staged Valves</code> <code>Closed-Loop PID (Back-EMF Comp)</code> <code>Root Locus & Bode/Nyquist</code> <code>State-Space Control</code> <code>Interloop Industrial Lines</code></td>
  </tr>
  <tr>
    <td><b>📐 CAD, CAM, CFD & Fabrication</b></td>
    <td><code>SolidWorks (CSWP Certified)</code> <code>AutoCAD 2D/3D</code> <code>KiCad PCB Layout & DRC</code> <code>CNC G-Code & Toolpath Optimization</code> <code>3D Printing & Additive CAM</code> <code>Aerodynamic & Centrifugal Impellers</code></td>
  </tr>
  <tr>
    <td><b>💻 Systems Programming & Tools</b></td>
    <td><code>Modern C++ (17/20, OOP, Memory Mgmt)</code> <code>Python (NumPy, SciPy, CVXPY, OSQP)</code> <code>MATLAB / Simulink</code> <code>Git & GitHub Actions CI/CD</code> <code>Linux / Ubuntu</code></td>
  </tr>
</table>

---

## 🏆 Flagship Autonomous & Industrial Innovations

### 1. ⚡ [Principia Robotica (v1.0.0)](https://github.com/EngineerAbdullahBinZafar/principia-robotica) — *World's First Embodied AI Safety Gateway*
> **The Zero-Trust Barrier Between Large Language Models and Physical Hardware Actuation**

- **Problem:** AI LLMs (Claude, GPT-4o, Gemini) propose unvalidated `/cmd_vel` velocity commands that cause fatal hardware crashes, stall torques, and boundary violations.
- **Solution:** A sub-millisecond Quadratic Programming (QP) solver intercepting commands via Model Context Protocol:
  $$\min_{u} \frac{1}{2}\|u - u_{\text{AI}}\|^2 \quad \text{s.t.} \quad L_f h(x) + L_g h(x) u \ge -\gamma h(x)$$
- **Performance:** **$\sim 0.082\text{ ms}$ solve latency (>12,000 Hz throughput)**, 14 registered MCP tools, 68/68 unit tests passed (100%), pure Python `principia.linalg` fallback with zero SIMD lock-in.
- **Live 60 FPS Visualizer:** [https://engineerabdullahbinzafar.github.io/principia-robotica/](https://engineerabdullahbinzafar.github.io/principia-robotica/)

---

### 2. 🕷️ Project SPIDEY — *Hexapod Autonomous Bio-Inspired Walking Robot (FYP)*
> **18-DOF Multi-Terrain Autonomous Hexapod with Real-Time Inverse Kinematics & Bio-Inspired Gaits**

- **Kinematics & Gait Engine:** Designed dynamic forward and inverse kinematic solvers (DH parameters) supporting Tripod, Wave, and Ripple gaits on irregular rough terrain.
- **Embedded Architecture:** High-speed STM32/ESP32 multi-channel PWM servo timing architecture with synchronized trajectory interpolation and IMU attitude stabilization.
- **Physical Fabrication:** Custom-engineered CNC airframe, laser-cut linkage mechanics, and multi-layer power distribution board handling dynamic current transients.

---

### 3. 🌀 VORTEX-100 — *Industrial Aerodynamic Fluid Amplifier & Bladeless System*
> **Engineered Centrifugal Impeller, Volute Plenum, and Coandă Airfoil Assembly**

- **Aero & CAD Realization:** Modeled 11-blade high-pressure centrifugal impeller, volute diffuser plenum, and precision Coandă aerodynamic ring airfoil in SolidWorks (CSWP certified).
- **Physical Prototyping:** 3D-modeled, CFD-analyzed, and rapid-prototyped multi-part assembly (`Base_Pedestal`, `Centrifugal_Impeller`, `Ring_Airfoil`) with complete procurement Bill of Materials (BOM).
- **Thermal & Fluid Performance:** Multiplied entrained air volume via fluid dynamics principles, reducing power draw by 35% compared to conventional bladed fans.

---

### 4. 🌐 [ros2-mcp-server](https://github.com/EngineerAbdullahBinZafar/ros2-mcp-server) — *Model Context Protocol Gateway for ROS 2*
> **Direct Real-Time AI Agent Bridge to ROS 2 Nodes, Topics, Services, and Hardware Feedback**

- Enabled Claude Desktop, Cursor, and Windsurf agents to inspect ROS 2 graph topologies, subscribe to sensor topics, and publish filtered actuators inside a strict hardware protection sandbox.

---

## 🏭 Industrial Internship & Manufacturing Experience

### **Interloop Limited** — *Industrial Automation & Controls Intern (Aug 2025 – Sep 2025)*
*Interloop is one of the world's largest multi-category manufacturing conglomerates.*

- **Pneumatic & Actuation Optimization:** Audited automated production lines, optimizing three-stage valve sequencing and pneumatic timing to eliminate pressure drops across guarded machinery access points.
- **Environmental Closed-Loop Telemetry:** Calibrated environmental control systems holding ambient production humidity within **$\pm 2\%$ of target setpoints** for sensitive fiber processing.
- **Sensor & PLC Diagnostic Integration:** Analyzed sensor noise in industrial measurement chains, validating hardware active filter circuits that reduced false-positive line trip rates.

---

## 🔬 Measured Physical Laboratory Deliverables (100% Hardware Build Rate)

Every single academic laboratory was backed by an operable, physical hardware prototype verified with empirical test data:

| Laboratory & Academic Module | Physical Hardware Build & Measured Performance Data |
| :--- | :--- |
| **Robotics & Mechanisms** | **3-DOF Kinematic Arm:** Modeled Jacobians in MATLAB; CNC-machined aluminum linkages; STM32 closed-loop PID control achieving **$\pm1\text{ mm}$ repeatability**. |
| **Sensors & Embedded Control** | **Autonomous Racing Drone:** Fused MPU-6050 6-axis IMU via **Kalman filtering** on ESP32; cut control latency by **40%** and held attitude error under **$2^\circ$** at 4.2:1 thrust ratio. |
| **Computer Vision Navigation** | **Vision-Guided Line UAV:** Real-time OpenCV path-tracking algorithm on custom KiCad PCB holding centerline deviation under **$15\text{ mm}$**. |
| **Electrical Machinery & Power** | **Regulated AC/DC Power Supply:** Transformer through full-wave bridge and LC smoothing stage, achieving **$<50\text{ mV}$ output voltage ripple**. |
| **Industrial Hydraulics & Pneumatics** | **Automated Safety Door:** Three-stage valve pressure-drop analysis with staged electro-pneumatic interlocks in compliance with industrial safety protocols. |
| **Machine Design & Elements** | **Fatigue Life & Gear Train Design:** Modeled multi-stage gear shafts and bearing selections in SolidWorks subjected to cyclical loading stress simulation (**Grade A**). |

---

## 🏅 Certifications & Engineering Accreditations

- 🎖️ **Certified SolidWorks Professional (CSWP)** — *Dassault Systèmes (Advanced 3D Modeling, Assemblies, GD&T)*
- 🎖️ **MATLAB Professional Certification** — *MathWorks (Model-Based Control Design & Simulation)*
- 🎖️ **Industrial Problem-Solving Certification** — *Hyundai Nishat Motor (Pvt) Ltd.*
- 🎖️ **Generative AI & Machine Learning Specialization** — *Google, IBM, Microsoft*

---

<div align="center">

### 💼 Open for Autonomous Systems, Robotics & Control Engineering Opportunities
**Targeting:** Global Autonomous Vehicle (BMW, Mercedes, Waymo), Aerospace/Turbomachinery (Rolls-Royce, Airbus), and Advanced Industrial Automation Systems.

[📧 Contact via Email](mailto:abz.king.1.9.2003@gmail.com) • [💬 Connect on LinkedIn](https://linkedin.com/in/abdullah-bin-zafar) • [🌐 Explore Principia Robotica](https://github.com/EngineerAbdullahBinZafar/principia-robotica)

</div>
