# Iris Flower Classification — Machine Learning Project

![Iris Flower](https://upload.wikimedia.org/wikipedia/commons/4/41/Iris_versicolor_3.jpg)

## Project Overview

The Iris Flower Classification project is a fundamental machine learning task aimed at building a model that accurately classifies Iris flowers into one of three species: *Setosa*, *Versicolor*, or *Virginica*. This project demonstrates core skills in data exploration, preprocessing, model building, evaluation, and deployment, making it an excellent example of applied machine learning.

---

## Problem Statement

Accurately identifying flower species based on physical measurements is a classic multi-class classification problem. Automating this process helps understand supervised learning pipelines and prepares for more complex real-world problems involving classification tasks.

---

## Dataset Description

This project uses the **Iris dataset** — a benchmark dataset in the ML community — containing 150 samples, equally divided into three classes.

- Features:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- Target: Species label (Setosa, Versicolor, Virginica)

**Dataset Source:**  
[UCI Machine Learning Repository: Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)

---

## Project Workflow & Technical Approach

### 1. Data Exploration & Visualization
- Conducted exploratory data analysis (EDA) to understand data distributions, detect imbalances, and observe feature relationships using pairplots and heatmaps.
- Visualized class distribution to confirm balanced dataset.

### 2. Data Preprocessing
- Handled categorical target variable by mapping species names to numeric labels.
- Checked for missing values and ensured data cleanliness.

### 3. Feature Engineering
- No complex feature engineering was necessary given dataset simplicity, but correlation analysis helped understand feature importance.

### 4. Model Selection & Training
- Implemented Support Vector Classifier (SVC), a powerful and widely used algorithm for classification.
- Used train-test split (80-20) with a fixed random seed for reproducibility.
- Performed 5-fold cross-validation to validate model robustness.

### 5. Model Evaluation
- Achieved a test accuracy of approximately **96.7%**.
- Cross-validation mean accuracy was consistently high (~96.6%), indicating strong generalization.
- Generated detailed classification reports and confusion matrices for performance insights.

### 6. Deployment
- Created a user-friendly web app with **Streamlit**, enabling real-time input of flower measurements and instant species prediction.
- This app showcases the end-to-end ML pipeline and allows users to interact with the model.

---

## Why This Project is Valuable

- Demonstrates the entire supervised ML workflow from raw data to deployment.
- Highlights skills in data analysis, visualization, preprocessing, model building, evaluation, and deployment.
- Uses a standard dataset, allowing easy reproducibility and benchmarking.
- Provides a practical web app that recruiters and hiring managers can interact with directly.
- Serves as a foundation for understanding multi-class classification problems, applicable to various domains such as healthcare, finance, and image recognition.

---

## Key Technologies & Tools

- **Python**: Core programming language.
- **Pandas & NumPy**: Data manipulation and numerical computations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning modeling, training, and evaluation.
- **Streamlit**: Rapid web app deployment for interactive ML demos.

---

## Results & Insights

| Metric            | Value    |
|-------------------|----------|
| Test Accuracy     | 96.7%    |
| Cross-Validation Accuracy | 96.6%    |
| Precision, Recall, F1-score | All above 96% for each species |

The model accurately distinguishes among the three Iris species based on flower dimensions. High precision and recall indicate reliable predictions with minimal false positives or negatives.

---

## How to Use

1. Clone the repository and install dependencies listed in `requirements.txt`.
2. Run the Jupyter Notebook for detailed analysis and model training.
3. Launch the Streamlit app to interactively predict Iris species by entering measurements.
4. Explore the codebase to learn and extend.

---

## Future Work & Improvements

- Experiment with other classifiers (Random Forest, KNN, Neural Networks) for comparison.
- Tune hyperparameters to potentially improve accuracy.
- Extend dataset with additional flower species for a more challenging multi-class task.
- Add automated testing and CI/CD pipeline for production readiness.

---

## Contact & Contributions

I welcome feedback and collaboration.  
Feel free to connect:

- GitHub: [https://github.com/omkar1872](https://github.com/omkar1872)  
- LinkedIn: [https://linkedin.com/in/omkar1872](https://www.linkedin.com/in/omkar1872/)  
- Email: chomkar1872@gmail.com


---


