# Experimental Investigation of Microstructure & Wear Properties of DMLS-Produced Inconel 718

##  Project Overview

This project investigates the **microstructural and defect characteristics of DMLS-produced Inconel 718** and studies the effect of **Hot Isostatic Pressing (HIP)** on the as-built material.

The primary objective is to improve the microstructural and defect characteristics of **additively manufactured as-built Inconel 718** through HIP treatment. The study compares the as-built condition with samples subjected to HIP at **1100°C and 1200°C** under controlled pressure and holding time.

The project focuses on understanding the relationship between **additive manufacturing parameters, defects, microstructure, hardness, and subsequent mechanical/tribological behaviour**.

---

##  Objectives

* Investigate the microstructure of **DMLS-produced Inconel 718** in the as-built condition.
* Study the influence of **HIP treatment** on microstructural and defect characteristics.
* Compare samples treated at **1100°C and 1200°C**.
* Characterize changes in grain morphology, phases, and microstructural features.
* Perform **Micro-Vickers hardness testing** on the different material conditions.
* Study the influence of HIP on internal defects such as porosity.
* Conduct future tensile and wear testing to correlate mechanical/tribological behaviour with microstructural evolution.

---

##  Material: Inconel 718

Inconel 718 is a **nickel-based superalloy** widely used in demanding high-temperature applications such as aerospace and gas-turbine components.

Its important strengthening and secondary phases include:

* **γ (Gamma)** — Ni-rich FCC matrix
* **γ″ (Gamma double-prime, Ni₃Nb)** — primary strengthening precipitate
* **γ′ (Gamma-prime, Ni₃(Al,Ti))** — secondary strengthening phase
* **δ (Delta, Ni₃Nb)** — can form at grain boundaries
* **Laves phase** — brittle phase associated with elemental segregation during solidification

The presentation identifies γ″ as the main strengthening precipitate and notes that Laves phase formation is particularly relevant to AM Inconel 718 because of rapid solidification and elemental segregation.

---

##  Additive Manufacturing Process

The samples were produced using **Direct Metal Laser Sintering (DMLS)** / laser-based powder bed fusion.

### Printing Parameters

| Parameter         |            Value |
| ----------------- | ---------------: |
| Laser Power       |            280 W |
| Scanning Speed    |         960 mm/s |
| Layer Thickness   |            40 μm |
| Laser Type        |           Nd:YAG |
| Process Gas       |            Argon |
| Hatch Distance    |          0.11 mm |
| Scanning Strategy | X + 67° rotation |
| Bed Temperature   |             80°C |
| Machine           |         EOS M280 |

These processing parameters were used for fabrication of the Inconel 718 samples.

---

##  Hot Isostatic Pressing (HIP)

### What is HIP?

Hot Isostatic Pressing combines **elevated temperature and high gas pressure** to improve the internal integrity of a material.

In the case of AM Inconel 718, HIP can help close internal porosity by applying pressure uniformly from all directions. The presentation describes how pore walls deform and diffusion-bond during the process. HIP can also help reduce/dissolve undesirable Laves phase.

### HIP Conditions Used

| Sample   | Temperature | Pressure | Holding Time |
| -------- | ----------: | -------: | -----------: |
| As-Built |           — |        — |            — |
| HIP-1100 |      1100°C |  120 MPa |          4 h |
| HIP-1200 |      1200°C |  120 MPa |          4 h |

The two HIP conditions were selected to study the effect of treatment temperature while maintaining the same pressure and holding time.

---

##  Sample Preparation & Characterization

The samples were prepared for microstructural characterization using a sequence of sectioning, mounting, grinding, polishing, and etching.

### Metallographic Preparation

1. Sectioning of samples
2. Hot/cold mounting in resin
3. Progressive grinding using SiC abrasive papers
4. Polishing using diamond suspension up to **1 μm**
5. Final polishing using colloidal silica
6. Chemical etching to reveal grain/phase structure

### Characterization Techniques

* **Optical Microscopy (OM)**
* **Scanning Electron Microscopy (SEM)**
* **Micro-Vickers Hardness Testing**

The Micro-Vickers testing was performed using a **0.5 kgf load** with a **10 s dwell time**.

---

##  Microstructural Comparison

Three material conditions are investigated:

### 1. As-Built Inconel 718

The as-built material represents the microstructure directly after DMLS processing and provides the baseline condition for comparison.

### 2. HIP at 1100°C

The sample was treated at:

**1100°C / 120 MPa / 4 h**

### 3. HIP at 1200°C

The sample was treated at:

**1200°C / 120 MPa / 4 h**

Optical and SEM micrographs were obtained for the three conditions to investigate the changes associated with HIP treatment.

---

##  Why HIP is Important for AM Inconel 718

During metal additive manufacturing, rapid melting and solidification can produce defects and chemical segregation.

Important concerns include:

* Internal porosity
* Lack-of-fusion defects
* Gas pores
* Elemental segregation
* Laves phase formation
* Microstructural heterogeneity

The project therefore uses HIP as a post-processing method to investigate whether these characteristics can be improved and how the resulting microstructure changes.

---

##  Future Work

The next stages of the project include:

### Tensile Testing

Tensile testing will be performed on the as-built and HIP-treated samples to evaluate:

* Tensile strength
* Yield strength
* Elongation
* Ductility

The results will be used to determine the influence of HIP treatment on mechanical properties.

### Secondary Heat Treatment

Suitable **solution treatment and aging treatments** will be investigated after HIP to modify the microstructure and promote strengthening phases such as **γ′ and γ″**.

The resulting mechanical and microstructural properties will then be compared.

### Wear Analysis

Ball-on-disc wear testing will be conducted on different heat-treated conditions to investigate:

* Wear rate
* Coefficient of friction
* Wear mechanisms
* Relationship between wear behaviour and microstructure

---

##  Project Structure

```text
DMLS-Inconel718-HIP-Study/
│
├── README.md
│
├── Literature/
│   └── Research_Papers/
│
├── Experimental_Data/
│   ├── Hardness/
│   ├── Microstructure/
│   └── Wear/
│
├── Images/
│   ├── Optical_Microscopy/
│   └── SEM/
│
└── Results/
    └── Analysis/
```

---

##  Tools & Techniques

**Material:** Inconel 718
**Manufacturing:** DMLS / Laser Powder Bed Fusion
**Post-Processing:** Hot Isostatic Pressing
**Characterization:** Optical Microscopy, SEM, Micro-Vickers Hardness
**Metallography:** Grinding, Polishing, Chemical Etching
**Future Testing:** Tensile Testing, Secondary Heat Treatment, Ball-on-Disc Wear Testing

---

##  Key Topics Studied

* Metal Additive Manufacturing
* DMLS / Laser Powder Bed Fusion
* Inconel 718 Metallurgy
* Nickel-Based Superalloys
* γ, γ′, γ″ and δ phases
* Laves Phase
* Porosity and AM Defects
* Hot Isostatic Pressing
* Microstructural Evolution
* Micro-Vickers Hardness
* Tribology and Wear
* Heat Treatment

---

##  References

1. Benzing, J. T. et al. (2023). *Enhanced strength of additively manufactured Inconel 718 by means of a simplified heat treatment strategy*. Journal of Materials Processing Technology, 322, 118197.

2. Lesyk, D. A. et al. (2022). *Porosity and surface defects characterization of hot isostatically pressed Inconel 718 alloy turbine blades printed by 3D laser metal fusion technology*. MRS Advances, 7(9), 197–201.

---

##  Project Team

**Taneti Naveen** — 230003078
**Paidi Nisanth** — 230003049

**Supervisor:** Dr. Girish Chandra Verma
**Department of Mechanical Engineering**
**Indian Institute of Technology Indore**

---

##  Project Status

**Current Stage:** Microstructural characterization and hardness evaluation of as-built and HIP-treated Inconel 718.

**Completed/Under Study:** DMLS sample preparation, HIP treatment at 1100°C and 1200°C, metallographic preparation, optical microscopy, SEM characterization, and Micro-Vickers hardness testing.

**Planned:** Tensile testing, secondary heat treatment, and ball-on-disc wear analysis.
