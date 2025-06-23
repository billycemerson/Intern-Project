# 🩺 COVID-19 Mortality Risk Factors Analysis  
An exploratory data analysis using **binary logistic regression** to uncover key mortality risk factors among COVID-19 patients at **Pratama Hospital Yogyakarta**.

---

## 🚀 Key Features

- Cleaned and preprocessed clinical data of 174 patients (2021–2023)
- Extracted structured variables from symptoms and treatment notes
- Performed statistical analysis:
  - Chi-square independence test
  - Binary logistic regression (overall and partial tests)
  - Odds ratio interpretation
- Evaluated model using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- Presented findings with practical recommendations for hospital action and future research directions

---

## 🛠️ Setup & Execution

1. Clone the repository:
   ```bash
   git clone https://github.com/billycemerson/COVID19-Mortality-Analysis.git
````

2. Open the `.Rmd` file using **RStudio**
3. Install required packages (see below)
4. Knit the document to `.docx` or `.pdf` for final output

---

## 📊 Sample Results

### 🔍 Significant Risk Factors (Odds Ratio)

* **Age > 50** → 11.46× more likely to die
* **Confirmed COVID-19 status** → 2.95× more likely to die
* **Outpatient care** → 55.17× more likely to die
* **Eating disorders** → 66.54× more likely to die
* **Shortness of breath** → 2.67× less likely to die

### 📈 Model Evaluation on Test Data

* **Accuracy**: 60.3%
* **Precision**: 54.5%
* **Recall**: 8.6%
* **F1 Score**: 14.9%

---

## 🧩 R Dependencies

Make sure the following packages are installed in your R environment:

```r
install.packages(c(
  "tidyverse", "readxl", "janitor", "broom", "ggplot2",
  "dplyr", "car", "ResourceSelection", "pROC", "caret"
))
```

---

## 📄 License

This project is open-source and licensed under the MIT License.

---
