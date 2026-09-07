# BLACKCATS_SIH26
This Smart India Hackathon 2026 presentation by Team BLACKCATS details HI-CAS (Helmet-Integrated Conformal Antenna System).
# 🐈‍⬛ BLACKCATS — HI-CAS

### Helmet-Integrated Conformal Antenna System for Tactical Communications

> **ONE TEAM. ONE LINK. ZERO COMMUNICATION GAPS.**

[![SIH 2026](https://img.shields.io/badge/Smart%20India%20Hackathon-2026-blue)](https://www.sih.gov.in/)
[![Problem Statement](https://img.shields.io/badge/PS-26185-red)](#)
[![Category](https://img.shields.io/badge/Category-Hardware-orange)](#)
[![Team](https://img.shields.io/badge/Team-BLACKCATS-black)](#)

---

## 📌 About the Project

**HI-CAS (Helmet-Integrated Conformal Antenna System)** is a compact, low-profile antenna architecture designed for **tactical communication in confined urban environments and Close-Quarter Battle (CQB) operations**.

The system replaces conventional protruding whip antennas with **helmet-integrated conformal antenna arrays**, reducing exposed hardware while maintaining reliable RF communication.

The proposed architecture uses **two independent single-band conformal antenna arrays**, supporting **UHF and L-band communication**, with a **diplexer** providing a single RF interface and **phase control** for improved signal coverage.

---

## 🎯 Problem Statement

### SIH 2026 — Problem Statement ID: 26185

**Helmet mounted conformal antenna for tactical communications in urban CQB environments.**

Traditional radio antennas create several challenges in confined environments:

* 📡 Protruding antennas can snag on surroundings.
* 🪖 Rigid antennas do not conform to helmet geometry.
* 📶 Helmet curvature and head proximity affect RF performance.
* 🔄 A compact platform must support multiple communication bands.
* ⚙️ Antenna performance can vary under realistic operating conditions.

---

## 💡 Our Solution

HI-CAS integrates the antenna directly with the helmet surface while maintaining a compact and modular architecture.

### Key Features

| Feature                       | Description                                                     |
| ----------------------------- | --------------------------------------------------------------- |
| 🪖 **Conformal**              | Follows the curvature of the helmet                             |
| 📡 **Dual-Band Architecture** | Separate optimized arrays for UHF and L-band                    |
| 📏 **Low Profile**            | Minimizes exposed hardware and snag risk                        |
| 🔌 **Single RF Interface**    | UHF and L-band are combined through a diplexer                  |
| 🎛️ **Phase Control**         | Optimizes radiation coverage                                    |
| 🔧 **Retrofittable**          | Designed for compatibility with existing helmet systems         |
| 🧩 **Modular**                | Architecture can be adapted to different helmet/radio platforms |

---

## 🏗️ System Architecture

```text
                 ┌─────────────────────┐
                 │     HELMET SHELL    │
                 └──────────┬──────────┘
                            │
             ┌──────────────┴──────────────┐
             │                             │
     ┌───────▼────────┐           ┌────────▼───────┐
     │  UHF CONFORMAL │           │ L-BAND         │
     │     ARRAY      │           │ CONFORMAL ARRAY│
     └───────┬────────┘           └────────┬───────┘
             │                             │
             └──────────────┬──────────────┘
                            │
                      ┌─────▼─────┐
                      │  DIPLEXER │
                      └─────┬─────┘
                            │
                      ┌─────▼─────┐
                      │ PHASE     │
                      │ CONTROL   │
                      └─────┬─────┘
                            │
                      ┌─────▼─────┐
                      │ SINGLE RF │
                      │ INTERFACE │
                      └───────────┘
```

### Operating Bands

* **UHF:** 200–450 MHz
* **L-band:** 1.2–1.5 GHz

The architecture combines the two independently optimized antenna paths into a **single tactical RF interface**.

---

## 🔬 Engineering Approach

The project focuses on integrating existing RF technologies into a helmet-compatible platform and validating their performance under realistic operating conditions.

### Development Flow

```text
DESIGN
   ↓
SIMULATE
   ↓
PROTOTYPE
   ↓
BEND TEST
   ↓
TEMPERATURE TEST
   ↓
RF VALIDATION
   ↓
STRUCTURAL VALIDATION
```

The main engineering challenges include:

### 1. Helmet Curvature

Bending can alter electrical length and electromagnetic coupling.

**Parameters to evaluate:**

* Resonant frequency
* S11
* VSWR
* Bandwidth

### 2. Temperature

Environmental temperature variations can influence antenna materials and RF behaviour.

**Validation:**

* RF measurements before temperature cycling
* RF measurements after temperature cycling

### 3. Head Proximity

The operator's head changes the electromagnetic environment surrounding the antenna.

**Parameters:**

* Impedance
* Efficiency
* Radiation characteristics

### 4. Structural Integration

The antenna must integrate with the helmet without compromising its intended functionality or protection.

Structural/ballistic certification is **not claimed** by this project and would require dedicated validation.

---

## 🧪 Validation

The prototype will be evaluated through:

* Antenna simulation
* S-parameter measurements
* VSWR measurements
* Bandwidth characterization
* Curvature/bending tests
* Temperature testing
* Head-proximity testing
* Radiation-pattern evaluation
* Efficiency measurements
* Structural integration assessment

---

## 🚀 Expected Impact

### Operational

Reduced physical obstruction and improved operator mobility in confined environments.

### RF Performance

Independent band-optimized conformal arrays provide a flexible approach to multi-band tactical communication.

### User Safety

Reduced exposed antenna components can reduce potential snag points.

### Scalability

The modular UHF/L-band architecture can potentially be adapted to different helmet and radio platforms.

### Potential Applications

* NSG / ATS teams
* Specialized tactical units
* Helmet-based communication systems
* Other applications requiring compact integrated RF systems

All applications remain subject to appropriate technical validation, certification and procurement requirements.

---

## 🛠️ Technologies & Tools

### RF / Antenna

* Conformal antenna arrays
* UHF antenna design
* L-band antenna design
* Diplexer
* Phase-control network
* RF measurement and characterization

### Simulation & Design

The project can be developed and validated using electromagnetic simulation and RF design tools.

### Hardware

* Helmet-integrated antenna prototype
* RF interconnects
* Diplexer
* Phase-control circuitry
* Tactical-radio interface

---

## 📂 Repository Structure

```text
blackcats_sih26/
│
├── README.md
│
├── antenna-design/
│   ├── UHF/
│   └── L-band/
│
├── simulations/
│   ├── radiation-patterns/
│   ├── S11/
│   ├── VSWR/
│   └── bandwidth/
│
├── hardware/
│   ├── schematics/
│   ├── PCB/
│   └── prototype/
│
├── mechanical/
│   ├── helmet-CAD/
│   └── mounting/
│
├── results/
│   ├── measurements/
│   └── plots/
│
├── documentation/
│
└── LICENSE
```

---

## 👥 Team

### BLACKCATS

**Smart India Hackathon 2026**

**Team ID:** 007
**Problem Statement:** 26185
**Category:** Hardware
**Theme:** Robotics and Drones

---

## 📜 Project Status

🚧 **Prototype / Development Stage**

The project is currently focused on antenna design, simulation, prototype development and validation.

The core technologies required for the system exist; the primary engineering challenge is their **integration and validation under realistic operating conditions**.

---

## 📚 References

Project documentation and research material will be maintained in this repository.

**Official repository:**
https://github.com/Sriharshithprasadns456/blackcats_sih26

---

## ⚠️ Disclaimer

This project is a **research and engineering prototype** developed for Smart India Hackathon 2026.

Performance, structural integrity, ballistic protection and operational suitability must be independently validated before any real-world deployment.

---

<p align="center">

### 🐈‍⬛ BLACKCATS

**ONE TEAM. ONE LINK. ZERO COMMUNICATION GAPS.**

</p>
