# Predicting Likes on Product Reviews Using Regression Models

## Project Overview
This project involves developing a machine learning model to predict the number of likes on product reviews for Yojo.com. Using a dataset of 28,000 reviews, the model utilized various textual features such as word count, sentiment, and subjectivity to forecast the popularity of reviews. After performing data cleaning, exploratory analysis, and feature engineering, several regression algorithms were tested. The model was evaluated based on Mean Absolute Error (MAE) performance, providing insights into how textual characteristics influence customer engagement.

## Objectives
- **Predict the number of likes** on product reviews based on textual features.
- **Apply regression techniques** to model and forecast the popularity of reviews.
- **Test different algorithms** and select the best-performing model based on MAE.

## Key Features
- **Textual Feature Engineering**: Extracted features like word count, sentiment, and subjectivity from the reviews.
- **Data Cleaning and Processing**: Handled missing values, normalized data, and performed exploratory analysis.
- **Regression Algorithms**: Tested various models such as Linear Regression, Decision Trees, and Random Forests, selecting the best model based on MAE.
- **Visualization**: Created graphs to compare model performance and visualize the correlation between features and likes.

## Tools & Technologies
- **Python**: Used for data processing, feature extraction, and modeling.
- **Jupyter Notebook**: For running and documenting the analysis.
- **scikit-learn**: Applied regression algorithms and evaluation metrics.
  
## Files Included
- **[Jupyter Notebook](./cossu_noorland_correct.ipynb)**: Contains the code for data cleaning, feature engineering, model training, and evaluation.
- **[Predictions CSV](./predictions_cossu_noorland.csv)**: The predicted number of likes for the reviews using the selected regression model.

## Dataset
The dataset includes 28,000 product reviews from Yojo.com, containing features such as:
- **Review Text**: The content of the review.
- **Number of Likes**: The dependent variable used to train the model.
- **Textual Features**: Word count, sentiment, and subjectivity scores extracted from the review text.
