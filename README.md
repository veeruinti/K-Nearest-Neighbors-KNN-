# 🧠 COVID-19 Hospitalization Prediction using KNN Algorithm

This project applies **K-Nearest Neighbors (KNN)** classification to predict whether a COVID-19 patient needs hospitalization based on health and medical parameters.

## 📘 Overview
The dataset contains patient attributes such as:
- Age
- Body Temperature (Normal / Moderate / High)
- Chronic Disease (Yes/No)
- Breathing Issue (Yes/No)
- Blood Oxygen Level (%)
- Target: Needed Hospitalization (Yes/No)

## 🧩 Steps Performed
1. **Data Cleaning & Preprocessing**
   - Checked for missing values
   - Encoded categorical columns using `pd.get_dummies()`
   - Converted target labels (“Yes”/“No”) to binary form

2. **Model Building**
   - Used `KNeighborsClassifier(n_neighbors=5)` for classification
   - Split data using `train_test_split()`

3. **Evaluation**
   - Confusion Matrix
   - Accuracy Score
   - Precision, Recall, F1-Score

## 📊 Model Performance
| Metric | Score |
|--------|--------|
| Accuracy | ≈ {acc:.2f}% |
| Precision | Based on positive class (1) |
| Recall | Based on positive class (1) |
| F1-Score | Based on positive class (1) |


## ⚙️ Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


## 📈 Visualization
Includes a **confusion matrix heatmap** and annotated performance metrics.
<img width="756" height="580" alt="image" src="https://github.com/user-attachments/assets/8108d5a6-f503-4d44-a4c8-e9cc6918ae46" />



## 👨‍💻 Author
**Veeranjaneya Inti**  
- 📍 AIML Student | Machine Learning Enthusiast  
- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/veeranjaneya-inti-138157255)


⭐ **If you like this project, give it a star and follow for more AI/ML projects!**
