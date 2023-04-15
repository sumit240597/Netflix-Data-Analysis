#                                                                     Netflix-Data-Analysis  


# OVERVIEW:-

This NETFLIX data has information about the TV Shows and Movies avialable till 2021.
This dataset is avialable on Kaggel.

I have perform some steps of EDA with the help of all importnt libarries.

# Data Cleaning:
I have perform data cleaning process with dupliacted ,isnull method and dropna method also for droping null values.

![image](https://user-images.githubusercontent.com/125980712/232229222-473d4381-52e9-4543-b0a6-275682f23611.png)


# Data Visulization:

With the help of matplotlib and seaborn libraries and groupby method i have perform some visulization.

-- For finding in which year  most of the movies and TV Shows realsed. 
I add a new coulmn in the data because in the existing data set there is only Realese Date is present in Object type, for the purpose i added a new column DATE and change its Datatype into DATETIME to perform the above statemnet
After that one more column added on the name of YEAR for extracting the Years from DateTime column

-- To finding out the Minimum and Maximum durations of TV SHOWS and MOVIES.
I have perfrom def function because in the Durations cloumns Movies duration was given in minutes but TV Shows given in SEASONS so for that purpose i have created 
a def function assuming that the 'Season' values to minutes, you would need to know the number of minutes each season corresponds to. 
This value may vary depending on the context of the data, but for the purpose of this example, let's assume that in  one season there is 8 episods with duration
of 60 mins each equivalent to 480 minutes.

