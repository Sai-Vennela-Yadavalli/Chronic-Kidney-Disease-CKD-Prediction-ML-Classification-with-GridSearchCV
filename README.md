# 🩺 Chronic Kidney Disease (CKD) Prediction – Classification with GridSearchCV

This machine learning project aims to predict the presence of **Chronic Kidney Disease (CKD)** in patients using a variety of classification algorithms. The models are trained and tuned using GridSearchCV, evaluated using standard metrics, and the best-performing model is deployed for future use.

---

## 🧠 Problem Statement

The client wants to develop a machine learning-based application that can accurately predict the presence of **Chronic Kidney Disease (CKD)** in patients based on multiple clinical and demographic parameters. Early detection is critical to enable **timely medical intervention** and **improve patient outcomes**.

---

## 🚀 Project Workflow

1. Data Preprocessing
2. Model Training using:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Decision Tree
   - Random Forest
   - K-Nearest Neighbors (KNN)
   - Naive Bayes
3. Hyperparameter Tuning with **GridSearchCV**
4. Model Evaluation using metrics like:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
5. Deployment of the best model

---

## 📊 Evaluation Summary

| Algorithm           | Accuracy | Best Parameters (via GridSearchCV) |
|---------------------|----------|------------------------------------|
| Logistic Regression | ✅ TBD   | ✅ GridSearchCV Tuned              |
| SVM                 | 72%      | kernel='rbf', C=10000              |
| Decision Tree       | 90%      | criterion='gini', splitter='best'  |
| Random Forest       | 94%      | n_estimators=100, criterion='gini' |
| KNN                 | ✅ TBD   | neighbors, weights tuned           |
| Naive Bayes         | ✅ TBD   | Default parameters                 |

📄 Full results and metrics are available in `Project - Documentation.pdf`

---

## 🗂️ Files Included

| File Name                                      | Description                                  |
|------------------------------------------------|----------------------------------------------|
| `1. SVM_Classification_GridSearch.ipynb`       | SVM with GridSearchCV tuning                 |
| `2. DecisionTree_Classification_GridSearch.ipynb` | Decision Tree classifier tuning           |
| `3. RandomForest_Classification_GridSearch.ipynb` | Random Forest with GridSearchCV tuning     |
| `4. LogisticRegression_Classification_GridSearch.ipynb` | Logistic Regression model               |
| `5. KNN_Classification_GridSearch.ipynb`       | KNN with hyperparameter tuning              |
| `6. NaiveBayes_Classification_GridSearch.ipynb`| Naive Bayes classifier                      |
| `Deployment.ipynb`                             | Best model loading & CKD prediction demo     |
| `Project - Documentation.pdf`                  | Evaluation results, Q&A, and performance     |
| `README.md`                                    | Project summary and structure (this file)    |

---

## 🛠️ Deployment

The best model is saved and used in the `Deployment.ipynb` notebook. It accepts clinical inputs and returns CKD prediction results.

---

## 📈 Metrics Tracked

- 🎯 Accuracy
- 🔁 Recall
- ✅ Precision
- 🧮 F1 Score
- ⚖️ Macro & Weighted Averages

---

## 👩‍💻 Author

**Sai Vennela Yadavalli**  
[LinkedIn](https://www.linkedin.com/in/sai-vennela-yadavalli-8b854432a/)

---

> “Early prediction saves lives. ML helps us get there faster.” 💉🔬
