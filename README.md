# Loan Approval Prediction: A Machine Learning Approach

## 📌 Project Overview

This project explores **loan approval prediction** using **Machine Learning models** to assess financial risk. By analyzing key applicant features (income, CIBIL Score, education level, etc.), we aim to build a predictive model that determines the likelihood of loan approval.

The report was developed using **Quarto (RStudio)** and later converted into **LaTeX (Overleaf)** for professional documentation.

## 📂 Repository Contents

- 📄 **Final Report (PDF)** – The complete analysis, results, and conclusions.
- 📁 **Quarto File (.qmd)** – The original version compiled in RStudio.
- 📁 **R Code Files** – Scripts used for data processing and model training.
- 📊 **Dataset** – Data used for training the model.

## 🚀 Methodology

1. **Exploratory Data Analysis (EDA)**: Identified key patterns in the dataset.
2. **Feature Engineering**: Selected the most relevant features.
3. **Model Selection**: Compared different ML algorithms to find the best-performing one.
4. **Evaluation**: Assessed the model using accuracy and other performance metrics.
5. **Report Documentation**: Finalized findings in a structured report using **LaTeX**.

## 🔍 Key Findings

✅ **CIBIL Score is the Most Critical Factor**: Loan approvals are heavily influenced by credit score, with applications scoring above 650 having a high approval rate, while those below 550 face near-certain rejection.

✅ **Income Alone Doesn’t Guarantee Approval**: Higher-income applicants tend to request larger loans, but approval also depends on debt-to-income ratios and credit history.

✅ **Loan Term Length Affects Approval**: Shorter terms (<5 years) increase approval chances for borderline CIBIL scores (550–650), while longer terms are riskier and often rejected.

## 📊 Machine Learning Models Used

🟢 **Decision Tree** – Strengths: Highly interpretable with clear "if-else" rules (e.g., CIBIL ≥ 550 → approve). Weaknesses: Lower accuracy (95.4%) due to oversimplification.

🟢 **Random Forest** – Strengths: Ensemble method with near-perfect accuracy (99.88%), robust to overfitting. Weaknesses: Less interpretable than a single tree.

🟢 **Best Model**: Random Forest – Final accuracy: 99.88% (outperformed Decision Tree in sensitivity, specificity, and precision).

## 🔧 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Loan-approval-prediction-project.git
   ```
2. Open the RStudio project or navigate to the Quarto files.
3. Run the scripts to reproduce the analysis.
4. View the final **PDF report** for key insights.

## 📝 Acknowledgments

This project was a **self-initiated project**. It was a challenging yet rewarding experience, especially formatting the report from **Quarto (RStudio) to LaTeX (Overleaf)!**

---

💡 **Let’s Connect!** If you have feedback or suggestions, feel free to open an issue or reach out. 🚀
