# Data Origin
I downloaded the .csv file of a dataset, provided by OurWorldinData.org, that tolled 33 different causes of deaths for various countries/regions between 1990 and 2019. I made minor formatting changes and saved it as an [.xslx file](https://github.com/AnthonySanchez2000/CustomProject/blob/main/WorldCauseofDeaths1990%20(SQL%20Import).xlsx). I imported the file into my Microsoft SQL Server Studio

# 1st Query
Although the Studio import wizard confirmed the data was properly imported, my [initial](https://github.com/AnthonySanchez2000/CustomProject/blob/main/SQL%20Queries) query was to double check that I can see the table

# 2nd
To build off of the initial query, I wanted [a new column that summed all the causes of death in each row](https://github.com/AnthonySanchez2000/CustomProject/blob/main/SQL%20Queries)

# 3rd
I wanted to see the entire table but [exclude the countries/regions that were not the United States, Canada, and Mexico](https://github.com/AnthonySanchez2000/CustomProject/blob/main/SQL%20Queries).

# 4th Query
Combining my 2nd and 3rd queries, my [4th query](https://github.com/AnthonySanchez2000/CustomProject/blob/main/SQL%20Queries) would display the whole table but only include the U.S, Canada, and Mexico. Then, the total death count would be shown in the last column.

# [Visualization](https://public.tableau.com/views/DeathsinNorthAmerica/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)
