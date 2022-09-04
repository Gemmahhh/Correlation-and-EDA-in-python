# Correlation-and-EDA-in-python
The movies dataset was gotten from kaggle. It was used for a personal project to put the skills I gained in the Udemy course "Data Analysis with Python and Pandas" into practice. 

I started the project by importing all the libraries I needed for the analysis such as:
- pandas
- numpy
- seaborn
- matplotlib
- wordcloud etc. 

Then, I read the csv file using pandas' read_csv method

I assessed and cleaned the data simultaneously to get it ready for the analysis and visualization. There were 15 columns and 7668 entries(rows) in the dataset. 

Some of the cleaning operations I performed are:
- Changing the datatypes of some of the columns
- Filling the empty cells of a particular column with '0'
- Removing duplicates

Some of the insights gotten from the analysis and visualization. 
- I was curious to know if increasing the bugdet of a movie would also increase the gross profit the movie generates so I used scatter plot to visualize it. Gross profit had a positive relationship with the budget. 
- I was also curious to know the country with the highest number of released movies so I plotted the top 10 and the highest was the United States. 
- Using wordcloud, I was able to view some of the most popular stars based on the available data. 
