# Gym Member Attendance Prediction

## Purpose
This project investigates the impact of behavioral and physical factors on gym attendance. It aims to offer new insights into members’ attendance patterns and strategies to improve engagement by leveraging data-driven methodologies to predict gym attendance patterns using historical data.

## Project Description
With a strong emphasis on behavioral analysis, this study identifies key factors influencing member attendance. Advanced feature selection techniques were employed to uncover significant variables and their correlations, providing actionable insights into member engagement and retention.

## Data Source
The analysis utilizes a public dataset available on the Kaggle platform, featuring detailed information on gym members, including physical attributes, training patterns, and behavioral attributes such as weekly attendance, average session length, and types of exercises practiced. The dataset consists of 973 entries with 15 variables.

## Technologies Used
- Python
- Jupyter Notebook
- Google Colab
- Visual Studio Code
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, SHAP

## Key Findings
- Cardio and Strength training are the most popular activities.
- Significant correlations were found between experience level and weekly training frequency, as well as training session duration, indicating strong predictors of attendance.

## Machine Learning Algorithms Used
### Decision Tree Regressor
- **Used for**: Establishing a performance baseline.
- **Advantages**: Handles complex, non-linear relationships; provides interpretable results.

### Linear Regression
- **Used for**: Standard model for predicting continuous outcomes.
- **Advantages**: Simplicity, effectiveness in interpreting linear relationships.

## Methodology
1. **Data Cleaning**: Outliers were removed using the Interquartile Range (IQR) method, reducing the dataset to 931 entries.
2. **Feature Selection**: Employed SHAP (SHapley Additive exPlanations) to identify and retain the most impactful features, enhancing model accuracy.
3. **Model Evaluation**: Split the data into 80% training and 20% testing to ensure robust model evaluation. Applied Decision Tree and Linear Regression models to compare effectiveness.

## Performance
- **Linear Regression**: Achieved an accuracy of 83.42%, with an F1-Score of 87.75%. It proved to be the best model for providing a balanced approach between precision and recall.
- **Decision Tree**: Showed good recall but was less precise, making it suitable for scenarios where identifying as many positive cases as possible is crucial.

## Setup Instructions

### Prerequisites
Ensure you have Python installed on your machine. If not, download and install Python from [python.org](https://www.python.org/downloads/).

### Development Tools
1. **Visual Studio Code**: Download from [here](https://code.visualstudio.com/Download) and install.
2. **Jupyter Notebook**: Install by running `pip install notebook`.
3. **Google Colab**: Access via [Google Colab](https://colab.research.google.com/) for an online Jupyter notebook environment.

### Installation
Clone the repository and install the required Python packages:
```bash
git clone https://github.com/HasanCinar076/gym-attendance-prediction.git
cd gym-attendance-prediction
pip install -r requirements.txt
