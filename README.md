# Intro-to-Data-Science-Project
Human Activity Recognition using Sensor Data
This project analyzes and models human activity data collected from wearable sensors. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, and the application of machine learning algorithms for classification and clustering.

Project Steps
Loading Libraries and Dataset
The notebook uses Python libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn. The dataset (WISDM_.csv) is loaded for analysis.

Data Cleaning

Checks for missing values and removes rows with missing sensor readings.
Removes duplicate entries.
Drops unnecessary columns (e.g., User_ID).
Converts sensor data to numeric format and standardizes the features.
Exploratory Data Analysis (EDA)

Visualizes acceleration data (X, Y, Z) for different activities over time.
Computes and displays statistical summaries (mean, median, standard deviation) for each activity.
Calculates the magnitude of the acceleration vector for further analysis.
Model 1: K-Nearest Neighbors (KNN) Classification

Splits the data into training and testing sets.
Trains a KNN classifier to predict activity labels based on sensor data.
Evaluates the model using accuracy, precision, recall, and confusion matrix.
Visualizes model performance for different values of K.
Model 2: K-Means Clustering

Applies K-Means clustering to group sensor data without using activity labels.
Compares the resulting clusters to the true activity labels using a confusion matrix.
Analyzes cluster centroids to understand the grouping of activities.
Key Features
End-to-end data science workflow: from raw data to model evaluation.
Visualizations for both data exploration and model results.
Demonstrates both supervised (KNN) and unsupervised (K-Means) learning approaches.
