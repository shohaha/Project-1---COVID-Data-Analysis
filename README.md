# **Project: Covid-19 Data Analysis**
#### Team Members: Shola, Noshaad, Khadra

This readme document has been compiled to describe our motivation and reasoning behind the data we chose to analysis and our main goals of the project. 

## Project Description

An extremely important aspect of our project was to identify correlations of aspects from our chosen data sets, analyse our findings by using continents and countries as a pivotal point of interest, then understand what drove these outcomes and detect future outcomes based on various correlations. These were our original main areas of research; -

* **Hospital Beds (per 1000) vs Covid Death Rates**
* **Covid Deaths vs Median Age (per continent)** 
* **Covid Total Cases vs Country Population Size**

## Data Sets Reference

* **'owid-covid-data.csv'**
Data set updated on a weekly basis
https://www.kaggle.com/datasets/georgesaavedra/covid19-dataset

* **‘archive/world_country_and_usa_states_latitude_and_longitude_values.csv’**
Data set used to map longitude and latitude
https://www.kaggle.com/datasets/paultimothymooney/latitude-and-longitude-for-every-country-and-state

* **‘hospital_beds_per_datahub_worldbank_v1.csv’**
Data set was initially used to depict a correlation of hospital beds vs Covid deaths
https://www.kaggle.com/datasets/ikiulian/global-hospital-beds-capacity-for-covid19

## Plotting Data

Originally, we intended to use hospital bed capacity as a pivotal point of focus to see if there was any correlation between hospital bed capacity and Covid-19 cases based on continents. While we worked on the data exploration and plotting of data, this data set didn’t depict much of a correlation between Covid deaths and hospital bed availability. Although we didn’t choose to use this data in further analysis, it has been included in our presentation as we see this as an essential part of our data exploration and analysis process which led us to our finial analysis.

Following on from our first scatter graph we went on to plot **Total Covid Deaths in relation to Median Age**, it was clear from R-value of 0.003 we couldn’t find a positive linear relationship. When we went on to plot **Population Density vs Total Confirmed Covid Cases** we found ourselves in a similar predicament as R-value was lower at 0.001 meaning we were unable to find a positive linear relationship. 
Diving further into plotting data we quickly became aware total values didn’t paint the picture we initially thought it would, so we collaboratively decided to use percentages of the total value rather than total values. We believe this helped our data visualisation process as we were able to paint a better picture once we made this vital change. **Continent Covid Statistics** bar graph represents a better picture using percentages.

Using bar charts, we decided to look at **Countries with Highest Total Covid Cases** and **Countries with Highest World Total Deaths**. From this we could see a country such as India had the highest population in comparison to other countries and a high number of cases and deaths which was understandable with their population density. We were also able to see United States had the highest number of total deaths in comparison to other countries which we drew a correlation to the fact that it took the country longer to implement lockdowns at the beginning. 

Our final set of bar charts compare **Countries with the Highest Total Covid Deaths** and **Countries with the Highest Total Covid Cases** both by country which paints a clearer picture compared to our first two bar graphs. During our data analysis process, we could see United States and Brazil had a higher number of total deaths and cases in comparison to the population, which we believe to be down to a lot of countries marking down many deaths as Covid deaths. 

By using pie charts to measure **Percentage of World Population by Continent** and **Percentage of World Total Cases by Continent** we were able to compare continents vs world total Covid cases and clearly see the disparity between continents and ultimately the effects of Covid. Interestingly Asia accounts for nearly 60% of the world population, yet they only account for less than 30% of world total Covid cases. Africa accounts for just under 20% of the world population, yet only accounts for 2.5% of total Covid cases.

We decided to use heatmaps to visualise how countries were affected by Covid around the globe and make use of markers on locations to show total confirmed Covid cases. 

## Data Analysis

* At the start of the coronavirus (COVID-19) pandemic there was concern that cases would overwhelm hospital capacity and that more densely populated countries would be more affected. Our Data Analysis didn’t show it clearly but that could be due to the data being incomplete and not being able to investigate further. 
* We found that there was a better question behind why the Top 20 countries did so badly compared to countries with fewer hospital beds per population or even lower GDP or a higher population density. 
* The charts show clearly that Asia and Africa did better than other continents. Could this be due to lower median age or because of lack of reporting? Our analysis brought more questions than answers to our questions at the start of the project.

## How to Run this Project

```python
import matplotlib

#Install matplotlib 
pip install matplotlib

import pandas

#Install pandas
pip install pandas


import numpy

#Install NumPy
pip install numpy

import requests

#Install Requests
pip install requests

import json

#Built-in module installation is not required to install via pip

import scipy

#Install scipy
pip install scipy

import seaborn

#Install Seaborn
pip install seaborn

#Check current python packages using terminal 
pip3 list 
```
