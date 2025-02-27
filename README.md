# EDA-for-Cuisine_Ratings
This repository showcases my first exploratory data analysis (EDA) project on a cuisine ratings dataset. The dataset, sourced from Kaggle, contains ratings and information about various cuisines.

link : https://www.kaggle.com/datasets/surajjha101/cuisine-rating.

Overview:
 - This Jupyter Notebook, titled cuisine_rating_EDA_final.ipynb, conducts an Exploratory Data Analysis (EDA) on a cuisine rating dataset. The primary objective is to analyze various factors influencing food ratings and to visualize the relationships between different variables.
Table of Contents
 - Introduction
 - Data Import
 - Data Exploration
 - Data Visualization
 - Conclusion

1. Introduction:
 - The notebook aims to explore the cuisine rating dataset, which includes user demographics and their corresponding ratings for different cuisines. This analysis will help in understanding patterns and trends related to cuisine preferences.

2. Data Import:
 - The necessary libraries for data manipulation and visualization are imported at the beginning of the notebook:
python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

The dataset is downloaded using Kaggle's API, and the path to the dataset files is printed for reference:
python

import kagglehub
path = kagglehub.dataset_download("surajjha101/cuisine-rating")
print("Path to dataset files:", path)

4. Data Exploration:
 - The dataset consists of various features, including user demographics (e.g., age, gender, marital status) and their ratings for food and service quality. Key statistics are computed to summarize the data:
Count of unique users and cuisines.
Mean ratings for food, service, and overall experience.
The notebook includes several code cells that display the first few rows of the dataset and provide statistical summaries.

5. Data Visualization:
 - Visualizations are created using Matplotlib and Seaborn to illustrate relationships between different variables. This includes:
Histograms of ratings.
Box plots comparing ratings across different cuisines.
Heatmaps showing correlations between various features.
python

6. Conclusion:
 - This notebook provides insights into how different factors affect cuisine ratings. The visualizations help in identifying trends that can inform restaurant owners and marketers about consumer preferences.
Requirements

To run this notebook, ensure you have the following Python libraries installed:
NumPy
Pandas
Matplotlib
Seaborn

License:
This project is licensed under the MIT License - see the LICENSE file for details. Feel free to modify this README as necessary to better suit your project's needs before uploading it to GitHub.
