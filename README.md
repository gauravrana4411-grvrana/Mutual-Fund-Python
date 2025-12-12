# Mutual-Fund-Python
The Mutual Fund Plan with Python project is a Python-based application designed to help investors create, simulate, and evaluate mutual fund investment strategies. The goal of the project is to provide a comprehensive, interactive tool that combines financial analysis, risk assessment, and visualization to support better investment decisions.

Purpose
 ‘How can an investor build a diversified portfolio that gives good returns while keeping risk low?’
Investors want high returns, but also need to manage risk. Diversifying across multiple companies reduces risk, while analyzing risk-adjusted returns helps make smarter investment decisions. 
________________________________________
Understanding & Preparing the Data
 I used Nifty 50 closing price data for about 49 companies. The main columns are the date and closing prices.
First, I loaded the data in Python using Pandas, converted the date column to datetime format, and ensured there were no missing values. This makes sure all calculations like returns, volatility, and ROI are accurate.
Next, I calculated daily returns, which is essential to measure growth rates and risk correctly. 
________________________________________
Exploratory Data Analysis (EDA) 
 I explored the data to understand how stocks moved over time. I calculated:
•	Volatility: How much a stock’s price fluctuates
•	Growth Rate: How much a stock grows over time
•	ROI: Total return from the start to the end
To make this easier to understand, I used visualizations:
•	Time series line plots for stock prices over time to show trends and fluctuations
•	Bar charts to compare volatility, growth rates, and ROI among different companies
These visualizations helped me identify high-growth but risky stocks and moderate-growth, low-risk stocks for the portfolio. 
________________________________________
Portfolio Construction & Simulation
 I selected companies with ROI above the median and volatility below the median for a safer portfolio.
I then applied inverse-volatility weighting: companies with lower risk get higher investment allocation, while riskier companies get less.
To simulate growth, I calculated how a monthly investment of ₹5000, increasing 10% annually, would grow over 1, 3, 5, and 10 years. This shows the power of compounding over time. 
________________________________________
Risk and Return Analysis
 I compared the portfolio’s risk and ROI with high-growth companies:
•	Volatility bar charts show which stocks are safer
•	ROI bar charts show which companies give higher returns
Using these interactive charts, an investor can clearly see the trade-off between risk and return, making it easier to decide the right allocation. 
________________________________________
Insights & Recommendations
 Based on the analysis:
•	Companies like BPCL, ICICI Bank, and PowerGrid are ideal because they have high ROI and low volatility.
•	Less risky companies get higher investment percentages, ensuring stability.
•	The projections show that even a small monthly investment can grow significantly over 10 years with consistent, disciplined investing. 
________________________________________
Technical Details & Tools 
 I used Python libraries like:
•	Pandas for data handling
•	NumPy for calculations
•	Plotly for interactive charts and line/bar graphs
I also used functions to calculate volatility, growth rate, ROI, and future investment values. The code is modular, well-documented, and easy to follow. 
________________________________________
Visualizations
The visualizations—line plots for trends and bar charts for comparison—make it easier to understand stock behavior and portfolio performance at a glance.

Conclusion 
 This project demonstrates how to create a safe and profitable mutual fund plan using data. By combining high ROI, low-risk companies with risk-balanced allocation, investors can grow money steadily.
