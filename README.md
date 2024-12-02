# Credit_Card_Fraud_Detect_ML

# DATASET - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
![cc_fraud](https://github.com/user-attachments/assets/066a94ec-a71d-43ab-b9d5-e33861b53673)


# Credit_Card_fraud_detect_ML 
 - As part of my master’s capstone project, our two-member team focused on advising two investors, Mr.
Patrick Jyengar and Mr. Peter Jyengar, by creating personalized stock portfolios based on their financial
goals.
### 1. Client Needs:
 - Mr. Patrick Jyengar: A conservative investor aiming to maintain his post-retirement lifestyle. He
planned to invest $500K in equities, expecting to double his capital in 5 years with minimal risk.
 - Mr. Peter Jyengar: A risk-tolerant investor seeking high returns for his company's expansion. He
aimed to invest $1M in high-margin stocks to maximize returns within 5 years.
### 2. Data Utilized:
We worked with 10 years of stock data (2010–2020) for 24 companies across various industries and the
S&P 500 index as a benchmark.
### 3. Key Tasks:
 - Loaded and merged stock data into a single dataset.
 - Explored the data through visualizations to understand stock trends, returns, and risks.
 - Analyzed stocks using technical metrics, identifying those that fit each investor's profile.
### 4. Portfolio Construction:
 - For Mr. Patrick, we selected stable, low-risk stocks with consistent returns.
 - For Mr. Peter, we focused on high-growth stocks with strong historical performance and potential for
high returns.
### 5. Validation:
We forecasted future stock performance using historical data and active investment strategies to ensure
the portfolios met their respective financial goals.
The final deliverables included a cleaned dataset, a detailed Jupyter Notebook with analysis, and visual
dashboards to summarize insights for each investor.

### It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

### Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.



