# Online_Retail
## Introduction
The Online Retail dataset contains over 500,000 transactions from a UK-based online retailer, spanning December 2010 to December 2011. Each row represents a product purchased as part of an invoice, with details on product, quantity, price, customer, and country. This report provides a diagnostic analysis of the Online Retail dataset, focusing on explaining key patterns and anomalies identified during exploratory and descriptive analysis. The analysis investigates sales peaks, high returns, outlier customers/orders, and correlations among key variables.
## overview
The Online Retail dataset contains over 500,000 transaction records from a UK-based online retailer, covering December 2010 to December 2011. After cleaning, the dataset includes 524,878 transactions, 4,026 unique products, 4,338 unique customers, and 38 countries. 

## Key Metrics
The top 10 products account for a significant share of sales volume and revenue. 
The top 10 customers contribute a large portion of total revenue. 
The UK is the dominant market, followed by a few other European countries. 
About 65% of customers are repeat buyers, indicating strong customer retention. 
Sales show clear monthly seasonality, peaking in November and December (holiday season). 
Returns (negative quantities) are significant and concentrated among certain products and customers. 
Outlier orders and customers exist, indicating possible fraud, data entry errors, or wholesale activity.

## skills and concept demostrated
### Data Cleaning & Preparation
Identified and handled missing values appropriately (e.g., dropped nulls in product descriptions, retained nulls in CustomerID for non-customer analyses).
Removed duplicate records to ensure data integrity.
Filtered out invalid transactions (e.g., negative or zero quantities, non-positive prices).
Engineered new features such as TotalPrice for deeper analysis.
### Exploratory Data Analysis (EDA)
Computed and interpreted descriptive statistics (mean, median, quantiles, etc.).
Visualized data distributions using histograms and log scales to handle skewness.
Detected and visualized outliers using percentile thresholds and IQR.
Aggregated and grouped data by product, customer, country, and time for pattern discovery.
Analyzed time series trends at monthly, weekly, and daily levels.
### Data Visualization
Created bar plots, line plots, and histograms to communicate key findings.
Used visual cues (e.g., color, log scale, vertical lines) to highlight outliers and trends.
Decomposed time series into trend, seasonality, and residuals for deeper insight.
### Statistical Analysis
Performed group comparisons using t-tests and Mann-Whitney U tests.
Conducted chi-square tests to assess independence between categorical variables.
Calculated Pearson correlation coefficients to explore relationships between variables.
Tested for normality using the Shapiro-Wilk test.
Detected statistical outliers using the IQR method.
Quantified distribution shape with skewness and kurtosis.
### Customer Analytics
Conducted RFM (Recency, Frequency, Monetary) analysis for customer segmentation.
Scored and segmented customers for targeted marketing and retention strategies.
### Predictive Analytics & Machine Learning
Built and evaluated supervised learning models (logistic regression, random forest) for predicting repeat buyers and high-value customers.
Engineered advanced features (e.g., basket size, seasonality, first order value) to improve model performance.
Assessed model performance using ROC AUC and classification reports.
Applied unsupervised learning (KMeans clustering) for customer and product segmentation.
Detected anomalies using Isolation Forest and deep learning autoencoders.
Implemented association rule mining (apriori algorithm) for product recommendations.
Built collaborative filtering models for personalized product recommendations.
### Prescriptive Analytics
Translated analytical insights into actionable business recommendations (inventory management, customer retention, cross-selling, anomaly monitoring, etc.).
### Reporting & Communication
Summarized findings in clear, actionable language for business stakeholders.
Generated professional Word reports with tables, charts, and recommendations.
Provided code and documentation for reproducibility and transparency.
## visualization and analysis
[downoad](http://localhost:8888/lab/tree/Untitled49.ipynb)
## Analysis
### Sales & Orders 
Total sales: ~£8 million (after cleaning) 
Median order value: £9.92 
Median unit price: £2.08 
Median quantity per order line: 4 
### Top Contributors 
Top 10 products account for a large share of sales. 
Top 10 customers contribute a significant portion of revenue. 
UK is the dominant market, followed by a few European countries. 
### Customer Behavior 
Repeat buyers: ~65% of customers made more than one purchase. 
Customer segmentation: RFM analysis can identify VIPs and at-risk customers. 
### Time Trends 
Sales peak in November and December (holiday season). 
Monthly and weekly seasonality is evident. 
### Returns 
Returns (negative quantities) are significant and concentrated among certain products and customers. 
### Anomalies 
Outlier orders and customers exist, indicating possible fraud, data entry errors, or wholesale activity. 

### Recommendations and Conclusions
Focus on bestsellers and VIP customers for targeted marketing. 
Prepare for seasonality by adjusting inventory and promotions. 
Investigate high-return products and customers to reduce costs. 
Leverage cross-selling by promoting frequently bought-together items. 
Monitor anomalies for fraud and data quality. 
