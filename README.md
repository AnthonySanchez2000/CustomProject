# Data Origin
I downloaded the .csv file of a dataset, provided by [OurWorldinData.org](https://ourworldindata.org/grapher/annual-number-of-deaths-by-cause?time=1990..2019), that tolls 33 different causes of deaths for various countries/regions between 1990 and 2019. I made minor formatting changes and saved it as an .xslx file. I imported the .xslx file into my Microsoft SQL Server Studio

# First Query
Although the Studio import wizard confirmed the data was properly imported, my [initial](https://github.com/AnthonySanchez2000/ProjectPortfolio/blob/main/QueryStep1SelectAll.sql) query was to double check that I can see the table

# 2
To build off the initial query, I wanted [a new field that summed all the causes of death for each record](https://github.com/AnthonySanchez2000/ProjectPortfolio/blob/main/QueryStep2SelectAllDeathTotal.sql)

# 3
I wanted to see the entire table but [exclude the countries/regions that were not the United States, Canada, and Mexico](https://github.com/AnthonySanchez2000/ProjectPortfolio/blob/main/QueryStep3SelectUSCanadaMex.sql)

# Final
Combining my 2nd and 3rd queries, my [4th query](https://github.com/AnthonySanchez2000/ProjectPortfolio/blob/main/QueryStep4SelectUSCanadaMexDeathTotal.sql) would display the whole table but only include the U.S, Canada, and Mexico. Then, the death tolls would be shown in the last field.
