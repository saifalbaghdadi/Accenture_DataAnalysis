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



**DATA**

**ALLERGY**  8 rows
- id
- severity
- name

**ALLERGY_CUSTOMER**  37705 rows
- allergy_id
- customer_id

**ORDER**  178724 rows
- restaurant_id
- order_creation_date
- order_creation_time
- customer_id
- order_id

**ORDERABLES**  2790 rows
- item_price
- restaurant_id
- ID
- item_name

**ORDER_ITEM**  486031 rows
 - order_id
 - orderable_id
 - amount
  
**RESTAURANT**  425 rows
 - id
 - opening_hours
 - city
 - creation_date
 - street
 - email
 - phone_number
 - name


**1-ASK**
 - What is the connection between allergies and orders
 - Standard statistics about sales, changes, customers

**2-PREPARE**
Data is received in comma delimeted csv files
All files imported to an sql server on google cloud MS sql server for storage and sharing
Data types changed 

**3-PROCESS**
City attribute of 119 restaurant was missing, data vas not real so it left empty
While transferring data to csv files some letters like ***é*** used in restaurant and orderableitem tables were lost, they were fixed, extra brackets removed, other typos fixed.

**4-ANALYZE**
Power Bi used for analysis 

**5-SHARE**
Power Bi file is included in this repo

**6-ACT**


