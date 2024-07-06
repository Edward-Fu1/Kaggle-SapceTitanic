# Spaceship Titanic: Predicting Passenger Transportation

## Project Overview
This project is based on the Spaceship Titanic competition on Kaggle. The goal is to predict which passengers were transported to an alternate dimension during the Spaceship Titanic's collision with a spacetime anomaly.

## Dataset
The dataset is provided by Kaggle as part of the [Spaceship Titanic competition](https://www.kaggle.com/competitions/spaceship-titanic). It includes passenger information and whether they were transported.

## Technologies and Skills Used
- Python
- Data Analysis: NumPy, Pandas
- Data Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn
- Encoding Techniques:
  - Ordinal Encoder
  - One-Hot Encoder
- Algorithms: 
  - Logistic Regression
  - Random Forest Classifier

## Project Structure
1. Data Exploration and Visualization
2. Data Preprocessing
3. Feature Engineering
4. Model Training and Evaluation
5. Prediction on Test Set

## Key Steps

### 1. Data Exploration and Visualization
- Analyzed the distribution of features
- Visualized correlations between variables
- Explored the relationship between features and the target variable (Transported)

### 2. Data Preprocessing
- Handled missing values
- Encoded categorical variables:
  - Used Ordinal Encoder for ordered categorical variables
  - Applied One-Hot Encoder for nominal categorical variables
- Scaled numerical features

### 3. Feature Engineering
- Created new features based on domain knowledge and data insights
- Selected relevant features for model training

### 4. Model Training and Evaluation
- Implemented Logistic Regression and Random Forest Classifier
- Performed cross-validation to assess model performance
- Tuned hyperparameters for optimal results

### 5. Prediction on Test Set
- Applied the best performing model to the test dataset
- Generated predictions for submission to Kaggle
