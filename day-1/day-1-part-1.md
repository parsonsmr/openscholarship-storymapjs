[Return to homepage](https://negeenaghassi.github.io/openscholarship-dataviz/index.html "Return to homepage") | [Day 1, Part 2 >](https://negeenaghassi.github.io/openscholarship-dataviz/day-1/day-1-part-2 "Day 1, Part 2") 

Reminder: Use the [ongoing discussion post](https://github.com/negeenaghassi/openscholarship-dataviz/discussions/8 "ongoing discussion post") for any questions or thoughts that come up. 
## Day 1, Part 1 (in progress)
Welcome to Day 1 of the session! Today, we'll be covering: 
* What is data? What is data visualization?
* Why visualize? 
* Types of data
* Chart types
* Design principles
* Basic math
* Sketching/planning a visualization
* Data storytelling

Before you get started, head over to the [discussion post to introduce yourself!](https://github.com/negeenaghassi/osssdv/discussions/2 "discussion post to introduce yourself!")

If you run into any issues using GitHub or have any other questions, please don't hesitate to reach out to me at negeena@uw.edu. 

### What is data? 
To get started, we'll begin at the foundation: defining data. There are endless ways to phrase what data are, but a simple way of thinking about it is that data are pieces of information that, when combined and analyzed, describe that information.

Some examples of data might include:
* Recorded temperature over time
* Number and titles of books in a library
* Number of pens you lose in a year
* Interviews with UW students in a research study 
* Latitude and longitude of your favorite restaurants in Washington 
* Census records
* Answers to a user survey 

Data can be composed of digital and analog records, can be quantitative, qualitative, or geospatial, and so on. It might exist in spreadsheet software or on the back of a napkin. You likely come across data everyday, even if it's not always remarkable! 
### What is data visualization? 
Data visualization takes data and presents it in a graphical form. Data visualizations can be created by specific software, digital technologies, or even by hand. Below are some examples of data visualizations. 

For a glossary of data visualization-related terms, please refer to the [data visualization guide](https://guides.lib.uw.edu/datavisualization/glossary "data visualization guide"). 

**Mona Chalabi, "When Americans eat pizza"**

<img src="https://pbs.twimg.com/media/DVnPimwU0AEaI21?format=jpg&name=small" alt="Hand drawn data visualization by Mona Chalabi of a pizza depicting that most Americans eat pizza as a snack" width="550"/>

***Dear Data*, "A week of media," Giorgia Lupi**

<img src="https://images.squarespace-cdn.com/content/v1/54eec73ee4b0ae0904da0e94/1433941845707-GH4P0OIO244E3KNZ0MMG/Giorgia_DearData_27_Back.jpg?format=1000w" alt="Hand drawn data visualization by Giorgia Lupi depicting the key to a visualization about time and type of media consumed in a particular week" width="550"/> 

<img src="https://images.squarespace-cdn.com/content/v1/54eec73ee4b0ae0904da0e94/1433941843429-VKOJQ8KMRSGLMLRTBCGO/Giorgia_DearData_27_Front.jpg?format=1000w" alt="Hand drawn data visualization by Giorgia Lupi depicting a visualization about time and type of media consumed in a particular week" width="550"/> 

**Stephanie Evergreen, Percent of people in poverty 2009-2017**

<img src="https://i2.wp.com/stephanieevergreen.com/wp-content/uploads/2021/04/Equality4-1.jpg?ssl=1" alt="Slope chart that indicates that the percent of poverty has decreased between 2009 to 2017 for all racial groups except for Native Hawaiians and other Pacific Islanders." width="550"/> 

**Nathan Yau, "Where People Are Married and Not"**

<img src="https://flowingdata.com/wp-content/uploads/2021/05/prevalent-marst-desktop.png" alt="Choropleth map that indicates where people in the United States are married or not married with a high prevalence of marriage in the center of the US." width="550"/> 

### Why visualize?
There are many reasons to visualize data. An incomplete list is below:
* Communicate information in an engaging format
* Make it easier to absorb large quantities of data
* Identify trends and outliers in data

Sometimes, the reasons are less lofty: it's because our boss asked us to make one or because we need an image for a journal article. Whatever the reason, there are some general principles that will guide any visualization, which will be covered this week. 

## Types of data
There are two primary types of data: quantitative and qualitative. You will likely come across both types at some point. You may also come across geospatial data, potentially embedded in other types of datasets. 

Quantitative data is typically numerical and can be counted or compared. Put simply, if you can do math with the data points, it is likely quantitative. Some examples of quantitative data include:  
* Temperature in Seattle over the past ten years
* Number of books checked out of the library over an academic year
* Class average on a midterm

Qualitative data, on the other hand, is descriptive and is often in a narrative form. It tends to be comprised of text. Some examples of qualitative data include: 
* Interviews of health sciences professors at the UW
* Observations of otter behavior at the Seattle Aquarium
* Questionnaire about students' remote learning experiences

Geospatial data is different than quantitative and qualitative -- it is comprised of specific points on Earth. Some examples of geospatial data include: 
* Coordinates of your favorite restaurants in your hometown
* Coordinates of your route to school or work

The tool we will use this week is best suited for quantitative and geospatial data. 

### Chart types
There are several chart types that effectively communicate data. Some of the most frequently used chart types are described below. 

#### Bar charts
Bar charts are some of the most commonly used charts. They are great for comparing categorical data (for example, colors, book titles, departments, etc.). 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/barchart.png" alt="Example of a bar chart." width="1000"/> 

#### Line charts
Line charts are great at showing change over time. They are continuous and useful for comparing values over a period of time. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/linechart.png" alt="Example of a line chart." width="1000"/> 

#### Pie charts
The utility of pie charts is heavily debated in the data visualization world. Pie charts *can* be useful if they only present a few data points, are not cluttered but have labels, are 2-dimensional, they add up to 100%, and they are not from multiple points of time. They can quickly show parts of a whole. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/piechart.png" alt="Example of a pie chart." width="600"/> 

#### Maps
Maps are an intiutive and useful way to represent spatial data. They can identify the locations of places in relation to each other and can have data points attached to them. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/map.png" alt="Example of a map." width="750"/> 

#### Scatter plots
Scatter plots help identify the relationship (if any) between two variables. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/scatterplot.png" alt="Example of a scatter plot." width="750"/> 

#### Tables
Yes, tables can also be visualizations! Tables are a simple and effective way to compare variables against one another. Much like pie charts, they are most useful when they are not cluttered and include descriptive labels. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/table.png" alt="Example of a table." width="200"/> 

For further descriptions and examples of chart types, check out Chartio, Mike Yi and Mary Sapountzis, ["Essential Chart Types for Data Visualization,"](https://chartio.com/learn/charts/essential-chart-types-for-data-visualization/ "Essential Chart Types for Data Visualization") September 30 2019. 

Another useful tool for selecting an appropriate chart type for your data is [The Data Visualization Catalogue](https://datavizcatalogue.com/ "The Data Visualization Catalogue"). Not only does this site provide detailed descriptions of each chart type, it also has a function to [search by function/relationships](https://datavizcatalogue.com/search.html "search by function/relationships"). 



## Part 2
Whenever you're ready, proceed to [Day 1, Part 2](https://negeenaghassi.github.io/openscholarship-dataviz/day-1/day-1-part-2 "Day 1, Part 2") or [return to the homepage](https://negeenaghassi.github.io/openscholarship-dataviz/index.html "return to the homepage"). 
