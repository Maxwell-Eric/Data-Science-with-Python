## This project predicted obesity rates of large cities.
This data science project used the website www.city-data.com to scrape information about major cities in the US, which was then used to predict the cities obesity rates. 

The code iterates through each state creating a links to the majors cities and stores them in a CSV file.

The code then iterates through each city link and obtains the city, state, population, median household income, education rates, unemployment rates and obesity rates. 

The other attributers are used to predict obesity rate for the city using the RidgeCV linear regreassion model with 10 fold cross validation.
