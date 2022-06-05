# UFOs Sightings Analysis

## Overview of Project

Analysis of UFO sightings using a web app.

### Purpose

Create a web app using HTML and JavaScript to perform an in-depth analysis of UFO sightings with user input filters for multiple criteria at the same time. The filters should include date, city, state, country, and shape.

## Results

* Step 1: Go to the UFO Sightings webpage, you'll see the following page. 
* Link to webpage: https://psidhu42.github.io/UFOs/ 

!["Main Page"](https://github.com/psidhu42/UFOs/blob/main/resources/main_page.PNG)

* Step 2: Scroll down to view the default data table. The columns consist of "Date", "City", "State", "Country", "Shape", "Duration", and "Comments". To the left of the table is the "Filter Search" section, if you are on a smartphone, the "Filter Search" section may appear above the default data table.

!["Filter Search and Table View"](https://github.com/psidhu42/UFOs/blob/main/resources/filter_and_table.PNG)

* Step 3: To filter the table for different results enter a value for one or more of the categories and then press the "Enter" or "Return" key on your keyboard. See image below for example of filtered table results with "ky" as the state.

!["Filtered Table Example"](https://github.com/psidhu42/UFOs/blob/main/resources/filtered_search_example.PNG)

* Step 4: To reset the table to show the default data, scroll to the top of the page and press the "UFO Sightings" text in the top left corner.

!["Reset Table"](https://github.com/psidhu42/UFOs/blob/main/resources/reset_table.PNG)

## Summary

Although the filter search works well, it can cause confusion if the entered criteria text is in the wrong capitalization. For example, above "ky" was used to filter the table, if the user entered "KY" the filter search will return no results. The entered text has to be an exact match, and thus makes this method of filtering unreliable.

One recommendation would be to allow a more flexible text input, so "ky" and "KY" or even "Ky" for example would return the same filtered results. Another recommendation would be to add a "keyword" search box that could search with-in the "Comments" column to potentially return even more precise results that a user wants.