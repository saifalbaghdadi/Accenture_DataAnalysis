# Accenture_DA_pjct
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