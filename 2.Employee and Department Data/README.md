### Assignment Title:
### Employee and Department Data Analysis
#### Business Problem:

Your company wants to perform an in-depth analysis of the employees and departments within the organization to
improve HR processes and departmental efficiency. The analysis will help in understanding the distribution of employees
across departments, identifying salary patterns, and facilitating better data management. You have been provided with two
datasets: Employees and Departments. Your task is to perform various data analysis and management activities using
Excel.

---
#### Refer Employees Dataset: [employees.xlsx](https://docs.google.com/spreadsheets/d/1z2TDcU-Ai4Fg1Qgv2hPTN7QZzJHMgA61/edit?rtpof=true&sd=true) , [departments.xlsx](https://docs.google.com/spreadsheets/d/1L0nWcRAkaqRta5rRZGW1lx4zijpcMtZ9/edit?rtpof=true&sd=true)

- Columns: Employee ID, First Name, Last Name, Email, Phone Number, Hire Date, Salary, Manager ID, Department ID
Departments Dataset:
- Columns: Department ID, Department Name

#### Question and Solution

##### 1. Apply conditional formatting to the entire row in the Employees dataset to highlight salaries greater than 15,000 in green. Additionally, use conditional formatting to highlight employees hired within the last 4 years from 2000 in yellow.

<img width="685" height="295" alt="1" src="https://github.com/user-attachments/assets/ebd31ca6-9371-4611-9552-9a67e4d6e6a9" />

* conditional formatting formula.
* =AND(YEAR($F2)>=1996,YEAR($F2)<=2000)
* =$H2>15000
---
##### 2. In the Employees dataset, set up data validation to ensure that the Department ID column only accepts values that are present in the Departments dataset.

<img width="704" height="292" alt="2" src="https://github.com/user-attachments/assets/a7a0ee48-8ee8-4f64-b50e-b125af6f1c4f" />

---
##### 3. Use Power Query to combine first name and last name in a single name and extract the user name part from email column of employees table.

<img width="685" height="294" alt="3" src="https://github.com/user-attachments/assets/36a866fc-a35c-4507-bff6-fb579f8d250c" />

---
##### 4. Use Power Pivot to create a relationship between the Employees and Departments datasets using the Department ID.

<img width="526" height="239" alt="4" src="https://github.com/user-attachments/assets/50183428-b0e4-4159-9110-f584d6728990" />

---
##### 5. Create a Power Pivot table to analyse the total and average salary per department.

<img width="574" height="228" alt="5" src="https://github.com/user-attachments/assets/e9d440d7-f876-4efa-9dec-958941735185" />

---
##### 6. Convert the Employees dataset into an Excel Table and name it “Employees Table”.

<img width="904" height="326" alt="6" src="https://github.com/user-attachments/assets/2211cdf5-dd3f-4ed3-8a99-4fdfc4d2b8a9" />

---
##### 7. Use the Employees Table to filter and display only employees from the Sales department.

<img width="887" height="99" alt="7" src="https://github.com/user-attachments/assets/5618b990-b446-49ef-bab2-70de7ca6da1c" />

---
##### 8. Create a button in the Excel sheet and assign the recorded macro to add a new employee.

<img width="850" height="91" alt="8" src="https://github.com/user-attachments/assets/c87ecaba-b4f4-459a-bc4d-a594561d9ea4" />

---
##### 9. Use named ranges to create a formula that calculates the average salary of all employees.

<img width="274" height="95" alt="9" src="https://github.com/user-attachments/assets/233667cc-60fe-47bb-9a58-c8bf71ce6960" />

---
##### 10. Apply conditional formatting to compare salaries within each department, highlighting the highest salary in each department.

<img width="686" height="295" alt="10" src="https://github.com/user-attachments/assets/08015884-e95c-4aee-b582-0e17aec5ab51" />

---
##### Dashboard

<img width="845" height="227" alt="11" src="https://github.com/user-attachments/assets/ca26d896-ea03-4d67-932b-0cf46cec6cf1" />

---







