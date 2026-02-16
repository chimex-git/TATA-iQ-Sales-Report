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

Looking closely at the visualisation, there is a surge in Q4 followed by a sharp draw down. This is a stepping stone for the supply chain section to look into the causality of the surge.

## Top 10 High Value Customers :

This is a breakdown of the individuals contributing most to product purchase.

There is an observation to take note of; the highest value customer generated a negative revenue for product "POSTAGE". Also looking across the chart, the amount of purchases made by the high value customers for product "POSTAGE" were very minimal.

## Top 10 Markets (Excluding the UK) :

This view identifies the most organic growth outside the home market.


## Product Volume by Country :

Identify which regions buy in bulk versus high frequency small orders.

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

