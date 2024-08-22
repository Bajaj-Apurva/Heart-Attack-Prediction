# Heart-Attack-Prediction
This repository contains a Python implementation of a logistic regression model to predict the likelihood of heart disease based on patient data. The model is trained on a dataset containing various health indicators, and it predicts whether a person is at risk of having a heart attack.

## Dataset
The dataset used in this project is heart.csv, which includes the following columns:

age: Age of the patient

sex: Sex of the patient (1 = male, 0 = female)

cp: Chest pain type (1-4)

trtbps: Resting blood pressure (in mm Hg)

chol: Serum cholesterol (in mg/dl)

fbs: Fasting blood sugar (1 = true, 0 = false)

restecg: Resting electrocardiographic results (0-2)

thalachh: Maximum heart rate achieved

exng: Exercise induced angina (1 = yes, 0 = no)

oldpeak: Depression induced by exercise relative to rest

slp: Slope of the peak exercise ST segment (0-2)

caa: Number of major vessels colored by fluoroscopy (0-3)

thall: Thalassemia (1-3)

output: Target variable (1 = presence of heart disease, 0 = absence)

## Installation
#### Clone the repository:
git clone https://github.com/Bajaj-Apurva/Heart-Attack-Prediction.git

cd Heart-Attack-Prediction

#### Install the required packages:
pip install numpy pandas scikit-learn

## Usage
Ensure you have the heart.csv dataset in the project directory.

Run the Jupyter Notebook or Python script:

python Heart Attack Prediction.ipynb

The script will:

Load and preprocess the data

Split the data into training and testing sets

Train a logistic regression model

Evaluate the model's performance on both training and test data

Make predictions based on input data

## Code Explanation
#### Data Loading and Exploration:
Load the dataset using pandas and perform initial exploration to understand the data structure.
#### Data Preprocessing:
Separate features and target variable.

Split the data into training and test sets.
#### Model Training:
Train a logistic regression model on the training data.
#### Model Evaluation:
Evaluate the model using accuracy metrics on both training and test data.
#### Prediction:
Make predictions for new data points to determine the likelihood of heart disease.

## Results
The model provides an accuracy score for both the training and test datasets, helping to assess its performance.
Predictions are made on new input data to provide insights into potential heart disease risk.

## Contributing
Feel free to contribute to this project by submitting pull requests or reporting issues. Contributions are welcome!

## License
This project is licensed under the MIT License.
