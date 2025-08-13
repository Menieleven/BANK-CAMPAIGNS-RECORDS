# BANK-CAMPAIGNS-RECORDS

This project gives the detailed documentation of BANK CAMPAIGN RECORDS of group of people

## PROJECT OVERVIEW:
In this project, you are tasked with analyzing the Bank Campaign records.

AIMS AND OBJECTIVES: explore bank data to uncover success of campaign carried out.

### DATA SOURCES
The main data source is the Bank datd uploaded to the Kaggle database. 
this is an open-source data downloaded from my dashboard on the kaggle platform

### TOOLS USED
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1.  For Data Cleaning and analysis
      
- Microsoft PowerBi [Download Here](https://apps.microsoft.com)
  - For Analysis Cleaning and Visualization
  - For Data Visualization and reporting
    
- CSV (Comma Separated Value)  File
  
   
- GITHUB
  - For documentation AND Portfolio Building  


## EXPLORATORY DATA ANALYSIS:
Exploratory Data Analysis (EDA) involves investigating and summarizing datasets to discover patterns, trends, relationships, and anomalies, often before applying more complex statistical models.
EDA involves graphical and statistical techniques, helping analysts understand the data's underlying structure, spot errors, and gain insights that inform decision-making and further analysis.


## STAGE 1: WORKING WITH DATA ON MICROSOFT EXCEL
At the initial stage of the project, we downloaded the file from CANVAS LMS 
then we went ahead with Data Cleaning, Removing Duplicates value
  - Data cleaning i.e removing Duplicate values - Using this operation in Excel

## GENERATING REPORT USING PIVOT TABLE
  Highlight or click on the desired cell within your data range
  Go to the insert Tab, Click on the pivot  table button to open a dialog box
  Select Data Range, Choose where to place the pivot table (a new worksheet or in the existing worksheet)
  Build customize and format the table
  
Summarize Total sales by product and pie chart representation

![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/1A.JPG)
![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/1B.JPG)

 Summarize Total Sales by region and pie chart representation
 
![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/2A.JPG)
![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/2B.JPG)

Summarize Total Sales by Month In 2023 and pie chart representation

![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/3A.JPG)
![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/3B.JPG)

Summarize average sales by Product 

![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/4A.JPG)
![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/4B.JPG)

Average revenue per Region

![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/5A.JPG)

Summarize total revenue per Region

![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/1aded077d9d35a9eb406887866dd32c9dd3ae2ef/5B.JPG)



Sum of total revenue by Region
SUM OF TOTAL REVENUE BY REGION 

Sum of total Revenue by Region using excel function SUMIF

=SUMIF(range,criteria,[sum_range])
WHERE; 

Range : the range of cells to evaluate, in this sense region
Criteria: the condition that must be met (can be any of the 4 regions in this analysis- )
Sum_range: the actual cell to sum
=SUMIF(D2:D50001,D2,H2:H50001)
TOTAL REVENUE BY REGION USING EXCEL FUNCTION SUMIF 

8.Average sales per product

=AVERAGEIF(range,criteria,[average_range])
WHERE;

Range: the range of cells to evaluate, in this sense product
Criteria: the condition that must be met (can be any of the 6 products in this analysis)
Average_range: the actual cell to average
=AVERAGEIF(C2:C50001,C49988,H2:H50001)

AVERAGE SALES BY PRODUCT USING EXCEL FUNCTION AVERAGE IF
Percentage Revenue by Region
PERCENTAGE REVENUE BY REGION
Percentage sales by product
SALES PER PRODUCT IN PERCENTAGE

# EXPLORATORY DATA ANALYSIS (WITH SQL)
Convert excel sheet to csv
Remove headers
import the csv to my sql
Ensure to format the the date column into YYY-MM-DD while importing the csv into my SQL

A. Top selling product by total sales value

```
SELECT FROM SALESDATA
SELECT Product, SUM(TotalSales) As TotalSales
FROM orders
GROUP BY TotalSales DESC
LIMIT 1

```


# EXPLORATORY DATA ANALYSIS (WITH POWER BI)

OVERVIEW OF SALES RECORD

![Image_alt](https://github.com/Menieleven/MENI-LITA-PROJECT/blob/9b2c8a4bf41309caf4ad640d2c7e0ac37731e544/SALES2.JPG) 

OVERVIEW 2 




