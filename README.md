**Analyze Monthly Retail and Food Services Sales(MRTS)**

*Description*      
-Performed ETL & analyzed different business under MRTS data using time series models such as trends, percentage change & rolling time window     

*Extract Transfer Load(ETL)*    
1. Extracted, cleaned & appended data of 'Monthly Retail and Food Services Sales'for years 1992-2020 using python     
Below are the steps for data cleaning:    
   
   a. Imported necessary libraries for reading & cleaning the data   
   b. Removed unnecessary rows from header & footer, replaced NA & S with 0   
   c. Dropped the columns not needed for analysis Ex: removing columns "NAICS Code" & "total"   
   d. Use melted function to reshape & combine the data for many years   
   e. Renamed & changed data type of necessary columns    
   f. Dropped NAN values from rows     
   g. Dropped sheet for year 2021 as it doesn't contain data for 12 months                        
   
2. Converted cleaned excel file into csv to make it consistent and usable for further analysis                     

3. Loaded the data into database using Python script                                  

   a. Connected Python with mysql            
   b. Created database & Table                    
   c. Inserted data into table by reading csv file using python                        
   d. Validated accuracy of data by querying mysql workbench & compared total number of rows & sum of values between csv and database                     

  
*Data Analysis & Visualization*                         
-Analyzed the data using pandas                                 
-Created visual presentation using matplotlib & analyzed data using trend, percentage change & rolling time for different kind of businesses                       
