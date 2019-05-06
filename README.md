## Intro
GeoPandas is an extremely useful and mostly user-friendly tool for doing basic GIS analysis and plotting in Python. I use it more frequently than QGIS or other tools because it integrates nicely with Jupyter Notebooks and uses Pandas under the hood, both of which are regular parts of my daily data journalism toolkit.

It's important to realize that GeoPandas is really just a nice wrapper around a bunch of other useful Python libraries including Pandas, Matplotlib, Fiona, Shapely and others. If you want to do something complicated that's not covered by the GeoPandas documentation, there's a good chance you can still do it by looking at the documentation for one of those other libraries.

## Getting started

In other projects, I would use the Pipenvs to save out my dependencies. For the sake of this class, I want you to create a native virtual environment the way you've been doing all class. You want to install the following libraryes: `pandas`, `geopandas` and `descartes`. This last ones is required for making map graphics.


## Data Sources

The unemployment data in `data` comes from the [Bureau of Labor Statistics](
https://www.bls.gov/lau/#cntyaa) "Labor Force data by county, 2018 annual averages". I've cleaned up the column names to make it easier to merge, but otherwise haven't changed anything.

The geographic data comes from the [Census Tigerline](https://www2.census.gov/geo/tiger/TIGER2018/) site, where the most definitive U.S. geographic data comes from. I simplified these files a lot, including removing Hawaii and Alaska for simplicity.

## Helpful links

[Geopandas reference](http://geopandas.org/install.html)

[Jonathan Soma's excellent geopandas tutorials](http://jonathansoma.com/lede/foundations-2017/classes/geopandas/mapping-with-geopandas/)

[Spatial Reference for getting EPSG numbers](http://spatialreference.org/ref/epsg/3310/)

[Pyplot options](https://matplotlib.org/3.0.2/api/_as_gen/matplotlib.pyplot.plot.html#matplotlib.pyplot.plot)

[Spatial join example](https://github.com/datadesk/geopandas-spatial-join-example)

[Matplotlib colormaps](https://matplotlib.org/users/colormaps.html)

[Matplotlib named colors](https://i.stack.imgur.com/lFZum.png)

[Census shapefiles](https://www2.census.gov/geo/tiger/TIGER2018/)

