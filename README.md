# Accenture_DA_pjct

# Data Analysis on the Cloud

- Repository: `challenge-collecting-data`
- Type of Challenge: `Consolidation`
- Duration: `8 days`
- Deadline: `23/03/2022 4:30 PM`
- Team challenge : 5
- Developers : `Baki Guher` , `Moshood Owolabi`
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







Allergy table cleaned from duplicate values 
Allergy_Customer table all values are unique 

Findings: 
-some customers have more than one type of allergy

 - allergy 	8755 customers
 - allergy	8718 customers
 - allergy	3838 customers


**TABLES**

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