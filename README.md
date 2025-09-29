Airport Flight Performance Dashboard

Introduction

This project provides a comprehensive analysis of historical airport flight data using Power BI. The goal is to transform a static dataset of flight operations into an interactive dashboard that allows for deep-dive analysis into airline performance, flight delays, and passenger traffic patterns.

This dashboard is designed to help stakeholders understand operational performance, identify historical trends, and make data-driven strategic decisions.

🎯 Problem Statement

The primary goal is to provide airport managers and analysts with a powerful tool to explore historical flight data. The dashboard aims to answer key business questions about operational efficiency, airline performance, and the primary causes of flight delays, based on past events.

📊 Dataset

This project uses a static, historical dataset containing flight information. The data includes key features for operational analysis.



Key Features:

flight number

airline

origin/destination

scheduled and actual timings

delay information

passenger count

⚙️ Project Workflow

Data Cleaning and Transformation (Power Query): The raw dataset was imported into Power BI and cleaned using the Power Query Editor. This involved correcting data types, handling missing values, and creating new columns to aid in the analysis (e.g., calculating delay duration in minutes).

Data Modeling: A data model was established, creating relationships between tables (e.g., a central Flights table and dimension tables like Airlines, Airports, and a dedicated Date table) to build a robust and efficient star schema.

DAX Calculations: Key Performance Indicators (KPIs) and other metrics were created using DAX measures. This includes calculations for On-Time Performance Percentage, Average Delay Time, and Total Passenger Volume.

Dashboard Development: An interactive, multi-page report was designed in Power BI. The dashboard includes a variety of visuals, slicers, and drill-down capabilities to allow for a thorough exploration of the data.

💡 Results & Business Insights

The dashboard provides a clear and interactive view of airport performance, enabling several key insights:



Performance Benchmarking: The dashboard allows for easy comparison of the On-Time Performance (OTP) and average delay times across different airlines and routes.

Trend Analysis: Users can identify historical trends, such as the busiest travel months, days of the week with the most delays, or peak operational hours.

Route & Airline Insights: The visuals highlight the most profitable or highest-traffic routes and provide a performance scorecard for each airline.

Delay Diagnosis: Users can drill down to understand the most common reasons for delays and which routes or airlines are most affected.

💻 Tech Stack

BI Tool: Power BI
Data Source: CSV / Excel
🚀 How to Use
To view this project on your local machine, follow these steps:

Clone the repository:
git clone https://github.com/santhoshsant15044-prog/Airport-Insights.git
Navigate to the project directory:

cd Airport-Insights
Open the Power BI File:

Open the Airport Insights.pbix file using Power BI Desktop.

If the dataset (CSV/Excel) is included in the repository, you may need to update the data source path in Transform Data > Data source settings to point to the file's location on your local machine.

