# Data Analysis on the Cloud

- Repository: `challenge-data-analysis`
- Type of Challenge: `Consolidation`
- Duration: `8 days`
- Deadline: `23/03/2022 4:30 PM`
- Team challenge : 5
- Team :[`Havva Ebrahimi Pour`](https://www.linkedin.com/in/havva-ebrahimi-pour/), [`Saina Nuersulitan`](https://www.linkedin.com/in/saina-n-4b76b3139/), [`Saif Malkshahi`](https://www.linkedin.com/in/saifmalkshahi/),[`Lelo (Manou) Tokwaulu`](https://www.linkedin.com/in/lelotokwaulu/),[`Baki Guher`](https://linkedin.com/in/baki-guher)
- Level: `Junior AI Developer`
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
| id | int |
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
   - Standard sales and item reports with filtering
   - What is the connection between allergies and orders
   - Any insights from data

**2-PREPARE**
Data is received in comma delimeted csv files, preliminary cleaning and simple typo fixing is done. 
All files imported to an sql server on google cloud MS sql server for storage and sharing
Data types changed 

**3-PROCESS**
City attribute of 119 restaurant was missing, data was not real so it left empty.
While transferring data to csv files some letters like ***é*** used(French words) in restaurant and orderable_item tables were lost, they were fixed.
Extra brackets removed.
Other typos fixed. 
Dublicate values removed from Allergy table. 

**4-ANALYZE**
PowerBi used for analysis 
Excel software used for data cleaning

**5-SHARE**
Power Bi and presentation file is included in this repo


## Team
**Havva Ebrahimi Pour**
 - data cleaning 
 - dashboard design

**Saina Nuersulitan**
 - created trello dashboard to track workflow
 - prepared the dashboard for PowerBI
 - combined all the reports

**Lelo Tokwaulu**
 - cleaned restaurant table
 - prepared sales reports 
 - contributed to 'ReadMe' file redaction and client presentation

**Baki Guher**
 - arranged data storage and sql server
 - prepared allergy reports

**Saif Malkshahi**
 - prepared presantation 
 - data cleaning


## Repo Architecture 

```

│   README.md                     : This file
|   acc_analysis.pdf              : PowerBi pdf report 
│___   
|    original_csv_file              : Files received from customer
│   │ ODL_ALLERGY_CUSTOMER.csv      : 
│   │ ODL_ALLERGY.csv               : 
│   │ ODL_ORDER.csv                 : 
│   | ODL_ORDERABLES.csv            : 
│   | ODL_ORDER_ITEM.csv            : 
│   | ODL_RESTAURANT.csv            : 
│___  
|    cleaned_csv_files          : Cleaned files before importing to sql server
│   │ ALLERGY_CUSTOMER.csv      : 
│   │ ALLERGY.csv               : 
│   │ ORDER.csv                 : 
│   | ORDERABLES.csv            : 
│   | ORDER_ITEM.csv            : 
│   | RESTAURANT.csv            : 
     
```


## Installation & Usage
 - Request Power BI report
 - Authorize your Ip address on google cloud to reach the data
 - Open file in PowerBi desktop application
 
