# ❤️ SparkML Heart Risk Classifier

A scalable machine learning pipeline using **Apache Spark** to classify the risk of heart disease based on medical attributes. This project leverages distributed computing for handling large datasets efficiently and includes robust preprocessing, feature engineering, model training, and evaluation.

---

## 📊 Project Overview

This project implements a **Random Forest Classifier** to predict the risk level of heart disease using the **UCI Heart Disease dataset**. It uses **PySpark MLlib** to handle large-scale data processing and build a production-ready pipeline.

---

## 🚀 Features

- Apache Spark ML pipeline for end-to-end processing
- Handling missing values with imputation
- Encoding categorical features
- Feature scaling and vector assembly
- Weighted classification to address class imbalance
- Model training using Random Forest Classifier
- Model evaluation with confusion matrix and metrics

---

## 🧠 Algorithms Used

- **Random Forest Classifier**
- **StringIndexer**
- **Imputer (mean strategy)**
- **StandardScaler**
- **MulticlassClassificationEvaluator**

---

## 🛠️ Technologies

- Python 🐍
- Apache Spark ⚡
- PySpark MLlib
- Pandas, Seaborn, Matplotlib (for visualization)

---

## 📂 Dataset

- **Source**: UCI Machine Learning Repository - Heart Disease Dataset
- **Format**: CSV
- Make sure the file `heart_disease_uci.csv` is present in the same directory.

---

## 🔄 Workflow

1. **Start Spark Session**
2. **Load Dataset**
3. **Drop Unnecessary Columns**
4. **Fix Data Types**
5. **Handle Class Imbalance (Weighting)**
6. **Impute Missing Values**
7. **Encode Categorical Variables**
8. **Assemble Features into Vector**
9. **Train/Test Split**
10. **Train the Random Forest Classifier**
11. **Evaluate the Model**

---

## 📉 Model Evaluation

- Accuracy
- Precision / Recall
- F1-score
- Confusion Matrix (Plotted using Matplotlib)

---

## 🧪 How to Run

1. Install dependencies:

```bash
pip install pyspark pandas seaborn matplotlib
````

2. Run the notebook:

```bash
jupyter notebook SparkML_Heart_Risk_Classifier.ipynb
```

3. Make sure `heart_disease_uci.csv` is in the same directory as the notebook.

---

## 🧾 Sample Output

* Confusion matrix visualization
* Class weights applied
* Schema changes after preprocessing
* Final model performance scores

---

## ✅ Future Improvements

* Add support for multiple classifiers (e.g. Logistic Regression, GBT)
* Automate hyperparameter tuning
* Deploy model using Flask or Streamlit
* Save model using Spark ML persistence

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

Created by **Sayyed Hossein Hosseini DolatAbadi**
