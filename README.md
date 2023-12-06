# Predicting Energy Consumption: A Comparative Analysis of Regression Models
**Authors: Raj Kunamaneni, Anant Vishwakarma, Bobby Missirian**

### Introduction
This GitHub repository contains the code and documentation for the Kaggle competition "Predicting Energy Consumption: A Comparative Analysis of Regression Models." Predictive analytics, especially in energy consumption forecasting, is critical in various industries. This project focuses on evaluating the performance of different regression models using the Kaggle dataset from the "Predict Energy Behavior of Prosumers" competition.

### Repository Structure
```
code/: Contains the implementation of various regression models, including CatBoost, ExtraTrees, HistGradientBoosting, KNeighbors, and the proposed Regressive Neural Network.
data/: Stores the Kaggle dataset with gas prices, electricity prices, forecast weather, and other relevant metrics.
results/: Holds the results of the model evaluations, including MAE comparisons.
```

### Usage
Best to run on the Kaggle Competition website. The following instructions are for running locally. 

Clone the Repository:

```bash
git clone https://github.com/rajkunamaneni/Energy-Behavior-of-Prosumers.git
cd code/
```
 - Run Regression Models: Navigate to the code/ directory and run the scripts for different regression models.
 - Explore Results: Check the results/ directory for performance metrics and visualizations.

### Results and Discussion
The performance comparison of various regression models, as outlined in the results, is available in the results/ directory. The chosen metrics include Mean Absolute Error (MAE) for accurate model comparison.

### Future Directions
Explore refining the neural network architecture, exploring ensemble methods, and investigating additional variables for inclusion in the dataset.
