# Case_study1
Case Study 1 Walmart Sales Forecasting

 Walmart has 45 stores in different regions .Each store contains many departments .
 We need to project the sales for each department in each store for the week .
 
 Source Of Data:
                                     The Kaggle provided with historical sales data for 45 walmart stores location  
in different regions .

	2.1) Stores csv File: This File containe the information about the store ,indicating the type and size of the store.
	2.2) Train csv File: This file has the historical train data, which covers from 2010-02-05 to  
2012-11-01 within the file the given fields are 
    • Store     	 - The number of the store
    • Dept      	 - The department number 
    • Date      	 -  The week
    • Weekly_Sales  - Slaes for the given department in the given store for the week
    • IsHoliday         - Whether the week is a holiday week 
               
	In Train.csv there are total of 4,21,570 rows.  
	2.3) Test csv File: The test csv contain all the fields that train cav has except the  Weekly_Sales which we need to predict. There are total of 1,15,065 rows.
	2.4)Features csv File: This file contains the additional data related to the store,department and region activity for the week . It contain the following fields 
    • Store                  - The store number
    • Date                   - The week
    • Temperature      - Average Temperature in the region 
    • Fuel_Price         - Cost of the fuel in that region 
    • MarkDown1-5   - Anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
    • CPI                     - The Consumer Price index
    • Unemployment  - The unemployment rate
    • IsHoliday           - Whether the week is a holiday week 
	2.5) Additional Info: the four holidays fall within the following weeks in the dataset .
		Super Bowl    : 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
		Labor Day     : 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
		Thanksgiving : 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
		Christmas       : 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13
