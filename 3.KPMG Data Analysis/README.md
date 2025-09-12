#### Project Title: KPMG Data Analysis using Excel
#### Project Overview:
This project aims to analyze customer demographics, transactions, and new customer data to provide insights into business
performance and customer behavior. The project consists of six tasks that involve data cleaning, data analysis, and visualization using
Excel.
#### Dataset:[KPMG Dataset](https://docs.google.com/spreadsheets/d/1LxuheMo6rwzA1yq1r-gN5sKqTFcWZG7J/edit?gid=1445114962#gid=1445114962)
#### Dataset Description:
#### 1. Customer Address Dataset
**Description**: Contains information about customers' addresses and property valuation.
#### Columns:
* **customer_id**: Unique identifier for each customer.
* **address**: The street address of the customer.
* **postcode**: Postal code for the customer’s address.
* **state**: The state in which the customer resides (e.g., New South Wales, QLD).
* **country**: The country of residence, which is Australia for all entries.
* **property_valuation**: An integer value representing the valuation of the property where the customer
resides.
---
#### 2. Customer Demographic Dataset
**Description**: Contains demographic information about customers, including their personal details, job information,
and purchase behavior.
#### Columns:
* **customer_id**: Unique identifier for each customer.
* **first_name**: Customer’s first name.
* **last_name**: Customer’s last name.
* **gender**: Customer’s gender.
* **past_3_years_bike_related_purchases**: Number of bike-related purchases made by the customer in the past
three years.
* **DOB**: Date of birth of the customer.
**job_title**: Job title of the customer.
* **job_industry_category**: Industry category of the customer’s job.
* **wealth_segment**: Wealth segment classification of the customer (e.g., Mass Customer).
* **deceased_indicator**: Indicator if the customer is deceased (Y/N).
* **default**: Default status, including potential erroneous data.
* **owns_car**: Indicates if the customer owns a car (Yes/No).
* **tenure**: The tenure of the customer.
---
#### 3. Transactions Dataset
**Description**: Contains details of transactions made by customers, including product details and transaction dates.
#### Columns:
* **transaction_id**: Unique identifier for each transaction.
* **product_id**: Unique identifier for each product involved in the transaction.
* **customer_id**: Unique identifier for the customer who made the transaction.
* **transaction_date**: The date when the transaction occurred.
* **online_order**: Indicates if the order was made online (TRUE/FALSE).
* **order_status**: Status of the order (e.g., Approved).
* **brand**: Brand of the product purchased.
* **product_line**: Product line (e.g., Standard).
* **product_class**: Product class (e.g., medium).
* **product_size**: Size of the product.
* **list_price**: Listed price of the product.
* **standard_cost**: Standard cost of the product.
* **product_first_sold_date**: The date when the product was first sold.
---
#### 4. New Customer List Dataset
**Description**: Contains information about potential new customers, including their personal details, job information,
and potential value.
#### Columns:
* **first_name**: First name of the potential new customer.
* **last_name**: Last name of the potential new customer.
* **gender**: Gender of the potential new customer.
* **past_3_years_bike_related_purchases**: Number of bike-related purchases made in the past three years.
* **DOB**: Date of birth of the potential new customer.
* **job_title**: Job title of the potential new customer.
* **job_industry_category**: Industry category of the potential new customer’s job.
* **wealth_segment**: Wealth segment classification.
* **deceased_indicator**: Indicator if the potential new customer is deceased (Y/N).
* **owns_car**: Indicates if the potential new customer owns a car (Yes/No).
* **tenure**: Tenure of the potential new customer.
* **address**: Address of the potential new customer.
* **postcode**: Postal code for the address.
* **state**: State of residence.
* **country**: Country of residence.
* **property_valuation**: Valuation of the property.
* **Rank**: Rank based on some criteria.
* **Value**: Value of the potential new customer.
---
### Question and Solution:

#### Task 1: Data Cleaning 
**Objective**: Prepare the datasets for analysis by cleaning and correcting any inconsistencies.
#### 1. Customer Address Data:
  * Remove any duplicate records.
  * Ensure all state names are correctly formatted.
#### 2. Customer Demographic Data:
  * Identify and correct any erroneous data entries (e.g., invalid characters in default).
  * Standardize the format for missing data entries.
  * Correct any anomalies in gender representation.
#### 3. Transaction Data:
  * Ensure that transaction_date is in a consistent date format.
  * Remove any records with missing or incomplete information.
#### 4. New Customer Data:
  * Standardize address formatting.
  * Ensure consistent gender representation.
  * Correct any anomalies in job_title and job_industry_category.

##### Sol:
1. **Customer Address Data**: Removed duplicate records and standardized state names.
2. **Customer Demographic Data**: Corrected invalid entries, standardized missing values, and fixed gender representation issues.
3. **Transaction Data**: Ensured consistent date formats and removed incomplete records.
4. **New Customer Data**: Standardized address formatting, corrected anomalies in gender, job titles, and industry categories.
* All datasets are now clean and ready for analysis.
1. **Customer Address Data**:
<img width="510" height="290" alt="1" src="https://github.com/user-attachments/assets/b74b10ea-4356-42b8-8df3-5fe73dec7678" />
 
 2. **Customer Demographic Data**:
<img width="953" height="305" alt="5" src="https://github.com/user-attachments/assets/eef84b93-7289-4b7f-8ed8-2d8892d349ef" />


3. **Transaction Data**:
<img width="954" height="305" alt="3" src="https://github.com/user-attachments/assets/5b60b16a-1afc-4270-8213-f804889fbf57" />

4. **New Customer Data**:
<img width="958" height="295" alt="4" src="https://github.com/user-attachments/assets/8fc38eb3-efeb-4f1b-9b7c-daaca5623391" />

---

#### Task 2: Customer Segmentation
**Objective**: Segment customers based on demographic and transaction data to identify key customer groups.
#### 1. Segmentation by Wealth Segment:
  * Show the number of customers in each wealth_segment.
  * Calculate the average tenure for each wealth_segment.
#### 2. Segmentation by Gender:
  * Showing the number of customers by gender.
  * Calculate the average past_3_years_bike_related_purchases for each gender.
#### 3. Segmentation by Job Industry:
  * Showing the number of customers in each job_industry_category.
  * Analyze the distribution of wealth_segment within each industry.
##### Sol:

<img width="773" height="286" alt="4" src="https://github.com/user-attachments/assets/c82e8881-feb9-4ef0-a745-0155f614dccc" /> 
<img width="550" height="289" alt="5" src="https://github.com/user-attachments/assets/4382ef35-2c45-46d2-b873-74cfb81cc8a4" />
<img width="664" height="236" alt="6" src="https://github.com/user-attachments/assets/3f77221c-1809-4425-b862-e16e6b66cce7" />

---

#### Task 3: Transaction Analysis 
**Objective**: Analyze transaction data to identify trends and patterns.
#### 1. Sales Trend Analysis:
  * Create a chart showing the total sales per month.
  * Identify any seasonal trends or significant spikes in sales.
#### 2. Product Performance Analysis:
  * Show the total sales for each brand.
* Calculate the total sales and average list_price for each product_line.
#### 3. Customer Purchase Behavior:
  * Identify the top 10 customers based on total transaction value.
  * Calculate the average number of purchases per customer.

##### Sol:

<img width="668" height="262" alt="7" src="https://github.com/user-attachments/assets/c4333246-c09b-4b88-9c35-945f9ae8e50a" />
<img width="472" height="281" alt="8" src="https://github.com/user-attachments/assets/355f2d18-a4a4-4fd5-98df-39c6de155f7f" />
<img width="660" height="215" alt="9" src="https://github.com/user-attachments/assets/c14588b9-619f-4e9d-b796-f15ffa768c76" />

---

#### Task 4: New Customer Insights 
**Objective**: Analyze the new customer dataset to provide insights into potential new customer behavior and value.
#### 1. New Customer Demographics:
  * Show the distribution of new customers by wealth_segment and job_industry_category.
  * Calculate the average past_3_years_bike_related_purchases for new customers.
#### 2. New Customer Location Analysis:
  * Create a map or chart showing the distribution of new customers by state.
  * Analyze the correlation between property_valuation and customer wealth_segment.
#### 3. Potential Revenue from New Customers:
  * Estimate potential revenue based on past_3_years_bike_related_purchases and value.

##### Sol:

<img width="753" height="218" alt="10" src="https://github.com/user-attachments/assets/0326bd1b-2b40-4b89-96c4-53643267f7ec" />
<img width="869" height="292" alt="11" src="https://github.com/user-attachments/assets/3744ad6d-60f9-4bec-82d8-373dae154473" />

* 4.3 Potential Revenue from New Customers
  Potential Revenue=Past Purchases × Value per Customer
  * Create a new column in Transactions Data and Name the Column Potential Revenue.
  * To find the potential revenue = D2 * Q2
  * Where D2 = past_3_years_bike_related_purchases
  * Q2 = Value column
  * To find the total potential revenue = =SUM(_1_New_Customer_List[Potential Revenue])
  <img width="392" height="114" alt="12" src="https://github.com/user-attachments/assets/e84dbef8-3776-4d0e-80ca-c3958fdab2c4" />

---

#### Task 5: Customer Lifetime Value (CLV) Analysis 
**Objective**: Calculate and analyze the customer lifetime value to identify the most valuable customers.
#### 1. CLV Calculation:
  * Use the formula
  * Calculate CLV for each customer using transaction data.
<img width="413" height="344" alt="Screenshot 2025-09-07 172050" src="https://github.com/user-attachments/assets/b2df71c1-b6d2-4fe3-88ed-f1f131ce1f6f" />

#### 2. Segment CLV Analysis:
  * Show average CLV by wealth_segment.
  * Analyze the relationship between CLV and customer demographics (e.g., gender, job industry).

##### Sol:

<img width="709" height="219" alt="14" src="https://github.com/user-attachments/assets/02f79f70-4199-489c-a264-c145020748f5" />
<img width="586" height="217" alt="15" src="https://github.com/user-attachments/assets/4ac6ea05-97fb-4bce-9e13-54c027e42cee" />

---

#### Dashboard
<img width="733" height="293" alt="16" src="https://github.com/user-attachments/assets/b2c16a4e-aeb1-47ae-98aa-7e0f5571a4e2" />
<img width="493" height="292" alt="17" src="https://github.com/user-attachments/assets/13aba281-f4e5-43ee-b19b-137931464a25" />
<img width="884" height="200" alt="18" src="https://github.com/user-attachments/assets/384ff43e-cbed-47ff-849c-e378d7d6599f" />

---

#### Task 6: Executive Summary and Recommendations 
**Objective**: Summarize findings and provide actionable recommendations for business strategies.
#### 1. Summary of Key Insights:
  * Highlight key findings from customer segmentation, transaction analysis, new customer insights, and CLV analysis.
#### 2. Recommendations:
  * Provide recommendations for marketing strategies targeting high-value customer segments.
  * Suggest potential areas for business expansion based on new customer location analysis.
  * Recommend improvements in product offerings based on transaction analysis.

##### Sol:

###### Executive Summary (Key Insights)
1. **Customer Segmentation**:
   * Mass Customers form the largest group, followed by High Net Worth and Affluent Customers.
   * Average tenure is highest for High Net Worth Customers (~10.48 ).
   * Bike purchases in the past 3 years are slightly higher for Males than Females.
   * Most customers belong to Manufacturing and Financial Services industries.
2. **Transaction Analysis**:
   * The brand "Solex" is the top revenue generator, significantly outperforming others.
   * The "Standard" product line is the clear sales leader, contributing the majority of total revenue.
   *  The "Touring" product line commands the highest average price point.
3. **New Customer Insights**:
   * Most new customers belong to Mass Customer segment, followed by High Net Worth.
   * Financial Services and Manufacturing have the most new customers.
   * New customer concentration is highest in New South Wales.
4. **Correlation & CLV Analysis**
   * Weak correlation (0.0135) between property valuation and wealth segment → property value does not strongly predict wealth segment.
   * Mass Customers have the highest average CLV (290,310.50), followed by High Net Worth (288,773.65).
   * Males show a slightly higher CLV (300,867.63) compared to Females (288,895.87).
   * Entertainment and Telecommunications industries have the highest CLV (>320,000), while IT has the lowest (~201,000).
   * Purchase frequency is ~5 transactions per customer, indicating moderate engagement.

**Recommendations**:
1. **Marketing Strategy**
   * Target High Net Worth and long-tenure customers with loyalty programs and premium product offerings.
   * Create gender-specific campaigns since purchase patterns differ for Males vs Females.
2. **Business Expansion**
   * Focus expansion efforts in New South Wales as it has the largest base of potential new customers.
   * Develop partnerships with Financial Services and Manufacturing industries to acquire more customers.
3. **Product Strategy**
   * Promote Standard product line to mass customers for volume sales.
   * Introduce premium models under the Touring product line to attract High Net Worth customers.
   * Focus on top-selling brands like Solex and WeareA2B for maximum revenue impact.

 ---

 **Data Integrity Note**: Analysis of customer IDs revealed that **507 out of 4000 registered customers (12.7%) have no associated transactions**. This represents a segment of potential customers who have registered but have not yet made a purchase. It is worth noting that this is likely a **credit to the business's marketing effectiveness** in attracting leads, but also highlights a significant opportunity to improve conversion rates. For accuracy, these customers have been included in all segmentation and CLV analysis with $0.00 spent and 0 transactions.

 ---










