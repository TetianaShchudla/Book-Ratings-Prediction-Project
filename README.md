# Book Ratings Prediction Project - Goodreads

![image](https://github.com/mohamed06H/dsti-ml-book-ratings/assets/117094584/db4b1e23-be01-4156-a545-741258097a62)


__Hello and welcome__ to our project about the book average ratings prediction on the [Goodreads website](https://www.goodreads.com/). 

You can find here the analysis using machine learning techniques, including data cleaning and analysis, feature selection and engineering, model training and testing. In addition to this, we did the web scraping to enrich our dataset. 

_______________________________
 ## About us :
 
- __Tetiana Shchudla__ : Data Analyst student at DSTI

- __Mohamed Hamiche__ : Data Engeneer student at DSTI
 
- __Vincent Lamirault__ : Data Analyst student at DSTI


This project was initiated as part of a group project to be graded.  

As time goes by, we encountered issues and had to face challenging problems.

At some point, we decided to try and deal with this project as professionals instead of students.

Learning by doing, and not giving up, aiming best results.

We hope you'll enjoy and rate it well, even if the end is sad. Good books do not always end well by the way !

_______________________________

## Requirements :

- Jupyter Notebook
- pandas
- numpy
- requests
- BeautifulSoup
- matplotlib
- scipy.stats
- seaborn
- plotly.express
- plotly.figure
- plotly.offline
- datetime

______________________________
## Prologue : about scraping

Some files are here given to give access to what was initially done to enrich our dataframe.
They can be ran, but they may take time (at least 9 hours per notebook) since it browses the original website on more of 11.000 titles.

__Files to run :__
- _books_written_and_followers_scrape.ipynb_ (leads to creation of 'books_written_followers_latest_cleaned.csv')
- _books_discussion_scrape.ipynb_ (leads to creation of 'books_discussion_latest_cleaned.csv')

The notebooks include scrape part, and cleaning the data we get before we can include them to the main _'books.csv'_.

The two _csv_cleaned_ files are available on this Github, they enrich the original _'books.csv'_.


______________________________

## Main notebook from data cleaning to running models

__Files needed:__
- _books_written_followers_latest_cleaned.csv_
- _books_discussion_latest_cleaned.csv_
- _preparing_features.ipynb_

The original _'books.csv'_ is no more needed, since all of its data are included in the provided two csv file above.

### _Warning !_ You should take care of the path used in Step1. / 2.Importing data and merging 2 dataframes. Replace with your own path !

This notebook can be ran with the run all option, but we recommand to run it more like step by step from Step3. Model
