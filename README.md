# **fdnpy**

Complete Python SDK for FinancialData.net API

## **Installation**

pip install fdnpy

## **Usage Example**

from fdnpy import FinancialDataClient

\# Replace 'YOUR\_API\_KEY' with your actual key  
client \= FinancialDataClient(api\_key='YOUR\_API\_KEY')

\# Example: Get stock prices for Microsoft  
prices \= client.get\_stock\_prices(identifier='MSFT')  
print(prices)

\# Example: Get Microsoft's balance sheet  
balance\_sheet \= client.get\_balance\_sheet\_statements(identifier='MSFT', period='year')  
print(balance\_sheet)  
