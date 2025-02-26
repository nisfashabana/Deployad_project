# Deployad_project
## Project Overview
This project focuses on analyzing retail transaction data to extract insights into sales trends, customer behavior, and product performance. It includes data preprocessing, exploratory data analysis (EDA), customer segmentation, market basket analysis, sales forecasting, and churn prediction using machine learning techniques.

### Table of Contents	
 1.	Dataset Description
 2.	Key Analysis & Methodologies                                                                                                                                                                                    
    	•	Data Preprocessing
    	•	Exploratory Data Analysis (EDA)
    	•	Customer Segmentation
    	•	Market Basket Analysis
    	•	Sales Forecasting
    	•	Churn Prediction
 3.	Technologies Used
 4.	Results & Insights
 5.	How to Run the Project



Dataset Description

The dataset contains 30 columns, including:

  •	Transaction Details: Transaction ID, Date, Amount, Payment Type                                                                                                                                             
  •	Customer Demographics: Customer ID, Age, Gender, Location                                                                                                                                                  
  •	Product Information:  Category, Price, products,Segment                                                                                                                                                    
  •	Purchase Behavior: Frequency of purchases, Total spend, Returns                                                                                                                                             

Key Analysis & Methodologies                                                                                                                                                                                        
                                                                                                                                                                                                                    
1. Data Preprocessing                                                                                                                                                                                              

   •	Handled missing values and duplicates                                                                                                                                                                       
   •	Fixed inconsistent formats (e.g., date, price)                                                                                                                                                              
   •	Detected  outliers  ,Figured out fraudaulent Transactions                                                                                                                                                                 

2. Exploratory Data Analysis (EDA)

   •	Identified top-selling products & categories                                                                                                                                                                  
   •	Analyzed sales trends over time                                                                                                                                                                               
   •	Examined customer demographics


3. Customer Segmentation (RFM Analysis)

	 •	Recency (R): Days since last purchase                                                                                                                                                                           
	 •	Frequency (F): Total number of purchases                                                                                                                                                                        
	 •	Monetary Value (M): Total amount spent                                                                                                                                                                         
	 •	Clusters Identified: High-Value, Regular, One-Time Buyers                                                                                                                                                       

4. Market Basket Analysis (MBA)
 •	Used Apriori algorithm for association rule mining                                                                                                                                                              
	•	Discovered frequently bought-together items                                                                                                                                                                     
	•	Provided recommendations for cross-selling                                                                                                                                                                        

5. Sales Forecasting

	•	Applied ARIMA model for sales trend analysis
	•	Evaluated using Mean Absolute Error (MAE)

6. Churn Prediction

	•	Identified factors contributing to customer churn
	•	Built Logistic Regression model
	•	Achieved high accuracy in predicting at-risk customers

### Technologies Used

 •	Python (Pandas, NumPy, Scikit-learn, Statsmodels)
 
 •	Machine Learning (Logistic Regression)
 
 •	Market Basket Analysis (Apriori Algorithm)
 
 •	Time Series Forecasting ( ARIMA)
 
 •	Power BI (for dashboards and visualization)

### Results & Insights

 •	Top-selling products: Identified high-revenue items
 
 •	Customer Segmentation: High-value customers contribute significantly to revenue
 
 •	Market Basket Analysis: Discovered key product pairings for better recommendations
 
 •	Sales Forecasting: Achieved accurate predictions using ARIMA
 
 •	Churn Prediction: Identified key churn factors and high-risk customers

### How to Run the Project

1. Install Dependencies

pip install -r requirements.txt

2. Run Jupyter Notebooks

jupyter notebook

Open each notebook and execute the cells step by step.

3. View Power BI Dashboard

	•	Open retail_dashboard.pbix in Power BI to explore the interactive dashboard.

### Next Steps

 •	Improve sales forecasting accuracy by testing Prophet hyperparameters
 
 •	Implement a recommendation system using collaborative filtering
 
 •	Deploy the churn prediction model for real-time insights



   
