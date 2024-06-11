# Mortgage-Based-Securities-Analysis-and-Prediction

## Project Objective:
The goal is to utilize machine learning models to forecast the prepayment risk associated with mortgage-backed securities.

## What is Prepayment risk?
1. Prepayment risk is when people pay back a loan earlier than expected.
1. When they do this, they don't have to pay interest anymore on the part they've paid back.
1. So, if the loan is paid off early, investors won't get any more interest on those bonds.
1. It's important to check this risk with mortgage-backed securities (MBS).

That's what our project is all about.

## About Dataset
* The dataset is sourced from the official portal of Freddie Mac for home loans.
* It comprises 291,452 data points and 28 columns or parameters representing various features of the data.
* The columns include features such as CreditScore, FirstPaymentDate, FirstTimeHomebuyer, MaturityDate, MSA (Metropolitan Statistical Area), MIP (Mortgage Insurance Premium), Units, Occupancy, OCLTV (Original Combined Loan-to-Value Ratio), DTI (Debt-to-Income Ratio), OrigUPB (Original Unpaid Principal Balance), LTV (Loan-to-Value Ratio), OrigInterestRate, Channel, PPM (Prepayment Penalty Mortgage), ProductType, PropertyState, PropertyType, PostalCode, LoanSeqNum, LoanPurpose, OrigLoanTerm, NumBorrowers, SellerName, ServicerName, EverDelinquent, MonthsDelinquent, and MonthsInRepayment.
* The data provides detailed information about each loan, including borrower characteristics, loan terms, property details, and loan performance indicators.

* **Below are descriptions of some features found in the dataset:**

    1. **CreditScore**: The credit score of the borrower.
    2. **FirstPaymentDate**: The date of the first payment on the mortgage.
    3. **FirstTimeHomebuyer**: A binary indicator (Y/N) indicating whether the borrower is a first-time homebuyer.
    4. **MaturityDate**: The date when the mortgage matures.
    5. **MSA (Metropolitan Statistical Area)**: A code representing the metropolitan statistical area where the property is located.
    6. **MIP (Mortgage Insurance Premium)**: The mortgage insurance premium amount.
    7. **Units**: The number of units in the property (e.g., single-family, multi-family).
    8. **Occupancy**: The occupancy status of the property (e.g., Owner-occupied, Investment property).
    9. **OCLTV (Original Combined Loan-to-Value Ratio)**: The original combined loan-to-value ratio at the time of origination.
    10. **DTI (Debt-to-Income Ratio)**: The debt-to-income ratio of the borrower.
    11. **OrigUPB (Original Unpaid Principal Balance)**: The original unpaid principal balance of the mortgage.
    12. **LTV (Loan-to-Value Ratio)**: The loan-to-value ratio of the mortgage.
    13. **OrigInterestRate**: The original interest rate of the mortgage.
    14. **Channel**: The channel through which the mortgage was originated (e.g., Retail, Broker).
    15. **PPM (Prepayment Penalty Mortgage)**: A binary indicator (Y/N) indicating whether the mortgage has a prepayment penalty.
    16. **ProductType**: The type of mortgage product (e.g., Fixed-rate Mortgage, Adjustable-rate Mortgage).
    17. **PropertyState**: The state where the property is located.
    18. **PropertyType**: The type of property (e.g., Single-family, Condo).
    19. **PostalCode**: The postal code of the property location.
    20. **LoanSeqNum**: A unique identifier for the loan sequence.
    21. **LoanPurpose**: The purpose of the loan (e.g., Purchase, Refinance).
    22. **OrigLoanTerm**: The original term of the loan in months.
    23. **NumBorrowers**: The number of borrowers on the mortgage.
    24. **SellerName**: The name of the seller of the mortgage.
    25. **ServicerName**: The name of the servicer handling the mortgage.
    26. **EverDelinquent**: A binary indicator (0/1) indicating whether the mortgage has ever been delinquent.
    27. **MonthsDelinquent**: The number of months the mortgage has been delinquent.
    28. **MonthsInRepayment**: The number of months the mortgage has been in repayment.

### First Tasks Document:
You need to perform Data Preprocessing and Labelling individually on the available datasets mentioned in the above link.

1. Data Cleaning
2. Data Encoding
3. Data Labelling 

### Second Tasks Document:
next task in our ongoing project, which involves performing Exploratory Data Analysis (EDA) on the preprocessed data sets discussed in our recent meeting. The task breakdown is as follows:

Tasks: EDA(Exploratory Data Analysis):
1. Univariate Analysis.
2. BiVariate Analysis
3. Multivariate Analysis

You need to perform EDA (Exploratory Data Analysis) on the available prepared and preprocessed dataset as mentioned in the last Meeting.

Here's a step-by-step guide to perform exploratory data analysis (EDA) followed by univariate, bivariate, and multivariate data analysis on the given features:

1. Exploratory Data Analysis (EDA):
   - Start by loading the dataset and examining the first few rows to understand its structure and contents.
   - Check for missing values in each feature and handle them appropriately (e.g., imputation or removal).
   - Compute summary statistics (mean, median, min, max, standard deviation, etc.) for numerical features.
   - Visualize the distributions of numerical features using histograms or kernel density plots.
   - Explore the distribution of categorical features using bar plots or pie charts.
   - Check for outliers in numerical features using box plots or scatter plots.

2. Univariate Data Analysis:
   - For each numerical feature (CS, MIP, Units, OCLTV, DTI, OrigUPB, LTV, OrigInterestRate, OrigLoanTerm, EverDelinquent, MonthsDelinquent, MonthsInRepayment), analyze its distribution using histograms, kernel density plots, and summary statistics.
   - For each categorical feature (IsFirstTime, CreditRange, LTV_range, Repay_range), analyze the frequency distribution using bar plots or pie charts.

3. Bivariate Data Analysis:
   - Explore the relationship between pairs of numerical features using scatter plots or pair plots (for small subsets of features).
   - Compute correlation coefficients (e.g., Pearson, Spearman) between pairs of numerical features to quantify their linear relationship.
   - Investigate the relationship between numerical and categorical features using box plots or violin plots.

4. Multivariate Data Analysis:
   - Utilize techniques like heatmap or correlation matrix to visualize the correlation structure among all numerical features.
   - Perform dimensionality reduction techniques such as PCA (Principal Component Analysis) to identify important combinations of features.
   - Explore interactions between multiple features using 3D plots or parallel coordinates plots.

5. Additional Analysis (Optional):
   - Conduct hypothesis testing to compare groups or assess relationships between features.
   - Implement machine learning models (e.g., regression, classification) to predict or classify target variables based on the given features.
   - Validate findings through cross-validation or bootstrapping techniques.

6. Conclusion and Insights:
   - Summarize key findings from the analysis, including any patterns, trends, or relationships observed.
   - Provide insights or recommendations based on the analysis results, which could inform future decision-making or further investigation.

