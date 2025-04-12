```markdown
# 🛳️ Titanic Survival Prediction

A complete walkthrough using the Titanic dataset from [Kaggle](https://www.kaggle.com/competitions/titanic) to predict passenger survival. This project covers everything from exploratory data analysis to machine learning model training and submission creation.

---

## 📁 Project Structure

```
titanic-survival-prediction/
├── train.csv
├── test.csv
├── titanic_notebook.ipynb
├── titanic_submission.csv
├── requirements.txt
└── README.md
```

---

## ✅ What's Included

- Data loading and preview
- Null value inspection
- Exploratory Data Analysis (EDA) with charts
- Feature engineering (e.g., Title extraction, Family size)
- Missing value imputation
- Categorical encoding
- Model training (Logistic Regression and Random Forest)
- Evaluation metrics (Accuracy, Confusion Matrix, Classification Report)
- Feature importance visualization
- Kaggle-compatible CSV submission creation

---

## 🔍 Null Value Check

Before data cleaning, null values can be inspected using:

```python
print("Train Nulls:\n", train_df.isnull().sum())
print("\nTest Nulls:\n", test_df.isnull().sum())
```

This helps identify missing `Age`, `Cabin`, `Embarked`, and `Fare` fields.

---

## ⚙️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

### Core Libraries

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 🚀 How to Run

1. Clone the repo or download the notebook.
2. Download the dataset from [Kaggle Titanic](https://www.kaggle.com/competitions/titanic/data).
3. Place `train.csv` and `test.csv` in the same folder.
4. Launch the notebook:

```bash
jupyter notebook titanic_notebook.ipynb
```

---

## 📈 Sample Output

A submission CSV (`titanic_submission.csv`) is generated using predictions on the test set. Random Forest model yields around **80% accuracy** on validation.

---

## ✍️ Author

Michael Adams  
[@DataGuyMichael]([https://www.linkedin.com/in/michaeladamsds](https://linktr.ee/thedataguymichael))

---

## 📜 License

This project is licensed under the MIT License.
```
