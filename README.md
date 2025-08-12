# Reducing Distracted Driving Collisions in Ontario Using AI-Enabled Enforcement

## Overview
This project applies the Toyota Business Practice (TBP) A3 methodology, Exploratory Data Analysis (EDA), statistical hypothesis testing, 
and Machine Learning Operations (ML Ops) to reduce distracted driving collisions in Ontario by 50% by 2028.

## Repository Structure
- **/data** – Contains three datasets:
  - `NCDB_2010_2014_small.csv` – National Collision Database (2010–2014)
  - `KSI_CLEAN.csv` – Toronto Killed or Seriously Injured dataset
  - `Traffic_Collisions.csv` – Detailed collision records with contributing factors
- **/notebooks** – `notebook.py` containing:
  - Data cleaning and preprocessing
  - EDA and visualizations
  - Chi-Square & T-Test hypothesis testing
  - ML Ops pipeline for high-risk prediction
- **/docs** – Final Report, A3 Form, and Execution Instructions
- **requirements.txt** – Python dependencies

## Setup & Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/Amankhoja/Group_6-Motor-vehicle-accident.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure datasets are in `/data`.
4. Run the workflow:
   ```bash
   python notebooks/notebook.py
   ```

## Authors
- Aman Hasanali Khoja
- Abdur Rahman Shaik
- Anish Reddy
- Naresh Kasthuri
- Jayavanti Wesley
