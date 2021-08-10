# Thomas Draths
*An aspiring data scientist | Springboard alum | Former VP of Sales*

# Education
 - Certificate in Data Science, *Springboard*, 2021
 - Certificate, Business Essentials, *Univeristy College, London*, 2019
 - Bachelor Degree of Political Science, *University of Notre Dame*, 2003-2007


# Projects
## [Predicting soccer club strength using transfer data, Version 2](https://github.com/tdraths/spi_transfers_global)

This project is the second attempt at predicting soccer team strength using transfer data. It builds upon the work in the first verion with noticeable improvements.  - Expanded the dataset to include team data from nine top European soccer leagues.
- Used FuzzyWuzzy to standardize team & league names, as opposed to manually replacing using dictionary values.
- Tested multiple regressors with the data, selecting RandomForest as the best suited for the dataset and saw an improvement in R2 scores of about 50% over the previous version of this project.
- Utilized SHAP values to explain impact of each feature on predictions

## [Predicting Employee Attrition using data from IBM-Watson HR Analytics Project](https://github.com/tdraths/employee_attrition)

My second larger ML project, I used XGBoost to predict employee attrition at a fictional company.
- I began with a very clean dataset, and so focused on feature selection and hypertuning ML algorithms to find the best fit for the data.
- Evaluated algorithm selection using ROC-AUC scores given the imbalances in the data
- Used SHAP values to explain feature impact on predictions

## [Predicting soccer club strength using transfer data, Version 1](https://github.com/tdraths/transfers_capstone)

My first ML project and first capstone for the [Springboard Data Science program](https://www.springboard.com/courses/data-science-career-track/)
 - As it was my first project, my efforts were highly focused on cleaning the dataset, feature creation and choosing an algorithm.
 - Identified actionable next steps for a future version of the project, including better algorithm selection, hyperparameter tuning, and improved feature investigation. 

# Simple Web Apps
### [Penguins Classifier](https://penguins-classify.herokuapp.com/)
A classifier using the [Palmer Penguin dataset](https://github.com/allisonhorst/palmerpenguins) developed by Allison Horst in R.
 - Use the 'User Input Features' menu in the browser window to select your penguin and watch the classifier predict the penguin type.

### [Iris Classifier](https://flower-classify.herokuapp.com/)
A classifier using the [Iris Dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-dataset)
 - Use the left-hand column to select your flower features and watch the classifier predict the flower type.

<!---### [Boston Housing Classifier](https://boston-classifier.herokuapp.com/)
A classifier using the [Boston Housing Dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#boston-dataset)
 - Use the left-hand column to select a house's features and watch the classifier predict the price.--->

### Non-Deployed Apps**
[View the Repository](https://github.com/tdraths/streamlit_projects)
Simple .py files that demonstrate how much can be done in just a few lines of code.
