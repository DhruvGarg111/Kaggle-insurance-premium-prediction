##Predicting Insurance Premiums using K-Nearest Neighbors (KNN)

This repository contains the code and methodology for a Kaggle competition project to predict insurance premiums using the K-Nearest Neighbors (KNN) algorithm from the scikit-learn library.

##Project Overview

Insurance premium prediction is a crucial task in the insurance industry, where accurate estimates can help companies better manage risks and profits. This project focuses on using historical customer data to predict the premium amount for new customers based on various features such as age, income, and other demographic details.

##Dataset

The dataset for this project is sourced from a Kaggle competition. It contains the following key features:

Age: Customer's age.

Gender: Male or Female.

Region: The geographical region of the customer.

Annual Income: Customer's yearly income.

Health Conditions: Categorical/boolean values indicating pre-existing conditions.

Premium Amount: Target variable representing the annual insurance premium.

##Data Preprocessing

Handling Missing Values: Missing data was imputed with mean, median and most frequent in case of categorical data.

Encoding Categorical Variables: One-hot encoding was used for categorical features.

Feature Scaling: Standardization was applied to ensure features are on the same scale for KNN.

##Model

K-Nearest Neighbors (KNN)

The KNN algorithm was chosen for its simplicity and effectiveness in solving regression problems with a small to medium-sized dataset.

Key Parameters:

n_neighbors: Number of neighbors to consider.

