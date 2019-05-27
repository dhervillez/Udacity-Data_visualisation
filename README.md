# Udacity-Data_visualisation
Github backup of US flight delays data visualisation project

## Summary

Aim of the project is to visualize average US flight delays averaged by days on the period 1987-2008.

Data are
  - downloaded from http://stat-computing.org/dataexpo/2009/the-data.html
  - wrangled with python (pandas) to be synthetized in a smaller format ready to use by d3.js
  - visualized thanks to d3.js

My data visualization should be
  - self explanatory (with very limited text)
  - animated and interactive to practice both the writter driven and reader driven narrative approaches
  - simple and nice looking


## Design

I choose to build a calendar heatmap
  - the x-axis represents the month of the year
  - the y-axis represents the days of the week
  - each block of the heatmap is colored by the flight delay in minutes

The heatmap will be animated by year at loading. <br/>
Reader will then be abble to scroll through the years to better compare the flight delays accross time.

## Feedback

  - some rectangles are white --> fix the color scale
  - I would like to scan through the years
  - I would like to select a given year

## Resources

My google research on calendar heatmap with d3 lead me to the following website. <br/>
I adapted some of the d3.js scripts found on these websites for my project.

https://observablehq.com/@d3/calendar-view <br/>
https://blog.risingstack.com/tutorial-d3-js-calendar-heatmap/ <br/>
https://www.crowdanalytix.com/communityBlog/10-steps-to-create-calendar-view-heatmap-in-d3-js <br/>
