# Coffee Sales Excel Dashboard Project
This is a dashboard for visualizing coffee sales over the time period of 2019-2022.

The key metrics are Top 5 Customers and Top Permforming Countries. All the charts can be filtered by coffee roast, coffee package size, and whether the purchase was made by a customer that has a loyalty card.

I pulled in other worksheet's data to the Orders worksheet via the XLOOKUP and dynamic combination of INDEX and MATCH functions. The worksheets are the tables and the "tables" were "joined" or looked up by "foreign keys" Customer ID and Product ID.

Pivot tables were created for summarizing Total Sales, Sales by Customers, and Sales by Country.

A line chart was created for the Total Sales Pivot Table. Formatting edits were applied.

A stacked bar chart was created for the Sales by Customers Pivot Table which was then sorted in ascending order so that they display in descending order in the bar chart. Pivot table was then limited to display only the top 5 customers. Formatting edits were applied.

A stacked bar chart was also created for the Sales by Country Pivot Table which was then sorted in ascending order so that they display in descending order in the bar chart. Formatting edits were applied.

A timeline and slicers were created and connected to all the of the Pivot Tables.
