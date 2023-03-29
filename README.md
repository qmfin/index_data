# Dataset for index tracking

```python
import pandas as pd
df = pd.read_json('./index_data/STOXX1800.json.bz2', compression='bz2', orient='index')
```

- Filename suggests the index
- return is the daily return of the index. 
- ts is a dictionary of constituent-id (key) and return (value). 
- constituent-id is *inconsistent* across different indexes.
