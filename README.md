# 🚕 Ola Bookings Data Analysis

## 📌 Overview

This project analyzes Ola ride booking data to uncover trends, patterns, and actionable business insights. The analysis focuses on booking performance, revenue distribution, customer behavior, and operational efficiency using Python and Power BI.

## 🎯 Objectives

* Analyze overall booking and revenue performance  
* Identify cancellation patterns and operational issues  
* Compare revenue across different vehicle types  
* Understand customer payment preferences  
* Evaluate customer and driver ratings  

## 🛠️ Tech Stack

* Python (Google Colab)  
* Pandas, NumPy  
* Power BI (Dashboard Visualization)  

## 📂 Dataset

The dataset contains ~100K+ Ola ride booking records with the following features:

* Date & Time of booking  
* Booking Status (Success, Cancelled, etc.)  
* Vehicle Type  
* Pickup & Drop Locations  
* Booking Value (Revenue)  
* Ride Distance  
* Payment Method  
* Customer & Driver Ratings  
* Cancellation Reasons  

## ⚙️ Data Preparation

* Handled missing values and removed irrelevant columns  
* Standardized categorical data (e.g., cancellation labels)  
* Converted data types for analysis (date, numeric fields)  
* Prepared dataset for BI dashboard integration  

## 📊 Key Insights

* Majority of rides are successfully completed  
* Significant cancellations indicate operational challenges  
* Revenue is distributed across multiple vehicle categories  
* Digital payments (UPI, cards) dominate transactions  
* Revenue trends fluctuate over time, indicating varying demand  

## 📈 Dashboard Features

* KPI Cards: Total Bookings, Revenue, Distance, Ratings, Cancellations  
* Booking Status Distribution  
* Revenue by Vehicle Type  
* Payment Method Analysis  
* Revenue Trend (Line Chart)  
* Interactive Filters (Date, Vehicle Type, Booking Status)

## ▶️ How to Run

1. Clone the repository  
2. Open the Jupyter Notebook / Colab file  
3. Install required libraries:
   ``` bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Run the analysis notebook
5. Open Power BI file (.pbix) to view dashboard
