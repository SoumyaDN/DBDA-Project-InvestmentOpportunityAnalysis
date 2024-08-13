# DBDA-Project-InvestmentOpportunityAnalysis
Investment Opportunity Analysis

ABSTRACT:

The primary objective of this project is to analyze the stocks of various companies and market trends to evaluate investment performance. By comparing the returns and risks of individual companies with the overall market risk, this analysis aims to provide valuable insights for investors. The project focuses on helping investors manage their portfolios by diversifying investments with optimized weightage across different stocks. This is achieved by comparing the risks and returns from a large number of companies globally, thereby enabling informed decision-making for better portfolio management.

Introduction:

In the dynamic world of finance, making informed investment decisions is crucial for maximizing returns and minimizing risks. This project aims to provide a comprehensive analysis of stocks from various companies and market trends to evaluate investment performance. By examining the returns and risks associated with individual companies and comparing them with overall market risk, this study seeks to offer valuable insights for investors. The goal is to assist investors in managing their portfolios more effectively by diversifying investments with optimized weightage across different stocks. By leveraging data from a large number of companies globally, this project aims to enable informed decision-making and enhance portfolio management strategies.

We are building various portfolios of stocks from different companies, providing detailed information on total returns, initial investment amounts, and portfolio volatility. Additionally, we offer visualizations of the weightage of each stock, performance charts over time, and candlestick charts. These tools enable investors to choose appropriate portfolios based on their specific requirements, thereby enhancing their portfolio management strategies through informed decision-making.

Objective:

The objectives of the project are as -
	To calculate the Expected Returns of Stocks
	To estimate Stock risk and Market risk
	To calculate Correlation of stocks based on returns
	To Estimate Portfolio returns and risk
	To Reduce Risk by Diversification


Version uploaded on 13.08.2024. Order of files 

daily_data.sh : api call for 100 stocks from fmp api
hive_daily_upload_final.ipnb  : uploading the json files into hive
hive_daily_upload_final.py : python version of above
investment_analysis_final.ipynb : handles analysis of 100 stocks extracted from hive database
investment_analysis_final.py  : the python code for the above file
copycsv_final.sh :  copying the csv to grafana folder for visualization
investment_analysis_airflow_final.py  : airflow dag for scheduling the above codes to run daily
grafana_snapshot_link_investment_analysis_dashboard.txt : snapshot link of grafana dashboard
Investment_Analysis_Demo-1723560115987.json : grafana dashboard export file
