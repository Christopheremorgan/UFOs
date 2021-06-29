# UFOs

## Project Overview
Build a web page app for UFO enthusiasts about documented UFOs sightings in the US and beyond.  The web page includes a table of known sightings that can be filtered on multiple criteria. The web app was built using Javascript, HTML, and Bootstrap and uses data stored in a Javascript array to build a dynamic table that filters on user input.


## Results

#### On the landing page there is an explanation of the research and intent of the webpage following a graphics banner with an image background.
![image_name](https://github.com/Christopheremorgan/UFOs/blob/main/resources/landing_page.png)
---

#### To navigate to the documented UFO sightings table you must scroll down below the web page's purpose statement.
![image_name](https://github.com/Christopheremorgan/UFOs/blob/main/resources/landing_page_scroll.png)
---

#### Multiple filters can be applied via the filter input boxes on the left hand side of the screen.  In the image below shows the results from applying a country filter of 'us' and a shape filter of 'triangle'.
![image_name](https://github.com/Christopheremorgan/UFOs/blob/main/resources/first_filter.png)
---

#### We can add filters or remove filters as we go.  In the image below we applied a state filter of 'ca' so only sightings in California are displayed.  This is in addition to the filters applied in the previous image.
![image_name](https://github.com/Christopheremorgan/UFOs/blob/main/resources/second_filter.png)
---

#### Keeping all prior filters, we add the city filter of 'el cajon'.  Notice that two sightings were logged on the same day in El Cajon, CA.
![image_name](https://github.com/Christopheremorgan/UFOs/blob/main/resources/third_filter.png)


## Summary of Opportunities for Further Development 

#### Design Layout Drawback
One drawback of the current web page layout is that the dynamic table is 'hidden' when first landing on the page.   The user must scroll down to get to the table and the filters.   A potential layout opportunity is to place the page summary in a 'window' on the left side of the page while the filters and table are in a slightly wider window on the right side of the page.

#### Further Development Opportunities
If a user mistypes or enters a filter parameter that does not exist in the table, the table 'disappears' (possibly abducted) because there are no matches in the table.  To help users avoid 'no return' filters, drop down boxes or autfill guides are potential opportunities for future development.

One other development opportunity to consider is to add hover-over call-outs to share additional information available in the data.js file (length of time, additional comments) not included in the dynamic table.


## Links to Coding Files

[app.js](https://github.com/Christopheremorgan/UFOs/blob/main/static/js/app.js) 

[index.html](https://github.com/Christopheremorgan/UFOs/blob/main/index.html) 

[data.js](https://github.com/Christopheremorgan/UFOs/blob/main/static/js/data.js) 
