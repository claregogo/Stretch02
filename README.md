# Stretch02
Author: Zehui Li & Mujin Li
### Overview
This repo is for McCourt Intro to Data Science class Stretch_02, which focus on machine learning contains 4 exercise.

- **Exercise 01: set up**
   - In this exercise, we perform Principal Component Analysis (PCA) on U.S. Senate Votes data from Session 103 to Session 114.
   - The key steps including:
     -  **Analyze U.S. Senate Votes data from Session 103 to 114.** 
     -  **Replace missing values and filter data for Session 103.** 
     -  **Perform Principal Component Analysis (PCA) using the recipes package.**
     -  **Visualize voting patterns with scatterplots of PC1 and PC2.**
     -  **Demonstrates the use of PCA for data reduction and visualization.**

- **Exercise 02: K-Means Clustering of Senate Votes** 
   - Exercise 02 focuses on conducting cluster analysis on the Senate Votes data using K-Means clustering.
   - The key steps including:
     - **Perform cluster analysis on Senate Votes data.**
     - **Use K-Means clustering with 5-fold cross-validation and hyperparameter tuning.**
     - **Create a custom function for PCA and K-Means clustering.**
     - **Visualize clusters with scatterplots for different cluster numbers.**
     - **Highlights the application of clustering to discover voting behavior patterns.**

- **Exercise 03: Text Analysis of Executive Orders** 
   - Exercise 03 analysis text data from executive orders.
   - The key steps including:
     - **Analyze text data from executive orders.**
     - **Create bigrams from the text and filter out stop words.**
     - **Calculate TF-IDF for bigrams and presidents.**
     - **Illustrates text preprocessing, bigram analysis, and TF-IDF calculations.**

- **Exercise 04: Predicting Billing Outcome** 
   - Exercise 04 involves building a supervised machine learning model to predict whether bills passed or not.
   - The key steps including:
     - **Build a machine learning model to predict bill outcomes.**
     - **Preprocess text descriptions of Senate bills.**
     - **Split data into training and testing sets.**
     - **Create a recipe for text preprocessing, including tokenization and TF-IDF.**
     - **Train a logistic regression model and evaluate its performance.**
     - **Demonstrates text analysis and classification modeling for legislative data.**

### Project Description

1. `penalized lasso model`:
![penalized lasso model](lasso_plot.png){#fig-lasso_plot}

2. `random forest with hyperparameter tuning`:
![random forest](rf_plot.jpg){#fig-rf_plot}

3. `visualize the variable importance scores`:
![variable importance scores](rf_importance.png){#fig-importance_score}

### Reference

- [Tidy Modeling with R](https://www.tmwr.org/resampling)

- [tidytuesday: childcare costs](https://github.com/rfordatascience/tidytuesday/blob/master/data/2023/2023-05-09/readme.md)

- [Tidymodels: a predictive modeling case study](https://www.tidymodels.org/start/)

## Instructions:
1. Git clone the repo [Link](https://github.com/Freya-MJ/Assignment_08.git)
2. Install and load the packages: `tidyverse`, `tidymodels`, `recipes`, `patchwork`, `Rfast`, `tidytext`, `parsnip`, `snowballC`, `stopwords`, `gggraph`and `gutenbergr`.
3. Run the code in `index.qmd`


