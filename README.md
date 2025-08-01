# 🤖 Digital Lending E-Sign Prediction System

Welcome! This project tackles a real-world challenge in digital finance: **predicting whether a loan applicant will electronically sign (e-sign) their documents**. In an era where digital transformation is reshaping banking, understanding and anticipating user behavior is crucial for streamlining operations, improving customer experience, and reducing manual paperwork.

## 🚀 Why This Project?

Electronic signatures are a key step in digital lending, but not all applicants complete this process. By leveraging machine learning, we can:

- Identify applicants likely to e-sign, enabling targeted digital nudges  
- Optimize onboarding and reduce operational friction  
- Support data-driven decision-making for financial institutions  

This project demonstrates the end-to-end development of a predictive system, from raw data to deployable model, and is designed to showcase both technical rigor and practical impact.

---

## 📂 Project Structure

- `Bank-1.ipynb` — Main notebook: data exploration, visualization, feature engineering, model training, and evaluation  
- `train.csv` — Raw dataset of loan applicants  
- `data_model.csv` — Processed dataset after feature engineering  
- `e_sign_model.pkl` — Trained logistic regression model for e-sign prediction  
- `loan_prediction_model_final_tweaked.pkl` — (Optional) Additional model for loan prediction  
- `E signed or not classification.pdf` — Project documentation/report  

---

## 📊 Dataset at a Glance

Each row represents a loan applicant, with features such as:

- **Demographics:** Age, home ownership  
- **Financials:** Income, amount requested, risk scores  
- **Employment:** Years/months employed  
- **Credit Behavior:** Inquiries, debt status  
- **Target:** `e_signed` (1 = electronically signed, 0 = not signed)  

---

## 🛠️ Workflow Overview

1. **Data Cleaning:**
   - Address missing values and duplicate IDs for data integrity  
2. **Feature Engineering:**
   - Merge employment years/months → `total_employment_years`  
   - Create `income_to_loan_ratio` and `composite_risk_score`  
   - Encode categorical variables (e.g., pay schedule)  
3. **Visualization:**
   - Uncover patterns between features and e-signing behavior  
4. **Modeling:**
   - Train a logistic regression classifier  
5. **Evaluation:**
   - Confusion matrix, classification report, ROC-AUC  
6. **Model Export:**
   - Save trained model for deployment  

---

## 🏆 Key Achievements & Insights

- **E-signing Rate:** ~54% of applicants completed e-signing  
- **Model Performance:** ROC-AUC ≈ 0.60 – Baseline model with room for future improvement (e.g., boosting, embeddings)  
- **Influential Features:** Age, income, risk scores, home ownership, employment duration  

### 🎓 Learning Outcomes:

- Built a robust ML pipeline from scratch  
- Applied advanced feature engineering and data visualization  
- Interpreted model results for actionable business insights  
- Gained hands-on experience with real-world financial data  

---

## 💻 Getting Started

1. Open `Bank-1.ipynb` in Jupyter or VS Code  
2. Run all cells to reproduce the analysis and model training  
3. Use `e_sign_model.pkl` to make predictions on new applicant data  

_For details on data columns, modeling steps, or results, see the notebook or the PDF report._

---

## 📦 Requirements

- Python 3.x  
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`  

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
````

---

## 👤 Author

* **Afolabi Olawale** — AI Engineer & Data Enthusiast
* 📅 August 2025

> *This project was a rewarding opportunity to bridge data science and real-world business needs. Open to collaboration, feedback, or fintech AI challenges—let’s connect!*

---

*Want more details? Check out the notebook (`Bank-1.ipynb`) or the PDF report for a deep dive into the data and modeling process.*

```

Let me know if you want a `profile/README.md` next to summarize your journey and skills—or if you’re ready to pin this on GitHub.
```
