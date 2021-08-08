[< Day 1, Part 2](https://negeenaghassi.github.io/openscholarship-dataviz/day-1/day-1-part-2 "Day 1, Part 2") | [Return to homepage](https://negeenaghassi.github.io/openscholarship-dataviz/index.html "Return to homepage") | [Day 2, Part 2 >](https://negeenaghassi.github.io/openscholarship-dataviz/day-2/day-2-part-2 "Day 2, Part 2") 

Reminder: Use the [ongoing discussion post](https://github.com/negeenaghassi/openscholarship-dataviz/discussions/8 "ongoing discussion post") for any questions or thoughts that come up. 
## Day 2, Part 1 (in progress)
Welcome to Day 2, Part 1! This part will go over data cleaning, chart types, how to find datasets, and other aspects of getting start with creating a data visualization. 

### Structured, semi-structured, and unstructured data
Data comes in many formats -- sometimes computer generated, sometimes handwritten in a log, often collected by phones, and even found on the back of a napkin. However, most data, regardless of where it appears, is either in a **structured** format or **unstructured** format. 

#### Structured data
Structured data is typically tabular and consists of columns and rows in a database or a spreadsheet. When cleaned, all of the rows will have the same columns -- in other words, there are no row headers, only column headers. Most data visualization tools that can create visualizations with quantitative data require the data to be structured for them to work properly. This includes tools such as Tableau and Excel. 

In the example below, take note how each data point is organized into columns and rows. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/structureddata.PNG" alt="Structured data of a fake survey with responses to how much respondents like an animal to demonstrate and example of structured data without row headers." width="550"/>

#### Semi-structured data 
Semi-structured data is not tabular, but it does contain some tags or other ways of organizing the data. An example of semi-structured data is an email, which contains some markers to identify parts of the data (for example, sender name, date sent, size of attachments, and so on) but also includes parts that are not tagged (such as the subject or body of the email). 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/semistructureddata.png" alt="Semistructured data consisting of an email with some structured and unstructured elements visible." width="750"/>

#### Unstructured data
Unstructured data does not organize information in a particular model or hierarchy. Some examples include audio, video, and the text from an interview. While this format is harder to analyze using some data visualization tools, it can provide a level of complexity that can be stripped out when data is structured. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/unstructureddata.png" alt="UNstructured data consisting of fake interview text." width="550"/>

### Data cleaning
Data cleaning (also called data wrangling, tidying, normalizing, etc.) is the process of finding and correcting inaccurate or unstandardized data points. With many data visualization projects, data cleaning is the bulk of the work. 

#### Cross-tab vs normalized data

Part of data cleaning may involve making sure that the data is in a structured format that can be analyzed by a certain tool. This may involve converting a **cross-tab** dataset into a **normalized** dataset. 

Look at the example below of a cross-tab dataset. In order to find one record, the reader has to take two steps: go down to a specific row, then go to a specific column (or vice versa). Another way to look at it is that there are both column headers *and* row headers. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/crosstab.png" alt="Fake survey data about how much the respondents like a particular animal demonstrating cross-tab data structure with both columns and rows." width="550"/>

This format is difficult for many data visualization tools to process. Most popular tools require that each record be its own row (in a normalized or "unpivoted" format). The same example of structured data from above demonstrates this format. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/structureddata.PNG" alt="Structured data of a fake survey with responses to how much respondents like an animal to demonstrate and example of normalized structured data without row headers." width="550"/>

Note that for any particular record, there is only one step to find it: find the record. 

It can take some work to convert a dataset from cross-tab, but before you put in too many hours, check out these [instructions on how to automatically normalize your data using the Microsoft Excel Pivot Table Wizard](https://superuser.com/a/78464 "how to automatically normalize your data using the Microsoft Excel Pivot Table Wizard.")

#### Standardizing

When we read "100 Ave," "100 Ave.," "100 Avenue," and "One Hundred Ave," we understand that these records are likely referring to the same record. However, a computer will process each of those as separate locations. When the same data points are not standardized and consolidated, it can make it difficult when visualizing since they
