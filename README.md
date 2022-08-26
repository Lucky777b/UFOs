# UFOs

## Overview 

For this project, I was tasked with creating an active interactive HTML webpage, in which any user could click onto the website and be able to filter through the search criteria in one or all of the search fields, as desired. I was given a dataset in a JavaScript file, that contained information on various UFO sightings recorded from various locations in the US, and I used that dataset to determine what type of search fields to create, for the user to filter, while using the webpage. In my index.html file, I used CSS and Bootstrap to create how my webpage would look, for example, where to put the paragraph text vs. the data table, the image displayed in the header of the page, and the color or text styles used throughout the webpage. I used the D3 library to be able to select the data from the 'data.js' file, and create an event listener, which will call upon my filter functions in my 'app.js' file whenever the user changes their filter criteria.

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

![startupPage](https://github.com/Lucky777b/UFOs/blob/main/static/images/UFO_startup_page.png)

The beauty of this webpage is that the user does not have to fill out all of the filter boxes in order to create their search. The image below exemplify how the user can input text into just 1 filter search box, and still get results after they press enter. 

![apply1filter](https://github.com/Lucky777b/UFOs/blob/main/static/images/apply_1_filter.png)

This is what it would look like if the user applied text into only 2 of the filter search boxes: 

![apply2filters](https://github.com/Lucky777b/UFOs/blob/main/static/images/apply_2_filters.png)

This last image shows how the user can apply 4 filter searches and still retrieve results. 

![applymultiple](https://github.com/Lucky777b/UFOs/blob/main/static/images/apply_multiple_filters.png)

All of these examples were used to show how a user can filter through the UFO sightings data using one or all of the search fields, and this is useful for a user who maybe wanted to see all sightings in one state, one country, and then incorporate more filters to be more and more specific, like on certain dates or certain shapes. 

Now, to return back to the main page, for example, where none of the filter search fields were applied, the user can click 'UFO Sightings' (as shown below, where the mouse cursor is pointed/hovering over 'UFO Sightings') in the upper-left-hand corner of the webpage: 

![mouse](https://github.com/Lucky777b/UFOs/blob/main/static/images/mouse_pointer.png)

Or, the user can just clear all of the search fields and then hit 'Enter' on their keyboard, and the webpage will refresh to its original state, which shows the entire dataset, once again. 

## Summary

One drawback of this webpage is that the data is stagnant, meaning that it only contains what it contains, if someone wanted to see recent citings in the past couple days of their search, they wouldn't be able to because the webpage isn't pulling the data from an external website. Instead, it is just retrieving the results from an already compiled dataset, which in this dataset is only from sightings during the year 2010. 

It should also be noted that the dataset only contains data from the US, and not other parts of the world, which makes the 'Country' filter obsolete for this webpage. One way to fix this is to pull more datasets that incorporate UFO sightings from other countries.

This drawback could be mitigated by setting up an API with an external website that incorporates data that is dynamic and is consistently being recorded as each day progresses. This could allow for more relavent data results, and being able to retrieve current data could be more valuable to a user that wants to see UFO sightings that may have occurred recently in their area, or if they thought they saw something, then they could see if someone else saw something around the same date that they did. 

Even though I was proud of what I was able to create, I did notice a couple of things that I would like to learn how to do for this webpage or any future webpages that I create. One thing I would want to incorporate is the ability for the page to just refresh on its own, for example, the dataset would change as I am typing in my filter searches. I think this would be helpful for the user because they might not know what cities, states, or dates are in the dataset to filter, or if they were incorrectly spelling something within a search field, the result would just return nothing. If the ability for the page to 'change' as they are typing was applied, then they could see what is or isn't in the dataset as they go, as well as, allow the user to catch any spelling errors before typing it all out and retrieving no information in their results. 