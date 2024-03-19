import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('fdata.csv')
df['Date'] = pd.to_datetime(df['Date'])
start_date = '2016-10-03'
end_date = '2016-10-07'
filtered_data = df[(df['Date'] >= start_date) & (df['Date'] <= end_date)]
plt.figure(figsize=(10, 6))
plt.plot(filtered_data['Date'], filtered_data['Close'], marker='o', linestyle='-')
plt.xlabel('Date')
plt.ylabel('Closing Price')
plt.title('Financial Data of Alphabet Inc. (Oct 3, 2016 to Oct 7, 2016)')
plt.xticks(rotation=45)
plt.grid(True)
plt.tight_layout()
plt.show()
