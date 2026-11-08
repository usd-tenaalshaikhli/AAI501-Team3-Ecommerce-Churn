# Predicting Customer Churn in E-Commerce

This project is a part of the AAI-501 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).

**Project Status: Active**

## Installation
1. Clone this repository: `git clone https://github.com/usd-tenaalshaikhli/AAI501-Team3-Ecommerce-Churn.git`
2. Install the required packages: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Download the dataset from Kaggle (link below) and place it in the `data/` folder.
4. Open the notebooks in the `notebooks/` folder with Jupyter or Google Colab.

## Project Intro/Objective
The goal of this project is to predict which customers of an online retail business are likely to stop shopping with the company (churn), group customers into segments with different churn risk, and identify the customer characteristics most linked to churn. This can help a customer retention team find at-risk customers early and focus retention efforts where they matter most.

## Partner(s)/Contributor(s)
- Tena Alshaikhli
- Rishi Kapila
- Abhineet Sood

## Methods Used
- Exploratory data analysis and data visualization
- Data cleaning (missing values)
- Supervised learning: logistic regression, decision tree, random forest
- Hyperparameter tuning
- Unsupervised learning: k-means clustering
- Feature importance and feature selection
- Model evaluation: accuracy, precision, recall, F1 score, confusion matrix, ROC AUC

## Technologies
- Python
- pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

## Project Description
- **Dataset:** E-Commerce Customer Churn Analysis and Prediction (Kaggle): https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction
- **Size:** 5,630 customer records, 20 columns (customer ID, churn label, and about 18 features)
- **Variables:** customer information (gender, marital status, city tier, tenure), purchasing behavior (order count, preferred category, coupons used, payment method), engagement (hours on app, registered devices, days since last order), and satisfaction (satisfaction score, complaints, cashback)
- **Questions:** Which customers are most likely to churn? Which customer segments have the highest churn risk? Which features drive churn the most?
- **Analysis and modeling:** We compare three classification models, tune their parameters, use k-means to find customer segments, and test whether a simpler model with only the most important features performs nearly as well.
- **Challenges:** class imbalance (few customers churned), missing values, and explaining results in business terms.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Thank you to our instructors, Andrew Van Benschoten, Ph.D., and Dave Friesen, M.S., and to the creator of the Kaggle dataset.
