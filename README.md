# beer-data-analysis

__The code is analysing the dataset of reviews of different beers served at different breweries. It can be used to understand the more popular beers and places to go for a beer__


## Introduction

I have build this project based on the data provided by [Stratascratch](https://www.stratascratch.com) as part of a business analysis data project. It contains the beer data and the respective reviews of customers. To identify the popularity of the beer's  I have done the following analysis on the data:
1. Rank the top 3 breweries which produce the strongest beers.
2. Which year did beers enjoy the highest ratings?
3. Based on the users' ratings, which factors are important among taste, aroma, appearance, and palette?
4. If you were to recommend 3 beers to your friends based on this data, which ones would you recommend?
5. Which beer style seems to be the favourite based on the reviews written by users? How does written reviews compare to overall review score for the beer style?


## Usage

### Installation

The code is present in a Jupyter Notebook __Business_Analysis.ipynb__ and requires Python 3.9 to run it. The Jupyter Notebook can be run in the browser or can be installed from [here](https://jupyter.org)

### Data

The data is present in the datasets folder in the root directory. It consists of a single __BeerDataScienceProject.tar.bz2__ which contains all the reviews and beer data.

### Libraries
The following libraries have been used in the code:
1. [pandas](https://pandas.pydata.org)
2. [datetime](https://docs.python.org/3/library/datetime.html)
3. [matplotlib](https://matplotlib.org)
4. [seaborn](https://seaborn.pydata.org)
5. [nltk](http://nltk.org)


## Result

I have performed Exploratory Data Analysis(EDA) on the data using pandas to identify the characteristics useful to the business requirements. I have used the maplotlib library and seaborn library to visualise the analysis. The nltk library has been used to perform sentiment analysis using it's pretrained model
