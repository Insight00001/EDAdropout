# School Dropout Dashboard

This Streamlit application provides an Exploratory Data Analysis (EDA) dashboard for analyzing student dropout patterns. The app allows users to interact with various data visualizations, filter data, and perform statistical analysis to gain insights into factors contributing to student dropouts.
# Features
1. Data Overview: Displays the total number of students, including the breakdown by gender.
2. Categorical and Numeric Data Summaries: Provides summary statistics for both categorical and numerical data, 3. helping to understand data distribution and characteristics.
4. Filter Data: Allows users to filter categorical and numeric data based on selected features and values.
5. Data Visualization: Generate bar charts, histograms, scatter plots, and box plots for various features to explore relationships and distributions.
5. Correlation Analysis: Shows a heatmap of correlations between numeric features to identify potential relationships.
7. Principal Component Analysis (PCA): Visualizes data in 2D or 3D using PCA to identify key components affecting student outcomes.
8. Hypothesis Testing: Conducts chi-square tests to check dependencies between categorical variables and the target variable.
9. Percentage Distribution: Displays a pie chart showing the percentage distribution of selected categories.
# Requirements
1. Python 3.8+
2. Streamlit
3. Pandas
4. Plotly
5. Scikit-learn
6. SciPy
7. Numpy
# Installation
### clone the respository
git clone https://github.com/Insight00001/EDAdropout.git
cd your-repository
### install required packages
pip install -r requirements.txt
### Run
streamlit run app.py
# Usage
1. Navigate through the different sections using the selectbox to explore various analyses.
2. Select filters and visualize data to identify key insights related to student dropouts.
3. Perform statistical tests to understand the dependencies between variables.
# Project Structure
1. app.py: Main application file.
2. data/: Contains necessary CSV files used for data analysis and visualization.

# Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.
License

# This project is licensed under the MIT License.
