COVID-19 Mortality Risk Factors Analysis
An exploratory data analysis using binary logistic regression to uncover key mortality risk factors among COVID-19 patients at Pratama Hospital Yogyakarta.

🚀 Key Features
Cleaned and preprocessed clinical data of 174 patients (2021–2023)

Extracted structured variables from symptoms and treatment notes

Performed statistical analysis:

Chi-square independence test

Binary logistic regression (partial & overall test)

Odds ratio interpretation

Evaluated model with accuracy, precision, recall, and F1 score

Presented findings with practical recommendations for hospital and future research

📂 Project Structure
bash
Copy
Edit
COVID19-Mortality-Analysis/
├── data/                 # Raw and cleaned dataset
├── report/               # Final exported documents (DOCX, PDF)
├── plots/                # Visualizations and model charts
├── covid19_analysis.Rmd  # Main analysis script
└── README.md             # Project documentation
🛠️ Setup & Execution
Clone the repository:

bash
Copy
Edit
git clone https://github.com/billycemerson/COVID19-Mortality-Analysis.git
Open the .Rmd file with RStudio

Install the required R libraries (see below), and Knit to Word/PDF for final report

📊 Sample Results
Significant Risk Factors (Odds Ratio):

Age > 50 → 11.46× more likely to die

Confirmed COVID-19 status → 2.95× more likely to die

Outpatient care → 55.17× more likely to die

Eating disorders → 66.54× more likely to die

Shortness of breath → 2.67× less likely to die

Model Evaluation on Test Data:

Accuracy: 60.3%

Precision: 54.5%

Recall: 8.6%

F1 Score: 14.9%

🧩 R Dependencies
Make sure the following libraries are installed:

r
Copy
Edit
install.packages(c(
  "tidyverse", "readxl", "janitor", "broom", "ggplot2",
  "dplyr", "car", "ResourceSelection", "pROC", "caret"
))
📄 License
This project is open-source and licensed under the MIT License.
