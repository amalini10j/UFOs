# UFOs
UFO sighting analysis repository to analyze the UFO sightings data using javascript

## Overview of UFO Sighting Analysis
The objective of this exercise is to create a custom webpage to showcase different UFO sightings across the world. The basic requirement will be achieved by creating a table to organize the UFO data that is stored as a JavaScript array, or list. The functionality will be enhanced by adding filter capability to the table.

## Resources
**Data Source:** data.js
**Software:** JavaScript ES6+, CSS, Visual Studio Code 1.59, HTML

## Results
The webpage has a table with UFO sightings data and has the capability of filtering based on date of the sighting, city, country, state and the shape in which the sighting was observed.

The following image shows the Date and City filter in action. The table shows the data based on values entered in the two filters:

![FilteredTable](/FilterImages/Filters_Action1.png)

The following image shows all the five filters in action. The table shows the data based on values entered in all the available filters:

![FilteredTableAll](/FilterImages/Filters_Action2.png)

## Summary
The filters work well but there is scope of improvement.

### Drawback
- One drawback of the design is the way text filters work. The entire text is matched to get the relevant data but in a city filter even partial text match should bring up some data as the user enters it. Example - if user enters city as "el c" then it does not show any data. However, ideally the records for city el cajon should show up.

### Recommendations

- Make the text filters capable to compare partial text too
- The table can have an ajax call and filter data as user is typing in
- Having sort option on the table will make the webpage more usable 
- There should be a reset button below the filters to clear the filters and reset the table 




