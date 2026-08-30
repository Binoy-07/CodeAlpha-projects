# 🩺 CodeAlpha_DiseasePredictionModel

### 🎓 CodeAlpha Machine Learning Internship — Task 4: Disease Prediction from Medical Data

---

## 🎯 Objective
Predict the possibility of **heart disease** in a patient using medical data — age, blood pressure, cholesterol, blood sugar, heart rate, and other clinical features.

---

## 📂 Dataset
- 🌐 **UCI Heart Disease Dataset (Cleveland)** — auto-downloaded when internet is available.
- 🔄 If offline, the script automatically falls back to a **synthetic dataset** with the same structure, so it always runs successfully end-to-end.

---

## 🛠️ Approach
1. 📥 **Load Data** — real dataset or synthetic fallback
2. 🧹 **Preprocess** — clean missing values, feature scaling
3. 🤖 **Train Models**
   - Logistic Regression
   - Random Forest Classifier
   - Support Vector Machine (SVM)
4. 📊 **Evaluate**
   - Precision, Recall, F1-Score
   - ROC-AUC Score
   - Confusion Matrix
   - ROC Curve

---

## 🖼️ Visualizations Generated

| # | File | Description |
|---|------|--------------|
| 1️⃣ | `1_class_distribution.png` | 📊 Disease vs No-Disease class balance (pie chart) |
| 2️⃣ | `2_correlation_heatmap.png` | 🔥 Feature correlation heatmap |
| 3️⃣ | `3_feature_distributions.png` | 📈 Feature distributions by disease status |
| 4️⃣ | `4_confusion_matrices.png` | 🧩 Confusion matrices for all 3 models |
| 5️⃣ | `5_roc_curve_comparison.png` | 📉 ROC curve comparison |
| 6️⃣ | `6_feature_importance.png` | 🌟 Feature importance (Random Forest) |
| 7️⃣ | `7_metrics_comparison.png` | 🏆 Model performance comparison |

---

## 🚀 How to Run

### ▶️ On Google Colab (recommended)
1. Paste the code into a new notebook cell 📝
2. Run all cells top to bottom ⬇️
3. 🌍 Real UCI dataset downloads automatically (Colab has internet)
4. 🖼️ Add a new cell with the display code to show all visualizations inline

### 💻 Locally / VS Code
```bash
pip install pandas scikit-learn matplotlib seaborn joblib
python disease_prediction_model.py
```

---

## 📦 Output Files
- 🖼️ 7 visualization PNGs (listed above)
- 🧠 `disease_prediction_model.pkl` — trained Random Forest model
- ⚖️ `disease_prediction_scaler.pkl` — fitted StandardScaler

---

## 🧰 Tech Stack
🐍 Python &nbsp;|&nbsp; 🐼 Pandas &nbsp;|&nbsp; 🔢 NumPy &nbsp;|&nbsp; 🤖 Scikit-learn &nbsp;|&nbsp; 📊 Matplotlib &nbsp;|&nbsp; 🎨 Seaborn &nbsp;|&nbsp; 💾 Joblib

---

## 🏅 Internship Details
**Internship:** CodeAlpha Machine Learning Internship
**Task:** 4 of 4 — 🩺 Disease Prediction from Medical Data

---
✨ *Made with dedication as part of the CodeAlpha ML Internship journey!* ✨
