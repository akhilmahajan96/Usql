# Usql
We will be analyzing data using U-SQL for a restaraunt chain called "TacoBoutIT". "TacoBoutIT" has stores all over US. 

All the stores send their drive-thru timer data in their local time zones. The "drive-thru timer" data shows how long it takes the restaurant to serve a customer using the "drive-thru" lane from ordering the food to getting the food. The stores are sending the drive-thru timer files in comma separated text files. The files are name using format "StoreNumber"_"YYYYMMDD"_dttlog.txt.
  
We also have information regarding the "stores". 

Today we will be analyzing drive-thru timer data for lunch. Lunch is defined from 11 AM - 2 PM and the event code we are looking for is "LINE ".

-------------------------------------------------------------------------------------------------------------------------------------

After cloning the Git Hub repository or downloading the content, please open the "ADLA-USQL_Hands_On_Labs.docx" word documeent. The word document has 3 sections:-

1. Create Data Lake Analytics Service and Data Lake Store :- This section talks about how to create Data Lake Analytics Service and Data Lake Store.
2. Loading Data:- This section talks about how to create folders and upload the data which we would be analyzing. The data is stored in the "data" directory.
3. Running the Labs:- This section talks about how to run the USQL jobs in the Azure Portal.
