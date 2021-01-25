# ***UFO Sightings with JavaScript:***
## ***Overview of Project:***
UFO Sightings is a project which has been built to design a dynamic webpage using a front end development language.
By using JavaScript, a static webpage can be converted into a dynamic webpage by adding some functionality and customization to keep the user engaged and hence provide enhanced user experience at the run-time of the webpage or a complete website in general.

This webpage, in here, for this project, is built to present an instance of user interaction with the webpage, where the webpage accepts inputs from the user, and the results are automatically adjusted and hence reflected immediately on the web page. This inter-activity has been made possible by inserting JavaScript into an HTML webpage. Also, some CSS and Bootstrap has been used for styling of the webpage. The webpage has been tested for functionality using Chrome Developer tools on a local computer.

## ***Results:***
On this webpage, a user can enter options to filter the UFO sightings data based upon parameters such as date, city, state, country and shape. Once the values have been entered in for any or all the filter options, in the designated placeholders, the relevant sightings' data gets filtered out based upon the options user entered and is displayed right away in a neat table along side the filters, on the webpage.

The webpage also displays an impressive header, article summary and a brief article about UFO sightings The end results is a visually appealing webpage which is also interactive.

Below are some screenshots which display how the data in the table gets transformed to only display the data on the basis of chosen filter values.

### ***No Filters entered***

![](https://github.com/kirtibhandari/UFOs/blob/main/Resources/No_Filters.png)

### ***DATE filter***

Only DATE entered to filter data for a date 1/2/2010. Any date can be entered from the date chosen from dates which get displayed when the page was loaded afresh, with no filters, so that it displays results for that date only.

![](https://github.com/kirtibhandari/UFOs/blob/main/Resources/Date_Filter.png)

### ***Date and City Filter***

Now, we want to filter the above results on city basis along with already selected date. 

![](https://github.com/kirtibhandari/UFOs/blob/main/Resources/Date_and_City.png)

### ***COUNTRY filter***

The below image shows data in table when only 'ca' country selected.

![](https://github.com/kirtibhandari/UFOs/blob/main/Resources/country.png)

Thus, a user can apply only one filter or multiple filter options can be entered for multi-level filtering from the given parameters.

## ***Summary:***
 ### ***Drawback:***
 - This page uses only the data from a stored table at the back end, to display the information in the table, which does not have the updated real time information at all the times.

 ### ***Recommendations:***
 - Additional filter for the display of a RANGE of data can be added to enable the user to see data between two DATES.

    ***For example:*** FROM Date: 1/1/2010 TO Date: 1/4/2010
    The result should be all the UFO sightings between these two dates inclusively.

 - An additional functionality which enables users to select count/number of values, they want to choose from, for a parameter, may be added and code can be refactored accordingly.

    ***For example:*** User wants to see data for more than 1 countries, states, cities or shapes, or even for more than 1 dates, instead of a date range.
    
    User can be asked if he wants to see data for one city or multiple cities,say. Then, user can enter , for instance , 3 as the value. Then, 3 placeholders may be displayed as a result. User enters 3 cities in those dynamically generated city placeholders and the data in the table is then filtered out for 3 cities instead of only 1.

Live Glimpse of my project is avaialable at: https://kirtibhandari.github.io/UFOs/
