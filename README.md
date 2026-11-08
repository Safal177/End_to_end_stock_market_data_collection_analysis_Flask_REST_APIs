# End_to_end_stock_market_data_collection_analysis_Flask_REST_APIs

# Financial data analytics and REST API development with the help of Python, Flask, and Yahoo Finance

# About my project:
In this project, I worked on collecting company information and stock market data with the help of Yahoo Finance. The results were received through 4 REST API endpoints. I used jupyter notebook for data analysis. I also used the notebook to test API response. 

# Motivation and objectives: 
In this project, I was interested in linking Python programming with REST APIs, Flask, financial datasets extracting from different companies, datasets analysis, 
and APIs testing. I used Yahoo Finance (Python library) to get company information and extract data (stock market). Therefore, I did not need a csv or parquet datasets from the companies

# API endpoints:
I used “GET” route for 2 features (Company information, and stock market data) and “POST” route for 2 features (historical market data, and analytical insights).

# Python environment and API testing:
I installed all necessary Python libraries and frameworks in a Conda environment (flask_stock). I applied this environment to make Flask applications. This environment was used for the Flask application. I used Jupyter Notebook for building the API endpoints. These endpoints were tested through this notebook. Financial data for different companies were collected using Yahoo Finance (yfinance). Jupyter notebook was used to connect the Flask REST API through HTTP requests. The results from these requests were presented in the notebook.

# API testing and results: 
All four endpoints were developed. The endpoints were also tested on a local server with Apple (AAPL) and Microsoft (MSFT). HTTP 200 status codes for these companies were received through the endpoint. I got HTTP 400 status code when I tested missing symbol, missing initial_date, and missing final_date for AAPL. I also got this code for MSFT.

# Project file:
flask_project_yahoo_finance_company_data_analysis.ipynb
