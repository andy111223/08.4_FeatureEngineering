# Titanic Passengers Feature Engineering
This repository is for the author's learning purposes. It includes feature engineering on the Titanic dataset as part of a broader data analysis process. The work is done using Jupyter Notebook, following the CRISP-DM (Cross Industry Standard Process for Data Mining) framework.

## Overview
This project utilizes the Titanic dataset to practice feature engineering, data preprocessing, and visualization techniques. The focus is on exploring the Titanic dataset, processing data, transforming features, and visualizing relationships to understand how feature engineering can improve model performance.

## Concepts Learnt
1. CRISP-DM Process: This project forms a part of the CRISP-DM process, specifically the Data Preparation and Data Understanding phases.
2. Feature Engineering:
    - One Hot Encoding (OHE): Conversion of categorical data into numerical form using the OHE technique to enable the use of non-numeric attributes in machine learning models.
    - Handling Categorical and Numerical Data: Understanding and preprocessing categorical variables (e.g., titles, gender) and numerical variables (e.g., age, fare).
    - Dependant Variable (Target y): Defined and used the Survived column as the target variable (y) in the model.
    - Child Feature Creation: Created a binary feature to indicate whether a passenger is a child or an adult to examine if age correlates with survival.
3. Data Preparation Techniques:
    - Handling Missing Values: Replaced missing values in certain columns to avoid inconsistencies in analysis.
    - Feature Transformation: Extracted titles from names to create a new feature and group similar categories.
4. Exploratory Data Analysis (EDA):
    - Data Visualization Libraries: Learned how to create effective visualizations using the matplotlib and seaborn libraries to understand relationships between features. The dark theme and color palette customization were also applied to improve the aesthetics of visualizations.
    - YData Report: Generated exploratory data analysis reports with ydata_profiling to gain an overview of the dataset.
5. Dealing with Multicollinearity: Understanding how highly correlated features can negatively impact the model and how to address it.

6. Other Python Concepts:
    - Use of loc, isin, and map methods: To filter and transform the data.
    - Creating and Modifying Features: Using expressions and functions to create new features based on existing ones (e.g., creating Child and Title features).
    - Extracting Information: Extracted information like titles from the Name column using string methods.

## Installation
1. Clone the repository:

    `git clone https://github.com/andy111223/08.4_FeatureEngineering.git`

2. Navigate to the project directory:

    `cd 08.4_FeatureEngineering`

3. Install the necessary Python packages:

    `pip install pandas matplotlib seaborn ydata-profiling`

## Usage
To run the analysis, execute the following command:

`jupyter notebook titanic.ipynb`
## Summary
This project provides practice with feature engineering and data visualization. It demonstrates the importance of data preprocessing, feature creation, and transformation in the data analysis workflow. The notebook covers categorical and numerical data, creating dummy variables (OHE), and visualizing patterns with barplots. It also includes hands-on experience with Python data manipulation methods.