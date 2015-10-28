# INFM600_Akshata.Salehittal



----
DESCRIPTION
----



The data sets in this assignment were collected to analyze how safe the surroundings of Elementary Schools (in terms of road safety) are in the Howard County Area. Data sets related to my project were difficult to combine due missing data in many tables. I chose these tables as I felt I could do a better analysis.



----
Schools_Elementary.csv
----


This data set contains details of different Elementary schools in the Howard County area with their Names, their Street Addresses and City along with their Zip code. It also contains the Geometric Locations(Geographic Informations) of the schools with their point geometric locations. Each school contains a unique school ID with which any details of the school could be queried. 

Reference: Howard County Maryland (2014). Schools-Elementary [Data File].Retrieved from https://data.howardcountymd.gov/



----
Sign_Stop.csv
-----

This data set contains details of Stop Signs around Howard County. It particularly contains a unique ID for each sign, the size of each sign, the specific date when the sign had been installed, the kind of post i.e. the material with which it has been made i.e. wood/metal, the authorities it is maintained by, i.e. the County/School/State, and Point Geometric Locations(Geographic Informations).

Reference: Howard County Maryland. Sign-Stop [Data File]. Retrieved from https://data.howardcountymd.gov/



----Sign_Warning.csv
-----

This data set contains details of different warning signs around Howard County. It particularly contains a unique ID for each warning sign, the size of each sign, the specific date when the sign had been installed, the kind of post i.e. the material with which it was made i.e. wood, metal or other, the name of the sign and its Point Geometric location(Geographic Informations).

Reference: Howard County Maryland. Sign-Warning [Data File]. Retrieved from https://data.howardcountymd.gov/




----Combined_Dataset.csv-----
This table contains the columns from Schools_Elementary.csv and Sign_Stop.csv combined together.
Reference: Akshata Salehittal. Combined_Dataset [Data File]. Retrieved from https://drive.google.com/open?id=0B6hNVHNzQBN3eXJDNlNfQmk4dFU

----RESEARCH QUESTION
-----

1.Is it more likely to find a School in an area with more than 40 stop signs?


I would want to see the results reported in the form of maps where each geometric location of either a School, Warning Sign or Stop Sign would clearly be visible. 

This way we could easily visualize whether the Signs are actually placed near the School locations or not.
The best way to represent the map would be to give different colors to the Signs and Schools, so as to make it easily viewable and to get a good idea of the signs around the Schools.




On Excel, we could represent the data in a way that would calculate the distance between the coordinate values of the Stop/Warning Signs and Schools and would give us an approximate closest distance. This way we can understand and look at how many signs are near each school and therfore answer our research question.

----PROCESSING DOCUMENTATION
-----
The enitre process of combining the tables has been documented in a word file "Processing_Dcocument.doc"

----License-----
This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/.


  