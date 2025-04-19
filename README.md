
#  Heart Disease Prediction using Machine Learning

This project aims to predict the presence of heart disease using various machine learning models such as Logistic Regression, Decision Tree, and Random Forest. The notebook includes data preprocessing, exploratory data analysis, model training, and evaluation.


##  Project Structure

heart_disease_project/
│
├── heart_disease_data.xlsx              # Dataset used for training/testing
├── Heart_Disease_Prediction.ipynb       # Jupyter Notebook with ML pipeline
├── README.md                            # Project documentation


##  Dataset

A synthetic heart disease dataset was generated for this project. It contains features commonly used in cardiovascular risk prediction such as:

- Age
- Sex
- Chest pain type (`cp`)
- Resting blood pressure (`trestbps`)
- Cholesterol levels (`chol`)
- Fasting blood sugar (`fbs`)
- ECG results (`restecg`)
- Max heart rate (`thalach`)
- Exercise-induced angina (`exang`)
- ST depression (`oldpeak`)
- Slope of ST segment
- Number of major vessels (`ca`)
- Thalassemia value (`thal`)
- Target (0 = No disease, 1 = Disease present)

##  Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Evaluation metrics include:
- Accuracy
- Confusion Matrix
- Classification Report

## Requirements

You can install the required libraries using:

```bash
pip install -r requirements.txt
```

##  How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
```

2. Navigate to the project folder and open the notebook:
```bash
cd heart-disease-prediction
jupyter notebook Heart_Disease_Prediction.ipynb
```

3. Ensure `heart_disease_data.xlsx` is in the same directory.

##  License

This project is open-source and free to use under the [MIT License](LICENSE).
