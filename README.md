# 🌸 Iris Flower Classification Project

> A machine learning project to classify Iris flowers into species using sepal and petal dimensions.  
> 🔬 Built during a summer internship at **NovaNectar Services Pvt. Ltd.**

---

## 📁 Dataset

The project uses the classic [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris), which contains:

- Sepal length
- Sepal width
- Petal length
- Petal width
- Species (Setosa, Versicolor, Virginica)

---

## ⚙️ Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**  
  `pandas`, `numpy`, `seaborn`, `matplotlib`,  
  `scikit-learn` (Logistic Regression, Decision Tree, SVM)

---

## 🔍 Project Workflow

1. **Data Loading**
   - CSV file imported and loaded into pandas dataframe
2. **Data Cleaning & Inspection**
   - Checked null values, cleaned dataset
3. **Preprocessing**
   - Label encoding of target column `species`
   - Splitting into training & testing sets
4. **Model Building**
   - Trained three classifiers:
     - Logistic Regression
     - Decision Tree
     - Support Vector Machine (SVM)
5. **Model Evaluation**
   - Accuracy Score
   - F1 Score
   - Confusion Matrix
   - Classification Report
6. **Residual Analysis**
   - Plotted residuals for Logistic Regression
7. **Error Graph**
   - Compared actual vs predicted values across all models

---

## 📊 Results

| Model                | Accuracy | F1 Score |
|---------------------|----------|----------|
| Logistic Regression | ~97%     | ~0.97    |
| Decision Tree       | ~96%     | ~0.96    |
| SVM                 | ~98%     | ~0.98    |

> 📌 *Support Vector Machine performed the best on the dataset.*

---

## 📈 Visualizations

- Distribution of residuals
- Confusion matrix heatmaps
- Error graph comparing predictions vs actual values

---

## 🧠 Learnings

- Hands-on experience with supervised learning models
- Understanding of residual analysis in classification tasks
- Performance comparison of popular ML algorithms

---

## 💼 Internship Details

This project was completed as part of the summer internship at **NovaNectar Services Pvt. Ltd.**, under the domain of **Data Science and Machine Learning**.

---

## 📂 Files Included

- `iris.data.csv` – Dataset used for training
- `iris_classification.ipynb` – Full Jupyter notebook with code and output
- `README.md` – Project documentation

---
