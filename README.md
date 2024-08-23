# Students Performance Analysis

## Overview
This project analyzes the `StudentsPerformance.csv` dataset to explore various factors influencing student performance in math, reading, and writing. The project includes data preprocessing, exploratory data analysis, and the application of advanced data science techniques such as regression modeling, classification, feature engineering, and clustering.

## Features
- **Data Preprocessing:** Handling missing data, encoding categorical variables using one-hot encoding.
- **Exploratory Data Analysis (EDA):** Visualizations of student performance across different demographics and factors.
- **Predictive Modeling:** 
  - Regression models to predict scores.
  - Classification models to predict whether students pass or fail based on certain thresholds.
- **Advanced Techniques:**
  - Feature engineering to create new features.
  - Correlation analysis and feature selection.
  - Clustering to group students based on performance.
  - Dimensionality reduction using PCA.
- **Model Evaluation:** Calculation of metrics like Mean Squared Error (MSE) for regression and accuracy for classification.

## Setup

### Prerequisites
- Python 3.x
- Required Python libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, plotly

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/students-performance-analysis.git
   cd students-performance-analysis
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook or Python scripts to perform analysis.

## Usage
1. **Preprocess the data:** Ensure categorical variables are encoded and the data is split into training and testing sets.
2. **Run the models:** Train the regression or classification models and evaluate their performance.
3. **Explore the results:** Use visualizations and metrics to understand model performance and insights from the data.

## Results
- The project demonstrates how various factors like gender, parental education, and test preparation influence student performance.
- Regression models predict scores, while classification models determine pass/fail status.
- Clustering and PCA help in visualizing and understanding student groups based on their performance.

