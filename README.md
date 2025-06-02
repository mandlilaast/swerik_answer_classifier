# SWERIK Answer Classifier

This repository contains a rule-based solution for detecting ministerial answers to parliamentary questions in the Riksdag chamber protocols. Developed as part of the Junior SWERIK Research Engineer homework assignment.

## Contents

- `swerik_classifier.ipynb`: Main Jupyter notebook for parsing XML data, applying classification heuristics, and plotting results.
- `answers.csv`: Output file listing utterance IDs identified as ministerial answers.
- `plot.png`: Graph showing frequency of detected answers per year.
- `report.pdf`: Final report discussing methods, results, and limitations.

---

## 🛠️ Setup (using Conda)

### 1. Create and activate the environment

```bash
conda env create -f environment.yml
conda activate swerik-env
