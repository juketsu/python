# Series.unique()
pandas.unique(values)

## Purpose
Often used in data cleaning or analysis. 

## values
1d array-like  
such as : list, array, Pandas.Series

## Behavior
Removes duplicates.  
This does NOT sort.

## Return
  Index : when the input is an Index.  
  Categorical : when the input is a Categorical dtype.  
  ndarray : when the input is a Series/ndarray.  
  Pandas.Series : Return unique values of Series object.  
  numpy.ndarray : Return numpy.ndarray or ExtensionArray.  

```python
import pandas as pd
pd.unique(argument) # argument : 
pd.Series.unique()
```
