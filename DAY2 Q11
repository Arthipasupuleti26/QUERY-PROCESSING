import pandas as pd
import numpy as np
np.random.seed(0)
data = np.random.randn(10, 4)
df = pd.DataFrame(data, columns=['A', 'B', 'C', 'D'])
df.iloc[1, 1] = np.nan
df.iloc[3, 2] = np.nan
df.iloc[6, 0] = np.nan

styled_df = df.style.applymap(lambda x: 'background-color: yellow' if pd.isna(x) else '')

styled_df
