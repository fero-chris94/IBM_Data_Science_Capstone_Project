# IBM Data Science Capstone Project

Welcome to my IBM Data Science Capstone project repository! This comprehensive Readme provides an overview of the project structure, installation instructions, and an explanation of each component within the repository.

## Project Overview
This project is a capstone project for the IBM Data Science Professional Certificate. The goal of the project is to apply the skills and knowledge learned throughout the certificate program to a real-world data science problem.

The problem we addressed is the prediction of whether or not a SpaceX Falcon 9 rocket launch will be successful. I used a dataset of historical SpaceX rocket launches to train a machine learning model that can predict the probability of success for a new launch.

## Project Structure
The repository is organized as follows:

### Data Extraction:
The data for this project was collected from a variety of sources, including:

- The SpaceX API
- The NASA website
- The Kaggle dataset of SpaceX rocket launches

I used Python to scrape the SpaceX API and the NASA website to collect the data. I then cleaned and processed the data using Python and Pandas.

- 01_SpaceX_Data_Collection_with_API.ipynb: This Jupyter notebook demonstrates the process of data extraction using an API.
- 02_SpaceX_Webscraping.ipynb: This Jupyter notebook showcases the process of data extraction through web scraping.

### Data Wrangling:

- 03_SpaceX_Data_Wrangling.ipynb: This Jupyter notebook focuses on data cleaning, handling missing values, and transforming the data into a suitable format for further analysis.

### Exploratory Data Analysis (EDA):
I performed exploratory data analysis (EDA) to understand the data and identify any potential relationships between the features and the target variable (success/failure). I used matplotlib and seaborn to create visualizations of the data.

- 04_SpaceX_EDA_sql.ipynb: This Jupyter notebook showcases exploratory data analysis using SQL queries.
- 05_SpaceX_EDA_Data_Visualization.ipynb: This Jupyter notebook performs exploratory data analysis and visualizations to gain insights and understand the dataset.

### Interactive Analytics:

- 06_SpaceX_Interactive_Visual_Analytics_Folium.ipynb: This Jupyter notebook demonstrates interactive analytics using the Folium library for geospatial visualizations.
- 05_SpaceX_Interactive_Visual_Analytics_Plotly.py: This Jupyter notebook showcases interactive analytics and visualizations using the Plotly library.

### Machine Learning Model:
I built a machine learning model to predict the probability of success for a new SpaceX rocket launch. I experimented with a variety of machine learning algorithms, including logistic regression, decision trees, and random forests. The best performing model was a Decision Trees model with an accuracy of 87.7%.

I evaluated the performance of the machine learning model using a variety of metrics, including accuracy, precision, recall, and F1 score. I also performed a confusion matrix analysis to understand the types of errors that the model was making.

- 08_SpaceX_Machine_Learning_Prediction.ipynb: This Jupyter notebook focuses on applying machine learning algorithms to make predictions and solve the problem at hand.

### Results:

The machine learning model was able to predict the probability of success for a new SpaceX rocket launch with an accuracy of 87.7%. This means that the model was able to correctly predict whether or not a launch would be successful 87.7% of the time.

## Installation
To run the project, you will need to have Python and the following libraries installed:

- pandas
- matplotlib
- seaborn

- Clone this repository: git clone https://github.com/fero-chris94/IBM_Data_Science_Capstone_Project.git
Install the required dependencies by running pip install  or create a virtual environment and install the dependencies mentioned above.
Run the Jupyter notebooks in the specified order mentioned in the project structure to replicate the workflow.

## Conclusion
The results of this project show that it is possible to use machine learning to predict the success of SpaceX rocket launches. This information could be used by SpaceX to improve the safety of their launches and to reduce the cost of their operations.

Thank you for your interest in my project!
