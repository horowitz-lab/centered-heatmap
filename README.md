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
or if you don't use pandas, you can use pcolormesh however you normally do. Just use listwrap to center the pixels.

```
  import matplotlib.pyplot as plt
  from centered-heatmap import listwrap
  plt.pcolormesh( listwrap(coordinates_list_1) , listwrap(coordinates_list_2) , values_array ) 
```
