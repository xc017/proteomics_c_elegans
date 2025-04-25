# 🧬 SARS-CoV-2 Proteomics and Translateomics Analysis

This repository contains a comprehensive bioinformatics project conducted as part of a university course. The aim was to investigate the **protein–protein interactions (PPI)** and analyze **proteomics and translateomics data** related to SARS-CoV-2 infection, building upon key studies such as Gordon et al. (2020) and Bojkova et al. (2020).

---

## 📁 Project Files

- `combined_protein.tsv` — processed PPI dataset
- `SARS-CoV-2 proteins.xlsx` — reference sheet for viral proteins
- `Timecourse of proteome measurements.xlsx` — proteomics dataset
- `Translatome_measurements_use.xlsx` — translateomics dataset
- `w9.ipynb` — PPI analysis
- `w10.ipynb` — Proteomics analysis
- `w11.ipynb` — Translateomics analysis
- `proteomics_report.pdf` — Full written report with visualisations and interpretation

---

## 🧪 Summary of Analysis

### 1. Protein–Protein Interaction (PPI)
- Used SARS-CoV-2 protein NSP2 as a “bait” to detect specific human protein interactions.
- Filtered out proteins uniquely detected in NSP2 samples vs. EGFP controls.
- Functional enrichment done via Panther and GProfiler.

### 2. Proteomics Analysis
- Explored time-dependent host response during viral infection.
- Identified differentially expressed human and viral proteins at 2h, 6h, 10h, and 24h.
- Highlighted pathways affected: metabolic suppression, energy production, structural maintenance.

### 3. Translateomics Analysis
- Focused on newly synthesized proteins at 24h.
- Observed a sharp increase in viral protein translation during early stages of infection.
- Detected obstruction in host cell communication via downregulated exosome-related proteins.

---

## 📊 Tools & Techniques

- **Jupyter Notebooks** (Python, Pandas, Seaborn, Matplotlib)
- **Panther** for pathway enrichment
- **GProfiler** for functional annotation
- **Volcano plots**, correlation analysis, gene filtering

---

## 🔗 Jupyter Notebook Links (from report)

- [PPI Analysis](https://colab.research.google.com/drive/1iOeL-byaKAJbQL-SIZmpznSvxjdQn3wT?usp=sharing)
- [Proteomics](https://colab.research.google.com/drive/1cdccdwBPgJePV0sz52iRJvNiwcCOoXgr?usp=sharing)
- [Translateomics](https://colab.research.google.com/drive/1ozb8L_jM07-Vkv5fn74Cnxb65fCvAeWD?usp=sharing)

---

## 🧠 Key Findings

- SARS-CoV-2 NSP2 may disrupt host **ATP production**, **cell structure**, and **metabolic processes**
- Human proteins related to immune signaling and metabolism were suppressed
- Viral proteins increased sharply early on, outpacing human protein translation

---

## 📚 References

- Gordon et al. (2020). *A SARS-CoV-2 protein interaction map reveals targets for drug repurposing*. [Nature](https://doi.org/10.1038/s41586-020-2286-9)
- Bojkova et al. (2020). *Proteomics of SARS-CoV-2-infected host cells reveals therapy targets*. [Nature](https://doi.org/10.1038/s41586-020-2332-7)

---

## 👩‍🔬 Author

**xc017**  
Group 11 — University Proteomics Project

