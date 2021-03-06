# Surfs_up

## Overview of Analysis
The purpose of the following challange is to create a dataframe that contains dates and temperatures from a specific month from the the data that contains all the temperatures from specific dates. The two creates query has the month of June and the month of December. The month of June has 1700 temperatures associated with dates. And December has 1517 temperatures associated with dates. The dataframe is then used with the **Describe()** function. Which contains the count, mean, standard deviation, min, 25%, 50%, 75%, and max temperatures for each month.
## Results
### June Query Summary
> - Created a session query that uses the date of measurements from the data set, and then uses the tobs(temperature observations) of measurement from the data set, and then filtering the date by month and having the data filter by month that is equal to the 6th month.
<img width="132" alt="Temp_June" src="https://user-images.githubusercontent.com/97326526/166179856-b0a79c86-3066-4a96-ac62-e1fa9b6f0c99.PNG">

> - Creating a variable called results equal to the session query that was previously created.
> - Creating a dataframe that uses the variable results with column that are equal to the date and temperature for the month of June. And then using the **Describe()** function to show count, mean, standard deviation, min, 25%, 50%, 75%, and max temperatures.
<img width="131" alt="Desc_June" src="https://user-images.githubusercontent.com/97326526/166179864-2b243bdc-d2ba-43b0-8bdd-2b3901367f9e.PNG">
### December Query Summary
> - Created a session query that uses the date of measurements from the data set, and then uses the tobs(temperature observations) of measurement from the data set, and then filtering the date by month and having the data filter by month that is equal to the 12th month.
<img width="137" alt="Temp_Dec" src="https://user-images.githubusercontent.com/97326526/166180036-89baeb44-568a-4917-a4b0-dc2acf2c6cdc.PNG">

> - Creating a variable called results equal to the session query that was previously created
> - Creating a dataframe that uses the variable results with column that are equal to the date and temperature for the month of December. And then using the **Describe()** function to show count, mean, standard deviation, min, 25%, 50%, 75%, and max temperatures.
<img width="116" alt="Desc_Dec" src="https://user-images.githubusercontent.com/97326526/166180063-70db381d-012e-4fab-aedd-f96ac45d0c93.PNG">

## Summary
The following data shows that the temperature from June and December is pretty similiar with the average of June being 75 degree and December being 71 degrees, a 4 degree difference between the two months. The only difference between the two months is the mininmum temperature for June and December which is 64 degrees for June and 56 degrees in December which a 8 degree difference. And another difference between the two is the count June has a much higher count. June has 1700 measurements and December has 1517 measurements, which could mean there could of been a different avereage for the month of December with more measurement. A query that could show a more specifc area and lowerig the count for both months would be seeing the temperature for each month that relates to a specific station. Another query that could be used would also be a query that plots the dates and tobs that could show a histogram of how the temperature look on a graph and have visual representation of how the dataframe looks.
