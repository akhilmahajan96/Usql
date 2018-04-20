# Usql
We will be analyzing data using U-SQL for a restraunt chain called "TacoBoutIT". "TacoBoutIT" has stores all over US. 

All the stores send their drive thru timer data in their local time zones. The "drive thru timer" data shows how long it takes for the restraunt to serve a customer using the "drive thru" lane from ordering the food to getting the food. The stores are sending the drive thru timer files in comma separated text files. The files are name using format  <StoreNumber>_<YYYYMMDD>_dttlog.txt.
  
We also have information regarding the "stores". 

Today we will be analyzing drive thru timer data for lunch time. Lunch time is defined from 11 AM - 2 PM and the event code we are looking for is "LINE ".

-------------------------------------------------------------------------------------------------------------------------------------

After cloning the Git Hub repository or downloading the content, please perform the following tasks.

Use "ADLA-USQL_Hands_On_Labs.docx" word documeent to create Azure Data Lake Store and Azure Data Lake Analytics service. It also contains directions to create folders and upload the data which we would be analyzing. THe data is stored in the "data" directory. 
