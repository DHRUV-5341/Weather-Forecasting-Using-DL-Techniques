# Weather Forecasting Using Machine Learning

The project contains:

Analyzing the dataset to identify continuous and discrete variables is known as data exploration.
Feature selection is the process of using specific weather factors as forecast inputs, such as humidity, pressure_mb, wind_mph, cloud, and feelslike_c.
Model Development: Predicting the target variable using machine learning techniques

---

## Project Overview

The project includes:
- Data Preprocessing and Exploration
- Data Visualization and Outlier Detection
- Feature Selection and Balancing
- Implementation of Deep Learning Algorithms:
  - Long Short-Term Memory (LSTM)
  - Recurrent Neural Networks (RNN)
  - Deep Neural Networks (DNN)
  - Convolutional Neural Networks (CNN)
- Evaluation of Model Performance

---

## Dataset

The Dataset was taken from kaggle and it includes meteorological data such as:
- **Input Variables (X):**
  - `humidity`
  - `pressure_mb`
  - `wind_mph`
  - `cloud`
  - `feelslike_c`
- **Target Variable (y):**
  - `temp_c`

---

## Key Steps

### Data Exploration.
The objective of the **Missing Values Analysis** is to find missing values for cleaning.
Heatmaps, joint plots, scatter plots, and histograms are all basic visualizations.


### Outlier Detection and Handling
- Outliers are detected by Isolation-Forest Algorithm and all the outliers was exclude from the Dataset .

### Data Balancing
- Smote was used to handle imbalanced datasets, ensuring fair representation and distributtion of features in all the classes.

---

## Deep Learning Algorithms

### 1. Long Short-Term Memory (LSTM)
- Designed for time-series data.
- Evaluation metrics include accuracy, MAE, and RMSE.

### 2. Recurrent Neural Networks (RNN)
- Used for sequential data processing.
- Evaluation metrics similar to LSTM.

### 3. Deep Neural Networks (DNN)
- General-purpose architecture for regression tasks.
- Performance evaluated using RMSE and MAE.

### 4. Convolutional Neural Networks (CNN)
- Adapted for structured data to explore its forecasting capabilities.
- Metrics used include accuracy and loss.

---

## Results and Insights
- LSTM gave the best perfomance other algorithms like RNN, DNN and CNN were used to compare their perfomance and efficiency with LSTM.
- Feature selection (humidity, pressure, etc.) played a crucial role in model accuracy.

---

## Prerequisites

### Libraries Required
- `pandas`
- `seaborn`
- `matplotlib`
- Machine learning libraries for model implementation (e.g., TensorFlow/Keras, PyTorch).

Install dependencies using:
```bash
pip install pandas seaborn matplotlib tensorflow keras
