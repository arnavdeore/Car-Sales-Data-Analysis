<h1 align="center"> <b> Car-Sales-Data-Analysis </b> </h1>
<p align="center"> <img src="https://cdn.dribbble.com/userupload/23462936/file/original-f64595c0c5eea8cfc1cfd50c5e713796.gif" width="600"> </p>

In today's competitive automotive industry, tracking and analyzing sales performance is crucial for sustainable growth. This project focuses on developing a comprehensive and interactive Car Sales Dashboard using Power BI to empower the car dealership with data-driven decision-making. The dashboard provides real-time 
    insights into Key Performance Indicators (KPIs) related to car sales, enabling the company to monitor sales trends, identify growth opportunities, and optimize business operations.

## Project Overview
The primary objective of this project is to design and implement a dynamic Car Sales Dashboard using Power BI. The dashboard visualizes critical metrics related to sales, average prices, cars sold, and geographical distribution. This provides stakeholders with actionable insights to drive business decisions and improve operational efficiency.

## Scope of the Project
The Car Sales Dashboard covers the following key aspects:
   1. Sales Overview – Year-to-date (YTD) and Month-to-Date (MTD) sales performance, including Year-over-Year (YOY) growth and comparisons with previous years.
   2. Average Price Analysis – Evaluating the average sale price across periods and measuring growth.
   3. Cars Sold Metrics – Tracking the number of cars sold and comparing it with previous periods.
   4. Geographical and Demographic Insights – Analyzing car sales by dealer region, body style, and color.

---

## Dataset Description
The dataset used for this project contains 23,906 records and includes detailed information about car sales. Each record represents a unique sale transaction and contains the following attributes:

| Column Name      | Description                                                         |
|------------------|---------------------------------------------------------------------|
| **Car_id**       | Unique identifier for each car sale                               |
| **Date**         | Date of sale transaction                                          |
| **Customer Name**| Customer's full name                                              |
| **Gender**       | Gender of the customer (Male/Female/Other)                        |
| **Annual Income**| Customer's annual income in USD                                   |
| **Dealer_Name**  | Name of the car dealership                                        |
| **Company**      | Car manufacturer (e.g., Ford, Dodge, Toyota)                      |
| **Model**        | Specific model of the car sold                                   |
| **Engine**       | Engine type (e.g., Petrol, Diesel, Electric)                      |
| **Transmission** | Transmission type (Automatic/Manual)                              |
| **Color**        | Exterior color of the car                                         |
| **Price ($)**    | Sale price of the car in USD                                      |
| **Dealer_No**    | Unique identification number for the dealer                      |
| **Body Style**   | Car body style (SUV, Sedan, Hatchback, etc.)                      |
| **Phone**        | Customer’s contact number (e.g., +1-XXX-XXX-XXXX)                 |
| **Dealer_Region**| Geographical region where the car was sold (East, West, etc.)     |

---

# Methodology
The process of developing the Car Sales Dashboard is divided into the following steps:
     
  1. Data Collection and Preparation
     - Imported the dataset from the provided Excel file into Power BI.
     - Ensured correct data types for all fields, particularly the Date column.
     - Cleaned the dataset to handle any inconsistencies and standardized the column names.

  2. KPI Calculation -To deliver meaningful insights, the following KPIs were calculated using DAX (Data Analysis Expressions) in Power BI:
  
    - Sales Overview KPIs:
      1. Year-to-Date (YTD) Total Sales – Cumulative sales within the current year.
      2. Month-to-Date (MTD) Total Sales – Total sales for the current month.
      3. YOY Growth in Total Sales – Percentage increase/decrease compared to the previous year.
      4. Difference between YTD Sales and Previous YTD (PTYD) Sales – Absolute difference between the current and previous 
         year's YTD sales.

    - Average Price Analysis KPIs:
      1. YTD Average Price – Average car price for the current year.
      2. MTD Average Price – Average car price for the current month.
      3. YOY Growth in Average Price – Percentage change in the average price compared to the previous year.
      4. Difference between YTD Average Price and PTYD Average Price – Difference between the current and previous year's 
         YTD average price.

    - Cars Sold Metrics:
      1. YTD Cars Sold – Total number of cars sold this year.
      2. MTD Cars Sold – Total number of cars sold during the current month.
      3. YOY Growth in Cars Sold – Growth rate in cars sold compared to the previous year.
      4. Difference between YTD Cars Sold and PTYD Cars Sold – Difference in the number of cars sold compared to the
         previous year.

---
