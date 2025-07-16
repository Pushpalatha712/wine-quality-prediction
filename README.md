# wine-quality-prediction
# 🍷 Wine Quality Prediction using Machine Learning

This project focuses on predicting the **quality of wine** based on its physicochemical attributes using three different classification models:
- Random Forest Classifier
- Stochastic Gradient Descent (SGD) Classifier
- Support Vector Classifier (SVC)

## 🎯 Objective

To analyze chemical properties of wine such as acidity, sugar, and density, and predict the wine quality on a scale (typically 0–10) using supervised machine learning techniques.

## 📁 Dataset

The dataset used is `WineQT.csv`, which contains the following columns:

| Feature               | Description                                 |
|-----------------------|---------------------------------------------|
| fixed acidity         | Tartaric acid (g/dm³)                       |
| volatile acidity      | Acetic acid (g/dm³)                         |
| citric acid           | Citric acid (g/dm³)                         |
| residual sugar        | Sugar after fermentation (g/dm³)           |
| chlorides             | Salt content (g/dm³)                        |
| free sulfur dioxide   | Free SO₂ (mg/dm³)                           |
| total sulfur dioxide  | Total SO₂ (mg/dm³)                          |
| density               | Density of wine                             |
| pH                    | pH level                                    |
| sulphates             | Sulfate content (g/dm³)                     |
| alcohol               | Alcohol content (% vol)                     |
| **quality**           | Quality score (target variable, 0–10)      |

## 🛠️ Technologies Used

- Python
- Pandas & NumPy
- Seaborn & Matplotlib
- Scikit-learn (for ML models)

## 📈 ML Models Used

1. **Random Forest Classifier**
2. **SGD Classifier**
3. **Support Vector Classifier (SVC)**

## 🚀 How to Run

1. Make sure the dataset file is named `WineQT.csv` and located in the same folder.
2. Run the script:

```bash
python wine_quality_prediction.py

 *Steps Performed
*Data Loading & Exploration
Basic structure, statistics, and column correlation.

*Data Preprocessing

*Train-Test split

Feature scaling with StandardScaler

*Model Training
Train three classifiers using the same dataset.

*Evaluation

Confusion matrix

Classification report (precision, recall, F1-score)

*Visualization
Correlation heatmap of chemical features.

🧪 Sample Output
Correlation heatmap of features

Classification accuracy and precision of each model

Confusion matrices to compare performance

✅ Future Improvements
Add GridSearchCV for hyperparameter tuning

Convert regression problem (quality as continuous)

Feature importance visualization

Use PCA for dimensionality reduction and visualization


