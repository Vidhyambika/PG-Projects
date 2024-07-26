# NASA EDA & RUL Prediction

This repository contains jupyter notebooks that explores and predicts the Remaining Useful Life (RUL) of Turbofan engine using NASA's dataset. The project focuses on exploratory data analysis (EDA) and implementing machine learning models to predict RUL.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing & Data Inspection](#data-preprocessing-and-data-inspection)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Predicting the Remaining Useful Life (RUL) of machinery is critical in predictive maintenance, as aircraft components are susceptible to degradation, which directly affects their reliability and performance. This project utilizes NASA's dataset to perform EDA and build machine learning models for RUL prediction. The project is implemented in a Kaggle notebook and demonstrates the steps involved in data inspection and pre-processing, exploratory data analysis (including visualization), feature engineering, model building, training and testing (regression/classification), and evaluation.

Kaggle notebooks links: 
                        1. https://www.kaggle.com/code/vidhyambikasr/nasa-eda-rul-prediction (solved as a regression problem)

                        2. https://www.kaggle.com/code/vidhyambikasr/nasa-predictive-maintenance-rul (classification)
                        
## Dataset

The dataset used in this project is provided by NASA and is publicly available on Kaggle/NASA's website. It includes time-series data of engine sensor readings measured during their life cycles. 

- **Link to Dataset:** [NASA Turbofan Engine Degradation Simulation Data Set](https://www.kaggle.com/datasets/surajbhatt/nasa-cmaps)

## Data Preprocessing and Data Inspection

The data preprocessing and inspection step involves:

- Loading the dataset and understanding its structure
- Handling Null/NaN values
- Handling missing values and outliers
- Normalizing and scaling the data
- Splitting the dataset into training and testing sets
  
This step ensures that the data is clean and ready for analysis and modeling

## Exploratory Data Analysis

The exploratory data analysis (EDA) section covers:

- Understanding the structure and characteristics of the dataset
- Visualizing sensor readings and identifying patterns
- Analyzing correlations between different sensors
- Identifying key features that influence RUL

# Feature Engineering

The feature engineering step involves:

- Creating new features that may help in improving model performance
- Selecting important features through statistical methods (Dimensionality Reduction and Feature selection)
- Transforming existing features to better represent the underlying patterns in the data
  
## Machine Learning Models

This section covers the implementation of various machine learning models to predict RUL:

- Linear Regression (Notebook 1)
- Random Forest Regressor (Notebook 1)
- Support Vector Regression (Notebook 1)
- Random Forest Classifier (Notebook 2)
- Gaussian Naive Bayes (Notebook 2)
- K Nearest Neighbours(KNN) (Notebook 2)
- Support Vector Machines (Notebook 2)
- Support Vector Classifier (Notebook 2)

Each model is evaluated based on its performance metrics, such as Mean Squared Error (MSE) and R-squared (R²) for regression (Notebook 1); Accuracy, precision, recall, F1 score, confusion matrix, support, etc for classification (Notebook 2). **Hyper parameter tuning** is also performed to boost the R2 score and reduce error value in Notebook 1.

## Results

The results section presents the performance of each model, highlighting the best-performing model and its predictions. Visualizations of actual vs. predicted RUL are provided to illustrate the model's accuracy.

## Conclusion

This project demonstrates the importance of EDA in understanding the data and the effectiveness of different machine learning models in predicting RUL. The findings can be applied to similar predictive maintenance tasks in various industries.

## How to Use

To run the notebook and explore the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/vidhyambikasr/nasa-eda-rul-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd nasa-eda-rul-prediction
   ```

3. Open the notebook using Jupyter Notebook or any compatible environment:
   ```bash
   jupyter notebook NASA_EDA_RUL_Prediction.ipynb
   ```

4. Follow the instructions in the notebook to run the code and explore the results.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README further to suit your needs!
