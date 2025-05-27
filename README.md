Project Title: Data-Driven Assessment of Canadian Crops and Prices for US Venture Planning

This project provides a comprehensive analysis of Canadian crop production, farm prices, and currency 
exchange trends to support a US-based venture capital firm interested in the craft brewing and distilling 
supply chain.

Using R and the SQLite database engine, four datasets from Statistics Canada and the Bank of Canada were explored, 
loaded, and queried to derive strategic insights related to crop supply, price fluctuations, and foreign exchange 
conversions (USD/CAD).

The datasets used are:
- Annual_Crop_Data.csv: Yearly crop production data by province
- Monthly_Farm_Prices.csv: Crop prices per metric tonne
- Daily_FX.csv: Daily USD to CAD exchange rate
- Monthly_FX.csv: Monthly average USD to CAD

The steps completed are:
- Load Libraries & Establish Database Connection
- Create and Load 4 Tables: CROP_DATA, FARM_PRICES, DAILY_FX, MONTHLY_FX
- Run SQL Queries to Solve 15 Problems
- Generate Analytical Views including a combined crop-FX view

Key Outputs:
- Invest in High-Yield, High-Value Crops: Prioritize Canola and Wheat, especially in Saskatchewan and Alberta.
- Monitor Currency Fluctuations: Use monthly FX data to time large-scale purchases or contracts.
- Explore Yield Efficiency: Focus on crops consistently above 2000 kg/hectare post-2000.
- Data-Driven Contracts: Use the percentage of unharvested land to negotiate pricing margins.
- Scale Further with Time Series Forecasting: Predict yields & prices with models using R packages like forecast or prophet.

This analysis supports data-backed decisions in sourcing Canadian grain for US-based craft beverage operations.
Saskatchewan and Alberta emerge as high-performing provinces for Canola and Wheat, while FX trends suggest 
opportunities for cost-optimized imports when USD is strong.
