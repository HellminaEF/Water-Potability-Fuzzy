# Water Potability Prediction using Fuzzy Logic

This project applies Fuzzy Mamdani and Sugeno methods to determine the potability of water based on pH, turbidity, and sulfate levels. Implemented in a single Jupyter notebook using the Water Potability dataset from Kaggle.

## 📌 Project Objective
Compare the performance and interpretability of two fuzzy inference systems (Mamdani vs Sugeno) for determining drinking water eligibility.

## 🧪 Dataset
- Source: [Kaggle - Water Potability](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- Features used: `pH`, `Turbidity`, `Sulfate`

## 🛠️ Tools & Technologies
- Python
- Jupyter Notebook (Google Colab)
- `skfuzzy` for Mamdani system
- Manual rule-based logic for Sugeno system

## 📈 Sample Input
```python
pH = 7.2
Turbidity = 3.5
Sulfate = 180
```

## ✅ Results
- Mamdani Output: 0.77 (drinkable)
- Sugeno Output: 0.72 (drinkable)

## 👤 Contributor
This project was originally a group assignment, but fully implemented by:
- Hellmina Enjelina Fitri
