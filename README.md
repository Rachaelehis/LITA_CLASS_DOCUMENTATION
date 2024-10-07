# LITA_CLASS_DOCUMENTATION
## PROJECT TOPIC: DATA ANALYSIS
   - [Project Overview](#Project-Overview)
   
   - [Data Source](#Data-Source)

   - [Tools Used](#Tools-Used)
 
   - [Data Extraction, Data Transformation, and Data Loading](#Data-Extraction-Data-Transformation-and-Data-Loading)

   - [Data Analysis](#Data-Analysis)
 
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

### Data Extraction, Transformation, and Data Loading

 - Data Extraction

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

```SQL
Select * from [dbo].[VW_Anthony_and_Sons_Limited]
```

- Data Transformation

The data require no tranformation as it was already structured

- Data Loading

The view data was loaded on excel for **Analysis** and **Visualization**

### Data Analysis

With the use of Pivot table in excel, our large dataset was summarised and the table below was extracted for visualization

**Region by Revenue,**	

   |**Region**|**Revenue**|
|--------------|-----------------|
|**Row Labels**|Sum of Revenue| 
|**North Central**|2,170,467,840|
|**North East**|6,152,217,480|
|**North West**|3,224,784,960|
|**South East**|3,577,417,920|
|**South South**|4,119,141,480|
|**South West**|5,323,352,400|
|**Grand Total**|24,567,382,080|

**Region by Units Sold**

   |**Region**|**Units Sold**|
|--------------|--------------| 
|**North Central**|18,635|
|**North East**|70,401|
|**North West**|36,040|
|**South East**|41,576|
|**South South**|43,785|
|**South West**|59,228|
|**Grand Total**|269,665|

### Data Visualization

**Region by Revenue**

![image](https://github.com/user-attachments/assets/6d2ebf86-e425-4e2c-a69a-5ceb34a573be)

**Units Sold by Region**

![image](https://github.com/user-attachments/assets/d783c9bf-5fe9-4f17-a369-1e66d0eb5d0c)

[Click here to go back to the start](#LITA_CLASS_DOCUMENTATION)
