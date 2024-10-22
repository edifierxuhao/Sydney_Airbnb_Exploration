# Sydney_Airbnb_Exploration

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Besides the Anaconda distribution of Python, in order to plot Points on map, and add some base map, the following libraries are needed:
- **geopandas**, can be installed using `pip install geopandas`
- **shapely**, used for creating polygon or Points, can be installed using `pip install shapely`
- **contextily**,used for adding base map, can be installed using `conda install contextily --channel conda-forge`
- **geoplot**, used for plot heatmap on a map, can be installed using `conda install geoplot -c conda-forge`

## Project Motivation<a name="motivation"></a>

For this project, I was interested in using [Sydney Airbnb Dataset](https://www.kaggle.com/tylerx/sydney-airbnb-open-data) to better understand:

1. Is there any regional distribution pattern?
2. What's the trend of available room quantity and price with in a year?
3. What factors affect the house price more?
4. What are the top 5 words most used by reviewers to describe neighbourhood?

## File Descriptions <a name="files"></a>

There is a notebooks available here to showcase work related to the above questions.  This notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There are several files are from the the Sydney Airbnb Dataset, there are three files: `sydney_calendar_dec18.csv`, `listings_dec18.csv` and `sydney_reviews_dec18.csv` are too large to upload to Github, should be downloaded manually.

There are several `aus_poas.*` file, used for ploting map, was downloaded from [this link](https://web2.spatialvision.com.au/wp-content/uploads/2019/01/geopandas-blog.zip)

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@edifierxuhao123/how-to-run-an-airbnb-business-in-sydney-eed9b30d6c40).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to airbnb for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/tylerx/sydney-airbnb-open-data).  Otherwise, feel free to use the code here as you would like!
