# Job Seeker Analytics – Salary Prediction & Location Preference Classification

## Project Overview
This project analyzes job seeker profiles across Indian cities (2021) to solve two key problems:
1. **Salary Prediction** – Estimate expected salary based on profile attributes.
2. **Location Preference Classification** – Predict whether a candidate prefers Delhi NCR locations.

## Problem Statements
### 1. Salary Prediction (Regression)
- **Goal**: Predict salary using features like education, experience, specialization, industry, etc.
- **Model**: Regression algorithms (Linear, Random Forest, XGBoost)
- **Evaluation**: RMSE, R² Score

### 2. Location Preference Classification
- **Goal**: Classify if a candidate prefers Delhi NCR (Delhi, Noida, Gurgaon, Faridabad)
- **Model**: Classification algorithms (Logistic Regression, Decision Trees, SVM)
- **Evaluation**: Accuracy, Precision, Recall, F1 Score

## 📁 Folder Structure
See [here](#) for detailed folder breakdown.

## Tools & Libraries
- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Jupyter Notebooks
- GitHub for version control and documentation

## 📈 Results Summary
- Salary model achieved **R² = 0.78** on test data
- Location classifier reached **F1 Score = 0.84**

## ⚖️ Ethical Considerations
- Bias mitigation in salary prediction
- Fairness across geographic and demographic segments

## How to Run
```bash
# Clone the repo
git clone https://github.com/yourusername/job-seeker-analytics.git
cd job-seeker-analytics
```
# Install dependencies

```
pip install -r requirements.txt
```

# Run notebooks or scripts
```
jupyter notebook notebooks/salary_prediction.ipynb
```
