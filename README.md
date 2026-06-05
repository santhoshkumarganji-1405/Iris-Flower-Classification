# 🌸 Iris Flower Classification Using Machine Learning

## 📌 Project Overview

This project uses Machine Learning techniques to classify Iris flowers into three species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

The classification is performed using the famous Iris dataset available in Scikit-learn. Multiple machine learning algorithms are compared to identify the most accurate model for flower species prediction.

---

## 🎯 Objectives

* Load and explore the Iris dataset.
* Perform data analysis and visualization.
* Train machine learning classification models.
* Compare model performances.
* Evaluate the best-performing model using accuracy metrics and confusion matrix.
* Understand the fundamentals of supervised machine learning classification.

---

## 📂 Dataset Information

The Iris dataset contains:

* 150 flower samples
* 4 features:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
* 3 target classes:

  * Setosa
  * Versicolor
  * Virginica

Dataset Source:

```python
from sklearn.datasets import load_iris
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## 📊 Data Analysis

The project performs:

### Dataset Inspection

```python
df.info()
df.describe()
```

### Visualizations

* Species Distribution Count Plot
* Pair Plot Visualization
* Model Accuracy Comparison Chart
* Confusion Matrix Heatmap

---

## 🤖 Machine Learning Models Tested

| Model                     | Accuracy |
| ------------------------- | -------- |
| Decision Tree             | 96.7%    |
| Random Forest             | 100%     |
| K-Nearest Neighbors (KNN) | 100%     |
| Logistic Regression       | 100%     |

---

## 🏆 Best Model

Random Forest Classifier was selected for final training and testing.

```python
RandomForestClassifier(random_state=42)
```

---

## 📈 Model Evaluation

Evaluation Metrics Used:

* Accuracy Score
* Classification Report
* Confusion Matrix

### Final Accuracy

```text
Accuracy: 1.0
```

### Result

The trained Random Forest model achieved **100% accuracy** on the test dataset.

---

## 📷 Output Visualizations

### Species Distribution

* Count Plot of Iris Species

### Feature Relationships

* Pair Plot Visualization

### Model Comparison

* Accuracy Comparison Bar Chart

### Performance Evaluation

* Confusion Matrix Heatmap

---

## 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/your-username/Iris-Flower-Classification.git
```

### Navigate to Project Folder

```bash
cd Iris-Flower-Classification
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Notebook

Open the notebook in:

* Jupyter Notebook
* Google Colab

and execute all cells.

---

## 📁 Project Structure

```text
Iris-Flower-Classification
│
├── Iris_Flower_Classification.ipynb
├── README.md
├── requirements.txt
└── screenshots
    ├── countplot.png
    ├── pairplot.png
    ├── model_comparison.png
    └── confusion_matrix.png
```

---

## 📚 Learning Outcomes

Through this project, you will learn:

* Data preprocessing fundamentals
* Exploratory Data Analysis (EDA)
* Data visualization techniques
* Classification algorithms
* Model evaluation methods
* Machine Learning workflow using Scikit-learn

---

## 👨‍💻 Author

**Ganji Santhosh Kumar**

B.Tech Student | Machine Learning Enthusiast

---

## ⭐ GitHub

If you found this project useful, consider giving it a ⭐ on GitHub.

---

### Upload to GitHub

```bash
git init
git add .
git commit -m "Added Iris Flower Classification Project"
git branch -M main
git remote add origin https://github.com/USERNAME/Iris-Flower-Classification.git
git push -u origin main
```

Replace `USERNAME` with your GitHub username.
