# Budget Sales Analysis


##  Problem Statement:- 
Effective budgeting and sales analysis are crucial for businesses to manage finances, optimize resources, and achieve revenue targets. However, many organizations face challenges in accurately forecasting sales, tracking performance against budgeted targets, and identifying areas for improvement.The objective of this project is to analyze sales data and budget allocations to assess the performance of sales initiatives, evaluate budget adherence, and provide actionable insights to optimize sales strategies and resource allocation.

##Steps Followed
- Step 1 : Load data into Power BI Desktop, dataset is a Excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present. After checking for errors and null values select "Apply and Close" option
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : In the Dashborad there are 2 pages named as "Overview" and "Analytics".
- Step 7 : Since the data contain "Budget","Calender","Product","Customers","Territories","Sales" thus in order to represent all these data a visual called KPI cards were added on the canvas. KPI 1 shows the "overall standard cost, KPI 2 shows the "Overall unit price" and KPI 3 shows the"overall tax amount"".
- Step 8 : Visual filters (Slicers) were added for "product name","Region"
- Step 9 : KPI 4 shows the visual of 100% stacked bar chart for the sales amount of category and stacked coloumn chart for the sales amount by subcategory.
- Step 10 : KPI 5 shows the visual of clustered bar chart For the grand total by category and line chart shows the sales amount by country. 
- Step 11 : A budget table were added which contain the category, unit price ,sales amount and budget of year 2016 from the month of january to december.
- Step 11 : KPI 6 is a visual of gauge for the overall sales amount.
- Step 12 : KPI 7 represents the visuals of 100% stacked coloumn chart For the sales amount by occupation of customer.
- Step 13 : KPI 8 represents the visuals of clustered coloumn chart for the sales amount and yearly income from year 2014 to 2017. 
- Step 14 : KPI 9 represents the visuals of pie chart of top 3 model name sales amount and donut for the sales amount of top 5 region.
- Step 15 : KPI 10 represents the visuals of line chart For the standard cost and unit price by category.

## Snapshot of Dashboard[Power BI Desktop]
Page 1 : Overview
![Screenshot (14)](https://github.com/Harhare18/Budget-Sales-Analysis/assets/101700437/1df745a6-4fb8-46ca-978d-9b7438ecac59)


page 2 : Analysis
![Screenshot (15)](https://github.com/Harhare18/Budget-Sales-Analysis/assets/101700437/1beb24a6-f5b4-4f02-8baf-ca0e5658fe4d)



## Insights
Following inference can be drawn from the Dashboard    
KPI 1:
- There are 3.37M of overall standard cost.

KPI 2:
- There are 3.93M of overall unit price.

KPI 3: 
- There are 0.44M overall tax aamount.

KPI 4:
- In the category of bikes females had the more sales amount with 50.49% and in accessories and clothing male has more sales amount of 50.15% and 50.01%.
- In subcategory bikes has a more sales amount road bikes with 14.12m, mountain bikes with 9.95m and touring bikes with 3.84m.

KPI 5:
- In the category bikes has a more grand total of 15.8M.
- And United States and Australia has high sales amount with9.4m and 9.1m resp.

KPI 6:
- The overall sales amount is 29.31M.

KPI 7:
- In the occupation of professional and skilled manual the male has more sales amount of 51.83% and 51.96% resp.
- In the occupation of management and clerical the females has high sales amount of 51.09% and 51.68% resp.

KPI 8:
- Sales amount and yearly income is the same in the year from 2014 to 2017.

KPI 9:
- The model name Touring-3000 has more sales amount of 83.1% and region Southwest has high sales amoun of 44.76%.

KPI 10:
- In the category satndard cost of the components is high and unit price of bikes is high with 23M.
