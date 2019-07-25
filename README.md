
### Questions

### Objectives
YWBAT 
- apply time series techniques to find insights on a dataset

### Outline


```python
import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
```


```python
# Load in dataset 
df = pd.read_csv("./data/GlobalLandTemperatures_GlobalTemperatures.csv")
df.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>dt</th>
      <th>LandAverageTemperature</th>
      <th>LandAverageTemperatureUncertainty</th>
      <th>LandMaxTemperature</th>
      <th>LandMaxTemperatureUncertainty</th>
      <th>LandMinTemperature</th>
      <th>LandMinTemperatureUncertainty</th>
      <th>LandAndOceanAverageTemperature</th>
      <th>LandAndOceanAverageTemperatureUncertainty</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1750-01-01</td>
      <td>3.034</td>
      <td>3.574</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1750-02-01</td>
      <td>3.083</td>
      <td>3.702</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1750-03-01</td>
      <td>5.626</td>
      <td>3.076</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1750-04-01</td>
      <td>8.490</td>
      <td>2.451</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1750-05-01</td>
      <td>11.573</td>
      <td>2.072</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.shape, df.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 3192 entries, 0 to 3191
    Data columns (total 9 columns):
    dt                                           3192 non-null object
    LandAverageTemperature                       3180 non-null float64
    LandAverageTemperatureUncertainty            3180 non-null float64
    LandMaxTemperature                           1992 non-null float64
    LandMaxTemperatureUncertainty                1992 non-null float64
    LandMinTemperature                           1992 non-null float64
    LandMinTemperatureUncertainty                1992 non-null float64
    LandAndOceanAverageTemperature               1992 non-null float64
    LandAndOceanAverageTemperatureUncertainty    1992 non-null float64
    dtypes: float64(8), object(1)
    memory usage: 224.5+ KB





    ((3192, 9), None)




```python
### Transform data to time series
```


```python
### make a basic plot of each column with time
```


```python
### what insights can you find through time series analysis?
```


```python

```

### Assessment
