
# Finance Data Analysis Project

This project aims to analyze a personal loan dataset using various data analysis and machine learning techniques. The analysis includes data cleaning, visualization, feature engineering, and building predictive models to identify potential customers who may opt for a personal loan.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis and Visualizations](#analysis-and-visualizations)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project involves a comprehensive analysis of personal loan data. It includes importing data, cleaning, exploring, and visualizing it to gain insights. The goal is to build predictive models that can identify customers who are likely to take a personal loan.

## Dataset
The dataset used in this project contains information about customers and their loan status. The features include:
- Age
- Experience
- Income
- Family
- CCAvg (Average spending on credit cards)
- Education
- Mortgage
- Personal Loan (Target variable)
- Securities Account
- CD Account
- Online
- CreditCard

## Installation
To run this project, ensure you have Python installed. Then, install the necessary libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib plotly scikit-learn
```

You can also install the libraries from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/your-username/finance-data-analysis.git
cd finance-data-analysis
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook Finance_Data_Analysis_Project.ipynb
```

3. Run the cells in the notebook to see the analysis and visualizations.

## Analysis and Visualizations
The notebook includes detailed exploratory data analysis (EDA) with visualizations such as histograms, box plots, scatter plots, and heatmaps. These help in understanding the distribution of data and relationships between features.

## Machine Learning Models
The project includes the implementation of various machine learning models to predict personal loan approval:
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
- XGBoost

Model evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC are used to assess model performance.

## Results
The results of the analysis and machine learning models are documented in the notebook. The models are compared based on their performance metrics, and the best-performing model is selected for deployment.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a pull request






