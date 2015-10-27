# INFM600-irinya
The data set on Bus ridership was chosen to be a focal data set, as I find improving public transportation one of the most interesting topics in regard to community sustainability and global environmental situation.

**Bus ridership**. File - RTA_Fixed_Route_Ridership.xlsx  
The data set shows bus routes ridership by month for the period of time from July 2014 to June 2015. There are 15 routes presented. All the routes are operated by the Regional Transportation Agency of Central Maryland (RTA).  
Howard County Data Portal OpenHoward. (2015). *RTA Fixed Route Ridership* [Data set]. Retrieved from https://opendata.howardcountymd.gov/Transportation/RTA-Fixed-Route-Ridership/e43t-ah6g

I found two other data sets that could be combined with the data on bus ridership for further analysis:

**Rail ridership**. File - MTA_Rail_Ridership.xlsx  
Data shows weekday ridership by month for different types of rails: Metro, Light Rail, MARC Train. The average weekday ridership is indicative of the number of transit patrons making a one-way trip on any mode per weekday. This number is estimated and excludes holidays. Data is shown for the period of time from April 2007 to August 2015.  
Maryland State Department of Information Technology, Open Data Portal. (2014). *MTA Rail Ridership* [Data set]. Retrieved from https://data.maryland.gov/Transportation/MTA-Rail-Ridership/87we-ghfm

**Bus complaints**. File - Regional_Transportation_Agency_Complaints_by_Month__Service_and_Type.xlsx  
The data set presents number of complaints by month for fixed routes and paratransit trips. Complaints are divided into 13 types, and there is also field *Others* presented. Only complaints for Howard County are given. Data is shown for the period of time from July 2014 to June 2015.   
Howard County Data Portal OpenHoward. (2015). *Regional Transportation Agency Complaints by Month, Service and Type* [Data set]. Retrieved from https://opendata.howardcountymd.gov/Transportation/Regional-Transportation-Agency-Complaints-by-Month/acgs-q4xp

I combined the data on Bus ridership with the data on Rail ridership and got a new data set *MTA_Rail_and_RTA_Fixed_Route_Ridership_combined.xlsx*. The process of combination is described in the file *Processing_documentation_ridership.docx*.

The new data set *MTA_Rail_and_RTA_Fixed_Route_Ridership_combined* provides a view to see how bus ridership in Howard County correlates with rail ridership in Maryland. We can look at each route separately and at all routes combined. I find, the best way to present the data could be a graph with months on horizontal axis and ridership on vertical axis, probably in hundreds or even thousands. Different colors for different types of transportation will be most descriptive. Based on the graph we can hypothesize what affects the use of public transportation. For example, we can see a trend through rail and almost all buses ridership. There was a decline in January and February. We can find out if the same trend existed in previous years for rail ridership. We might look deeply in weather forecast and number of working days for these months. Are those numbers a result of reduced working days due to month length and snow days? Or is it a seasonal thing affected by weather? Based on that information future estimates can be drawn. To work more carefully with the data one might want to exclude weekend ridership from *Bus ridership* data (with RTA assistance), as *Rail ridership* is presented only for weekdays.  

To cite the new data set, please, use the following reference:
Yakubinskaya, I. V. (2015, October). *MTA_Rail_and_RTA_Fixed_Route_Ridership_combined* [Data set]. University of Maryland: Information Environments
Yakubinskaya, I. V. (2015, October). [MTA_Rail_and_RTA_Fixed_Route_Ridership_combined]. Unpublished raw data. 

For further analysis we could combine our focal data set on bus ridership with *Bus complaints* data set. Its part on fixed routes would be the most useful. Do numbers of complaints correspond with higher or lower ridership? Or no relationship could be observed? We might find what affected the use or how can we improve the service.

The data in the INFM600_irinya repository is distributed under a Creative Commons Attribution 4.0 International License.
