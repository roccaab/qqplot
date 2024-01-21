# Q-Q Plot
A **Q-Q Plot** assesses the quantile similarity between a dataset and a theoretical distribution (Uniform or Normal in this version). It provides a visual and more intuitive approach to compare the data distribution of a sample with either a theoretical distribution or that of a second sample.

It illustrates observed quantiles plotted against expected quantiles from the distribution. This implementation serves as a **QGIS plugin** designed for geospatial data analysis, incorporating a **k-means clustering function**.

Q-Q Plot representations allow for:

1. Verifying whether the experimental data follows the trend of a theoretical distribution or a second sample.

2. Providing information on deviations from this trend, such as the presence of outliers or wider tails.

3. In the case of comparing the sample with a theoretical distribution, enabling the estimation of parameters that the theoretical distribution should possess to better describe the trend of the sample, such as standard deviation and mean.


In the Synthetic Data Folder directory, you can find synthetic data to test the plugin (normal, uniform, and bimodal Gaussian distribution data).


## Clustering function

If the selected layer does not have the 'x' and 'y' fields as coordinates (regionalized variable), and an additional numerical field on which to apply the Q-Q Plot, the clustering function will be disabled.*

**To enable the clustering function, you need to install scikit-learn (if not already installed) an open source library for predictive data analysis.** 

Follow these steps :

1. Open the OSGeo4W Shell;

2. Type the following command and press Enter:

`pip install -U scikit-learn`

3. Restart QGIS;

4. Now you can use the clustering function in the plugin.

To list all installed packages along with their versions:

`pip list

Make sure to use OSGeo4W Shell before running these commands.
   

