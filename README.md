# Neutrogena-Sunscreen-Sales-Forecasting-Competitor-Analysis
**Business Understanding**

In the competitive skincare market, accurate sales forecasting is crucial for inventory planning and marketing. Traditional models miss real-time shifts in consumer sentiment and competitive trends. This project enhances Neutrogena’s sunscreen sales forecasts by integrating customer reviews and competitor analysis.

**Why This Matters:**
Customer reviews heavily influence purchasing decisions—studies show a one-star rating increase can boost revenue by 5–9%. By analyzing review sentiment, topics, and complaints, along with competitor product perception, we create forecasts that are more adaptive to consumer behavior and market shifts.

**Objective:**
Predict weekly unit sales 4–8 weeks in advance for three Neutrogena facial sunscreens, using both historical sales data and review signals. Success is defined by improved accuracy (e.g., reduced RMSE) over traditional models. These forecasts support smarter inventory management, targeted marketing, and proactive product decisions.

**Scope & Constraints:**
We analyze three Neutrogena products and two competitor products (EltaMD and L’Oréal) using review data (2018–2025) and pricing data (2024–2025). With limited sales data, we use review volume as a sales proxy, assuming a 2% review rate. Seasonality and external factors are considered indirectly via review trends. The goal is to deliver both accurate forecasts and actionable insights for Neutrogena’s business teams.

**For all the other details about the project, please check out the Project report in this repository**

The full code for this project, including data preprocessing, exploratory analysis, model 
training, and evaluation, is available through files: 
● All Product_Cleaning and EDA.ipynb – code to clean raw data files for 
neutrogena products and output the weekly aggregated dataset. 
● Product Predicting Proxy Sales.ipynb – code to predict sales and units. 
● Product Integration & Comparison.ipynb – code for sales comparison for 
products. 
● Competitor_Analysis.ipynb – code for competitor analysis. 
Data: [Project Data](https://drive.google.com/drive/folders/12WPtcrqM1IhTnt58HYdaKlhUzK8BPRrt)
By sharing the code, we aim to ensure transparency and allow further development by 
other data scientists or engineers.
