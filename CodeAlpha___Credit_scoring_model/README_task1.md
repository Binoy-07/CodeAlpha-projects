# 🏦 CodeAlpha_CreditScoringModel

### 🎓 CodeAlpha Machine Learning Internship — Task 1: Credit Scoring Model

---

## 🎯 Objective
Predict whether a person is a **✅ Good** or **❌ Bad** credit risk using their financial history — income, debt, credit amount, payment history, and more.

---

## 📂 Dataset
- 🌐 **UCI Statlog (German Credit Data)** — auto-downloaded when internet is available.
- 🔄 If offline, the script automatically falls back to a **synthetic dataset** with the same structure, so it always runs successfully end-to-end.

---

## 🛠️ Approach
1. 📥 **Load Data** — real dataset or synthetic fallback
2. 🧹 **Preprocess** — encode categorical features, feature engineering, scaling
3. 🤖 **Train Models**
   - Logistic Regression
   - Random Forest Classifier
4. 📊 **Evaluate**
   - Precision, Recall, F1-Score
   - ROC-AUC Score
   - Confusion Matrix
   - ROC Curve

---

## 🖼️ Visualizations Generated

| # | File | Description |
|---|------|--------------|
| 1️⃣ | `1_class_distribution.png` | 📊 Good vs Bad credit class balance (pie chart) |
| 2️⃣ | `2_correlation_heatmap.png` | 🔥 Feature correlation heatmap |
| 3️⃣ | `3_feature_distributions.png` | 📈 Feature distributions by credit risk |
| 4️⃣ | `4_confusion_matrices.png` | 🧩 Confusion matrices for both models |
| 5️⃣ | `5_roc_curve_comparison.png` | 📉 ROC curve comparison |
| 6️⃣ | `6_feature_importance.png` | 🌟 Feature importance (Random Forest) |
| 7️⃣ | `7_metrics_comparison.png` | 🏆 Model performance comparison |

---

## 🚀 How to Run

### ▶️ On Google Colab (recommended)
1. Open the notebook `Credit_Scoring_model_CodeAlpha_internship.ipynb`
2. Run all cells top to bottom ⬇️
3. 🌍 Real UCI dataset downloads automatically (Colab has internet)
4. 🖼️ All visualizations display inline in the notebook output

### 💻 Locally / VS Code
```bash
pip install pandas scikit-learn matplotlib seaborn joblib
python credit_scoring_model.py
```

---

## 📦 Output Files
- 🖼️ 7 visualization PNGs (listed above)
- 🧠 `credit_scoring_model.pkl` — trained Random Forest model
- ⚖️ `credit_scoring_scaler.pkl` — fitted StandardScaler

---

## 🧰 Tech Stack
🐍 Python &nbsp;|&nbsp; 🐼 Pandas &nbsp;|&nbsp; 🔢 NumPy &nbsp;|&nbsp; 🤖 Scikit-learn &nbsp;|&nbsp; 📊 Matplotlib &nbsp;|&nbsp; 🎨 Seaborn &nbsp;|&nbsp; 💾 Joblib

---
✨ *Made with dedication as part of the CodeAlpha ML Internship journey!* ✨
