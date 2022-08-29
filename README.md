# UFOs

## Overview 
The purpose of this analysis is to provide a location where users can view and query UFO sightings information. While the existance of UFOs may be questioned by many individuals there are also individuals who have believe they have seen UFOs in the past. 

The data was provided in a JavaScript file and containted the following informaiton:
 - Date
 - City
 - State
 - Country
 - Shape
 - Duration
 - Comments

To create the final website the following products/languages were used:
 - JavaScript
 - HTML
 - CSS

The web site allows users to scroll though a table of the full results or query the data to return a subset of the data. The user can query based on up to five attributes.

## Results

The url of the web site is: https://kkoehn8.github.io/UFOs/index.html

To query the data the user can enter their search parameters in the Filter Search section found on the left side of the website. 

![filter_search](https://github.com/kkoehn8/UFOs/blob/main/static/images/FilterSearch.PNG)

To conduct a search the user will do the following:
1. Enter the parameters in the search pages. The user can enter up to five search criteria in the search filters. For example, if the user wishes to query UFO sighting in Naples, Florida they would enter the value of naples in the City search and fl in the State search.
2. Press the enter button once the search parameters have been populated.

This will return the results of the search.

If the user wishes to reset the search there are two options:
1. In the search filter highlight the values and press the delete key, OR
2. Press the UFO Sightings text in the upper left of the website.

Either of these options will clear the search paramaters and return the complete unfiltered table to the user.

## Summary

The website is useful for users trying to query reported UFO sightings however there are some drawbacks of the website and some recommendations for further development.

One drawback of the webiste is that there could be better communication with the user when no results are returned. If a user selects filter parameters that return no values it would be useful if a message is returned stating "No UFO sightings match the filter parameters". This would give the user some additional information on why the table is blank. Without this the user may be wondering if they just need to wait or if the webpage got "hung up" when performing the query.

To increase the funcionality of the webpage the following items can be added: 
 - Change the filter control from a text box to a drop-down box that populates based on a user's typing. The existing conrol depends upon a user typing something correctly. If the control type is changed to a drop-down that populates based on a user's typing they can start typing a few letters and the values that match that will be populated. For example, if the user starts typing the letters "ca" in the City search it will populate cities in the data that start with those letters, therefore eliminating some typing errors.
 - Querying based on a date range. Currently the user has the ability to query based on a single date. The ability to query based on a date range would be useful. This could allow users to see patterns. For example, they may find that in a particular city for a particular weekend there were more UFO sightings than at other times. 