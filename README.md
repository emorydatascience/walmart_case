# Walmart Case Study

*This case study is based on the Kaggle competition [Walmart Recruiting - Store Sales Forecasting](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data).*

You are provided with historical sales data for 45 Walmart stores located in different regions. Each Walmart store contains a number of departments which are indexed numerically. The meaning of the department numbers are provided in a seperate file.

In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. These sales weeks are indicated in the data.


Table 1:  Code Sheet for the Variables in the Walmart Sales Data Set (`walmart_sales.csv`).
-------------------------------------------------------------
Variable              |      Code
----------------------|--------------------------------------
The store number      | Store |
The department number | Dept  |
The sales week        | Date  |
Sales for the given department in the given store| Weekly_Sales|  
Whether the week contains one of the four special holidays|IsHoliday |


## Supplementary Data

Table 2:  Code Sheet for the Variables in the Walmart Departments Data Set (`walmart_dept.csv`).
-------------------------------------------------------------
Variable              |      Code
----------------------|--------------------------------------
Department Number     | dept.numb |
Department Name | dept.name  |

*Note: Departments with (sub) in the name indicate subsidiary divisions of larger departments*

Table 3:  Code Sheet for the Variables in the Walmart Stores Data Set (`walmart_stores.csv`).
-------------------------------------------------------------
Variable              |      Code
----------------------|--------------------------------------
The store number     | Store |
Size of store | Size  |
