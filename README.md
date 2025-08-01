# 🌍 White Wine Quality Rating Using Machine Learning Predictions

## Objective
This project explores the use of machine learning to predict the quality of white wine based on its physicochemical properties. Using a dataset containing chemical measurements such as alcohol, residual sugar, acidity, and sulphates, we aim to build and compare models that estimate wine quality on a numerical rating scale. The goal is to identify which features most influence wine quality and how accurately it can be predicted using supervised learning techniques.

---

## 🔍 Hypothesis

We hypothesize that certain chemical properties — alcohol, residual sugar and volatile acidity — have a measurable impact on wine quality. Machine learning models trained on these features will be able to predict wine ratings with reasonable accuracy.

---

## 📊 Features Available:

- fixed acidity
- volatile acidity
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- sulphates
- alcohol
- quality (target variable)

---

## 📘 Models Used:

- K-Nearest Neighbors (KNN)
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Adaboost Regressor
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

---

## ✅ Expected Outcomes
- Identify which chemical features (e.g., alcohol, acidity, sugar) have the strongest relationship to wine quality.
- Evaluate the performance of multiple machine learning models in predicting wine ratings.
- Compare models (e.g., KNN, Linear Regression, Decision Tree) to determine which offers the most accurate and reliable predictions.
- Understand how data preprocessing (such as feature seclection and scaling) impacts model performance.

## ✅ Did We Meet the Hypothesis?
🎯 Partially met — classification models outperformed regression.
🌲 Random Forest Classifier reached 73% accuracy, with AUC scores up to 0.91 ✅
📉 Regression models (best R² ≈ 0.51) struggled due to:
🔹 Weak feature–target correlation
🔸 Imbalanced quality ratings 
   (most wines rated 5–6)
🧮 Class prediction (low/medium/high) proved more reliable  
        than exact score prediction.
⚙️ Hyperparameter tuning gave small improvements, but didn't 
        shift the overall outcome.

## 🧾 Dataset Description

## 🧱 Raw Datasets:
- **winequality-white.csv**

### Obstacles:
 
- Using the different models as we learned them.
- Lack of experience making us unsure if outcomes were right
  
---

## 💻 Technologies Used

| Area                 | Tools/Technologies                                      |
|----------------------|---------------------------------------------------------|
| Data Manipulation    | Python (Pandas, NumPy)                                  |
| Data Visualization   | Matplotlib, Seaborn, Pyplot                             |
| Documentation        | Jupyter Notebook, Markdown, GitHub,                     |
| Version Control      | Git, GitHub, Anaconda Powershell                        |
| Statistical Analysis | Scipy, statsmodels                                      |


---

## 📦 Deliverables

- ✅ [Repository "white_wine_project" on GitHub](https://github.com/ViktoriaGluhovskya/white_wine_project) 
- ✅ [Raw dataset](https://archive.ics.uci.edu/dataset/186/wine+quality)
- ✅ Jupyter Notebooks:
 - EDA.ipynb
 - wine_classification.ipynb
 - wine_regression.ipynb
- ✅ [Group 5 Trello Project Page](https://trello.com/b/BnUto7kx/whitewineprediction)
- ✅ README documentation: README.md
- ✅ [Group 5 Presentation](https://docs.google.com/presentation/d/1emStO1gfIZDSZ6A_puXTai4z7JZbwuCMvJInl-9JxJk/edit?slide=id.p1#slide=id.p1) 

---

## 👨‍💼 Target Audience

### 🍷 Winemakers or Vineyards
- Use model predictions to assess wine batches early in production.
- Improve quality by adjusting ingredients (alcohol, sugar, acidity).

### 🛒 Wine Retailers
- Predict and price wines based on expected quality ratings.
- Recommend wines to customers based on objective chemical data.

---

## 👥 Contributors
- Sherin Kuruvilla
- Viktoria Gluhovskaya
- Célestine Tsondo
- Delmar Bumanglag

---



