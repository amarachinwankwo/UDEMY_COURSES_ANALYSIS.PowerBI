# UDEMY COURSES ANALYSIS

### OBJECTIVES 

&#8226; To identify the total number of subscribers for the 4 subjects between the year 2011-2017. 

&#8226; To compare the number of subscribers, courses, and reviews at each level.

&#8226; To analyze how subscribers subscribed for either free or paid subject.

&#8226; To compare subscribers by level and subjects.

## DATA SOURCE

The data used for this project was a secondary data source from the web https://docs.google.com/spreadsheets/d/1Y7-G7-u5QQHX1At8mTwJDtMb4c92ZCal/edit?usp=drivesdk&ouid=108851604302942673557&rtpof=true&sd=true which comprises four different sheets for the 4 subjects which are: Business Finance,Graphic Design, Musical Instrument and Web Development. 

DATA CLEANING AND TRANSFORMATION

Power Query editor was used for the cleaning and PowerBI was used for the visualization.
&nbsp;For the Business Finance sheet, the applied step include:

&#8226; Removed 13 empty columns.

&nbsp; For the Graphic Design sheet, the applied steps includes:

&#8226; Removed 13 empty columns.

&#8226; Filtered by removing empty from Customer_id column.

&nbsp; For the Musical Instrument sheet, the applied steps includes:

&#8226; Removed 13 empty columns.

&#8226; Filtered by removing empty from the column_id column.

&nbsp;For the Web Development sheet, the applied steps include:

&#8226; Filtered, by removing empty from the column_id column.

The next step in the data cleaning and transformation was to Append the 4 sheets as one sheet and l named it “Udemy Courses_Consolidated”. The applied steps includes:

&#8226; Splitted “published_timestamp” column containing date and time by space delimiter.

&#8226; Filtered the subject column by removing empty.

&#8226; Renamed “published_timestamp1” and “published_timestamp2” to “published_time” and “published_date”.

&#8226; Counted rows before removing duplicates.

&#8226; Removed duplicates.

&#8226; Counted rows after removing duplicates.

&#8226; Changed a column type to calendar type.

&#8226; Added a conditional column.

&#8226; Changed a column type to date type.

ANALYSIS

&#8226; 12 million people subscribed for the four subjects between the year 2011-2017

&#8226; A total of 3687 courses were offered. 

&#8226; More people subscribed for the paid courses than those that took the courses for free

&#8226; The Wed Development subject had the majority of subscribers than the Business Finance, Graphic Design and Music.
