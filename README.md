# Mental-Fitness-Tracker

## Overview
This project aims to predict mental fitness levels based on various factors such as country, year, and prevalence rates of different mental health disorders. The prediction is performed using machine learning techniques, specifically Random Forest regression.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, plotly

## Installation
1. Clone the repository to your local machine:
    ```
    git clone <repository_url>
    ```
2. Navigate to the project directory:
    ```
    cd mental-fitness-prediction
    ```
3. Install the required libraries:
    ```
    pip install -r requirements.txt
    ```

## Usage
1. Ensure that you have all necessary data files in the project directory.
2. Run the Jupyter notebook `mental_fitness_prediction.ipynb` to train the predictive models and make predictions.
3. Follow the instructions provided in the notebook to preprocess the data, train the models, and make predictions.

## File Descriptions
- `mental_fitness_prediction.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, and predictions.
- `prevalence-by-mental-and-substance-use-disorder.csv`: CSV file containing prevalence data for mental and substance use disorders.
- `mental-and-substance-use-as-share-of-disease.csv`: CSV file containing data on mental and substance use as a share of disease.

## Data
The dataset used in this project includes information on prevalence rates of mental and substance use disorders across different countries and years.

## Model Evaluation
The trained models are evaluated using metrics such as Mean Squared Error (MSE) and R-squared (R2) score to assess their predictive performance.

## Results
The predictions made by the trained models can be interpreted to understand the likelihood of individuals having mental health disorders based on the provided input data.
