 # API-INTEGRATION-AND-DATA-VISUALIZATION
 
 *COMPANY*: CODETECH IT SOLUTIONS PVT.LTD
 
 *NAME*: PERUMALLA LAKSHMI PRASANNA
 
 *INTERN ID*: CT08PRF
 
 *DOMAIN*: Python programming
 
 *DURATION*: 4 Weeks
 
 *MENTOR*: Neela Santosh Kumar



For this task, I selected financial data, specifically Apple Inc. (AAPL) stock prices from 2000 to February 2025. The goal was to retrieve and visualize historical stock trends using an API.

I obtained the data from Alpha Vantage, a financial market data provider. To access it, I registered at www.alphavantage.co and received a unique API key. This key enabled API requests to fetch stock price data.

Implementation in Google Colab
I implemented this project in Google Colab, a cloud-based Python environment, using essential libraries:
requests – To fetch data via API calls.
matplotlib – For visualization.

Steps for Data Retrieval and Processing
API Request & Data Extraction:

Used Alpha Vantage’s Time Series Daily Adjusted API to get stock prices.
Sent an HTTP request and retrieved JSON-formatted data containing date, open, close, high, low, and volume.

Data Cleaning & Formatting:

Converted JSON response into a DataFrame.
Formatted the date column, sorted values, and removed missing data.
Data Visualization:

Created line graphs to show stock trends from 2000 to 2025.
Added labels, legends, and titles for clarity.

Data Formatting Issues: Parsed JSON correctly to ensure accurate conversion into a structured DataFrame.

Support & Learning:
Throughout the project, I leveraged ChatGPT for assistance in API requests, JSON parsing, debugging errors, and improving visualization techniques. It provided solutions to common issues and helped refine the workflow.

Conclusion:
This project strengthened my understanding of API integration, financial data analysis, and visualization.


*Output*

![Image](https://github.com/user-attachments/assets/13cb90df-2966-46eb-bcbb-2ed6fb03536e)

