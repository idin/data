# data
public datasets

## Crime in Atlanta

### How to Access the Data
```python
import pandas as pd
df = pd.read_csv('https://raw.githubusercontent.com/idin/data/main/crime_in_atlanta.csv', index_col=False, low_memory=False)
```