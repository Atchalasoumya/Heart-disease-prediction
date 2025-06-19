# ❤️ Heart Disease Prediction

This project uses machine learning to predict the presence of heart disease in a patient based on various medical attributes. It is implemented in a Jupyter Notebook and includes data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

## 📁 Project Structure

```
Heart Disease Prediction.ipynb
README.md
requirements.txt
```

## 📊 Dataset

The dataset used for this project appears to be a version of the **Cleveland Heart Disease dataset** which contains medical attributes such as:

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Maximum Heart Rate Achieved (thalach)
- Exercise-Induced Angina (exang)
- Oldpeak (ST depression)
- Slope of the peak exercise ST segment
- Number of major vessels (ca)
- Thalassemia (thal)
- Target variable indicating the presence of heart disease

## ⚙️ Requirements

Install required packages:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. Clone this repository or download the notebook.
2. Open the notebook in JupyterLab / Jupyter Notebook / VSCode.
3. Run all the cells sequentially.
4. View the model training process, performance metrics, and predictions.

## 🔍 Model Details

- **Algorithms Used**: 
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - XGBoost (if applicable)

- **Evaluation Metrics**:
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)
  - ROC Curve

## 📈 Results

The model(s) were evaluated on test data, and the best performing model achieved **high accuracy** in predicting the presence of heart disease.

## 📌 Highlights

- Complete EDA with correlation heatmap and boxplots
- Feature scaling and preprocessing
- Model comparison and selection
- Confusion matrix visualizations
- User-friendly and easy-to-follow code

## 🧠 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Deployment using Flask or Streamlit
- Use of more complex ensemble methods

## 📄 License

This project is for educational purposes.
