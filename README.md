# Superstore-Sales-Performance-Dashboard
Introduction
This Tableau project aims to visualize the sales performance of the Superstore dataset. The dashboard provides an overview of total sales, profit, volume, sales per customer, regional distribution, top states by sales, sub-category sales, and sales trend over time.

## Dashboard Overview
### Dashboard Name: Sales Dashboard
### Dashboard Title: Superstore Sales Performance
Dashboard Description: Sales overview of the Superstore data
Dashboard Size: Width – 1055, Height – 850 (FIXED)
View 1: Total Sales

Displayed total sales in thousands with the header "Total Sales".
Color coded sales using the palette #76b7b2.
Disabled tooltip for this view.
Sheet named "Total Sales".
View 2: Total Profit

Similar to Total Sales with total profit displayed.
View 3: Total Volume

Similar to Total Sales with total volume displayed.
View 4: Sales Per Customer

Similar to Total Sales with sales per customer displayed.
View 5: Pie Chart (Total Sales by Region)

Pie chart displaying the percent of Total Sales by Region.
Used the Summer Color Palette and added black borders.
Formatted tooltip to display Region Name, Percent of Total Sales, and Total Sales value formatted in currency.
View 6: Bar Chart (Top N States by Sales)

Horizontal Bar Chart displaying the top N states by Sales.
Implemented a Parameter for users to change the value of N.
Sorted data in descending order and used custom color for bars with labels displayed in $.
View 7: Bubble Chart (Sales by Sub-Category)

Bubble chart displaying Sales by sub-category.
Bubbles colored by category with tooltip displaying sub-category and sales value in $.
View 8: Line Chart (Sales Trend by Month-Year)

Continuous line chart displaying Sales trend by Month-Year.
Formatted X-axis to display month and year in MMM YY format.
Hidden axis titles and formatted tooltip to display Month-Year and sales value in $.
Dashboard Filters
Applied filters for Order Date (Range of date), Segment, and Ship Mode.
Formatted filter background and added borders.
Placed filters in a horizontal container and distributed them evenly.
Dashboard Containers
Horizontal Container 1: Title/Logo with shopping cart image.
Horizontal Container 2: Filters arranged horizontally.
Horizontal Container 3: Scorecards arranged horizontally.
Horizontal Container 4: Pie Chart and Bar Chart arranged horizontally.
Horizontal Container 5: Bubble Chart and Line Chart arranged horizontally.
Vertical Container: All horizontal containers placed one above the other in sequential order.
Dashboard Formatting
Legends: Hidden titles and placed next to associated charts.
Borders: Added borders per chart or container for clarity.
Fit View: Set the dashboard to "Entire View" wherever applicable.
Sheet Titles: Provided meaningful titles for each visualization.
Hide Sheets: Hidden all sheets after finalizing the dashboard.
Actionable Filters and Parameters
Utilized the Pie chart and Bubble chart as Actionable Filters.
Placed the parameter close to the Bar chart and Sheet title.
Final Dashboard
