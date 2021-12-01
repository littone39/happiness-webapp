AUTHORS: Jayti Arora, Emily Litton

DATA: World Happiness Report 2005-2021. Includes information from Gallup Poll about
country happiness (life ladder), gdp, social support, and other related quality of life 
statistics over time.

STATUS: Users can view data for a single country on the 'Map' page by clicking a country 
on the map or selecting one from the drop down menu. The data displayed is from the most 
recent year and then there is a small graph that shows happiness over time. Users can also 
create a scatter plot comparing happiness score to another variable on the page titled 
'Plot'. Navigation works and home/about pages provide additional information. 
All features are working.

NOTES: To use this app, clone this repo and pull data from data.sql into a postgreSQL database. Next, 
add a file called config.py with the following format: 

    user: "<username associated with the database>"
    password = "<password for db>"
    database = "<name of db>"

Now type "python3 app.py localhost 5000" into the command line to view webapp
at localhost:5000 on your browser. 