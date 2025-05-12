# 🎮 Gaming Habits & Academic Performance Analysis

This project explores the relationship between students' gaming habits and their academic performance using statistical analysis, machine learning, and deep learning techniques. The goal was to build predictive models and identify key behavioral insights.

---

## 📁 Dataset

- **File Used:** `gameandgrade.csv`
- Includes features related to gaming frequency, duration, and academic scores.

---

## 🧹 1. Data Processing & Preparation

- **Missing Values:** Identified and cleaned.
- **Encoding:** Categorical variables were converted to numeric types.
- **Scaling:** Applied `StandardScaler` to normalize features.
- **Train-Test Split:** 80% training, 20% testing.
- **Binary Classification:** Grades were binarized as:
  - `1 = Pass` (≥ median)
  - `0 = Fail` (< median)

---

## 📊 2. Visualization & Analysis

- **Statistical Summary:** Mean, median, and distributions calculated.
- **Heatmap Analysis:** Showed correlations between variables.
- **Boxplot:** Analyzed relationship between gaming time and performance.

---

## 🤖 3. Machine Learning Models

### Models Used:
- Logistic Regression
- Ridge Classifier
- Random Forest
- Gradient Boosting
- AdaBoost
- Decision Tree
- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)
- Naive Bayes

### Evaluation:
- **Metrics:** Accuracy & Execution Time
- **Visualization:** Heatmap to compare model performance

---

## 🧠 4. Deep Learning Models

### Architectures:
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)

### Training:
- All models trained for **20 epochs**

### Evaluation:
- Accuracy and training/testing time measured
- Results visualized with heatmaps

---

## ✅ 5. Conclusion & Key Findings

- **Top ML Performers:** Random Forest and Gradient Boosting showed highest accuracy.
- **Best DL Models:** CNN and ANN outperformed LSTM and GRU.
- **Insight:** Gaming habits have a measurable impact on academic performance, with certain thresholds correlating with decreased grades.

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn)
- TensorFlow / Keras
- Matplotlib, Seaborn
- Jupyter Notebook

---




## Author
[Mosaad Hendam](https://github.com/Mosaad2010-star)
