# Heart Disease Prediction Model

This project implements various machine learning models to predict the risk of heart disease using the Framingham Heart Study dataset.

## Overview

The project uses multiple classification algorithms to predict the 10-year risk of coronary heart disease (CHD) in patients. The models implemented include:
- Logistic Regression
- Linear SVC
- Polynomial SVC
- Random Forest
- Gaussian RBF SVC

## Dataset

The project uses the Framingham Heart Study dataset (`framingham.csv`) which includes the following features:
- Age
- Sex
- Cigarettes per day
- Total cholesterol
- Systolic blood pressure
- Glucose level
- 10-year risk of coronary heart disease (target variable)

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd College_ML_Project
   ```

2. **Set Up Python Environment**
   ```bash
   # Create a virtual environment
   python -m venv venv
   
   # Activate virtual environment
   # On Windows:
   venv\Scripts\activate
   # On Unix or MacOS:
   source venv/bin/activate
   ```

3. **Install Required Dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
   ```

4. **Download Dataset**
   - Place the `framingham.csv` file in the project directory

5. **Run the Notebook**
   ```bash
   jupyter notebook "Heart Disease Prediction.ipynb"
   ```

## Project Structure

- `Heart Disease Prediction.ipynb`: Main Jupyter notebook containing the analysis
- `framingham.csv`: Dataset file
- `README.md`: Project documentation

## Methodology

1. **Data Preprocessing**
   - Handling missing values
   - Feature normalization
   - Class imbalance handling using SMOTE

2. **Model Training and Evaluation**
   - Split data into training (70%) and testing (30%) sets
   - Train multiple classification models
   - Evaluate using accuracy and ROC-AUC scores

## Results

The models achieved the following accuracy scores:
- Logistic Regression: 70% accuracy
- Linear SVC: 71% accuracy
- Polynomial SVC: 69% accuracy
- Random Forest: 73% accuracy
- Gaussian RBF SVC: 71% accuracy

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

## License

This project is licensed under the MIT License - see the LICENSE file for details.
