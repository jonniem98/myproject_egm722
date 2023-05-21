# myproject_egm722
A repository for coursework related to EGM722 at UU, created by Jonathan Matchett

This code creates an interactive map using data from Northern Ireland using the matplotlib library in Python. The map includes the counties, towns, water, and rivers of Northern Ireland. The code also uses the rasterio module to open a dataset for Northern Ireland and then uses the percentile stretch function to display the imagery. Finally, the code also adds a scale bar and a legend to the map. The code also uses the rasterio module to open a dataset, NI_Mosaic.tif, and then prints the mode the data was opened in, the number of bands, the size in height and width, as well as the bounding box and crs for the data set. It then reads the dataset and displays the image. Functions are defined for displaying and stretching the image, and the epsg:2157 code is applied to it.

To install this code, firstly investigate the environment and readme files in the repository. The readme file (here) also gives a description of how to undertake setup for this code. The environment file shows the modules that are required to allow successful executions of this code. Ensure that you have the modules listed in the environment downloaded and installed before continuing. If you do not have the necessary modules installed the code will not work correctly. Advice on installing the packages can be found on the PyPi webpage (Python Software Foundation, 2023). To use this webpage simply search the required module or browse and find the necessary modules (Figure 1) and then follow the instructions for installation using methods relevant to conda, the package and environment management system.  

This code can be run in any Python 3 interpreter. The author wrote and executed the code using the jupyter notebook, however users can avail of other interpreters providing it uses Python 3. Executing the import functions at the start of the code will ensure the necessary modules are loaded in.

The following is a list of the main python dependencies (modules) required to allow successful execution of this code. 
-	Cartopy (Python Software Foundation, 2023a)
-	Geopandas (NumFocus, 2023)
-	Matplotlib (Hunter, 2007)
-	Numpy (NumPy, 2023)
-	OS (Python Software Foundation, 2023a)
-	Rasterio (Mapbox, 2023)
-	Shapely (GEOS, 2023)

Installation Guide 

1. Start a new shell session. 
2. Activate your python environment.
3. Add the conda-forge and default channels to your conda configuration: 
      conda config --add channels conda-forge 
      conda config --add channels defaults
4. Install the necessary packages:
      conda install os 
      conda install geopandas
      conda install cartopy
      conda install rasterio
      conda install matplotlib.pyplot
      conda install numpy
      conda install shapely 
5. Verify that the packages were installed successfully by importing them in the python shell: 
      import os 
      import geopandas
      import cartopy
      import rasterio
      import matplotlib.pyplot
      import numpy
      import shapely 
6. You should now be ready to start using your new packages 

