# UFO

## Project Overview
Create a webpage and dynamic table that allows users to filter for multiple crtieria at the same time. Filters should include date, city, state, country and shape.

## Resources
- Data Source: data.js
- Software: Visual Studio
- Files: app.js, data.js, style.css, index.html

## Challenge Overview
One technical analysis deliverable and a written report:
- Deliverable 1: Filter UFO sightings on multiple criteria

## Results

### Deliverable 1: Determine the Summary Statistics for June
The webpage has been updated to include an image in the jumbotron and an article displays the purpose of the website and the data table. 

<webpage1>

To assist the user with navigating the data in the UFO sighting table, dynamic filters have been setup for specfic table columns in the UFO sighting data table. Using "d3.selectAll("input").on("change", updateFilters)", functionality has been setup that listens for each time a filter is updated and will fitler the table with the new results. 

<webpage 2>
 
As the user enters in filters, the table automatically filters the data accordingly.

<webpage 3>

## Summary

The drawback with the design is not knowing the range of data that the UFO sighting table holds. It's difficult to know how far back the data goes and how current it is. 

### Recommendations

- I would recommend creating a date filter that allows the user to put in a date range. The placeholder for that field or a side note provide below the date field could provide the user with a min and max date based on the table data.

- The fitlers are case sensitive. For example, if the user types in 'US' instead of 'us' it will return zero records. Coding needs to be added that will either change the users input to all lower case or ignore upper and lower case.

- It would be helpful to give the table dynamic sorting on each column. That would help the user to become familar with the min and max of the table. 

- For the fitlers, it would be more user friendly and avoid users misspelling and affecting their results, if each fitler were a dropdown with the available data options. City, State and Country should be a drop down of all geo options and the shape would be a list generated from the UFO sighting data table.




