# Diabetes Prediction Project

This project aims to predict whether a patient is at risk of diabetes based on various medical features using machine learning algorithms.

## Overview

Diabetes is a chronic disease that occurs when the body cannot effectively use or produce insulin. Early detection of diabetes can help in the management and prevention of complications. This project utilizes machine learning to predict whether a patient is likely to have diabetes based on their medical data.

## Dataset

The dataset used for this project is the **Pima Indians Diabetes Database**, which contains information about patients' medical history, such as:
- **Pregnancies**: The number of pregnancies the patient has had.
- **Glucose**: The patient's blood glucose level.
- **BloodPressure**: The patient's blood pressure.
- **SkinThickness**: The thickness of the skin fold at the triceps.
- **Insulin**: The level of insulin in the patient's blood.
- **BMI**: The body mass index (BMI) of the patient.
- **DiabetesPedigreeFunction**: A function that scores the likelihood of a patient having diabetes based on family history.
- **Age**: The patient's age.

## Machine Learning Model

This project uses **Logistic Regression** and **Random Forest** as machine learning models to classify whether a person has diabetes (1) or not (0). The dataset is split into a training and test set for model evaluation.

### Steps Taken:
1. **Data Preprocessing**: Cleaned the data by handling missing values and scaling the features.
2. **Model Training**: Used **Logistic Regression** and **Random Forest** algorithms for classification.
3. **Model Evaluation**: Evaluated the models using accuracy, precision, recall, and F1 score.

## Requirements

To run this project locally, you need to have the following Python libraries installed:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install these dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/alireza-asl/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. Run the notebook to see the analysis and model predictions:

   ```bash
   jupyter notebook
   ```

3. Follow the instructions in the notebook to train and evaluate the models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset is taken from the **Pima Indians Diabetes Database** available on [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database).
- Thanks to all the contributors to the open-source community.
