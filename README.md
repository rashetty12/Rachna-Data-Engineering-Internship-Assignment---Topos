# Webscrapping
Step 1 :- As the question states obtain data related to the top cities of the united states, 
I considered the page where it displayed the top US cities and was ranked based on the population

Step 2 :- For web scrapping I used the Package BeautifulSoup and passes the URL which provided all the details of the wikipedia page.

Step 3 :-Created a table which is the table on teh webpage containing the states and the city names.
with the help of Beautiful soup , details of the table were obained when find by class method was used to obtainthe table

Step 4 :- Created a dataframe comprising of the columns having the colums values on the web page that is the state name, city name, ranking based on population
and other details etc. I considered only the State name, City Name, and the 2018 rank based on population.


Steo 5 :- One thing that was observed that each and every city was a link which lead to the city page and different details of the City was obtained.
So I made a list of the City links.

Step 6 :- Anoher Observation is that on each and every city page on the left side there was a table and on thefirst 3 rows pictures and the names of famous
tourist attarctions were mentioned as links.

Step 7 :- Obtaining that data in each and every city page , hence we obtain the main attraction of each and every city. hnec made it to a dataframe.

Step 8 :- Concatenated two data frames
Data frame1 :- City name, state Name, Rank
Data frame 2 :- Famous attraction of the cities

Step 9 :- Converted into a csv format.
