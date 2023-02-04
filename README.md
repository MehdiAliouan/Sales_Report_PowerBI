# Sales_Report_PowerBI

[Link to repport](https://app.powerbi.com/reportEmbed?reportId=3b7e786a-8d6b-4f4b-b3fa-8c922d4bc175&autoAuth=true&ctid=1158e2d5-dc24-41ad-abce-62841076dbde&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXdlc3QtdXMtYi1wcmltYXJ5LXJlZGlyZWN0LmFuYWx5c2lzLndpbmRvd3MubmV0LyJ9)


1.	Data Gathering  :
Assemble a sales reports with different visuals to best show the Sales Insights in one page Dashboard.

- Sales (folder by year)
- Categories (Excel)
- Geography (Excel)
- Product (CSV / Database)
- SalesRep (Excel)
- SubCategories (Excel)


2.	Data Transformation and Data Modeling:

Do the respective transformations to the Sales fact table in order to split the Country form the City in field “Location”. Make sure you set up the correct Data Type to allow Geo maps.

Do the necessary updates in the Date field to make sure you can setup the Date format.

Create unique key (GeoKey) in Sales and Geography table

The Dimensional queries SalesRep and Sub Category need additional treatment. Some ID columns have the following format:
 
Create a small function that removes the “ID - ” part of these columns that you can invoke and reuse for these two queries to clean the IDs.

Create the Data Model connecting all tables and using the Calendar table.

3.	DAX calculations

Calculate Total Revenue in Sales table, using the Product’s Retail Price, and multiplying it by the Units.

Calculate Total Cost in Sales table, using the Product’s Standard Cost, and multiplying it by the Units.

Calculate Gross Profit in Sales: Total Revenue – Total Cost

Calculate a Gross profit MoM growth Change% measure that could benefit us in decision making

Calculate a measure for AVG sales per day – this is the average sum of Total Revenue per day based on the Dates of actual Sales.	




![Screenshot 2023-02-01 184726](https://user-images.githubusercontent.com/91919362/216122406-0e7822a2-68cf-4a1b-931a-ebe3ecef7dac.jpg)
![Screenshot 2023-02-01 184759](https://user-images.githubusercontent.com/91919362/216122413-06e6f672-28cf-4f3c-a452-56467573378a.jpg)
