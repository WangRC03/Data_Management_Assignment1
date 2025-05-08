# U.S. Retail and Food Services Sales Analysis (2023–2025)
This project provides a detailed analysis of monthly U.S. retail and food services sales for the years 2023 and 2024, along with a forecast for 2025.Using open data from the U.S. Census Bureau,this notebook explores sales trends, seasonal patterns,and growth in key retail segments.The goal is to support data-driven decision-making in the retail industry.

## Project Objectives
- Analyze and visualize trends in monthly retail sales.
- Compare year-over-year (YoY) and month-over-month (MoM) performance.
- Explore sub-industries excluding volatile categories like motor vehicles and gasoline.
- Forecast total retail sales for the year 2025 using Exponential Smoothing.
- Offer insights and recommendations for business strategy and planning.

## Data Cleaning
The data was cleaned and reshaped to make it analysis-ready:
- Skipped non-data header rows in Excel.
- Removed empty rows and columns.
- Standardized column types and labels.
- Separated 2023 and 2024 data into structured monthly records.

## Key Insights
- **Retail Sales Grew in 2024**:Most months outperformed 2023, suggesting steady consumer demand or inflation-driven pricing.
- **Core Segments Held Strong**:Even after excluding fuel and vehicles, retail sales stayed solid.
- **Seasonal Patterns Were Clear**:Sales peaked in spring (Mar–May) and the holidays (Oct–Dec).
- **Forecast for 2025 is Positive**:The model predicts continued growth with similar seasonal peaks.

## Recommendations
1. **Inventory Planning**:Align stock with seasonal demand peaks (spring and year-end).
2. **Campaign Strategy**:Run promotions in slow months like June and September.
3. **Category Focus**:Invest in resilient retail areas like food, clothing, and home goods.
4. **Data-Driven Decisions**:Use forecast models for staffing, logistics, and budget planning.
5. **Adaptability**:Monitor consumer behavior and be ready to pivot based on trends.

## Tools & Libraries
- Python (Pandas,Matplotlib,Seaborn)
- Statsmodels (for time series forecasting)
- Google Colab

## Author
**WANG RONGCHENG**  
This project was completed as part of an academic data analysis assignment (2024–2025).  
All charts, forecasts, and interpretations were created using publicly available U.S. government data.

## Source
Data sourced from [U.S. Census Bureau](https://www.census.gov/retail/index.html).
