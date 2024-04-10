# San Fransisco Housing Prices by squarefoot and gross rent price
Creating visualizations to help improve the decision making process. In this example, we use hvplot to visualize average sale price per square foot, and average gross rent for neighborhoods in San Fransisco. 

---

## Technologies
PyViz -- This is a visualization package which can access multiple visualization libraries. We will use two of those libraries, hvPlot and GeoViews.



> Install hvPlot and GeoViews to your working directory.


```
conda install -c pyviz hvplot geoviews
```

## Installation Guide

Make sure these packages are imported into your working directory

```
import pandas as pd
import hvplot.pandas
from pathlib import Path
import xarray as xr
import hvplot.pandas  # noqa
import hvplot.xarray  # noqa
import cartopy.crs as ccrs
```
---

## Usage

To use this analyzer open the folder in jupyter lab, and run all. Note that visual studio code has a hard time rendering the interactive plots, so please use jupyter lab or notebook. 

----


![Bar Chart]('Images/bokeh_plot.png')

----

## Contributors

G. Cale McDowell

@gcm107
---

## License
