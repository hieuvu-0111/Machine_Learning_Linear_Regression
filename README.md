# Linear regression {-}

This notebook is adapted from a Machine Learning course assignment aiming to familiarize students with the use of Linear Regression model supported by scikit-learn. Particularly:

1.  **Coding Tasks:**

    1.1 Analyze the dataset using libraries like Pandas and Matplotlib.  
    1.2 Preprocess the data for modeling.  
    1.3 Divide the data into training and test sets with a suitable ratio (e.g., 80/20) to ensure unbiased model evaluation.  
    1.4 Train a Linear Regression model on the training set.    
    1.5 Evaluate the model performance on the test set.  

2.  **Open discussion questions:**

    2.1 Does income or income stability have a stronger influence on the loan sanction amount? For example, analyze the data to see if a higher income or a "High" income stability rating leads to a greater loan approval amount.  
    2.2 Is there a significant difference in loan amounts based on property location? For example, compare the average loan amounts for properties in rural, urban, and semi-urban locations.  
    2.3 Is there a gender bias in loan approvals? For example, investigate if there is a difference in average loan amounts offered to male and female applicants.  
    2.4 Are there any new features you could create from the existing data (e.g., loan-to-value ratio) that might be useful for analyzing loan amounts?  
    2.5 Beyond loan amount prediction, what other insights can be extracted or predicted from this dataset? For example, explore possibilities of using the data to understand borrower behavior, property market trends, or develop targeted marketing strategies.  


The dataset we will be working on is 'house-loan.csv'. It is composed of attributes such as gender, age, income, etc. This dataset is to predict the loan amount for which a customer can request a bank with his/her collateral house.

