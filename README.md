# Team Lapiyano – Motus x UJ Hackathon 2025

Welcome to **Team Lapiyano's** submission for the Motus & University of Johannesburg Hackathon 2025.

Our project tackles the challenge of **predicting whether a car lead results in a sale**, using machine learning techniques with a focus on real-world impact and data-driven insights.

---

## 🔍 Problem Statement

Predict the **likelihood of a lead converting into a sale** based on attributes provided in the Motus dataset. The solution aims to assist dealerships in optimizing their sales pipeline and focusing on high-potential leads.

---

## 📁 Project Structure

| File / Folder                 | Description |
|------------------------------|-------------|
| `TeamLapiyano.ipynb`         | Core notebook with full preprocessing, modeling, and evaluation pipeline |
| `TeamLapiyano_commented.ipynb` | Same notebook with detailed inline comments explaining every step |
| `Final Evaluation Standings/Results.pdf` | 📊 Final performance evaluation provided by organizers |

---

## 📊 Approach Summary

- **Model Used**: XGBoost Classifier
- **Preprocessing**:
  - Handling missing values with `SimpleImputer`
  - Encoding categorical features
  - Feature selection based on domain insights
- **Balancing Strategy**:
  - Applied SMOTE (Synthetic Minority Oversampling) for class imbalance
- **Evaluation Metrics**:
  - Precision-Recall AUC
  - Confusion Matrix
  - ROC Curve

---

## 📦 Requirements

To run this notebook:

```bash
pip install -r requirements.txt
```

Minimum packages:
- `xgboost`
- `pandas`
- `numpy`
- `scikit-learn`
- `imblearn`
- `matplotlib`
- `seaborn` (optional)

---

## 📄 Final Evaluation

You can find the official evaluation results in:

```
📁 Final Evaluation Standings/
   └── 📄 Results.pdf
```

This file contains performance standings as assessed by the hackathon organizers.

---

## 🚀 Authors

- **Team Lapiyano** – University of Johannesburg Hackathon 2025

---

## 📬 Contact

For any questions or feedback, feel free to reach out to the team or open an issue.
