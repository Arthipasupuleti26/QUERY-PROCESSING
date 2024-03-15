import yfinance as yf
import pandas as pd
import matplotlib.pyplot as plt
ticker_symbol = 'GOOGL'
start_date = '2024-01-01'
end_date = '2024-03-01'
data = yf.download(ticker_symbol, start=start_date, end=end_date)

plt.figure(figsize=(10, 6))
data['Volume'].plot(kind='bar', color='green')
plt.title('Trading Volume of Alphabet Inc. (GOOGL)')
plt.xlabel('Date')
plt.ylabel('Volume')
plt.xticks(rotation=45)
plt.grid(True)
plt.tight_layout()
plt.show()
