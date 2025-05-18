# 🧠 R&D – Multitask Learning for Low-Resource Arabic Dialects

This repository contains research and experimental work on Multitask Learning (MTL) applied to low-resource Arabic dialects. It aims to improve core NLP tasks such as dialect-to-MSA translation, dialect identification, and diacritic restoration by leveraging task interdependencies.

## 📌 Project Overview

- **Context**: Arabic dialects present significant challenges for NLP due to their linguistic diversity and lack of annotated data.
- **Goal**: Evaluate the impact of multitask learning versus single-task learning on several downstream NLP tasks.
- **Approach**: Implement and test shared encoder-decoder and hierarchical attention models, with auxiliary tasks to enhance primary performance.

### Key Contributions

- Comparative evaluation between MTL and STL models across 3 tasks:
  - Dialect-to-MSA Translation
  - Dialect Identification (city, state, country levels)
  - Diacritic Restoration
- Architecture exploration:
  - Shared encoder-decoder models (LSTM-based)
  - Hierarchical attention models (HA-MTL)
- Metrics achieved:
  - BLEU score (MTL): **0.62** vs STL: **0.0394**
  - Dialect classification accuracy (MTL): **89%**

> 📄 For detailed results and analysis, see `R_D_paper_F.pdf`

---

## 📂 Repository Structure

```
R-D/
├── R&D 1.ipynb             # Main experimental notebook: data loading, model training
├── TESTING.ipynb           # Evaluation notebook with results and metrics
├── R_D_paper_F.pdf         # Research report with methodology and results
└── README.md               # Project documentation
```

---

## 🚀 Quick Start

1. **Clone the repo**:

```bash
git clone https://github.com/brahex123/R-D.git
cd R-D
```

2. **Install dependencies** (example with pip):

```bash
pip install -r requirements.txt
```

3. **Launch the notebooks**:

```bash
jupyter notebook
```

Open `R&D 1.ipynb` to begin training or `TESTING.ipynb` to reproduce evaluation.

---

## 📈 Results Snapshot

| Task                     | Metric        | STL     | MTL     |
|--------------------------|---------------|---------|---------|
| Dialect → MSA Translation | BLEU Score    | 0.0394  | 0.35    |
| Dialect Classification   | Accuracy      | 73%     | 89%     |
| Diacritic Restoration    | Accuracy      | 85%     | 92%     |

---

## 📚 References

- Moukafih et al. (2024) — *Improving Neural Machine Translation of Arabic Dialects to MSA using MTL*
- Abdul-Mageed et al. — *DiaNet: Hierarchical Attention MTL for Dialect Identification*
- Alqahtani et al. — *MTL for Diacritic Restoration*

---

## 🤝 Acknowledgments

This project was conducted as part of an academic collaboration between:

- **International University of Rabat (UIR)**
- **Supervisors**: Pr. Youness Moukafih, Pr. Hakim Hafidi

---

## 📬 Contact

- **Author**: Brahim Mechaouat  
- [Portfolio](https://brahex123.github.io/ibrahex123.github.io/)  
- [GitHub](https://github.com/brahex123)

---

