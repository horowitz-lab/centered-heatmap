# centered-heatmap
A heatmap where the pixels are centered on the values

Example usage:

centered-heatmap.heatmap(df)

or

import matplotlib.pyplot as plt

plt.pcolormesh( listwrap(df.columns),listwrap(df.index), df )
