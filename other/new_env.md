# Set Up an New Environment

## 1. Create an New Environment

GeoPandas and Rasterio are not built-in libraries in Anaconda. Thus, you need to install these two libraries in order to import and use them in your Python program. Please complete the following steps to install the libraries:

1. Open __Anaconda Prompt__ in the Start Menu. It opens as a black window with command lines.
2. Type the following command in the prompt and hit `Enter` to create a new environment "geo".

    `conda create --name geo`

    Hit `y` and `Enter` when asked to proceed.


3. Type `conda activate geo` to activate the new environment.
<img src="https://raw.githubusercontent.com/qiang-yi/spatial_data_science/main/image/wk4/install_env.gif" width="700" align="left">

## 2. Install Jupyter Lab, GeoPandas and Rasterio

4. Type `conda install jupyterlab` and hit `Enter` to install jupyter notebook in the "geo" environment. Hit `y` and `Enter` when asked to proceed.
<img src="https://raw.githubusercontent.com/qiang-yi/spatial_data_science/main/image/wk4/install_jupyter.gif" width="700" align="left">

5. Use the following command to install GeoPandas.     Hit `y` + `Enter` when asked to proceed.

    `conda install --channel conda-forge geopandas`

5. Use the following command to install Rasterio. Hit `y` + `Enter` when asked to proceed.

    `conda install --channel conda-forge rasterio`

6. Type `jupyter notebook` in the prompt to launch Jupyter Notebook in the "geo" environment. Open the downloaded Lab3.ipynb in the newly launched Jupyter Notebook.

> **Note**: If you encounter an error when importing geopandas (as below), please do the following:<br>
 Go to Anaconda Prompt, activate the geo environment, and use the following command to install rtree <br><br>`conda install -c conda-forge rtree=0.9.4` <br><br>After the installation, please launch Jupyter Notebook and import geopandas again.</span>

 <img src="https://raw.githubusercontent.com/qiang-yi/spatial_data_science/main/image/wk4/error.png" width="500" align="left"><br>


**In the future, if you want to use the "GeoPandas" and "Rasterio" libraries, you need to activate the "geo" environment and launch Jupyter Notebook from the Anaconda Prompt.**

<img src="https://raw.githubusercontent.com/qiang-yi/spatial_data_science/main/image/wk4/activate.gif" width="700" align="left">
