
# 🧬 PCR Learning Laboratory
### Powered by [GenoFlow](https://github.com) · Professional Molecular Biology Training Platform

This educational platform simulates a complete PCR workflow in your browser. No installation needed. Perfect for biology, biotechnology, and medical laboratory students who want to understand PCR deeply instead of just memorizing steps.

### 🎯 What You'll Learn

By completing all modules, you will be able to:

- Explain the molecular mechanism of each PCR step (Denaturation, Annealing, Extension)
- Calculate exact reagent volumes using the **C₁V₁ = C₂V₂** dilution formula
- Set up a PCR reaction correctly (order and technique matter!)
- Design a basic thermal cycling program and calculate primer Tm
- Interpret agarose gel results and diagnose common failures
- Understand real-world applications of PCR in diagnostics, forensics, and research

### 📚 Modules Overview

| Module | Focus | Key Skills |
|--------|-------|------------|
| **01 Theory & Concepts** | What PCR is and how it works | Molecular mechanisms, exponential amplification, history & applications |
| **02 Mix Calculations** | Precision in reagent volumes | C₁V₁ = C₂V₂ formula, interactive calculator, practice problems |
| **03 Virtual Lab Protocol** | Hands-on pipetting simulation | Correct order of addition, realistic pipetting, guided tutorial |
| **04 PCR Programming** | Thermal cycling design | Program builder, temperature profile visualization, primer Tm calculator |
| **05 Gel Electrophoresis** | Result interpretation | Analyze 4 common gel outcomes (clean band, no band, multiple bands, smear) |
| **06 Assessment** | Knowledge test | 20-question quiz + Certificate of Completion (80%+ to pass) |

### 🧪 Standard 50 µL PCR Reaction Mix (Master Mix Approach)

This is the typical setup you'll practice in the **Mix Calculations** and **Virtual Lab** modules:

| Component              | Stock Concentration | Volume (µL) | Final Concentration | Role |
|------------------------|---------------------|-------------|---------------------|------|
| Nuclease-Free Water    | -                   | 22          | -                   | Solvent / volume adjustment |
| 2× Master Mix          | 2×                  | 25          | 1×                  | Contains Taq polymerase, dNTPs, buffer, Mg²⁺ |
| Forward Primer         | 10 µM               | 1           | 0.2 µM              | Binds to one strand |
| Reverse Primer         | 10 µM               | 1           | 0.2 µM              | Binds to opposite strand |
| DNA Template           | ~50 ng/µL           | 1           | ~1 ng/µL            | Source of target sequence |
| **Total**              | -                   | **50**      | -                   | - |

**Important order**: Always add **Water first**, **DNA Template last**.

### 🔥 The Three Steps of PCR (Repeated 25–35 times)

| Step          | Temperature | Duration     | What Happens |
|---------------|-------------|--------------|--------------|
| **Denaturation** | 94–96°C    | 30 seconds  | Double-stranded DNA separates into single strands |
| **Annealing**    | 50–65°C    | 30 seconds  | Primers bind to complementary sequences on single strands |
| **Extension**    | 72°C       | 1 min/kb    | Taq polymerase synthesizes new DNA strands |

**Exponential growth formula**:  
**Final copies ≈ Initial copies × 2ⁿ** (where n = number of cycles)

### 📊 Common Gel Electrophoresis Results & Troubleshooting

| Gel Observation          | Likely Meaning                     | Common Causes                              | How to Fix |
|--------------------------|------------------------------------|--------------------------------------------|----------|
| Single clean band at expected size | Successful PCR                    | Everything optimized                       | - |
| No bands                 | No amplification                  | Missing polymerase, bad primers, wrong annealing temp, no template | Check reagents, optimize Tm, add fresh template |
| Multiple / extra bands   | Non-specific amplification        | Annealing temperature too low, too much primer | Increase annealing temp by 2–5°C, reduce primer concentration |
| Smear (no discrete bands)| Degraded DNA or over-amplification| Old/degraded template, too many cycles    | Use fresh high-quality DNA, reduce cycle number |
| Band in NTC (no template control) | Contamination                  | Reagent or lab contamination               | Use new reagents, clean workspace |

### 🚀 How to Run the Lab

1. Download or clone the repository
2. Open **`pcr_learning.html`** in any modern web browser (Chrome/Firefox/Edge recommended)
3. Start with **Theory**, then follow the modules in order
4. Use the **Virtual Lab** for realistic pipetting practice (tutorial arrows will guide you)
5. Finish with the **Quiz** to earn your certificate

**Fully client-side** — works offline after the first load.

### 🧬 Why This Lab Exists

PCR is one of the most transformative techniques in modern biology. It powers COVID-19 testing, forensic DNA analysis, genetic research, and much more. Traditional textbooks often make it feel abstract. This lab makes it **visual, interactive, and practical** so you truly understand the "why" behind every step.

Made with ❤️ for students who want to think and work like real molecular biologists.


---

## 📁 Repository Structure

```
pcr-learning-lab/
│
├── index.html          # Complete application (all HTML + CSS + JS)
├── README.md           # This file
└── LICENSE             # MIT License
```

---

## 🎓 Learning Outcomes

After completing this lab, a student will be able to:

- ✅ Explain what PCR is and why it matters in medicine, forensics, and research
- ✅ Describe the three steps of a PCR cycle and the temperatures involved
- ✅ Calculate reagent volumes using the C₁V₁ = C₂V₂ dilution formula
- ✅ Execute a proper PCR setup protocol with correct pipetting technique
- ✅ Design a thermal cycling program for a given primer pair
- ✅ Interpret gel electrophoresis results and diagnose PCR failures

---

## 🧪 Screenshots

> *Coming soon — add screenshots of your app here!*
>
> Tip: Take screenshots of the Welcome screen, a Theory module, the Virtual Lab, and a Gel result. Upload them to a `/screenshots` folder and reference them here:
> ```markdown
<img width="484" height="474" alt="Image" src="https://github.com/user-attachments/assets/712809ae-eacf-4599-b6c9-35482ac6ee4d" />
<img width="472" height="374" alt="Image" src="https://github.com/user-attachments/assets/3e39cbdb-0ea0-45eb-92eb-dd9af279ae5f" />
<img width="934" height="1036" alt="Image" src="https://github.com/user-attachments/assets/b1ffc241-c862-4b48-8138-46596ec5965c" />

> ```

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to use, copy, modify, and distribute this project, including for commercial purposes, as long as you include the original license notice.

---

## 👤 Author

**GenoFlow** · Professional Molecular Biology Training

> Built with ❤️ for biology students who want to learn PCR before entering the lab.

---

*⭐ If this project helped you, consider giving it a star on GitHub!*
