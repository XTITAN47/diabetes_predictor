# Diabetes Prediction Web App

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.0%2B-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24%2B-green)
![XGBoost](https://img.shields.io/badge/XGBoost-1.4%2B-yellowgreen)

## Overview

This project is a web application built using **Streamlit** that predicts whether a person is diabetic or not based on various health metrics such as Glucose level, Blood Pressure, BMI, etc. The prediction model is trained using **Logistic Regression**, **Support Vector Machine (SVM)**, and **XGBoost** algorithms, with hyperparameter tuning to optimize performance. The model is then deployed as a user-friendly web app.

## Features

- **Interactive Web Interface**: Built with Streamlit, the app provides an intuitive interface for users to input their health metrics and get instant predictions.
- **Multiple Models**: The app uses Logistic Regression, SVM, and XGBoost models, with hyperparameter tuning to ensure the best accuracy.
- **Model Comparison**: The project includes a comparison of different models to highlight their performance metrics.
- **Scalability**: The app can be easily scaled to handle more data or additional features.

## Dataset

The dataset used for training the model is the **PIMA Diabetes Dataset**, which contains the following features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: Class variable (0 or 1)

## Model Performance

The models were evaluated based on their accuracy, precision, recall, and F1-score. Below is a summary of the performance:

| Model                  | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| Logistic Regression    | 0.7532   | 0.81      | 0.80   | 0.81     |
| SVM                    | 0.7273   | 0.77      | 0.82   | 0.79     |
| XGBoost                | 0.7597   | 0.80      | 0.84   | 0.82     |
| Stacking Classifier    | 0.7662   | 0.80      | 0.85   | 0.82     |

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction

2. Install the required dependencies:

pip install -r requirements.txt

3. Run the Streamlit app:

streamlit run Diabetes_Prediction_web_app.py

4. Access the app:
Open your browser and go to http://localhost:8501 to interact with the app.

<h2>Usage</h2>
1.Input Data: Enter the required health metrics in the input fields provided by the web app.<br>
2.Get Prediction: Click on the "Diabetes Test Result" button to get the prediction.<br>
3.Result: The app will display whether the person is diabetic or not based on the input data.<br>

<h2>Contributing</h2><br>
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.<br>

1.Fork the repository.<br>
2.Create a new branch (git checkout -b feature/YourFeatureName).<br>
3.Commit your changes (git commit -m 'Add some feature').<br>
4.Push to the branch (git push origin feature/YourFeatureName).<br>
5.Open a pull request.<br>

<h2>License</h2><br>
This project is licensed under the MIT License. See the LICENSE file for details.<br>

<h2>Acknowledgments</h2><br>
The dataset used in this project is from the PIMA Diabetes Dataset.<br>

Special thanks to the developers of Streamlit, Scikit-learn, and XGBoost for their amazing libraries.
