# Dataset Analysis

## Overview
This project involves analyzing a Facebook dataset to uncover patterns and insights. Various data analysis techniques and visualizations are used to provide a comprehensive understanding of the dataset. A custom linear regression model is implemented to predict the total interactions based on several features.

## Data
The dataset used in this project contains 500 entries and 19 columns, each representing different features of Facebook posts. The dataset is preprocessed and cleaned before analysis to ensure accurate results. Below are the main columns used for the analysis and some initial statistics:

### Key Columns Used
- `Page total likes`
- `Lifetime Post reach by people who like your Page`
- `like`
- `Lifetime People who have liked your Page and engaged with your post`
- `Total Interactions` (target variable)

### Removed Columns
- `Lifetime Post Total Reach`
- `Lifetime Post Total Impressions`
- `Lifetime Engaged Users`
- `Lifetime Post Consumers`
- `Lifetime Post Consumptions`
- `Lifetime Post Impressions by people who have liked your Page`
- `comment`
- `share`

### Dataset Information
- **Total Entries**: 500
- **Total Columns**: 19

## Methods
The analysis includes the following steps:

### Data Preprocessing
- **Data Cleaning**: Handling missing values by filling them with mean values of the respective columns.
- **Feature Selection**: Dropping unused columns to focus on relevant features.

### Data Transformation
- **Data Normalization**: Standardizing the features to have zero mean and unit variance.

### Modeling
- **Linear Regression Model**: Implementing a custom linear regression model with gradient descent to predict `Total Interactions`.
- **Train-Test Split**: Splitting the dataset into training and testing sets.
- **Gradient Descent**: Optimizing the model parameters using gradient descent.

### Evaluation
- **Error Metrics**: Calculating training and testing errors using Sum of Squared Errors (SSE).
- **Visualization**: Plotting the training and testing errors over epochs to visualize the model's learning process.

### Visualization
- **Libraries Used**: Using `matplotlib` for creating visual representations of the data and model performance.

## Results
The results section includes various plots and statistical summaries that highlight the key findings from the dataset. These visualizations help in understanding the relationships between different variables and the performance of the linear regression model.

### Key Plots
- **Training and Testing Errors**: Visualization of errors over epochs to evaluate the model's performance.
- **Cost Function**: Plot of the cost function over epochs to observe the convergence of the gradient descent.
- **Theta Parameters**: Visualization of the changes in theta parameters over epochs.

## Conclusion
The analysis provides valuable insights into the dataset and demonstrates the implementation of a custom linear regression model. The conclusions drawn can be used for further research or practical applications in social media analytics.

## Installing Libraries
To install the required libraries, use the following command:
```bash
pip3 install -r requirements.txt
