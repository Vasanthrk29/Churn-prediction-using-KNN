# 📊 Churn Prediction Using KNN

This project builds a **customer churn prediction model** using the **K-Nearest Neighbors (KNN)** classification algorithm. Customer churn prediction is critical for businesses to identify customers at risk of leaving and to design effective retention strategies.

---

## 📝 Project Overview

The workflow includes:

- **Data Preprocessing:**  
  - Handling missing values
  - Encoding categorical variables
  - Feature scaling for distance-based modeling
- **Exploratory Data Analysis (EDA):**  
  - Analyzing churn patterns and feature correlations
- **Model Training:**  
  - Applying KNN to classify customer churn
- **Model Evaluation:**  
  - Measuring performance using accuracy, confusion matrix, and ROC curve
- **Prediction:**  
  - Predicting churn on new/unseen data

---

## 🚀 Features

✅ One-hot encoding of categorical columns  
✅ Scaling features to ensure fair distance calculations  
✅ Hyperparameter tuning to find the optimal value of **K**  
✅ Visual evaluation of model performance  
✅ Clear, reproducible code and examples

---

## 📂 Project Structure

- ├── data/ # Raw dataset files
- ├── notebooks/ # Jupyter Notebooks for EDA and modeling
- ├── src/ # Python scripts (preprocessing, modeling)
- ├── results/ # Outputs (plots, evaluation metrics)
- ├── requirements.txt # Dependencies
- ├── README.md # This file

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook

---

## 📝 Dataset

The dataset includes customer attributes such as:
- Demographic information
- Account activity
- Service usage metrics
- Churn labels (`0 = No churn`, `1 = Churn`)

## 📈 Evaluation Metrics

The model performance is evaluated using:

- Accuracy

- Confusion Matrix

- Precision, Recall, F1-Score

![image](https://github.com/user-attachments/assets/bd7ca0d9-eeed-4d74-bbd8-98de9df73ca2)


## ✨ Results
Achieved an accuracy of XX% on the test dataset.

The model successfully identifies churned customers with reasonable precision and recall.

## 🚀 How to Run

Open the Jupyter Notebook:

```bash
jupyter notebook

```

## ⚙️ Installation

Clone this repository:

```bash
git clone https://github.com/Vasanthrk29/churn-prediction-knn.git
cd churn-prediction-knn
pip install -r requirements.txt
```
---


## 🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork this repository and submit a pull request.

## 📬 Contact
If you have any questions or suggestions, please reach out:

GitHub: Vasanthrk29

Email: vasanthrk2004@gmail.com
