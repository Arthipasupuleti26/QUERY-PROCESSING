import yfinance as yf
import pandas as pd
import matplotlib.pyplot as plt
ticker_symbol = 'GOOGL'

start_date = '2024-01-01'
end_date = '2024-03-01'

data = yf.download(ticker_symbol, start=start_date, end=end_date)
plt.figure(figsize=(10, 6))
plt.scatter(data.index, data['Close'], s=data['Volume']/1e6, alpha=0.5)
plt.title('Trading Volume vs. Stock Prices of Alphabet Inc. (GOOGL)')
plt.xlabel('Date')
plt.ylabel('Stock Price (USD)')
plt.xticks(rotation=45)
plt.grid(True)
plt.tight_layout()
plt.show()
