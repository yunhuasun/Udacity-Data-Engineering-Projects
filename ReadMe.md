# Udacity Data Engineer Nanodegree - Capstone Project
### Data Engineering Capstone Project

#### Project Summary

* The project is to build an ETL pipeline that extracts data from I94 Immigration Data set and World Temperature Data set, processes them using Spark, and loads data into data lake as a set of dimensional tables. The I94 Immigration Data comes from the US National Tourism and Trade Office Source. The World Temperature Dat dataset comes from Kaggle Source. 

#### Scope 

##### I94 Immigration Data (Data Source is in SAS format) 
* This data comes from the US National Tourism and Trade Office. Data contains international visitor arrival statistics by world regions and select countries (including top 20), type of visa, mode of transportation, age groups, states visited, and the top ports of entry. 
* The data set contains 3,096,313 Rows

##### World Temperature Data (Data sour is in CSV format) 
* This dataset is from Kaggle and contains monthly average temperature data at different country in the world wide.
* https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data
* The data set contains 8,599,212 Rows

#### Tools
* Python
* Pandas - exploratory data analysis on small data set
* PySpark - data processing on large data set

#### Conceptual Data Model
![Data Model](https://github.com/yunhuasun/Udacity-Data-Engineering-Projects/blob/9e82d6a2a0aa1373543497b51c9f7020290b03a7/Data%20Model.jpg)
