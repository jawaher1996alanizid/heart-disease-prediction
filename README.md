# Heart Disease Prediction using Logistic Regression

This project uses a machine learning model (Logistic Regression) to predict whether a person is likely to have heart disease based on several medical attributes.

## 🔍 Dataset
The dataset contains various health-related features such as:
- Age
- Gender
- Chest pain type
- Resting blood pressure
- Cholesterol levels
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression
- Slope of the ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia

The target column indicates the presence (1) or absence (0) of heart disease.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Model
The model used is **Logistic Regression** from scikit-learn.

### Performance:
- **Training Accuracy**: 85.5%
- **Test Accuracy**: 80.3%

### Evaluation Metrics:
- Accuracy Score
- Confusion Matrix

## How to Use
To test the model with your own data:
1. Open the notebook in Google Colab.
2. Modify the `input_data` with your own values:
   ```python
   input_data = (63,1,3,145,233,1,0,150,0,2.3,0,0,1)
# heart-disease-prediction
Predicting heart disease using machine learning
