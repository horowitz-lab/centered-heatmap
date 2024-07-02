# centered-heatmap
A heatmap where the pixels are centered on the values

Example usage:

  `centered-heatmap.heatmap(df) # df is a pandas dataframe`

or

```
  import matplotlib.pyplot as plt
  from centered-heatmap import listwrap
  plt.pcolormesh( listwrap(df.columns),listwrap(df.index), df ) # df is a pandas dataframe
```
