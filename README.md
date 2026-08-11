import pandas as pd

secom_df = pd.read_csv('/content/secom.data',delim_whitespace=True, header=None)

secom_labels_df = pd.read_csv('/content/secom_labels.data',delim_whitespace=True, header=None)
