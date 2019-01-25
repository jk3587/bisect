For every row in a dataframe, calculate
```python
percentileofscore(df[(df['d'] > row['d']-interval) & (df['d'] < row['d']+interval)], row['a'])
```
