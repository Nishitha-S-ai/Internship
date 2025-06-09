
# 🌧️ Rainfall Prediction Using Machine Learning

This project focuses on enhancing the accuracy of rainfall prediction using supervised machine learning techniques. It addresses the challenge of imbalanced datasets through **NearMiss under-sampling** and compares multiple classifiers to identify the most effective model. Additionally, it applies **RandomizedSearchCV** for hyperparameter tuning to optimize performance.

## 📂 Project Structure
- `RainfallPrediction.ipynb` – Jupyter Notebook containing complete code (preprocessing, NearMiss, modeling, evaluation).
- `weatherAUS.csv` – Dataset containing historical weather data (sourced from Kaggle).
- `output_plots/` – Visualizations like confusion matrices, F1 score plots (optional if you generate them).
- `requirements.txt` – (Optional) List of Python libraries used.

## 🚀 Features
- Preprocessing of real-world weather data  
- Dataset balancing using **NearMiss under-sampling**  
- Evaluation of multiple ML models: Random Forest, SVM, KNN, Decision Tree, MLP  
- Performance comparison using Accuracy, Precision, Recall, and **F1-score**  
- Hyperparameter tuning with **RandomizedSearchCV**

## 📈 Best Result
- **AdaBoost** achieved the best overall **F1-score**, making it the most effective model after balancing and tuning.

## 🧠 Tech Stack
- Python  
- Scikit-learn  
- imbalanced-learn (for NearMiss)  
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
