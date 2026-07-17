
🛒 E-Commerce Recommendation System using Apache Spark & Databricks
📌 Project Overview
This project demonstrates an end-to-end E-Commerce Recommendation System built using Apache Spark, Databricks, and the Medallion Architecture (Bronze, Silver, Gold). It processes customer purchase data, performs large-scale analytics, generates personalized product recommendations using the ALS (Alternating Least Squares) algorithm, and visualizes business insights through an interactive Databricks Dashboard.

The project combines Data Engineering, Big Data Analytics, Machine Learning, Structured Streaming, and Business Intelligence into a single workflow.

🚀 Features
Data ingestion using Apache Spark
Medallion Architecture (Bronze → Silver → Gold)
Data cleaning and transformation
Spark SQL analytics
Customer purchase analysis
Real-time Structured Streaming simulation
Product recommendation using ALS Collaborative Filtering
Interactive Databricks Dashboard
Business KPI visualization
🛠️ Technology Stack
Category	Technologies
Language	Python
Big Data	Apache Spark, Spark SQL
Platform	Databricks
Streaming	Structured Streaming
Machine Learning	Spark MLlib (ALS)
Architecture	Medallion Architecture
Visualization	Databricks Dashboard
Dataset	Instacart Online Grocery Shopping Dataset
📂 Project Workflow
Raw Dataset
      │
      ▼
 Bronze Layer
 (Raw Data Storage)
      │
      ▼
 Silver Layer
 (Data Cleaning & Transformation)
      │
      ▼
 Gold Layer
 (Business Ready Tables)
      │
      ├───────────────┐
      ▼               ▼
 Spark SQL        ALS Recommendation
 Analytics           Engine
      │               │
      └───────┬───────┘
              ▼
 Databricks Dashboard
📊 Dashboard Highlights
The dashboard provides interactive business insights including:

Total Customers
Total Products
Total Orders
Total Departments
Top 10 Trending Products
Purchases by Department
Orders by Day of Week
Orders by Hour of Day
Purchase Activity Heatmap
Top 5 Recommended Products (ALS)
🤖 Recommendation System
The recommendation engine uses the Alternating Least Squares (ALS) algorithm from Spark MLlib.

Input
User ID
Product ID
Purchase Interaction
Output
Personalized Top-N Product Recommendations
Predicted Preference Score
⚡ Structured Streaming
A purchase producer simulates incoming customer purchases.

The streaming pipeline:

Reads real-time purchase events
Aggregates product purchases
Updates trending products
Stores results for analytics
Feeds dashboard visualizations
📁 Project Structure
E-Commerce-Recommendation-System/

│
├── notebooks/
│   ├── 01_Data_Analysis.ipynb
│   ├── 02_Medallion_Architecture.ipynb
│   ├── 03_EDA_By_SparkSQL.ipynb
│   ├── 04_ALS_Recommendation.ipynb
│   ├── 05_Recommendation_Generation.ipynb
│   ├── 06_Structured_Streaming.ipynb
│   └── 07_Purchase_Producer.ipynb
│
├── dashboard/
│
├── README.md
└── requirements.txt
📈 Business Insights
The project helps answer questions such as:

Which products are purchased most frequently?
Which departments generate the highest sales?
At what time do customers place the most orders?
Which day of the week has the highest purchasing activity?
What products should be recommended to each customer?
🎯 Future Improvements
Deploy recommendation engine as an API
Real-time Kafka streaming integration
User authentication
Product recommendation web application
Incremental model retraining
Cloud deployment using Azure or AWS
👤 Author
Lavanya Peesa

Data Science Graduate | Apache Spark | Databricks | Machine Learning | Data Engineering
