# UFOs

## Overview 

For this project, I was tasked with creating an active interactive HTML webpage, in which any user could click onto the website and be able to filter through the search criteria in one or all of the search fields, as desired. I was given a dataset in a JavaScript file, that contained information on various UFO sightings recorded from various countries, and I used that dataset to determine what type of search fields to create, for the user to filter, while using the webpage. In my index.html file, I used CSS and Bootstrap to create how my webpage would look, for example, where to put the paragraph text vs. the data table, the image displayed in the header of the page, and the color or text styles used throughout the webpage. I used the D3 library to be able to select the data from the 'data.js' file, and create an event listener, which will call upon my filter functions in my 'app.js' file whenever the user changes their filter criteria.

## Resources 

* Software/Libraries:
  * JavaScript
  * D3 Library
  * HTML
  * CSS 
  * Bootstrap

* Data: [data.js](https://github.com/Lucky777b/UFOs/blob/main/static/js/data.js)

## Results/How To Use UFO Finder Webpage 

[UFO Finder Webpage](https://lucky777b.github.io/UFOs/)

The link above, [UFO Finder Webpage](https://lucky777b.github.io/UFOs/), will direct the user to the 'UFO Sightings' HTML page. This link is also an active webpage, in which, the user can open the link, and start filtering in any one of the 5 'Filter Search' boxes, located in the bottom left-hand side. The image below is an example of what should be seen upon accessing the link above.

[startupPage](https://github.com/Lucky777b/UFOs/blob/main/static/images/UFO_startup_page.png)

The beauty of this webpage is that the user does not have to fill out all of the filter boxes in order to create their search. The image below exemplify how the user can input text into just 1 filter search box, and still get results after they press enter. 

[apply1filter](apply_1_filter.png)

This is what it would look like if the user applied text into only 2 of the filter search boxes: 

[apply2filters](apply_2_filter.png)

This last image shows how the user can apply 4 filter searches and still retrieve results. 

[applymultiple](apply_multiple_filters.png)

All of these examples were used to show how a user can filter through the UFO sightings data using one or all of the search fields, and this is useful for a user who maybe wanted to see all sightings in one state, one country, and then incorporate more filters to be more and more specific, like on certain dates or certain shapes. 

Now, to return back to the main page, for example, where none of the filter search fields were applied, the user can click 'UFO Sightings' in the upper-left-hand corner of the webpage: 

[mouse](mouse_pointer.png)

Or, the user can just clear all of the search fields and then hit 'Enter' on their keyboard, and the webpage will refresh to its original state, which shows the entire dataset, once again. 

## Summary