# UFOs
## Overview of the Project
The purpose of this project is to build a webpage that will allow a visitor to filter results of a table which lists UFO sightings. The filters are dynamically applied to the initial table using javascript functions. The functions allow multiple filters to be applied at the same time, allowing users to narrow down the results more easily.
## Results
The table begins with no filters active and all results presented to the user as shown below.
![No Filters](https://github.com/JorMerr/UFOs/blob/main/static/images/no-filters.PNG)

The table will filter results when the user inputs text into one of the filter fields and pressing `Enter`. The input must be in lowercase, otherwise no results will be returned. 
If there are no sightings in our dataset which match the filter applied, the table will be empty. Below, we can see the results when Canada is searched in the Country filter.
![Country: Canada](https://github.com/JorMerr/UFOs/blob/main/static/images/filter-country-Canada.PNG)

Filters are saved when applied, so the user is able to apply multiple filters, such as the City of El Cajon, and the Type of Light, shown below.
![City: El Cajon, Type: Light](https://github.com/JorMerr/UFOs/blob/main/static/images/filter-city-El_Cajon-type-Light.PNG)


## Summary
The webpage will now dynamically filter the UFO sighting data using the filters specified. Each filter input is saved when the input changes, which allows for the ability to filter with multiple inputs. The webpage still contains the navbar link which allows the table to reset back to the original state with no active filters.
One drawback of this page is that the filters are case sensitive. If a filter such as the State is input as uppercase letters, then the table will not generate any results. 
It is recommended to build code into the filter function to have any input use the .toLowerCase method to allow for filtering in both lower and upper case. It is also recommended that 