### Scenario:
A Data Analyst in a local government office has been tasked with importing some data from another department that relates to inventory information about their fleet of vehicles. The data is in comma-separated value (CSV) format and the data also needs cleaning up before you can start to run any kind of analysis on it.

### Implementation:
The raw dataset includes 62 rows and 4 columns:

<img src="https://github.com/pltnhan07/EDAwithExcel/assets/145864240/1a8a7afc-9b2d-4022-ac9b-cea4093d452f" width="300" height="200" alt="Description of image">

#### 1. Clean and Prepare the Data:
1.1. Empty rows: 
Use the Filter feature to look for blanks and remove all empty rows from the data.
Results: 6 rows are deleted, and 56 rows are left.

1.2. Duplicate records: 
Use the Remove Duplicates feature to look for and remove any duplicated records from the data.
Results: 2 rows of duplicates are removed, 52 rows left.

1.3. Spelling: 
The original source file data has not been checked for errors in the spelling. Use the Spelling in the Review tab to fix errors.

<img src="https://github.com/pltnhan07/EDAwithExcel/assets/145864240/d99d7210-5197-4ed8-9795-1681a25fbc6f" width="300" alt="Image 1">

1.4. Whitespace: 
Use the Find and Replace feature to remove all double-spaces from the data.

<img src="https://github.com/pltnhan07/EDAwithExcel/assets/145864240/44297b8e-d0a2-4112-a089-1ca5e4c5d73a" width="300" alt="Image 2">

1.5. Department names:
Use Flash Fill to reduce the department names to just one column, and then remove any unnecessary columns.

<img src="https://github.com/pltnhan07/EDAwithExcel/assets/145864240/ab55d241-e5bb-4b2c-81b6-cecdfefeb28f" width="300" alt="Image 3">

After removing unnecessary columns:

<img src="https://github.com/pltnhan07/EDAwithExcel/assets/145864240/21e5d7f1-6267-4a83-b157-324a2f119974" width="300" alt="Image 4">

There are 3 columns left.

#### 2. Analyze the Data:
2.1. Format the data as a table: 
Use the Format as Table option to format the data as a table.

2.2. Value Generating:
Use AutoSum to find these values (SUM, AVERAGE, MIN, MAX, COUNT) for column ‘C’ and record each of the values.

<img src="https://github.com/pltnhan07/EDAwithExcel/assets/145864240/2681aee3-100d-4c3b-aa05-22f8896bebf3" width="300" alt="Image 5">

2.3. Analyze Data by Pivot Table: 
a. Sum of equipment count by department:

<img src="https://github.com/pltnhan07/EDAwithExcel/assets/145864240/19e0ea83-d78d-4723-b10a-110bb55c745e" width="800" alt="Image 6">

b. Top 1 sum of equipment count by department and equipment class:

<img src="https://github.com/pltnhan07/EDAwithExcel/assets/145864240/c35fd5f4-d79a-4f50-bba9-ff6b0020538e" width="800" alt="Image 7">

c. Top 1 sum of equipment count by equipment class and department:

<img src="https://github.com/pltnhan07/EDAwithExcel/assets/145864240/99d64c50-530e-46c6-b294-310b54fcfc1f" width="800" alt="Image 8">

##### Observations:
- General Services is the department with the most significant number of equipment items overall.
- Health and Human Services, Fire and Rescue, and Environmental Protection also have notable amounts of equipment.
- Sedans are most commonly used by Health and Human Services, indicating a potential need for this type of vehicle in their operations.
- Smaller departments possess minimal equipment, which could reflect the nature of their operations or smaller operational scopes.





