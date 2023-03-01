# ANALYSIS AND PREDICTIONS OF CUSTOMER BEHAVIOR


 >  An approach to predict which customers are likely to unsubscribe from the services offered by the telecom company.


## Inference and analysis :

- The data consisited of 21 Features (Columns) and 7044 rows.
- Performed Univariate(Skewness, Kurtosis plots) and Bivariarate analysis to understand the data distribution and how the features are contributing to the customer churn.
- Pre-processed the data using methods like label encoding, one hot encoding, handling null values, dropping irrelevant columns.
- Visualising correlation matrix to understand which features are higly correlated. Below are the observations.
            - Internet service, Online security, Online Backup, DeviceProtection, Tech Support and streaming are highly correlated features.
            - Total charges and customer ID are also very correlated, maybe the ID is chosen according to high-potential customers.
            - The most correlated to churn : Senior, Partner, Multiple lines, online backup, Monthly charges.
- Trained machine learning algorithms like : Logistic Regression, Decision Trees, Support Vector Machines and achieved 84% accuracy with Logistic Regression model.

## Technical :
- Statictical analysis.
- Machine learning.
- Python (Pandas, sklearn, numpy, matplotlib, seaborn)
- Jupyter Notebook.

## Installation
1. Install Anaconda navigator (MacOS) - https://docs.anaconda.com/anaconda/install/mac-os/.
                              (Windows) - https://docs.anaconda.com/anaconda/install/windows/    
2. It will install python if not present on the system.
3. Open Anaconda navigator > Open Jupyter notebook > Make a pull request to me and then open the notebook once it is on your machine and continue developing.

> Happy Learning and Developing : 😄 😄 
