import pandas as pd

secom_df = pd.read_csv('/content/secom.data',delim_whitespace=True, header=None)

display(secom_df.head())
