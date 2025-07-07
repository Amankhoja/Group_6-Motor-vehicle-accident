# 🚗 GROUP 6: Motor Vehicle accident

This project investigates the impact of DUI (Driving Under the Influence) on traffic collisions in Toronto using Exploratory Data Analysis (EDA) and statistical hypothesis testing. The objective is to determine if there has been a statistically significant reduction in DUI-related incidents after 2014, and to analyze patterns based on time, driver condition, and location.

---

## 📁 Project Structure

```
dui-accident-analysis/
├── README.md
├── requirements.txt
├── data/
│   └── Dataset.csv
├── notebook/
│   └── notebook.ipynb
├── images/
│   ├── dui_by_driver_condition.png
│   ├── dui_by_hour.png
│   └── dui_by_division.png
```

---

## 📊 Dataset

- **Source**: [Toronto Open Data Portal – Motor Vehicle Collisions - KSI](https://open.toronto.ca/dataset/motor-vehicle-collisions-ksi/)
- **File Used**: `Dataset.csv` (cleaned and preprocessed version)
- **Features Used**:
  - `DATE`, `TIME`, `ALCOHOL`, `DRIVCOND`, `DIVISION`, etc.

---

## 🧪 Hypothesis

**Research Question**: Has the number of DUI-related accidents significantly decreased after 2014?

- **H₀ (Null Hypothesis)**: There is no statistically significant difference in DUI-related collisions before and after 2014.
- **H₁ (Alternative Hypothesis)**: There is a statistically significant decrease in DUI-related collisions after 2014.

✅ We used a **two-sample T-test** on yearly DUI counts, which yielded a statistically significant p-value (< 0.05), leading us to **reject the null hypothesis**.

---

## 📈 Exploratory Data Analysis (EDA)

The notebook provides:
- Missing data analysis
- Trend of DUI accidents over years
- Breakdown of DUI cases by:
  - Driver condition
  - Time of day (hour)
  - Police division

All plots are included in the `images/` folder and generated during runtime.

---

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Amankhoja/Group_6-Motor-vehicle-accident
cd Group_6-Motor-vehicle-accident
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the Jupyter Notebook
```bash
jupyter notebook ./notebook/notebook.ipynb
```

Make sure all paths remain **relative** (e.g., `./data/Dataset.csv`) and not absolute.

---

## 📦 Dependencies

See `requirements.txt`:

```
pandas
numpy
matplotlib
seaborn
scipy
```

---

## 📚 References

- Toronto Police Services. (n.d.). *Motor Vehicle Collisions – KSI*. Retrieved from [Toronto Open Data](https://open.toronto.ca/dataset/motor-vehicle-collisions-ksi/)
- SciPy Stats Documentation – [T-test](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html)

---

## 👥 Authors

- Group 6 – CSCN8040 (Conestoga College)