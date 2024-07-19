# Buenos Aires Housing Price Prediction Project

This project is focused on predicting housing prices in Buenos Aires based on various factors such as size, location, and neighborhood. The analysis is divided into several notebooks, each addressing different aspects of the prediction model.

## Notebooks Overview

1. **Prepare Data**
   - This notebook focuses on preparing the dataset for analysis. It includes data cleaning, handling missing values, and initial exploratory data analysis.
   - **Key Steps:**
     - Loading and inspecting the dataset.
     - Cleaning the data by removing outliers based on the surface area of the properties.
     - Visualizing the distribution of house sizes.

2. **Predicting House Price with Size**
   - This notebook explores the relationship between house size and price. Various regression models are applied to predict house prices based on the size of the property.
   - **Key Steps:**
     - Filtering the dataset for houses and removing null values.
     - Visualizing the correlation between property size and price.
     - Building and evaluating a linear regression model to predict house prices based on size.
   - **Visualizations:**
     - Histogram of house sizes.
     - Scatter plot of price vs. area.
     - Baseline and model predictions.

3. **Predicting House Price with Location**
   - This notebook investigates how the location of a property influences its price. It includes geographical analysis and visualization to understand location-based price variations.
   - **Key Steps:**
     - Wrangling the dataset to include geographical coordinates.
     - Merging data from multiple sources.
     - Building and evaluating a linear regression model to predict house prices based on location.
   - **Visualizations:**
     - Map visualization of property locations.
     - 3D scatter plots showing price variations with location.

4. **Predicting Price with Neighborhood**
   - This notebook delves into the impact of neighborhood characteristics on house prices. It examines socio-economic factors and other neighborhood-specific attributes.
   - **Key Steps:**
     - Extracting neighborhood information from the dataset.
     - One-hot encoding neighborhood data for modeling.
     - Building and evaluating a Ridge regression model to predict house prices based on neighborhood.
   - **Visualizations:**
     - Bar chart of feature importance for neighborhoods.

5. **Explore**
   - This notebook is dedicated to further exploratory data analysis, uncovering hidden patterns and insights within the dataset.
   - **Key Steps:**
     - Checking for missing values and dropping unnecessary columns.
     - Analyzing the multicollinearity between features.
   - **Visualizations:**
     - Heatmap of feature correlations.

6. **Predicting Price with Size, Location, and Neighborhood**
   - This comprehensive notebook combines size, location, and neighborhood factors to build a robust predictive model. It aims to provide a more accurate and holistic prediction of house prices.
   - **Key Steps:**
     - Wrangling and merging data from multiple sources.
     - Combining features for a comprehensive model.
     - Evaluating the performance of the combined model.

## Getting Started

To run these notebooks, you will need to have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- geopandas
- plotly
- category_encoders

## Data

The data used in this project includes various features such as:
- Property size (in square meters)
- Location (latitude and longitude)
- Neighborhood characteristics
- Socio-economic factors

## How to Use

1. Clone the repository.
2. Ensure you have all the necessary libraries installed.
3. Open each notebook in Jupyter Notebook or Jupyter Lab.
4. Run the cells sequentially to reproduce the analysis.

## Results

Each notebook provides detailed results and visualizations for the respective analysis. The final notebook combines all factors to give a comprehensive prediction model for housing prices in Buenos Aires.

## Conclusion

This project offers insights into the real estate market in Buenos Aires and demonstrates the application of various machine learning techniques for price prediction. By considering multiple factors, the models aim to provide accurate and reliable price estimates.

