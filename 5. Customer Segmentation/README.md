# Customer Segmentation
### Workflow Overview
![WF](https://github.com/ChampAnuwat/MADT-8101-Seminar-in-Customer-Analytics/blob/main/5.%20Customer%20Segmentation/Data%20Preparation.png?raw=true)
### 1. Import Dataset
#### Sample datasets are from HDI company, it's the network marketing business in Asia, including 2 datasets
* Members
* Transactions 2021-2023
### 2. Creat Customer Single View and prepare dataset for doing Model
#### Customer Single View includes
* member_id: Define “ent” from member data as primary key
* original_status: -
* sponsorship: Influential power
* registered_year: Starting year of being  member 
* registered_month: Starting month of being  member 
* member_duration: Membership age since starting until current
* no_of_purchasing: Number of purchasing (Ticket counted)
* total_spending: Sum of sales amount
* avg_spending: Average total_spending per Ticket
* total_product_qty: Sum product quantity
* total_product_qty_bycategory: Sum product quantity by category (26 category)
* category_count: Count purchased category
* sku_count: Count purchased sku
* Percent_paid: Paid/Total_spending
* avg_paid: Percent_paid/no_of_purchasing
* MTBP_Days: Last purchased-First purchased/no. of purchasing
* NO_CAT_rank: Percentile of number of purchasing by category (26 category)
* Percent_no_online: total online transactions/total transactions
### 3. Customer Segmentation Model
* Doing K-Mean Clustering two rounds
![SegmentModel](https://github.com/ChampAnuwat/MADT-8101-Seminar-in-Customer-Analytics/blob/main/5.%20Customer%20Segmentation/Model_Customer%20Segmentation.png?raw=true)
* Model Results
![SegmentModel1]()
