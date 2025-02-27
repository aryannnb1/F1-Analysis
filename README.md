# HISTORY OF F1: Data Analysis of the Premier Motorsport Championship and Using Machine Learning to Predict the Championship Standings

## Overview

This project focuses on the history of Formula 1 (F1), the premier motorsport championship, and utilizes data analysis and machine learning techniques to predict championship standings. The project encompasses data collection, preprocessing, exploratory data analysis (EDA), and model training to provide insights and accurate predictions.

## Dataset

The dataset includes historical data of F1 races, drivers, teams, and championship standings. Key attributes in the dataset include:

- **Race Information**: Date, location, circuit, and race results.
- **Driver Information**: Driver names, nationalities, and career statistics.
- **Team Information**: Team names, constructors, and performance history.
- **Championship Standings**: Points, positions, and winners for each season.

## Data Preprocessing

### Handling Missing Values
- Identified and handled missing values appropriately.

### Feature Engineering
- Created new features to enhance the predictive power of the models.
- Combined relevant data points to provide comprehensive insights.

### Data Normalization & Cleaning
- Standardized numerical features.
- Converted categorical variables to numerical representations.

## Exploratory Data Analysis (EDA)

- Analyzed historical trends and patterns in race results and championship standings.
- Examined correlations between various features.
- Visualized key metrics and performance indicators across different seasons.

## Model Training

Utilized machine learning models to predict championship standings. Tested various algorithms, including:

- **Linear Regression**
- **Decision Trees**
- **Random Forest**
- **Gradient Boosting Regressor**

Evaluated model performance using metrics such as RMSE and R² scores.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook or any Python IDE

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aryannnb1/F1-Analysis.git
   cd F1-Analysis
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Run the data preprocessing and EDA notebook to clean and analyze the dataset.
3. Run the model training notebook to train and evaluate the machine learning models.

### Results

The final model performance will be evaluated using metrics such as RMSE and R² scores to determine the accuracy and reliability of the predictions.

## Contributing

Contributions are welcome! I've been planning on using Neural Networks for improving the predictions and creating a webapp to host this project. Please fork the repository and submit a pull request for any improvements or bug fixes.
