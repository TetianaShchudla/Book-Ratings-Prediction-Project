- About us :
	Tetiana Shchudla : Data Analyst student at DSTI
	Mohamed Hamiche : Data Engeneer student at DSTI
	Vincent Lamirault : Data Analyst student at DSTI

	This project was initiated as part of a group project to be graded.
	As time goes by, we encountered issues and had to face challenging problems.
	At some point, we decided to try and deal with this project as professionals instead of students.
	Learning by doing, and not giving up, aiming best results.

	We hope you'll enjoy and rate it well, even if the end is sad. Good books do not always end well by the way !


_______________________________

- requirements :
	Jupyter Notebook
	pandas
	numpy
	requests
	BeautifulSoup
	matplotlib
	scipy.stats
	seaborn
	plotly.express
	plotly.figure
	plotly.offline
	datetime


_______________________________

- Prologue : about scraping

Some files are here given to give access to what was initially done to enrich our dataframe.
They can be ran, but they may take time (at least 9 hours per notebook) since it browses the original website on more of 11.000 titles.
Files to run : 	
	- books_written_and_followers_scrape.ipynb (leads to creation of 'books_written_followers_latest_cleaned.csv')
	- books_discussion_scrape.ipynb (leads to creation of 'books_discussion_latest_cleaned.csv')

The notebooks include scrape part, and cleaning the data we get before we can include them to the main 'books.csv'
The two csv _cleaned files are available on this Github, they enrich the original 'books.csv'.


______________________________

- Main notebook from data cleaning to running models

Files needed :
	- books_written_followers_latest_cleaned.csv
	- books_discussion_latest_cleaned.csv
	- DATA & FEATURES.ipynb
The original 'books.csv' is no more needed, since all of its data are included in the provided two csv file above.

!!!!!!!!!!!!!!!!!!!
Warning ! You should take care of the path used in Step1. / 2.Importing data and merging 2 dataframes. Replace with your own path !
!!!!!!!!!!!!!!!!!!!

This notebook can be ran with the run all option, but we recommand to run it more like step by step from Step3. Model
