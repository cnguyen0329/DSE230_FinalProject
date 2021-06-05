# DSE230 Final Project by Christina Nguyen and Steven Cozine
Final Project for DSE230 - Spring 2021

## Project Data Set
Individual household electric power consumption Data Set from UCI Machine Learning 
https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption

This data set consists of electricity consumption by one French household, located in Sceaux, France, over the span of nearly 4 years (Dec 2006 - Nov 2010). The data set has 2075259 rows of data and 9 attributes, with each row consisting of one minute of recorded data. 

## Project Description
To use scalable analytic platforms like Dask and Pyspark paired with Hadoop to compute basic machine learning processes. 

For our project we will be using Dask as the primary scalable analytic platform as there are many similar libraries with sklearn and it seems to perform a bit faster compared to Pyspark.

### Hardware used
This project's scope will be limited to our two personal laptops: Dell XPS 13 9360 with Ubuntu VM (Intel i7, 8 GB ram) and Dell XPS 13 9360 Developer Edition (Intel i5, 16 GB ram).

### Libraries used
* Used libraries provided by the class' launch.sh docker. 
* Updated to Dask 2021.05.1 (this line will be part of the Jupyter Notebook)

## To run the Notebook
1. Store the data file in the same folder as the Notebook
2. Run the launch.sh file and open up Jupyter Notebook
3. Open up the Notebook and ensure that Dask and Dask distributed are updated to Dask 2021.5.1; we included the code in the Notebook so run that cell!
4. Run the Notebook
