# Data Science Portfolio

My name is Fakhri Nurrahmadi. I am an aspiring Data Scientist. I am currently re-learning relational database, statistical analysis tools, data visualization, machine learning modelling. You can find me on:
- [LinkedIn](https://www.linkedin.com/in/fnurrahmadi/)
- [Kaggle](https://www.kaggle.com/hidious)
- [GitHub](https://github.com/fnurrahmadi)
- Or directly email me at fnurrahmadi@gmail.com

This repository is created to store the projects I have completed with Python in hopes of building a solid Data Science portfolio. Each folder in this repository contains a separate project. I am thrilled to continue stacking more projects here as I am driven by my will to learn and improve 😊

# [Projects](https://github.com/fnurrahmadi/data-science-portfolio)

## [Project 1: Telco Customer Churn](https://github.com/fnurrahmadi/FN-Repo/tree/main/Telco%20Customer%20Churn)
- Predicting customer churn using a classification model and developing a retention program
- Handling missing data and fixing data types of categorical and numerical features
- Exploring data and making analysis based on the features with respect to churn
- Encoding categorical data, scaling numerical data, and treating data imbalance
- Selecting features mainly based on the rankings generated by Boruta
- Tuning parameters of Random Forest Classifier to improve prediction
- Measuring the distance of a customer's data point (tenure and charge per year) to find the maximum discount amount to be given

![line of best fit with data points](https://raw.githubusercontent.com/fnurrahmadi/data-science-portfolio/edd9f521ac68ccb43fa36fc4ac00994bf0cdc4f3/Telco%20Customer%20Churn/img/output_159_1.png)

In the graph above, a line of best fit is plotted based on the overall tenure in years and charges per year. To find the maximum amount that can be given to a customer, we can find the distance between the charges per year of the customer and the charges on the line of best fit at a particular tenure. A positive distance indicates that the maximum amount of discount we can give them. Meanwhile, a negative distance indicates that the customer is not profitable for retention and their value is less than the overall customers.
