# Reducing Distracted Driving Collisions in Ontario Using AI-Enabled Enforcement

## Overview
This project applies the Toyota Business Practice (TBP) A3 methodology, Exploratory Data Analysis (EDA), statistical hypothesis testing, and Machine Learning Operations (ML Ops) to reduce distracted driving collisions in Ontario by **50% by 2028**.  
Our approach combines real-world collision data analysis, hypothesis testing, and AI modeling to identify high-risk conditions and recommend targeted enforcement strategies.

---

## Research Hypothesis
Weekly **distracted-driving** collisions in Ontario can be reduced from **216/week** to **108/week** by implementing AI-powered predictive checkpoint deployment and targeted mobile alert systems.

---

## Repository Structure
- **`/data`** – Contains the datasets used in analysis:
  - `NCDB_2010_2014_small.csv` – National Collision Database (2010–2014)
  - `KSI_CLEAN.csv` – Toronto Killed or Seriously Injured dataset
  - `Traffic_Collisions.csv` – Detailed collision records with contributing factors
- **`/notebooks`**
  - `notebook.py` – End-to-end workflow including:
    - Data cleaning and preprocessing
    - Exploratory Data Analysis (EDA) and visualizations
    - Chi-Square & T-Test hypothesis testing
    - ML Ops pipeline for high-risk prediction
- **`/docs`**
  - `Final_Report.pdf` – Full project paper
  - `A3_Form.pdf` – Toyota Business Practice A3 form
  - `Execution_Instructions.pdf` – Step-by-step instructions to run code
- **`requirements.txt`** – Python dependencies

---

## Setup & Execution

### 1. Clone the repository
```bash
git clone https://github.com/Amankhoja/Group_6-Motor-vehicle-accident.git
cd Group_6-Motor-vehicle-accident
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the analysis
```bash
python notebooks/notebook.py
```
or open the notebook in Jupyter:
```bash
jupyter notebook notebooks/notebook.ipynb
```

---

## Features
- **Data Cleaning** – Removes missing values, normalizes codes, and merges multiple datasets.
- **EDA** – Identifies collision trends, high-risk times, and environmental factors.
- **Statistical Testing** – Validates hypotheses using Chi-Square and T-Tests.
- **Machine Learning** – Random Forest model predicts high-risk conditions for human-factor collisions.
- **Countermeasure Recommendations** – Based on Toyota Business Practice Step 5.

---

## Sample Outputs
- Weekly collision trend plots
- High-risk time-of-day and day-of-week charts
- Statistical test results (Chi-Square & T-Test)
- Feature importance rankings from the ML model
- Example countermeasure roadmap

---

## Authors
- Aman Hasanali Khoja
- Abdur Rahman Shaik
- Anish Reddy
- Naresh Kasthuri
- Jayavanti Wesley

---

## License
This project is for academic purposes under the **Case Studies in Artificial Intelligence and Machine Learning** course at Conestoga College.
