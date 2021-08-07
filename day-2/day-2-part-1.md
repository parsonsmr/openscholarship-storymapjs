## Day 2, Part 1
Welcome to Day 2, Part 1! This part will go over data cleaning, chart types, how to find datasets, and other aspects of getting start with creating a data visualization. 

### Structured, semi-structured, and unstructured data
Data comes in many formats -- sometimes computer generated, sometimes handwritten in a log, often collected by phones, and even found on the back of a napkin. However, most data, regardless of where it appears, is either in a **structured** format or **unstructured** format. 

#### Structured data
Structured data is typically tabular and consists of columns and rows in a database or a spreadsheet. When cleaned, all of the rows will have the same columns -- in other words, there are no row headers, only column headers. Most data visualization tools that can create visualizations with quantitative data require the data to be structured for them to work properly. This includes tools such as Tableau and Excel. 

In the example below, take note how each data point is organized into columns and rows. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/structureddata.PNG" alt="Structured data of a fake survey with responses to how much respondents like an animal to demonstrate and example of structured data without row headers." width="550"/>

#### Semi-structured data 
Semi-structured data is not tabular, but it does contain some tags or other ways of organizing the data. An example of semi-structured data is an email, which contains some markers to identify parts of the data (for example, sender name, date sent, size of attachments, and so on) but also includes parts that are not tagged (such as the subject or body of the email). 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/structureddata.PNG" alt="Semistructured data consisting of an email with some structured and unstructured elements visible." width="550"/>

#### Unstructured data
Unstructured data does not organize information in a particular model or hierarchy. Some examples include audio, video, and the text from an interview. While this format is harder to analyze using some data visualization tools, it can provide a level of complexity that can be stripped out when data is structured. 

<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/unstructureddata.png" alt="UNstructured data consisting of fake interview text." width="550"/>
