# 🩺 COVID-19 Mortality Risk Factors Analysis

An exploratory data analysis using **binary logistic regression** to uncover key mortality risk factors among COVID-19 patients at **Pratama Hospital Yogyakarta**.

---

## 🚀 Key Features

- Cleaned and preprocessed clinical data from 174 patients (2021–2023)
- Extracted structured variables from unstructured symptom and treatment notes
- Performed statistical analysis:
  - Chi-square independence test
  - Binary logistic regression (overall and partial significance tests)
  - Odds ratio interpretation
- Evaluated model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- Delivered findings with practical recommendations for hospital policy and future research

---

## 🛠️ Setup & Execution

1. Clone the repository:

   ```bash
   git clone https://github.com/billycemerson/COVID19-Mortality-Analysis.git
````

2. Open the `.Rmd` file using **RStudio**

3. Install the required R packages (see below)

4. Knit the document to `.docx` or `.pdf` for final reporting

---

## 📊 Sample Results

### 🔍 Significant Risk Factors (Odds Ratio)

| Variable                | Odds Ratio | Interpretation                            |
| ----------------------- | ---------- | ----------------------------------------- |
| Age > 50                | 11.46×     | Much higher risk of death                 |
| Confirmed COVID-19 case | 2.95×      | Increased risk                            |
| Outpatient care         | 55.17×     | Substantially higher mortality risk       |
| Eating disorders        | 66.54×     | Extremely high mortality risk             |
| Shortness of breath     | 0.37×      | Lower risk — potentially counterintuitive |

> Note: Odds ratio < 1 indicates a *lower* likelihood of death.

---

### 📈 Model Evaluation (Test Data)

* **Accuracy**: 60.3%
* **Precision**: 54.5%
* **Recall**: 8.6%
* **F1 Score**: 14.9%

---

## 📦 R Dependencies

Make sure to install the following R packages before running the analysis:

```r
install.packages(c(
  "tidyverse", "readxl", "janitor", "broom", "ggplot2",
  "dplyr", "car", "ResourceSelection", "pROC", "caret"
))
```

---

## 📄 License

This project is open-source and licensed under the **MIT License**.

```
