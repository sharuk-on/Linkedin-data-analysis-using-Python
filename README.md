# Linkedin-data-analysis-using-Python
## Data scrapping, data cleaning , wrangling and analysis using python. 

This project contains data scrapped from linkedin on job offer for data analyst in india. The data was scrapped using Octoparse program on 29/11/2021. It is relative small dataset.
This dataset contains 6 months job offering in LinkedIn with various field like company, locations, time posted, job position etc. 

Data cleaning:

Just like any data scrapped from web, this dataset also littered with missing data, null values, values with spaces and new line characters etc. by now you would have guessed it, this data definitely need some cleaning.
Most of the cleaning done with the help of split, replace and sometime with regular expressions. Replacing null values in every field, even removing some fields etc... Proceeding to next step with cleaned dataset.

Data wrangling:

Before doing any type analysis we need to breakdown some data to their discreet form. Like extracting city and state from locations, month from date posted and so on. There are some obstacles as expected and all of them arise from same 33 unconventionally termed data with no definitive patterns to break them down. As already mentioned size of the dataset at hand, it is apparent every data counts. With some manual tweaks they are good to go.

EDA, analysis and visualization on progress
