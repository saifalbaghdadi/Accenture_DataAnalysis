# Accenture_DA_pjct

# Data Analysis on the Cloud

- Repository: `challenge-data-analysis`
- Type of Challenge: `Consolidation`
- Duration: `8 days`
- Deadline: `23/03/2022 4:30 PM`
- Team challenge : 5
- Developers : `havva`, `saif`,`baki` ,`lelo`, `saina`, 
- Level: `Junior Developer`
- Organization: `Becode  AI Bootcamp`


## Mission objectives

- Be able to connect to data stored in a cloud database.
- Be able to use data visualization libraries `matplotlib` or `seaborn`) or data tools like PowerBI to explore the data.
- Be able to clean a dataset for analysis.
- Be able to use colors in visualizations correctly.
- Be able to establish conclusions about a dataset.
- Be able to find and answer creative questions about data.
- Be able to think outside the box.
- Be able to create a dashboard containg visualizations to bring business insights.



### DATA

| ALLERGY | 8 rows  |
| ----------- | ----------- |
| id | int |
| severity | Text |
| name | Text |


| ALLERGY_CUSTOMER | 37705 rows  |
| ----------- | ----------- |
| allergy_id | int |
| customer_id | int |


| ORDER | 178724 rows  |
| ----------- | ----------- |
| restaurant_id | int |
| order_creation_date | datetime |
| customer_id | int |
| order_id | int |


| ORDERABLES | 2790 rows  |
| ----------- | ----------- |
| item_price | decimal |
| restaurant_id | int |
| ID | int |
| item_name | text |

| ORDER_ITEM | 486031 rows  |
| ----------- | ----------- |
| order_id | int |
| orderable_id | int |
| amount | int |


| RESTAURANT | 425 rows  |
| ----------- | ----------- |
| id | int |
| opening_hours | text |
| city | text |
| creation_date | datetime |
| street | text |
| email | text |
| phone_number | text |
| name | text |

  


**1-ASK**
 - No specific question is given, we need to ask our questions
 - Based on preliminary analysis of data we come up with: 
   - What is the connection between allergies and orders
   - Are there any changes on sales based on items
   - 

**2-PREPARE**
Data is received in comma delimeted csv files, preliminary cleaning and simple typo fixing is done. 
All files imported to an sql server on google cloud MS sql server for storage and sharing
Data types changed 

**3-PROCESS**
City attribute of 119 restaurant was missing, data vas not real so it left empty
While transferring data to csv files some letters like ***é*** used in restaurant and orderableitem tables were lost, they were fixed, extra brackets removed, other typos fixed. Dublicate values removed from Allergy table 

**4-ANALYZE**
PowerBi used for analysis 

**5-SHARE**
Power Bi file is included in this repo

**6-ACT**


