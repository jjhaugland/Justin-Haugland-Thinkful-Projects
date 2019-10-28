

```python
import pandas as pd
import matplotlib.pyplot as plt

# Make a blank data frame.
df = pd.DataFrame()

# Populate it with data.
df['age'] = [14, 12, 11, 10, 8, 8, 6]
```


```python
#calculates mean
import numpy as np

np.mean(df['age'])
```




    9.857142857142858




```python
#finds median
np.median(df['age'])
```




    10.0




```python
# Return the mode using the statistics module.
import statistics
statistics.mode(df['age'])
```




    8




```python
#calculates variance
df['age'].var()
np.var(df.age)
```




    6.408163265306122




```python
#calculates standard deviation
np.std(df['age'], ddof=1) 
```




    2.734262327610589




```python
#calculates standard error 
np.std(df['age'] ,ddof=1) / np.sqrt(len(df['age']))
```




    1.0334540197243192




```python
# Make a blank data frame.
df = pd.DataFrame()

# Populate it with data.
df['age'] = [14, 12, 11, 10, 8, 8, 7]
```


```python
#calculates mean
np.mean(df['age'])
```




    10.0




```python
#finds median
np.median(df['age'])
```




    10.0




```python
# Return the mode using the statistics module.
statistics.mode(df['age'])
```




    8




```python
#calculates variance
df['age'].var()
np.var(df.age)
```




    5.428571428571429




```python
#calculates standard deviation
np.std(df['age'], ddof=1) 
```




    2.516611478423583




```python
#calculates standard error 
np.std(df['age'] ,ddof=1) / np.sqrt(len(df['age']))
```




    0.9511897312113418




```python
df = pd.DataFrame()

# Populate it with data.
df['age'] = [14, 12, 11, 10, 8, 1, 7]
```


```python
#calculates mean
np.mean(df['age'])
```




    9.0




```python
#finds median
np.median(df['age'])
```




    10.0




```python
# Return the mode using the statistics module.
#this gives an error 
```


```python
#calculates variance
df['age'].var()
np.var(df.age)
```




    15.428571428571429




```python
#calculates standard deviation
np.std(df['age'], ddof=1) 
```




    4.242640687119285




```python
#calculates standard error 
np.std(df['age'] ,ddof=1) / np.sqrt(len(df['age']))
```




    1.6035674514745462




```python
# Make a blank data frame.(does not work if this is not here)
df = pd.DataFrame()

df['fans'] = [20, 23, 17, 5]
```


```python


np.mean(df['fans'])
```




    16.25


