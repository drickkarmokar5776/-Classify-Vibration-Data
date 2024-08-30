
# Project Title

A brief description of what this project does and who it's for
Machine Learning Model to Classify Vibration Data from 12 Different Machines


## Documentation

[Documentation](https://linktodocumentation)

Overview
This notebook demonstrates a complete workflow for processing and analyzing vibration data using machine learning techniques. The process includes data loading, preprocessing, dimensionality reduction, clustering, and classification.

Workflow
Data Loading and Preparation

Load raw vibration data from .dat files.
Convert the data into Pandas DataFrames.
Save the DataFrames to CSV files for further processing.
Normalization

Apply normalization to the data to ensure uniform scaling.
Save the normalized data to new CSV files.
Dimensionality Reduction

Load the normalized data and perform Principal Component Analysis (PCA).
Impute missing values and standardize features.
Save the PCA-transformed data to a CSV file.
Clustering

Perform k-Means clustering on the PCA-transformed data to create pseudo-labels.
Add these pseudo-labels to the DataFrame.
Classification

Split the data into training and testing sets.
Train a Support Vector Machine (SVM) classifier using the training data.
Evaluate the SVM model's performance using accuracy, confusion matrix, and classification report.
Evaluation

Assess the model's accuracy.
Visualize the confusion matrix to understand classification performance.
Generate a detailed classification report.
Data Files
Raw Data Files: .dat files containing raw vibration data.
Normalized Data Files: CSV files with normalized vibration data.
PCA Output File: CSV file containing PCA-transformed features.
Combined Scaled Data: CSV file containing all scaled data combined.
Dependencies
numpy
pandas
sklearn
seaborn
matplotlib
Ensure that you have the necessary Python packages installed to run the notebook successfully.

Usage
Data Preparation: Replace placeholder code with actual data loading and processing code specific to your dataset.
Normalization: Adjust normalization parameters as needed.
Dimensionality Reduction: Configure PCA to match your data’s feature set.
Clustering and Classification: Modify clustering and classification parameters based on your specific requirements.
This notebook provides a comprehensive pipeline for analyzing vibration data and can be adapted to various datasets and analysis needs.


 Results and Visualizations
 Accuracy:
The SVM model achieved an accuracy of 97.3%, surpassing the target accuracy of 96%. This indicates that the model is well-suited for the classification of vibration data.
 Confusion Matrix:
The confusion matrix provided insights into the model's classification performance across different machine states. It highlighted how well the model could distinguish between different machine conditions.
 Classification Report:
The classification report, including precision, recall, and F1-score for each class, offered a detailed view of the model’s strengths and areas for improvement.

