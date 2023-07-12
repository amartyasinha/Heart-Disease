# Heart Disease Prediction

This project focuses on predicting heart disease using machine learning algorithms. The dataset used for this project contains various attributes related to heart health, such as chest pain type, resting blood pressure, cholesterol level, and more.

## Dataset

The dataset used for this project is stored in the file "your_dataset.csv". It consists of the following columns:

- SN: Serial number
- Age: Age of the patient
- Sex: Gender of the patient (0: Female, 1: Male)
- ChestPain: Type of chest pain (0: asymptomatic, 1: nonanginal, 2: nontypical, 3: typical)
- RestBP: Resting blood pressure
- Chol: Serum cholesterol level
- Fbs: Fasting blood sugar > 120 mg/dl (0: No, 1: Yes)
- RestECG: Resting electrocardiographic results (0-2)
- MaxHR: Maximum heart rate achieved
- ExAng: Exercise-induced angina (0: No, 1: Yes)
- Oldpeak: ST depression induced by exercise relative to rest
- Slope: The slope of the peak exercise ST segment (0-2)
- Ca: Number of major vessels colored by fluoroscopy (0-3)
- Thal: Thalassemia (0: fixed, 1: normal, 2: reversable)
- AHD: Presence of heart disease (0: No, 1: Yes)

## Preprocessing and Modeling

The dataset was preprocessed as follows:

- The "SN" column was excluded as it does not provide meaningful information.
- Missing values were dropped from the dataset.
- Categorical features ("ChestPain" and "Thal") were encoded using label encoding.
- Numeric features were scaled using standard scaling.

The dataset was then split into training and testing sets, with a test size of 0.2 and a random state of 42. Three machine learning algorithms were applied to the dataset:

1. Logistic Regression
2. Decision Tree
3. K-Nearest Neighbors (KNN)

## Results

Here is the Accuracy Results for these machine learning algorithms:

1. Logistic Regression:
   - Accuracy: 0.867

2. Decision Tree:
   - Accuracy: 0.817

3. K-Nearest Neighbors (KNN):
   - Accuracy: 0.750

## Confusion Matrices

The confusion matrices for each model were visualized using heatmaps. The accuracy scores and confusion matrices are available in the code.

Please refer to the code for more details on the implementation.