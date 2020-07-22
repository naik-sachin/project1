# Module 1 Project - Movie Industry Analysis

This repository contains the contents for the Module 1 project where we analyze the movie industry and provide recommendation based on the insights we find in the data. 

## The Datasets

We had certain data already given to us but we decided to use the following from the available datasets.

* [tn.movie_budgets.csv.gz](https://github.com/snaik21352/project1/blob/master/Notebooks/tn.movie_budgets.csv.gz)  -  This gave us information on movie budgets

We also used a webscraper to scrape data off IMDb

* [newfulldf.csv](https://github.com/snaik21352/project1/blob/master/Notebooks/newfulldf.csv)  -  This final .csv file contains all the cleaned data merged into one .csv file


## The Notebooks

We had a few notebooks to split up how we extracted and cleaned our data.

1. [Web_Scraper.ipynb](https://github.com/snaik21352/project1/blob/master/Notebooks/Web_Scraper.ipynb)
	* In this notebook, we show the steps we took to scrape [IMDb](https://www.imdb.com/) with [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/). The scraped data was saved as [All_movies_year_1990-2020.csv](https://github.com/snaik21352/project1/blob/master/All_movies_year_1990-2020.csv)

2. [Combining Data.ipynb](https://github.com/snaik21352/project1/blob/master/Notebooks/Combining%20Data.ipynb)
	* In this notebook, we show the steps to create the final cleaned dataset [newfulldf.csv](https://github.com/snaik21352/project1/blob/master/Notebooks/newfulldf.csv)

3. [EDA.ipynb](https://github.com/snaik21352/project1/blob/master/Notebooks/EDA.ipynb)
	* In this notebook, we show the different visualization and analysis we did based on the cleaned data


## The Presentation

You can find the Google Slides presentation [here](https://docs.google.com/presentation/d/1679d20gadi5_Q87Sc3tBHk--LrzjMmOg7c2lTDUWyfQ/edit?usp=sharing)