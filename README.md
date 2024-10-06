# LITA_CLASS_DOCUMENTATION
## PROJECT TOPIC: DATA ANALYSIS
   - [Project Overview](#Project-Overview)
   
   - [Data Source](#Data-Source)

   - [Tools Used](#Tools-Used)
 
   - [Data Extraction, Transformation, and Loading](#Data-Extraction-Transformation-and-Loading)
 
- ### Project Overview
The primary aim of the project is to able to acquire knowledge and skills on data analysis. The focus will be on understanding,presenting and interpreting data adequately to get meaningful results. By the end of this project, I aim to be able to develop skills in using data analysis tools, interpreting data and present my findings appropriately.
 
- ### Data Source
The data set for analysis will be selected form an open source platforms provided as a part of the course. I will ensure that the data is relevant to the problem statement.

- ### Tools Used
Throughout the training i will be using the following tools and software

- Mircosoft Excel
  1. For Data Cleaning
  2. For Analysis
  3. For Data Visualisation
   
[Download Microsoft Excel](https://microsoft-excel-2016.en.download.it/#google_vignette)
    
- SQL (Structed Query Language) for:
   1. Data Storage
   2. Data Querying and Manipulation
    
[Download SQL](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

- ### Data Extraction

Our data was extracted from **SSMS (SQL Server Management Studio)** using the query below:

Input:
```SQL 
Select * from [dbo].[Anthony and Sons Limited]
```

Output:

![Anthony and Sons Limited image](https://github.com/user-attachments/assets/b1298dfa-464a-42f2-9643-0f3dc57995fb)

afterwhich, the needed field was created to **View** using the query below:

Input:
```SQL 
Create View VW_Anthony_and_Sons_Limited
as
Region, Market, Store, Trade_Date, Mode, Line_Of_Business, Revenue, Units_Sold, Transaction_Category
from [dbo].[AnthonyandSonsLimited]
```



