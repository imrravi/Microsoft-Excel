# Assignment Title:
## Analysing Espresso Store Sales Data

### Problem Statement:
The Espresso Store dataset contains detailed information about orders, customers, and
product details. The objective is to analyse this dataset to gain valuable business
insights, optimise sales strategies, and improve customer satisfaction. You are required
to use Excel's advanced features to perform data analysis and derive actionable insights.

### Dataset: [Espresso Store Data.xlsx](https://docs.google.com/spreadsheets/d/1S71_vRKxbrXFt35NGSZS-ZqRJu_l32Pv/edit?rtpof=true&sd=true&gid=103369774#gid=103369774) what if [data.xlsx](https://docs.google.com/spreadsheets/d/1Mf-KRMO_RqXhv-jgVu4bLse9CCQPViPn/edit?rtpof=true&sd=true&gid=469798847#gid=469798847)

### Question and Solution

#### 1. Format the 'amount' column to display values as currency up to 2 decimal places and apply date formatting to the 'date' column to show dates in 'dd m, yy' format.

<img width="821" height="321" alt="Screenshot 2025-09-05 150258" src="https://github.com/user-attachments/assets/1eeebe86-690d-4145-ae42-cd154b49ef39" />

#### 2. Arrange orders sorted by 'ship city' in Z to A order, and by 'amount' in descending order. Display orders with an amount greater than 500 and status 'Returned'.

<img width="925" height="316" alt="2" src="https://github.com/user-attachments/assets/3f51f2ef-16f5-435b-ad6b-ffbd30ea42af" />

* For all Returned order we used FILTER function.

<img width="922" height="319" alt="2 1" src="https://github.com/user-attachments/assets/4f8c5438-206e-4fda-a9ab-2750a324948f" />

#### 3. Retrieve the 'ship state' for a given customer id=442660.

<img width="314" height="63" alt="3" src="https://github.com/user-attachments/assets/3a342d1b-37dc-49cf-b8fd-939166f9f848" />

* For Ship State used VLOOKUP.
* =VLOOKUP(H2,'2.Sort & Amount>500'!B1:N31048,13,FALSE)
* 2.Sort & Amount is Sheet Name.

#### 4. Label orders as “most demanded” that were placed on Myntra channel and have amount greater than 800 and rest orders as “least demanded”.

<img width="844" height="320" alt="4" src="https://github.com/user-attachments/assets/de9d19fb-f913-4224-acc8-10ab5ff8bbf4" />

##### Steps
* Created a new column and used IF function.
* =IF(G2="Myntra",IF(M2>800,"Most Demanded","Least Demanded"),"")
* We can also use conditional formatting.
* =AND($G2="Myntra",$M2<800) after writing this formula selected red colour.
* Again for Most Demanded used this =AND($G2="Myntra",$M2>800) and select green colour.

#### 5. Count the number of orders from men in the '30-40' age group and extract the middle part of each order id.

<img width="711" height="319" alt="5" src="https://github.com/user-attachments/assets/46631b12-5407-4551-b53f-42b805bc940a" />

* =COUNTIFS(Gender,"Men",Age,">="&30,Age,"<="&40)
* =MID(A2,5,7)

#### 6. Replace all occurrences of kurta category to kurta sets and top category to tops.

<img width="99" height="296" alt="6" src="https://github.com/user-attachments/assets/c0762636-7028-4587-96a2-3a8f5728245c" />

#### 7. Calculate the order dates three months after the given dates.

<img width="140" height="290" alt="7" src="https://github.com/user-attachments/assets/ce69b85b-011c-4948-97f1-7f7a70444888" />

* =EDATE(F2,3)

#### 8. Create a One-Way Data Table to show how different interest rates from different banks affect the loan amount of individuals? (Use What if Dataset).

<img width="443" height="198" alt="8" src="https://github.com/user-attachments/assets/4b94b309-192c-4223-8fb9-340e3951a2f3" />

* Used Data Table tools from What-If Analysis.

#### 9. Use Goal Seek to find out how much change in administration expenses would be required to get the goal profit of 400000? (Use What if Dataset).

<img width="731" height="296" alt="9" src="https://github.com/user-attachments/assets/4ab3565b-f43d-453e-85f5-c1d5de09f76a" />

* Used Goal Seek tools from What-If Analysis.

#### 10. Create a Pivot Table to summarise total sales (amount) by month. And generate a Pivot table and chart to compare the number of orders across different age groups.

<img width="758" height="278" alt="10" src="https://github.com/user-attachments/assets/308870ab-adef-44e4-b851-69377bafeb4c" />


#### Dashboard

<img width="896" height="280" alt="11" src="https://github.com/user-attachments/assets/29142738-6056-4cf0-b647-b2a251a5a6fe" />

* The most state on sales is Maharashtra.
* The month of March has high sales.
* Sales of the set product are higher.




