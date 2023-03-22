Olympic Games 1896 - 2016, the topics covered:

(1) Medal count by games and the top 10 NOC teams

(2) Country insights by medals, gender, age etc.

(3) Age and Gender distribution

(4) Continent overview

Datasource: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results

The datasource (Excel file) contains 271116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event (athlete-events).

The columns are:
1.	ID - Unique number for each athlete
2.	Name - Athlete's name
3.	Sex - M or F
4.	Age - Integer
5.	Height - In centimeters
6.	Weight - In kilograms
7.	Team - Team name
8.	NOC - National Olympic Committee 3-letter code
9.	Games - Year and season
10.	Year - Integer
11.	Season - Summer or Winter
12.	City - Host city
13.	Sport - Sport
14.	Event - Event
15.	Medal - Gold, Silver, Bronze, or NA

Workings:
1) Power BI features: Dependent slicer, tooltips, page navigation, bookmarks, Grouping, helper tables.
2) DAX advanced: LOOKUPVALUE, RANKX, SELECTEDVALUE, ALLEXCEPT, SUMMARIZE, GROUPBY, IF, DISTINCTCOUNT, MEDIAN, CONCATENATE
3) Age column has 9474 NA values, Height has one value with Athlete Name and 60171 NA values, Weight has 62875 NA values. 
   NA VALUES % - AGE 3.5%, Height 22% and Weight 23% in the total dataset.
4) Removed unnecessary columns such as Height, Weight and Team. Also removed NA values in the Medal Column as only medal winners were analyzed.
5) After removing NA values the dataset was reduced to 35000+
6) Multiple tables were made from the dataset to help in better understanding of data and applying filters.
7) Converted age,medals into bins and groups to better visualize the data.



