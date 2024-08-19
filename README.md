# Wine Quality Analysis and Prediction

## Project Overview
This project focuses on analyzing wine quality and predicting wine ratings using machine learning techniques, specifically K-Means Clustering and Neural Networks. The analysis includes exploratory data analysis, feature engineering, and model development to understand factors influencing wine quality and to predict quality ratings.

## Dataset
The dataset contains various chemical properties of wines along with their quality ratings. Features include:
- Fixed acidity, volatile acidity, citric acid
- Residual sugar, chlorides
- Free sulfur dioxide, total sulfur dioxide
- Density, pH, sulphates, alcohol
- Quality (target variable)
- Color (red/white)

## Methodology

### Data Preprocessing and Exploratory Analysis
- Summary statistics calculation
- Handling of missing values
- Conversion of categorical variables to numerical
- Correlation analysis
- Extensive data visualization including:
  - Distribution of quality ratings
  - Scatter plots of alcohol vs density for each wine color
  - Bar plots of average alcohol content by quality
  - Box plots for various features
  - Pair plots for feature relationships

### Feature Engineering
- Creation of a binary 'good' feature based on quality ratings
- Principal Component Analysis (PCA) for dimensionality reduction

### Model Development

#### 1. K-Means Clustering
- Applied to group wines based on their characteristics
- Analysis of cluster centroids to understand wine profiles

#### 2. Neural Network
- Initial model with 50 epochs
- Hyperparameter tuning for improved performance

## Results

### K-Means Clustering
Cluster analysis revealed distinct wine profiles based on chemical properties.

### Neural Network Performance

#### Initial Model (50 epochs):
- Test Accuracy: 70.62%
- Best Training Accuracy: 73.37%
- Best Validation Accuracy: 71.38%

#### Tuned Model:
- Test Accuracy: 71.23%
- Best Training Accuracy: 76.26%
- Best Validation Accuracy: 71.85%

## Key Findings
- The neural network model showed moderate success in predicting wine quality.
- Tuning the model resulted in slight improvements in accuracy.
- The project revealed important relationships between chemical properties and wine quality.

## Technologies Used
- Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras


## Future Work
- Explore ensemble methods for potentially improved predictions
- Investigate the impact of feature selection on model performance
- Develop a user-friendly interface for wine quality prediction



This project demonstrates the application of machine learning techniques in wine quality analysis and prediction, providing insights into the factors influencing wine quality and the effectiveness of different modeling approaches.
