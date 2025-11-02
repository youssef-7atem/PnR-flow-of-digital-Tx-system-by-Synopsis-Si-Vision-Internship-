# 🧠 SI-Vision Internship Final Project — PnR Flow Digital Tx System

**Author:** Youssef Mohamed Hatem  
**Supervisor:** Eng. Bassant Samir  
**Date:** August 22, 2025  
**Organization:** SI-Vision  

---

<p align="center">
  <img src="https://img.shields.io/badge/EDA-Synopsys-blueviolet?style=for-the-badge&logo=synopsys" alt="Synopsys"/>
  <img src="https://img.shields.io/badge/Language-TCL-orange?style=for-the-badge" alt="TCL"/>
  <img src="https://img.shields.io/badge/Toolchain-IC%20Compiler%20II%20|%20PrimeTime%20|%20StarRC-green?style=for-the-badge" alt="Tools"/>
</p>

---

## 📘 Project Overview

This repository documents the **final internship project** completed at **SI-Vision**, focusing on implementing a complete **RTL-to-GDSII (Register-Transfer Level to Layout)** flow for a **Digital Transmitter (Tx) System** using **Synopsys EDA tools**.

The project explores **three distinct design compilation strategies**, each emphasizing a different optimization target:

1. **Compile for Timing Optimization** — Prioritizing performance and critical path closure.  
2. **Compile for Area Optimization** — Minimizing silicon area without violating timing constraints.  
3. **Compile for Power Optimization** — Reducing dynamic and leakage power while maintaining timing and functionality.

Each methodology illustrates the trade-offs among **timing**, **area**, and **power**, providing insights into how EDA tools balance competing design objectives to deliver the best possible **Quality of Results (QoR)**.

---

## ⚙️ Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| **Synthesis** | Synopsys Design Compiler |
| **Place & Route (PnR)** | Synopsys IC Compiler II |
| **Static Timing Analysis (STA)** | Synopsys PrimeTime |
| **Parasitic Extraction** | Synopsys StarRC |
| **Automation & Scripting** | TCL |
| **Verification** | DRC, LVS, and STA reports |
| **Platform** | Linux (CentOS / Red Hat Environment) |

---

## 🧩 Flow Breakdown

### 🔹 1. Compile for Timing Optimization
This flow focuses on achieving **maximum performance** by meeting stringent timing constraints.

**Objectives:**
- Optimize critical paths.
- Achieve positive slack and frequency targets.
- Build a balanced and low-skew clock tree.

**Key Stages:**
- Compilation & Path Modifications  
- Setup Data Preparation  
- Floorplan & Power Plan Design  
- Timing-Driven Placement  
- Clock Tree Synthesis (CTS)  
- Routing  
- Chip Finishing (DRC/LVS Fixes)  
- STA & StarRC Validation  

---

### 🔹 2. Compile for Area Optimization
This flow prioritizes **reducing the silicon footprint** while keeping the design functional and timing-clean.

**Objectives:**
- Compact layout with efficient cell packing.  
- Minimize area overhead while retaining acceptable QoR.  
- Resolve congestion and maintain manufacturability.

**Key Steps:**
- Area-Driven Compilation using compact libraries.  
- Floorplanning for tight utilization.  
- Power Plan with minimal overhead.  
- Dense placement and efficient routing.  
- STA verification with buffer insertion for hold fixes.

---

### 🔹 3. Compile for Power Optimization
This flow is designed to **minimize dynamic and leakage power** while ensuring functional and timing integrity.

**Objectives:**
- Use low-power standard cell libraries.  
- Apply power-aware floorplanning and CTS.  
- Reduce switching activity through optimized logic mapping.  
- Achieve power gating and voltage domain efficiency.

**Steps:**
- Power-Oriented Compilation & Data Setup  
- Floorplan and Power Grid (IR Drop Minimization)  
- Power-Aware Placement  
- Low-Power CTS and Routing  
- Parasitic Extraction with StarRC  
- STA Validation & Power Estimation  

---

## 📂 Repository Structure


---

## 🧾 Full Report

The full project documentation, including figures, timing histograms, and detailed reports, is included in the repository.

<p align="center">
  <a href="./SI_vision_Final_project_report.pdf" target="_blank">
    <img src="https://img.shields.io/badge/View%20Full%20Report-PDF-red?style=for-the-badge&logo=adobeacrobatreader" alt="View PDF Report"/>
  </a>
</p>

<embed src="./SI_vision_Final_project_report.pdf" type="application/pdf" width="100%" height="800px" />


## 🧾 Full Report

The detailed internship report (including timing, area, and power optimization flows) is available below:

[📘 **Click here to open the full PDF report**](./docs/SI_vision_Final_project_report.pdf)

> If the link doesn’t open inline, right-click and choose **“Open link in new tab”**.

