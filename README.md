# Using Javascript to Enhance the Visual Appeal and Functionality of a Simple Web Page
## Overview of Project
Javascript (JS) is  a programming language that, along with Hyper Text Mark Up Language (HTML) and Cascading Style Sheets (CSS), forms the foundation of web pages and the World Wide Web.  Wherein the uses of Javascript have been increasing since it’s initial development in 1995, the primary application of Javascript in web page design is to assist in the creation of dynamic and visually appealing content.  The purpose of this analysis was to use Javascript to assist in the creation of a web page for displaying and filtering, based on user input, information pertaining to sightings of Unidentified Flying Objects (UFO’s) in the United States of America (USA). 

## Results
In its default, or “loading” configuration, the web page produced displays a title, a catchphrase (along with an image) some background information and, most importantly, all available UFO sighting data along with filtering options at the bottom of the page (See Figure 1).

### Figure 1: The UFO Web Page in Loading Configuration
![]( https://github.com/Scruffy-Bearie/UFO/blob/main/static/images/Figure1.png)

The data filtering option was programmed to display all “filtering fields” along with “place holders” so that a user would be able to immediately see not only what options existed for filtering the data but also how the desired search/filter criteria should be entered into each field (See Figure 2).

### Figure 2: Close up of Filtering Fields Displaying “Place Holders”
![]( https://github.com/Scruffy-Bearie/UFO/blob/main/static/images/Figure2.png)
 
 The data filtering option was also programmed such that once the desired filter/search criteria had been entered according to the format indicated by the “place  holder”, the user had only to hit the “Enter” key or “left click” on their mouse anywhere outside of the filter field to initiate the search (See Figure 3).

### Figure 3: Sightings Data Filtered to Display Sightings in “Florida”
![]( https://github.com/Scruffy-Bearie/UFO/blob/main/static/images/Figure3.png)

Finally, the data filtering option was programmed such that data could be filtered according to multiple criteria by simply entering the desired parameters into each field in the format indicated by the respective “place holders” (See Figure 4).

### Figure 4: Sightings Data Filtered to Display Sightings of “Spheres” in “Florida”
![]( https://github.com/Scruffy-Bearie/UFO/blob/main/static/images/Figure4.png)

## Summary

Although the web page designed meets the desired criteria and it aesthetically pleasing, there are a few drawbacks and functional limitations which could be addressed in future iterations:

•	The filter fields, although containing “place holders” to indicate “how” search parameters should be entered, do not make it obvious “what” search options are actually allowed/permitted/accepted.  Future iterations of the web page could/should include drop down menus for each filter field from which the user could select search options or at least be able to see what options are allowed/permitted/accepted.


•	The search parameters are “activated” (the data set is filtered) after each individual parameter is entered which, for the limited data set being accessed/searched, is acceptable but may prove annoying/time consuming if a larger/more complete data set were ever to be linked to the web page.  Future iterations of the web page could/should “re-introduce” the “search button” that was removed from the initial design such that a researcher could enter their desired search parameters into the filter fields and then “click” on the button to activate the search (instead of having each individual parameter searched in succession).

•	As currently programmed, the web page displays all results from the current search on the same page meaning that if the search returned a large number of results, the user must scroll down and the filter fields (and the parameters entered) are no longer visible.  Future iterations of the web page could/should be programmed such that a limited number of search results are displayed in the data field at any one time with an option for the user to (with a “click”) repopulate the field with the “next” page of search results.  As such it would be possible for the user to examine the search results while still being able to see the search parameters which generated those results.

Wherein the researcher/programmer truly believes that each of the suggestions outlined above would improve the overall quality/functionality of the web page, it is difficult to know at the moment whether the programming time required to achieve those improvements would be economically feasible.
