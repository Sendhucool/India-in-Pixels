README : India In Pixels

Objective of project: 
1. To retrieve the data of runs scored by every ODI player from the year 1970 to 2019
2. Sort the data year-wise
3. Calculate the total runs scored by each player for the whole time period

Files in repository:
Cricinfo.ipynb - Jupyter Notebook of code written to retrieve data from website: http://stats.espncricinfo.com
scores.xlsx - Excel sheet of the csv output rendered by the code

Required external dependencies to run the program:
1. Pandas
2. BeautifulSoup

Output:
CSV file - Row 1: Player Name (Country Name)
		   Row 2-onwards: Runs scored each year

Blank fields are indicated by '-'

Data cleaned in Excel: Added Country Name as separate column & Calculated total scores