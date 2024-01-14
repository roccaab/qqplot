# Q-Q Plot
 A Q-Q Plot assesses quantile similarity between a dataset and a theoretical distribution (Uniform or Normal for this version). It plots observed quantiles against expected quantiles from the distribution. This implementation functions as a QGIS plugin for geospatial data analysis.

In the Synthetic Data Folder directory, you can find synthetic data to test the plugin.


## Clustering function
**To enable the clustering function, you need to install scikit-learn. Follow these steps:**

1. Open the OSGeo4W Shell.

2. Type the following command and press Enter:

`pip install -U scikit-learn`

3. Now you can use the clustering function in the plugin.

*If the selected layer does not have the 'x' and 'y' fields as coordinates, and an additional numerical field on which to apply the Q-Q Plot, the clustering function will be disabled.*
