# Titanic Survival Prediction

This project is a complete walkthrough for solving the [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic), where the goal is to predict whether a passenger survived or not based on features like age, sex, class, and more.

## Project Structure

```
titanic-survival-prediction/
├── train.csv
├── test.csv
├── titanic_notebook.ipynb
├── titanic_submission.csv
├── requirements.txt
└── README.md
```

## What's Included

- Null value inspection
- Exploratory Data Analysis (EDA)
- Feature engineering
- Categorical encoding
- Missing value imputation
- Model training: Logistic Regression & Random Forest
- Evaluation: Accuracy, Confusion Matrix, Classification Report
- Feature importance visualization
- Submission file creation

## Example: Null Value Check

```python
print("Train Nulls:\n", train_df.isnull().sum())
print("\nTest Nulls:\n", test_df.isnull().sum())
```

This reveals missing values in columns like `Age`, `Cabin`, `Embarked`, and `Fare`.

## Setup

Install dependencies with:

```bash
pip install -r requirements.txt
```

Main libraries used:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Running the Notebook

1. Download the Titanic dataset (`train.csv` and `test.csv`) from [Kaggle](https://www.kaggle.com/competitions/titanic/data).
2. Place both files in the project folder.
3. Launch Jupyter:

```bash
jupyter notebook titanic_notebook.ipynb
```

## Output

- A Kaggle submission file `titanic_submission.csv` will be generated.
- The notebook reports model accuracy (around ~80% using Random Forest).

## License

This project is licensed under the MIT License.

## Author

Michael Adams  
[@DataGuyMichael]([https://linktr.ee/thedataguymichael])
```


