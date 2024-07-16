 •  Summary 
 We used requests package to access API and create dataframes by passing the data. We created some of the columns based 
 on one column by slicing function; renamed some of the columns; converted some of our data into lowercase format, plain 
 text, or integers. We subtracted different columns and created different dataframes for our studys.We created the summary 
 tables of total incident grouped by different variable. The table displayed statistic information as standard deviation, 
 minimum and maximum. We performed plots to show the trend of total shooting incidents per month from 2006 to 2021. We 
 performed mutiple visualation containing total incidents over time; total incidents by occur time, by occur location, by 
 borough, by involved parties’s age and sex. We performed mapping for each incident and heat map of total cases by zip 
 code. We performed scatter plot and a linear regression for the relationship of the total incidents against complaints and 
 arrests for year 2016 and 2017. We removed the useless values and exported our clean data to the database with sqlite. We 
 performed a decision tree regression to predict the murder based on the selected columns and test the algorithm to the testing 
 dataset. 
 •  Key findings. 
 1)  Total shooting incidents were decreasing until April 2020 and bounced back since then. 
 2)  Shooting tends to happen in day rather than night, summer rather than winter, outside rather than inside. 
 3)  Shooting distribution regarding borough, sex group stays relatively the same over time. 
 4)  Total shooting has moderate positive relationship with total complaint. 
 • Information about the datasets and the reason these datasets were picked 
 NYPD Shooting Incident Data from 2006-2021, the NYPD Arrests Data (Historic) and NYPD Complaint Data (Historic). 
 The first dataset was for us to study the patterns of shootings within New York City. The other two datasets were for us to 
 study the relation between shooting against arrest and complaint.
 • Challenges. 
 Lack of zip codes on the dataset so had to use latitude and longitude to merge data. 
 • Research topic 
 1)  How to convert latitude and longitude into zip codes. 
 2)  How to plot heat map by zip code. 
 3)  How to fit regression model  and decision trees by using Python.
 • Data Set Website: 
 NYPD Arrests Data (Historic):  https://data.cityofnewyork.us/Public-Safety/NYPD-Arrests-Data-Historic-/8h9b-rp9u 
 NYPD Complaint Data Historic. 
 https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i 
 NYPD Shooting Incident Data (Historic). 
 https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8
