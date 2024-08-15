# Analysis-and-Modeling

Housing Price Prediction

Project Overview

This project aims to predict housing prices in California using various machine learning models. By leveraging feature engineering, hyperparameter tuning, and evaluating different models, we identify the most effective approach for predicting median house values based on features such as location, demographics, and housing characteristics.

Requirements

    Python 3.7+
    Libraries:
        pandas
        numpy
        scikit-learn
        matplotlib
        seaborn
        tensorflow (if you experiment with neural networks)

Data

The dataset used for this project is the California Housing Prices dataset, which includes various features such as:

    longitude, latitude: Geographical coordinates.
    housing_median_age: The median age of houses in the area.
    total_rooms, total_bedrooms: Total number of rooms and bedrooms.
    population, households: Population and number of households in the block.
    median_income: Median income of households.
    median_house_value: The target variable, representing the median house value.

Notebooks

    CaliforniaHousingProject_01.ipynb: Initial exploration of the data, including visualization and statistical analysis, and Feature Engineering to enhance model performance (Creation of new features like BedroomsPerRoom and RoomsPerHousehold). 
    CaliforniaHousingProject_02.ipynb: Implementation and evaluation of different models, including Linear Regression, Random Forest, and Neural Networks. Hyperparameter tuning using GridSearchCV. Final model selection and conclusions. 

Results

The most effective model for predicting housing prices was Random Forest. Key findings include:

    Feature engineering significantly improved model performance, particularly the BedroomsPerRoom ratio.
    Traditional models, like Random Forest, outperformed more complex neural networks, likely due to the dataset size and complexity.
    The best model achieved an R² of of above 80% on the test set.

Acknowledgements

    Source of the dataset: Kaggle 

    
    
