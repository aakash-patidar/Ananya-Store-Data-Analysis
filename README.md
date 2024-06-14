# Ananya Store Data Analysis
<p align="center">
  <img width="400" height="360"src="https://github.com/aakash-patidar/Ananya-Store-Data-Analysis/assets/171103471/dff1aff7-018f-488e-a32e-de74c939ece7">
</p>

## Scenario
I am a data analyst working on the analyst team at Ananya Store, a clothing retailer offering a variety of apparel through multiple channels including Myntra, Amazon, Meesho and several other platforms. Ananya Mishra, the owner and Chief Creative Officer of Ananya Store, believes that analyzing the 2023 annual sales report will provide valuable insights into our customer base and help drive sales growth in 2024.

The key steps followed in the analysis:  
- Ask
- Prepare
- Process
- Analyze
- Share
- Act

## About the company  
Ananya Store is a dynamic clothing retailer known for its wide array of apparel available through top channels such as Myntra, Amazon, Meesho, and various other platforms. Company's mission is to blend creativity with quality, offering customers a seamless shopping experience and stylish wardrobe choices. Ananya Mishra, the visionary owner and Chief Creative Officer, sees the analysis of the 2023 annual sales report as pivotal in gaining profound insights into our customer base, opening the way for substantial sales growth in 2024.

### Store Dataset: [Ananya_Store_Dataset](https://github.com/aakash-patidar/Ananya-Store-Data-Analysis/blob/main/Ananya%20Store%20Data%20Analysis.xlsx)

## Tools Used  
- Microsoft Excel: Data Cleaning
- Microsoft Excel: Data Processing
- Pivot Tables: Data Analysis
- Microsoft Excel Charts: Data Visualization

## Data Analysis Process    
### Ask:  
The "ask" phase of the data analysis process involves recognizing the current problem, understanding stakeholder expectations, defining the business task, and identifying how insights will benefit stakeholders.  

**Business Task:**  
Analyze the 2023 annual sales report to gain insights that will guide the company in understanding its customer base and help drive sales growth in 2024.  

**Key Stakeholders**  
The key stakeholders for this project include:
- Ananya Mishra: Ananya Store’s owner and Chief Creative Officer  
- Ananya Store Management team: A management team, a group of high-level associates hired by a owner to take on essential responsibilities within the business
- Ananya Store Analytics team: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Ananya Store’s business strategy  

**To address the business task of analyzing the annual sales report for 2023 to understand the company's customer base and help drive sales growth in 2024, the following questions will guide the analysis:**    
- Compare the sales and orders using single chart    
- Which month got the highest sales and orders    
- Who purchased more: men or women in 2023   
- What are different order status in 2023    
- List top 10 states contributing to the sales  
- Relation between age and gender based on number of orders    
- Which channel is contributing to maximum sales  
- Highest selling category?, etc.

### Prepare:  
The "prepare" phase of the data analysis process involves collecting and preparing the necessary data for analysis. Key steps include identifying data sources such as databases, spreadsheets, or external sources, and then extracting the relevant information.      

Ananya Mishra, owner and Chief Creative Officer of Ananya Store, encourages the use of the 2023 annual sales report, which includes information about orders, customers, shipments, and channels. The dataset is in XLSX format and contains 19 columns, including Index, Order ID, Cust ID, Gender, Age, Date, Status, Channel, SKU, Category, Size, Qty, Currency, Amount, Ship City, Ship State, Ship Postal Code, Ship Country, and B2B.  

### Process:  
The "process" step in data analysis involves cleaning, transforming, and integrating data to make sure it is accurate, consistent, and ready for analysis. This includes tasks like handling missing values, correcting errors, standardizing formats, and merging data from different sources. These steps are essential to ensure the quality and reliability of the data for meaningful analysis.  

#### Data Cleaning     
The tool we used for the process step is Microsoft Excel. The following actions were performed to clean the data:  
- **Checking for Duplicates:** Utilized Excel's built-in "Remove Duplicates" feature to identify duplicates. This process ensured data integrity by eliminating any redundant entries.  
- **Checking for Blank Values:** Blank values were checked using Excel's Filter option. Removing blanks (or missing values) is a crucial step in data transformation to ensure data completeness and accuracy. This process helps maintain the integrity of the dataset and ensures reliable analysis results.
- **Handling Missing Data:** Used Excel's tool like Conditional formatting to identify and handle any missing data.
- **Validating Column Values:** Validate the data to ensure its accuracy and consistency. In the Gender column, values were inconsistent, with some entries as "M" instead of "Male" and "W" instead of "Women." We standardized the column by changing "M" to "Men" and "W" to "Women" using the Find & Replace option. Similarly, in the Qty column, all values should be numerical, but some entries were written as "ONE" instead of "1" and "Two" instead of "2." We corrected these to ensure consistency in the column.

#### Data Processing  
- In one analysis, we needed to examine the relationship between Age and Gender, but the Age column had too many distinct values, complicating the analysis. To simplify this, we created a new column named Age Group and categorized the ages into three groups: ages below 30 as Young Adults, ages 30 to 49 as Adults, and ages 50 and above as Seniors, using the formula **=IF(E2>=50, "Senior", IF(E2>=30, "Adult", "Young Adult"))**. We then pasted the results as values to streamline data processing.  
- Next, in another analysis, we needed to identify the highest sales and orders by month. To achieve this, we created a new column named Month and extracted the month from the Date column using the formula **=TEXT(G2, "mmmm")**. We then pasted the results as values to streamline data processing.


  <img src="https://github.com/aakash-patidar/Ananya-Store-Data-Analysis/assets/171103471/97e0d78a-ef11-4aba-8e33-ff516e39adf1">  




  



















 




