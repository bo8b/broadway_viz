## Financial and Attendance History for Broadway Theatrical Productions

Bob Manasco
bobmanasco@gmail.com
29 July 2020

### Overview

In this narrative visualization, I examine the history of Broadway shows as far back as 1901.  I look at attendance trends over the past 25 years, and then delve more thoroughly into the financial gross revenues for recent productions.

Data for the charts contained in this Data Visualization project have been retrieved from the website Towards Data Science (full reference is contained on the website).


### Messaging

The message being communicated through this data visualization is that Broadway producing strategies have changed over time.  As time passes, producers mount fewer productions, but the shows that do get produced appear to be more successful, at least by attendance and gross income standards.

### Narrative Structure

I have followed the “martini glass” approach to narrative visualization.  This was accomplished by having a few screens with very little interaction, to set up the information I am trying to convey.  Then, in the final chart, I allow some limited filtering and popovers for displaying additional information so that the reader can explore the data more fully.

### Visual Structure

The scenes in this narrative visualization are made up of a scene with no graph at all, merely text introducing the topic and setting up the coming visualizations, then a bar chart graphing number of new shows by year over time, then another bar chart graphing the attendance rate of shows by year over time, and finally a scatterplot showing the correlation between attendance rate and gross profit by show.  This way, we start with the most general information (number of shows) with the widest parameters (1901-2018), then narrow the scope a bit and focus on one measure of success (attendance rate) for a smaller date range (1998-2018), and finally display specific data for each show in this subset, allowing readers to see the strong correlation between attendance and gross income.

Each of the scenes that contain charts also follow the same format: a title, a short text introduction, the chart itself, then a more lengthy text description of what the chart is showing.

The annotations for each scene all use the same sized black font, connected by a black line, to a dark grey line that shows some key point or trend in each scene.  The only difference is on the final graph, where the text is still the same size and font, but is color-coordinated to the type of show being highlighted.

There are several parameters used in this narrative visualization, that all relate to historic Broadway productions: Year, Number of Openings, Percentage of Available Tickets Sold, Weekly Gross Revenue, and Show Type (Musical or Play).  The Number of Openings is graphed by Year in the first bar chart.  The average Percentage of Available Tickets Sold is graphed by Year in the second bar chart.  In the final scatterplot, Weekly Gross Revenue is plotted against Percentage of Available Tickets Sold.  Readers can filter by Show Type, and this adjusts not only the specific show data that is displayed, but also the trend line adjusts by the data shown.  Finally, readers can mouseover the specific data points to see additional popover information about each production.

Moving the mouse over the legend is the trigger that filters the data displayed on the screen and displays the new trend line for the filtered data.  The scene contains an on-screen tool tip informing readers of this filtering ability.  Also, moving the mouse over specific data points will pop up additional information about the show.

