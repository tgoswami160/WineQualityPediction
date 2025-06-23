
# 🍷 Wine Quality Prediction

This project aims to predict the quality of wine using machine learning algorithms based on various physicochemical properties of wine samples.

---

## 📁 Project Structure

* `wineQualityProject.ipynb` — Main Jupyter notebook containing all steps: data preprocessing, visualization, model training, and evaluation.

---

## 📊 Dataset

The dataset used is the **Wine Quality Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).
It includes attributes such as:

* Fixed acidity
* Volatile acidity
* Citric acid
* Residual sugar
* Chlorides
* Free sulfur dioxide
* Total sulfur dioxide
* Density
* pH
* Sulphates
* Alcohol
* **Quality** (Target Variable)

---

## 🎯 Objective

To classify wine samples based on their quality score (rated between 0–10) using machine learning algorithms, and identify the most effective model.

---

## ⚙️ Techniques Used

* **Data Preprocessing**: Handling nulls, normalization, label encoding
* **Exploratory Data Analysis**: Visualizations like heatmaps, pairplots, distribution plots
* **Machine Learning Models**: Supervised classification techniques
* **Evaluation Metrics**: Accuracy, Confusion Matrix, Classification Report

---

## 🤖 Model Comparison

Various machine learning algorithms were trained and tested. Their performance (based on accuracy) is summarized below:

| Model                  | Accuracy (%) |
| ---------------------- | ------------ |
| Logistic Regression    | \~86.0%      |
| Decision Tree          | \~87.5%      |
| Support Vector Machine | \~88.0%      |
| K-Nearest Neighbors    | \~85.0%      |
| Gradient Boosting      | \~88.3%      |
| **Random Forest**      | **\~89.5%**  |

### 🏆 Best Performing Model

**Random Forest Classifier** outperformed all other models with the highest accuracy of approximately **89.5%**.
It was effective due to:

* Ensemble-based learning (bagging)
* Reduced risk of overfitting
* Robustness to feature interactions and non-linearities

---

## 📌 Requirements

Install required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🚀 Getting Started

1. Download or clone this repository
2. Install dependencies
3. Open and run `wineQualityProject.ipynb` in Jupyter Notebook or any Python IDE

---

## 📚 References

* [UCI ML Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)

