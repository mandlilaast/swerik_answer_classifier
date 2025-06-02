# SWERIK Answer Classifier

This repository contains a rule-based solution for detecting ministerial answers to parliamentary questions in the Riksdag chamber protocols. Developed as part of the Junior SWERIK Research Engineer homework assignment.

---

## 📁 Contents

- `swerik_classifier.ipynb`: Main Jupyter notebook for parsing XML data, applying classification heuristics, and plotting results.
- `answers.csv`: Output file listing utterance IDs identified as ministerial answers.
- `plot.png`: Graph showing frequency of detected answers per year.
- `report.pdf`: Final report discussing methods, results, and limitations.
- `Riksdagen_records_task.pdf`: Homework task description as provided by SWERIK.
- `TaskForJuniorResearchEngineerErikMandel.pdf`: PDF version of the solution report.
- `environment.yaml`: Conda environment file with dependencies, including pip-installed `pyriksdagen`.

---

## 🛠️ Setup Instructions (using Conda)

### 1. Create and activate the environment

```bash
conda env create -f environment.yaml
conda activate swerik-env
```

### 2. Launch the Jupyter Notebook

```bash
jupyter notebook
```

### 3. Open the notebook

Open `swerik_classifier.ipynb` in Jupyter and run the cells to parse data and generate the output files.

---

## 🧰 Dependencies

This project uses Python 3.11 and the following packages:

- **pandas** – data manipulation  
- **lxml** – XML parsing  
- **matplotlib** – plotting  
- **jupyter** – interactive notebooks  
- **pyriksdagen** – Riksdag data API (installed via pip)

All dependencies are included in `environment.yaml`.

---

## ✍️ Author

**Erik Mandel**  
📧 [erik.mandel@outlook.com](mailto:erik.mandel@outlook.com)
