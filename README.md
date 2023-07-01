
# Car-Fuel-Consuming-Prediction-EDA
- This repository contains the code and data for a project on Car Fuel Consuming Prediction.The project uses the auto-mpg.csv dataset, which can be downloaded from Kaggle:https://www.kaggle.com/datasets/uciml/autompg-dataset
# Data Content
The data is technical spec of cars. The dataset is downloaded from UCI Machine Learning Repository

* Title: Auto-Mpg Data

* Sources:
(a) Origin: This dataset was taken from the StatLib library which is
maintained at Carnegie Mellon University. The dataset was
used in the 1983 American Statistical Association Exposition.
(c) Date: July 7, 1993

* Past Usage:

See 2b (above)
Quinlan,R. (1993). Combining Instance-Based and Model-Based Learning.
In Proceedings on the Tenth International Conference of Machine
Learning, 236-243, University of Massachusetts, Amherst. Morgan
Kaufmann.

* Relevant Information:

* This dataset is a slightly modified version of the dataset provided in
the StatLib library. In line with the use by Ross Quinlan (1993) in
predicting the attribute "mpg", 8 of the original instances were removed
because they had unknown values for the "mpg" attribute. The original
dataset is available in the file "auto-mpg.data-original".

"The data concerns city-cycle fuel consumption in miles per gallon,
to be predicted in terms of 3 multivalued discrete and 5 continuous
attributes." (Quinlan, 1993)

* Number of Instances: 398

* Number of Attributes: 9 including the class attribute

### feature attributes:
* mpg: continuous
* cylinders: multi-valued discrete
* displacement: continuous
* horsepower: continuous
* weight: continuous
* acceleration: continuous
* model year: multi-valued discrete
* origin: multi-valued discrete
* car name: string (unique for each instance)

## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Sklearn
- Xgboost
- Lightgbm
- Catboost


- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly Sklearn Xgboost Lightgbm Catboost
    
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

The analysis includes the following tasks:

* Importing Libraries
* Importing Dataset
* Exploratory Analysis
* Missing Values
* Data Visualization
* Outlier Detection
* Feature Engineering
* Preprocessing
* Model Building
* Model Evaluation
* Model Regulariztaion
* Model Tuning
* AVeraging models
* Visualization the result


The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## Conclusion 
* In This Project, I built a model of Car Fuel Consuming Prediction with Gradient Boosting Regressor,XGBoost Regressor,LightGBM Regressor,Random Forest Regressor after evaluating some classification algorithms. I have explored lots of insights by visualizing the dataset and I got precise result from model classification. I got R2: 0.8839842503755497 after averaging models.

