# UFOs
## Project Overview
The purpose of this analysis is to create a webpage about UFO sightings with a dynamic table that responds to multiple filters. The webpage was built using JavaScript & HTML along with CSS styling. The table, filled with UFO sighting data, is able to be filtered by date, city, state, country, and shape.

## Results
The following steps walk through using the webpage filters:

- The filter pane is located about halfway down the page on the left hand side

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ![Filters](https://user-images.githubusercontent.com/90863226/145638682-bbad2337-e75d-4b2d-8b33-2c5a67281fd9.png)

- Input desired search criteria in one or more of the filters

&nbsp; &nbsp; &nbsp; &nbsp; Filtering using **ONE** filter:
![fl_state_filter](https://user-images.githubusercontent.com/90863226/145643170-e493ca2e-49a5-43eb-96dc-d968ece4a55a.png)


&nbsp; &nbsp; &nbsp; &nbsp; Filtering using **MULTIPLE** filters:
![state_and_shape_filter](https://user-images.githubusercontent.com/90863226/145641372-711355bc-2b9f-434e-848b-febd93f942a2.png)

- Clear the filter inputs to reset the table to include all UFO sightings


## Summary
This is a great start for this UFO sightings webpage, however there are a couple of drawbacks with the current design.  First the user can't easily tell how they are supposed to input each field, and secondly clearing multiple filters to get back to an unfiltered view is a little cumbersome.  With these drawbacks in mind I would suggest the following enhancements:

1. Changing the filters to be a date range selector for the date and a drop down list for the others with the ability to select multiple choices of each filter
2. Create a "Clear Filter" button that, upon clicking, clears all filters and resets the table back to the default view showing all data
