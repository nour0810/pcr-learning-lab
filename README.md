# 🧬 PCR Learning Laboratory

**[🚀 Open PCR Learning Lab Now](https://htmlpreview.github.io/?https://github.com/nour0810/pcr-learning-lab/blob/main/index.html)**

*No installation needed — works directly in your browser*

---

**An interactive virtual lab to master Polymerase Chain Reaction (PCR)** — entirely in your browser.

This educational platform simulates a complete PCR workflow with theory, calculations, realistic pipetting, thermal cycling design, gel interpretation, and a final assessment.

Perfect for biology, biotechnology, and medical laboratory science students.

### 🎯 What You'll Learn

By completing all modules, you will be able to:
- Explain the molecular mechanism of each PCR step (Denaturation, Annealing, Extension)
- Calculate exact reagent volumes using the **C₁V₁ = C₂V₂** dilution formula
- Set up a PCR reaction correctly (order and technique matter!)
- Design a thermal cycling program and calculate primer Tm
- Interpret agarose gel results and diagnose common failures
- Understand real-world applications in diagnostics, forensics, and research

### 📚 Modules

| Module                        | Focus                              | Key Skills |
|-------------------------------|------------------------------------|------------|
| **01 Theory & Concepts**      | What PCR is and how it works       | Molecular mechanisms, exponential amplification, applications |
| **02 Mix Calculations**       | Precision in reagent volumes       | C₁V₁ = C₂V₂ formula, interactive calculator, practice |
| **03 Virtual Lab Protocol**   | Hands-on pipetting simulation      | Correct order, realistic pipetting, guided tutorial |
| **04 PCR Programming**        | Thermal cycling design             | Program builder, temperature profile, Tm calculator |
| **05 Gel Electrophoresis**    | Result interpretation              | Diagnose clean band, no band, multiple bands, smear |
| **06 Assessment**             | Knowledge test                     | 20-question quiz + Certificate (80%+ to pass) |

### 🧪 Standard 50 µL PCR Reaction Mix

| Component              | Stock Concentration | Volume (µL) | Final Concentration | Role |
|------------------------|---------------------|-------------|---------------------|------|
| Nuclease-Free Water    | —                   | 22          | —                   | Solvent |
| 2× Master Mix          | 2×                  | 25          | 1×                  | Taq polymerase + dNTPs + buffer + Mg²⁺ |
| Forward Primer         | 10 µM               | 1           | 0.2 µM              | Binds to one strand |
| Reverse Primer         | 10 µM               | 1           | 0.2 µM              | Binds to opposite strand |
| DNA Template           | ~50 ng/µL           | 1           | ~1 ng/µL            | Target sequence |
| **Total**              | —                   | **50**      | —                   | — |

**Important**: Always add **Water first**, then Master Mix → Primers → **DNA Template last**.

### 🔥 The Three Steps of PCR

| Step            | Temperature | Duration     | What Happens |
|-----------------|-------------|--------------|--------------|
| **Denaturation**   | 94–96°C    | 30 seconds  | DNA double helix separates into single strands |
| **Annealing**      | 50–65°C    | 30 seconds  | Primers bind to complementary target sequences |
| **Extension**      | 72°C       | 1 min/kb    | Taq polymerase synthesizes new DNA strands |

**Amplification formula**: Final copies ≈ Initial copies × 2ⁿ (n = number of cycles)

### 📊 Gel Electrophoresis Troubleshooting

| Gel Observation                  | Likely Meaning              | Common Causes                              | How to Fix |
|----------------------------------|-----------------------------|--------------------------------------------|----------|
| Single clean band at expected size | Successful PCR             | Conditions optimized                       | — |
| No bands                         | No amplification           | Bad primers, missing Taq, wrong Tm, no template | Check reagents, optimize annealing temperature |
| Multiple / extra bands           | Non-specific amplification | Annealing temperature too low              | Increase annealing temp by 2–5°C |
| Smear (no discrete bands)        | Degraded DNA               | Old or degraded template DNA               | Use fresh high-quality DNA |
| Band in NTC                      | Contamination              | Contaminated reagents or workspace         | Use new reagents, clean area |

### 🚀 How to Run the Lab

**Quick Start:**
→ **[Open PCR Learning Laboratory](https://htmlpreview.github.io/?https://github.com/nour0810/pcr-learning-lab/blob/main/index.html)**

**Alternative (local):**
1. Open `index.html` in any modern web browser (Chrome/Firefox/Edge recommended)
2. Start with **Theory & Concepts**, then follow the modules in order
3. Practice pipetting in the **Virtual Lab** (tutorial arrows will guide you)
4. Complete the quiz to earn your certificate

**Fully client-side** — works completely offline after the first load.

### 🧬 Why This Lab Exists

PCR powers COVID-19 testing, forensic DNA analysis, genetic research, and many other fields. This lab makes learning PCR **visual, interactive, and practical** so you truly understand the science instead of just memorizing steps.

Made with ❤️ for students who want to think and work like real molecular biologists.

---

### 📸 Screenshots

#### 1. Welcome Screen
![Welcome Screen - PCR Learning Laboratory](https://github.com/user-attachments/assets/19f4de48-bcef-4415-8e7e-894cca99430b)

#### 2. PCR Components
![Virtual Lab Protocol - Realistic Pipetting](https://github.com/user-attachments/assets/bad01c42-567e-4e12-8e1e-069c59eca739)

#### 3. PCR Setup
![Gel Electrophoresis - Result Analysis](https://github.com/user-attachments/assets/a269c84f-e4e9-4c32-8cc7-ad8c292c19c0)

---

### 📁 Repository Structure
pcr-learning-lab/

├── index.html         # Complete single-file application

├── README.md

├── LICENSE            # MIT License

└── screenshots/       # Demo images

---

## 📄 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

**Author**: nourelhouda (nour0810)

---

⭐ If this project helped you learn PCR, please give it a star!
