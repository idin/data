# data
public datasets

## Crime in Atlanta

### How to Access the Data
```python
import pandas as pd
file_url = 'https://raw.githubusercontent.com/idin/data/main/crime_in_atlanta.csv'
df = pd.read_csv(file_url, index_col=False, low_memory=False)
```