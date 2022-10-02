# Data Visualization Assignment Two - Geographic Vectors

The geographic vector data
As the second assignment, we note that student always have the freedom to construct visualizations using previously used technologies. For example, the main idea of this assignment is to create a data-map, but, if the hypothesis demands it, feel free to incorporate a scatter plot, time series, histogram, or bar chart. This will always be true of our assignments.

Data Relation:
A set of points, distributed on the surface of Earth, or other planet. Each point registers the location of a feature of interest. In some cases, there is a relationship between the points, as they define a road, or a political boundary. Other times they are independent, like cities. Locations may have additional data attached to them, such as the size of the city, or the number of lanes in a road.

English Language Description:
Here, ordered pairs are longitude and latitude. Special care must be taken to ensure that the projection of points on the surface of a sphere (longitude/latitude pairs) to a plane (such as a Mercator projection) is done correctly and consistently. In plain English, you are supposed to create a map that includes points or lines that show data, and other lines, like political boundaries or rivers for reference.

Data Sources:
Mostly, you'll have an easier time if you get geojson formatted data. Most states and municipalities maintain geographic data sets for public use. Political boundaries are held within many (all?) states as part of their digital assets. Aggregations are also common at places like geoboundaries.org. Open street map is an amazing (overwhelming?) resource. There are numerous vector maps of interesting points, like cities, cell phone towers, mines, Walmarts, etc. Consider some of the historical databases too, for example, there are databases of ancient cities that include features for the cities. Awesome-geojson is a clearing house of geojson utilities, converters, and data sources. Some high quality data can only be accessed using the ArcGIS REST API. This API is confusing for a newcomer but is common for state geographic information system (GIS) data. For example,  this page describes data on the dams in Montana. If you go to the bottom to query that dataset, you get this page. To get the geojson of the data, enter something that is true in the first field (1=1 works, not 1==1) and then the final pulldown menu should be geojson no other options need be changed. (Thanks to Hannah and Lindsey for figuring this out!)

Example Hypotheses:

Rivers and cities are usually close. So are roads and cities. The largest rate of growth is currently in cities in the mountains. Coastal cities have more irregular networks of roads around them than do cities on the plains. Walmart is spreading in Mexico. The craft brewery craze is slowing, except in Portland OR. Cellphone tower density is lowest in mountainous regions.

Required Software:
Vega, Vega-lite, or D3 for CS students. Tableau or plotly for non-CS students.

Submission:

Students must post a link in the comments section for assignment submission to the appropriate portion of their github hosted web pages. On those web pages, I should find a clear statement of the hypothesis, data sources, and two data visuals. 

Students must also upload a single file that is an annotated version of the web page submitted. When printed, this annotated version must be no more than 8.5 x 11 inches.

On the same day the work is turned in, 5 students will be randomly called upon to present their work to the class for comments. Presentations must be 10 minutes or less!
