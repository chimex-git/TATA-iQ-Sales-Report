# TATA-iQ-Sales-Report
This TATA iQ Sales Report transforms raw, transactional data into actionable commercial intelligence, focusing on market penetration and revenue sustainability.
 
# Project Report

## Title: 
Executive insights on the Global Revenue Performance and Market Expansion Strategy(FY 2011) for TATA iQ

## Aim : 
To analyze the online retail dataset, identify high-growth opportunities, evaluate seasonal revenue trends, and provide data-backed recommendations for the global expansion of the Tata retail brand.

## Objective : 

Ensure data integrity by filtering out anomalies (e.g negative values for the quantities/price).

Visualize monthly revenue to identify peak demand periods.

Identify top-performing countries by revenue and quantity (excluding the UK).

Segment the top 10 customers by spend to inform retention strategies.


## Visualisation : 
You can interact with the visualisation here:
https://public.tableau.com/app/profile/joseph.efobi/viz/TATADataVisualisation_17709950337120/Overview?publish=yes



# Analysis :

## Monthly Revenue Trend :
This is a time series analysis showing the trajectory of every business at each quarter.
Looking closely at the visualisation, there is a surge in Q4 followed by a sharp decline. This is a stepping stone for the supply chain section to look into the causality of the surge and also check what might have caused the decline.

Observing seasonality trends is also a great idea to note. Regardless of the availability of each product in the market, they have various seasons when they sell well. Therefore identifying those products and noting their sales seasonality would even enable the surge observed in Q4 to become a usual uptrend beginning from Q1.


<img width="974" height="467" alt="image" src="https://github.com/user-attachments/assets/8b6572ea-0aa5-4ca3-8ba3-578f1c1b21d6" />


## Top 10 Customers By Revenue :

This is a breakdown of the individuals contributing most to product purchase.

There is an observation to take note of; the highest value customer generated a negative revenue for product “POSTAGE”. Also looking across the chart, the amount of purchases made by the high value customers for product “POSTAGE” were very minimal.

However,  easy channels should be made available for customers to reach out to the customer care department of the company in case of any complaint for any product or shipping delay. loyalty programmes and proper enlightenment campaigns should also be a second call which would enable the customers to understand when? and how? to use the company products

<img width="812" height="473" alt="image" src="https://github.com/user-attachments/assets/fc7b93e6-790c-4275-921b-79d81bf88a58" />




## Top 10 Markets (Excluding the UK) :

This view identifies the most organic growth outside the home market which has an organic growth already

<img width="812" height="465" alt="image" src="https://github.com/user-attachments/assets/16c6a4e7-5fb5-4a20-ad83-5d2ce8024ab2" />




## Product Volume by Country :

This chart identifies which countries buy in bulk versus high frequency small orders.

<img width="818" height="436" alt="image" src="https://github.com/user-attachments/assets/bdb51e9d-ee44-4f3a-9f19-a7af8bb42fe6" />


## Metric Calculations :

Revenue = [Quantity] × [Unit Price]

Number of Customers = COUNTD( [Customer ID])

# Tools Used :

Python for data cleaning then Tableau for data visualisation.


# Skills Demonstrated :

## Data Gathering : 

I downloaded the online retail dataset for TATA from https://www.theforage.com/virtual-experience/MyXvBcppsW2FkNYCX/tata/data-visualisation-p5xo/communicating-insights-and-analysis 

Data Cleaning and Transformation :

The dataset was originally in xlsx format. I had to convert it to a CSV format for a detailed data cleaning in Python.

 

I removed 1,000+ records of unit price and products with negative values to prevent revenue inflation.


# Conclusion :

The analysis of the 2011 online retail dataset confirms that while the United Kingdom remains the primary revenue driver, there is a noticeable untapped potential in high-affluence global markets like the Netherlands, Germany and France.

Therefore the revenue peaks observed in the final quarter, necessitates a needed proactive supply chain adjustment every early September.

# Recommendations:

Inventory Optimization: 

Increasing stock levels by 25-30% every Q3 would help to prevent stock-outs during the high-velocity demands in the October–December period.

Market-Specific Marketing: 

It is necessary to allocate 60% of the international marketing budget to the top three identified countries (e.g., Netherlands, France, and Germany) where their GDPs promise  high ROI.

Customer Retention: 

It is advisable to implement a targeted loyalty program for the Top 10 Customers identified in this report, as their lifetime value significantly outpaces the general consumer base.

Feel free to interact with the dashboard here : https://public.tableau.com/app/profile/joseph.efobi/viz/TATADataVisualisation_17709950337120/Overview?publish=yes



