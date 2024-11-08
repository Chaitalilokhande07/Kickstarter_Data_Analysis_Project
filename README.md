# Kickstarter_Data_Analysis_Project
# Overview
This project is centered around creating an analytics platform for a crowdfunding site, with the goal of enhancing user experience and refining funding strategies. By incorporating a range of data visualization techniques, it offers valuable insights into user engagement, funding patterns, and campaign success.
# Technologies used 
Excel: Analyzing data and creating dashboards  
Power BI: Building interactive data visualizations  
Tableau: Displaying funding trends and performance metrics  
MySQL: Managing databases and running SQL queries to extract data
# Key Features 
**Data Analysis:**  
- Utilized SQL to extract and transform large datasets for efficient management.  
- Performed detailed analysis to uncover patterns and trends in crowdfunding data.

**Interactive Dashboards:**  
- Designed dynamic dashboards in Excel, Power BI, and Tableau to visualize important metrics, including:  
  - User engagement data  
  - Funding trends across various campaigns  
  - Performance metrics segmented by demographics

**Reporting and Insights:**  
- Created detailed reports to communicate findings to stakeholders.  
- Delivered actionable insights to aid in strategic decision-making and drive operational improvements.

To download the datasets, please visit: [https://drive.google.com/file/d/1NjpBq3Qzc1IU4OdEGa3Ky_cex2u1ZwvU/view?usp=sharing](https://drive.google.com/file/d/1NjpBq3Qzc1IU4OdEGa3Ky_cex2u1ZwvU/view?usp=sharing)

### Requirements:

1. **Date Conversion**:  
   - Convert the date fields to natural time format (currently in Epoch time). For reference on converting Epoch time, please read the article here: [Epoch Converter](https://www.epochconverter.com/).

2. **Create a Calendar Table**:  
   - Build a Calendar Table using the "Created Date" column, which contains dates from the earliest to the latest.  
   - Add the following columns to the Calendar Table using the formulas provided:  
     - **A. Year**  
     - **B. Month Number**  
     - **C. Month Full Name**  
     - **D. Quarter (Q1, Q2, Q3, Q4)**  
     - **E. Year-Month (YYYY-MMM)**  
     - **F. Weekday Number**  
     - **G. Weekday Name**  
     - **H. Financial Month (April = FM1, May = FM2, March = FM12)**  
     - **I. Financial Quarter (FQ-1, FQ-2, etc. based on Financial Month)**

3. **Build the Data Model**:  
   - Use the attached Excel files to create the data model in PowerPivot.

4. **Currency Conversion**:  
   - Convert the Goal amount into USD using a static USD exchange rate.

5. **Projects Overview KPIs**:  
   - **Total Projects by Outcome**  
   - **Total Projects by Location**  
   - **Total Projects by Category**  
   - **Total Projects by Year, Quarter, Month**  
   - **Successful Projects**  
   - **Amount Raised**  
   - **Number of Backers**  
   - **Average Number of Days for Successful Projects**  
   - **Top Successful Projects** (Ranked by Number of Backers and Amount Raised)  
   - **Success Rates**:  
     - Percentage of Successful Projects Overall  
     - Percentage of Successful Projects by Category  
     - Percentage of Successful Projects by Year, Month, etc.  
     - Percentage of Successful Projects by Goal Range (choose your own goal ranges)

# Getting Started:

To run this project locally, follow these steps:

1. **Clone the Repository**:  
   - Clone the project repository to your local machine.

2. **Set Up the Database**:  
   - Import the provided SQL scripts into your MySQL database.

3. **View the Dashboards**:  
   - Open the dashboards in Excel, Power BI, or Tableau to explore and interact with the data.

# Contributing:

Contributions are welcome! If you have any suggestions or improvements, please feel free to create a pull request or open an issue.
