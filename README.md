# SALES DATA CLEANING PROJECT (EXCEL POWER QUERY)
---

### Project Overview
This project demonstrates a complete data cleaning workflow on a dirty sales dataset using Excel Power Query. The dataset originally contained 823 rows and 16 columns, affected by poor structure, duplicate entries, and inconsistent data distribution. The objective was to transform the data into a clean, analysis ready format suitable for business intelligence and reporting purposes.
![Screenshot 2025-06-10 162534](https://github.com/user-attachments/assets/d264e1a2-26ed-437e-b34e-f01e99ffa9f2)
![Screenshot 2025-05-31 022026](https://github.com/user-attachments/assets/30defb33-993b-49ba-a56e-f66522b2f18b)
![Screenshot 2025-05-31 021613](https://github.com/user-attachments/assets/bf7713f3-c873-4e6b-9784-719a1982c740)




### Dataset Description
The raw dataset presented the following data quality issues:
- Presence of blank cells and duplicate rows.
- Segment names and shipping modes were used as column headers instead of data values.
- Sales values were scattered across multiple columns based on segment and shipping mode.
- Inconsistent spacing and non-uniform headers.

### Tools and Technology
- Microsoft Excel (Power Query)

#### Data Source: 
- Internal Sales Data (Confidential)

### Data Cleaning Workflow
All data transformation tasks were performed in Power Query using the steps below:
- Transpose Table
Reoriented the data to bring column headers into the first row, making it suitable for further structuring.

- Use First Row as Headers
Promoted the first row to header level to define column names appropriately.

- Fill Down
Filled down the segment and shipping mode columns to replace nulls with meaningful data labels.

- Unpivot Other Columns
Unpivoted all sales related columns to convert the wide format data into a tidy, long format structure with columns for segment, shipping mode, Order ID, and sales value.

- Filter and Clean Rows
Removed:
- Duplicate entries.
- Rows with missing or irrelevant values.
- Placeholder and null rows generated during transformation.

- Close and Load
Loaded the cleaned dataset into an Excel table, ready for pivoting, visualization, or export.

### Final Outcome
The cleaned dataset includes:
- Well labeled and consistent column headers
- A normalized, analysis friendly structure
- No blanks, duplicates, or fragmented entries
- Ready for reporting, analysis, or dashboard development
