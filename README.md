# ❤️ Enhanced Heart Attack Prediction Using Machine Learning

A research-based machine learning project that aims to predict the likelihood of heart attacks using classification algorithms — K-Nearest Neighbors (KNN), Naive Bayes, and Decision Tree — applied to a large-scale cardiovascular dataset.

## 👨‍💻 Contributors
- **Karthi K.** – https://www.linkedin.com/in/karthi-k-508277333/ – Department of MCA, Chanakya University  
- **Shan Khanna** – https://www.linkedin.com/in/shan-khanna/ – Department of MCA, Chanakya University  
- **Under the guidance of:** Prof. **JB Simha** - https://www.linkedin.com/in/jbsimha/

---

## 📄 Abstract

Cardiovascular disease (CVD) is the leading cause of death globally. In this research, we explore machine learning as a predictive tool for identifying individuals at risk of heart attacks. This project compares the performance of KNN, Naive Bayes, and Decision Tree classifiers on a dataset of over 70,000 patient records.

---

## 📦 Dataset

- **Source:** [Kaggle - Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)
- **Features Include:**
  - Age (in days)
  - Gender (1 = female, 2 = male)
  - Height & Weight (used for BMI)
  - Blood Pressure: Systolic (`ap_hi`) & Diastolic (`ap_lo`)
  - Cholesterol & Glucose Levels
  - Lifestyle: Smoking, Alcohol consumption, Physical Activity
  - Target: Presence or absence of cardiovascular disease (`cardio`)

---

## 🛠️ Preprocessing

- ✅ Converted age from days to years
- ✅ Engineered BMI from height and weight
- ✅ Removed outliers using IQR and boxplots
- ✅ Encoded categorical features
- ✅ Scaled numeric values using StandardScaler

---

## 📊 Exploratory Data Analysis

- Correlation heatmaps
- Distribution plots for features
- Boxplots for outlier detection

---

## 🧠 Machine Learning Models

1. **K-Nearest Neighbors (KNN)**  
   - GridSearchCV for optimal `k`
   - Evaluated with and without cross-validation
2. **Naive Bayes**  
   - Lightweight and fast
   - Good baseline accuracy
3. **Decision Tree**  
   - Interpretable via feature importance plots
   - Achieved best performance overall

---

## 📈 Results

| Model         | Accuracy |
|---------------|----------|
| KNN (optimized)      | 72.37%   |
| Naive Bayes   | ~70%     |
| Decision Tree | **Best** |

Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 📌 Key Takeaways

- Decision Tree provided the best interpretability and accuracy.
- Naive Bayes was fastest with reasonable performance.
- KNN required fine-tuning of `k` and benefited from cross-validation.

---

## 🔭 Future Work

- Use more advanced ensemble models (e.g., Random Forest, XGBoost)
- Integrate real-time health dashboards
- Expand dataset categories and demographics

---

## 📑 References

1. Bah Ibrahima & Xue Yu – *KNN Algorithm Used for Heart Attack Detection*
2. World Health Organization Reports on Cardiovascular Disease
3. Scikit-learn Documentation
4. Mayo Clinic – Heart Disease Diagnosis
5. Kaggle – Cardiovascular Dataset

---

## 🚀 Run Locally

```bash
git clone https://github.com/Karthi3298/Heart-Attack-Detection.git
cd Heart-Attack-Detection
pip install -r requirements.txt
python main.py  # or open the notebook file
```
---
## 📬 Contact

For any queries or collaboration opportunities, feel free to reach out:

- **K. Karthi** – karthik.mca24@chanakyauniversity.edu.in  
- **Shan Khanna** – shank.mca24@chanakyauniversity.edu.in


