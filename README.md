# 📱 Megaline — Mobile Plan Recommendation

### Machine Learning | Supervised Classification | Customer Analytics

---

## 🎯 Project Overview

Megaline, a telecommunications company, wants to recommend one of its two new mobile plans — **Smart or Ultra** — to customers who are still using legacy plans.

The goal of this project is to develop a machine learning classification model that analyzes customer usage patterns and predicts which plan is the most suitable for each user.

**Business objective:** Support personalized plan recommendations and data-driven commercial decisions.

---

## 📊 Dataset

The project uses the `users_behavior.csv` dataset, containing customer usage information.

| Feature | Description |
|:---|:---|
| `calls` | Number of calls |
| `minutes` | Total call duration |
| `messages` | Number of text messages |
| `mb_used` | Internet data consumption |
| `is_ultra` | Target variable (0 = Smart, 1 = Ultra) |

---

## ⚙️ Project Workflow

The project followed a supervised machine learning workflow:

| Stage | Activities |
|:---|:---|
| **01 — Data Exploration** | Dataset structure, data types, missing values, duplicates, and target distribution. |
| **02 — Data Preparation** | Separation into training (60%), validation (20%), and test (20%) sets. |
| **03 — Model Training** | Development of Decision Tree, Random Forest, and Logistic Regression models. |
| **04 — Model Optimization** | Hyperparameter tuning and validation accuracy comparison. |
| **05 — Final Evaluation** | Testing the selected model and performing a sanity check against a baseline. |

---

## 🤖 Models & Results

### Validation Performance

Three classification algorithms were evaluated:

| Model | Accuracy |
|:---|---:|
| 🥇 Random Forest | **82.12%** |
| Decision Tree | 80.25% |
| Logistic Regression | 73.87% |

**Random Forest** achieved the best validation performance and was selected for final evaluation.

### 🏆 Final Model Performance

<details>
<summary><strong>Test set results</strong></summary>

| Evaluation | Accuracy |
|:---|---:|
| Random Forest | **82.89%** |
| Dummy Classifier (Baseline) | 69.36% |
| Improvement | **+13.53 percentage points** |

</details>

<details>
<summary><strong>Project performance highlights</strong></summary>

- Required accuracy: 75%
- Final test accuracy: 82.89%
- Baseline accuracy: 69.36%
- The final model exceeded the required performance threshold.

</details>

---

## 💡 Business Insights

The results demonstrate the potential of machine learning to support Megaline's commercial strategy.

The model can help the company:

- **Personalize recommendations:** Match customers with plans based on their usage patterns.
- **Improve customer segmentation:** Identify different consumption profiles.
- **Support marketing strategies:** Develop more targeted commercial campaigns.
- **Strengthen decision-making:** Transform customer data into actionable insights.

The model should be considered a decision-support tool and validated with new customer data before real-world deployment.

---

## 🛠️ Technologies

| Category | Tools |
|:---|:---|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Development | Jupyter Notebook |
| Version Control | Git, GitHub |

---

## 📌 Conclusion

The project successfully developed a classification model to recommend Megaline's Smart or Ultra mobile plans based on customer behavior.

The **Random Forest Classifier achieved 82.89% accuracy on the test dataset**, outperforming the baseline model by 13.53 percentage points and exceeding the required 75% threshold.

These results demonstrate how machine learning can help telecommunications companies understand customer behavior, personalize their services, and make more informed business decisions.

---

## 👨‍💻 Author

**Julian Lopez**

Economics Graduate | Data Science | Business Analytics

[GitHub Profile](https://github.com/Julianlo11)

---

*Machine Learning Project — Sprint 10*

Author

Julian Lopez
Economics Graduate | Data Science & Business Analytics

GitHub Profile
