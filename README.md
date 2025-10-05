# 🏥 Healthcare Patient Risk Stratification

## 📋 Project Overview
This project applies **Machine Learning** to predict and visualize patient health risk levels (Low, Medium, High) using anonymized clinical data.  
It fulfills **Task 5: Healthcare Patient Risk Stratification** from the Data Analytics specialization — focusing on **risk prediction, interpretability, and visualization**.

---

## 🎯 Objectives
- Perform data cleaning and encoding of patient attributes.  
- Train a **Gradient Boosting Classifier** for risk prediction.  
- Achieve AUC > 0.85 on test data.  
- Create interpretable model visualizations using Matplotlib and SHAP.  
- Generate a risk stratification report and supporting visuals.

---

## ⚙️ Tech Stack
| Category | Tools |
|-----------|--------|
| Language | Python 3.10+ |
| Libraries | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SHAP |
| Environment | Jupyter Notebook / VS Code |

---

## 📂 Files Included
| File | Description |
|------|--------------|
| `Health_Risk_Dataset.csv` | Input anonymized patient dataset |
| `healthcare_risk_model.py` / `.ipynb` | Main code file (preprocessing, training, visualization) |
| `patient_risk_predictions.csv` | Model predictions and categorized risk levels |
| `feature_importance.png` | Feature contribution visualization |
| `risk_distribution.png` | Count of patients by predicted risk level |
| `probability_distribution.png` | Histogram of “High Risk” probabilities |
| `requirements.txt` | Dependencies for easy setup |
| `README.md` | Project overview and usage instructions |

---

## 🚀 How to Run
1. **Clone the repository**
   ```bash
   git clone <your_repo_link>
   cd healthcare-risk-stratification

2. Install dependencies
   pip install -r requirements.txt

3. Run the script or notebook
   python healthcare_risk_model.py

Outputs

After execution, the following files will be generated automatically:
patient_risk_predictions.csv → contains predicted and true risk levels.
feature_importance.png → top features influencing model predictions.
risk_distribution.png → visual summary of predicted patient risk levels.
probability_distribution.png → probability density of “High Risk” patients.

🧠 Interpretation

Feature Importance: Identifies which clinical features (e.g., heart rate, blood pressure, oxygen saturation) most affect risk level.
Risk Distribution: Displays how patients are spread across risk categories.
Probability Distribution: Reveals how likely patients are to fall into the “High Risk” category, helping clinicians prioritize follow-ups.

🔐 Ethical Compliance
All data used is anonymized and handled according to HIPAA-like standards.
No personally identifiable information (PII) is stored or displayed.

👨‍⚕️ Author

Name: Muhammad Yaseen
Tools Used: Python, Pandas, Scikit-learn, Matplotlib, SHAP

🏁 Evaluation Criteria Checklist
✅ Robust preprocessing and encoding
✅ Model with AUC > 0.85
✅ Clean, interpretable visualizations
✅ Ethical data handling
✅ Professional documentation