
# 🌧️ Rainfall Prediction Using Machine Learning

This project focuses on enhancing the accuracy of rainfall prediction using supervised machine learning techniques. It addresses the challenge of imbalanced datasets through **SMOTE** and compares multiple classifiers to identify the most effective model.

## 📂 Project Structure
- `RainfallPrediction.ipynb` – Jupyter Notebook containing complete code (preprocessing, SMOTE, modeling, evaluation).
- `weatherAUS.csv` – Dataset containing historical weather data (sourced from Kaggle).
- `output_plots/` – Visualizations like confusion matrices, F1 score plots (optional if you generate them).
- `requirements.txt` – (Optional) List of Python libraries used.

## 🚀 Features
- Preprocessing of real-world weather data  
- Dataset balancing using **SMOTE**  
- Evaluation of multiple ML models: Random Forest, SVM, KNN, Decision Tree, MLP  
- Performance comparison using Accuracy, Precision, Recall, and **F1-score**  
- Hyperparameter tuning with **GridSearchCV**

## 📈 Best Result
- **Random Forest** achieved the best performance with a high F1-score after applying SMOTE.

## 🧠 Tech Stack
- Python  
- Scikit-learn  
- imbalanced-learn (for SMOTE)  
- Pandas, NumPy, Matplotlib, Seaborn  
- Jupyter Notebook

## 📊 Dataset Source
- [Kaggle – Rain in Australia](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

## 📌 How to Run
1. Clone the repository  
2. Install required libraries using:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook in Jupyter or VS Code  
4. Run cells in order

## 📬 Contact
Created by **Nishitha S**  
Email: `snishitha06@gmail.com`
