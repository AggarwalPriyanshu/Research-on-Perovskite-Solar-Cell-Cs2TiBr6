# 🔬 Research on Lead-Free Perovskite Solar Cell (Cs₂TiBr₆)

> **Numerical Simulation & Performance Optimization using SCAPS-1D**

This repository presents a **detailed numerical investigation** of a **lead-free double perovskite solar cell based on Cs₂TiBr₆**, focusing on **device architecture optimization**, **transport layer engineering**, and **performance benchmarking** using **SCAPS-1D simulation software**.

The work aims to demonstrate the feasibility of **high-efficiency, environmentally friendly perovskite solar cells** by optimizing material selection and energy band alignment.

---

## 🧾 Abstract

Lead-free perovskite solar cells have gained significant attention as sustainable alternatives to conventional lead-based photovoltaics. In this work, a Cs₂TiBr₆-based perovskite solar cell is numerically modeled and optimized using the SCAPS-1D simulator. Multiple device architectures with different electron and hole transport layers are analyzed to study their impact on photovoltaic performance. An optimized structure of **Au / CuAlO₂ / Cs₂TiBr₆ / IGZO / FTO** achieves a maximum **power conversion efficiency (PCE) of 19.53%**. The enhancement is attributed to improved band alignment, reduced interfacial recombination, and efficient charge extraction. These results highlight the strong potential of Cs₂TiBr₆ as a lead-free absorber for next-generation photovoltaic devices.

---

## 🎯 Objectives

- Model a **lead-free perovskite solar cell** using SCAPS-1D  
- Analyze the impact of **HTL and ETL material selection**
- Identify the **best-performing device architecture**
- Compare simulated results with **reported literature**
- Present **numerical, graphical, and comparative analysis**

---

## 🧱 Device Architecture

### 🔝 Optimized Structure (Best Performing)

```

Au / CuAlO₂ / Cs₂TiBr₆ / IGZO / FTO

```


- **Absorber Layer:** Cs₂TiBr₆  
- **Hole Transport Layer (HTL):** CuAlO₂  
- **Electron Transport Layer (ETL):** IGZO  
- **Front Contact:** FTO  
- **Back Contact:** Au  

---

## 🛠️ Simulation Tool & Parameters

- **Simulator:** SCAPS-1D  
- **Temperature:** 300 K  
- **Absorber Thickness:** ~600 nm  
- **Illumination:** AM 1.5G  
- **Simulation Type:** J–V and QE analysis  

---

## 📊 Numerical Results (Best Performing Configuration)

> Extracted directly from `MINOR_MAIN_TABLE.xlsx`

| Parameter | Symbol | Value |
|---------|--------|------|
| Open-Circuit Voltage | V<sub>OC</sub> | **1.123 V** |
| Short-Circuit Current Density | J<sub>SC</sub> | **23.54 mA/cm²** |
| Fill Factor | FF | **73.88 %** |
| Power Conversion Efficiency | PCE (η) | **19.53 %** |
| Device Structure | — | **Au / CuAlO₂ / Cs₂TiBr₆ / IGZO / FTO** |
| Operating Temperature | — | **300 K** |

✔ Represents the **highest efficiency configuration**  
✔ Values are **simulation-backed and non-random**

---

## 📈 Architecture Comparison Summary

- **CuAlO₂ HTL** improves hole extraction and reduces recombination  
- **IGZO ETL** offers favorable band alignment and electron mobility  
- Cu₂O and PCBM-based structures show **lower FF and efficiency**  
- ZnSe-based ETLs suffer from **higher recombination losses**

---

## 🖼️ SCAPS Simulation Outputs

### J–V Characteristics
<img src="RESULTS/JV_Curve.png" width="650"/>

### Quantum Efficiency (QE)
<img src="RESULTS/QE_Curve.png" width="650"/>

### Energy Band Diagram
<img src="RESULTS/Band_Diagram.png" width="650"/>

📁 **Graph Directory Reference**

```
RESULTS/
├── JV_Curve.png
├── QE_Curve.png
└── Band_Diagram.png

```

---

## 📚 Comparison with Literature

Most reported Cs₂TiBr₆-based lead-free perovskite solar cells show efficiencies in the range of **3–12%** due to poor carrier transport and suboptimal band alignment.  

This work achieves a significantly improved **PCE of 19.53%**, surpassing many reported devices, primarily due to optimized transport layers and reduced interfacial recombination.

---

## 📂 Repository Structure

```
Research-on-Perovskite-Solar-Cell-Cs2TiBr6/
│
├── RESULTS/
│ ├── JV_Curve.png
│ ├── QE_Curve.png
│ └── Band_Diagram.png
│
├── DATA/
│ └── MINOR_MAIN_TABLE.xlsx
│
├── REPORT/
│ ├── Project_Report.docx
│ └── Synopsis.docx
│
├── REFERENCES/
│ ├── Research_Papers.pdf
│ └── Reference_Material.pptx
│
└── README.md
```


---

## 🔮 Future Scope

- Experimental validation of simulated architecture  
- Interface defect density optimization  
- Temperature-dependent performance analysis  
- Tandem solar cell integration  

---

## 👤 Author

**Priyanshu Aggarwal**  
Electronics & Communication Engineering  

📧 Email: Priyanshuaggarwal.in@gmail.com  
🔗 LinkedIn: https://linkedin.com/in/priyanshu1201  
💻 GitHub: https://github.com/AggarwalPriyanshu  

---

⭐ If you find this repository useful, feel free to star it!
