# Zomato-Analytics-Dashboard-Using-PowerBI
Objective
The objective of this project is to identify the key factors driving sales  and provide actionable insights for improving sales for restaurants This dashboard provides insights of varoius city performance , user analysis of users which help zomato team for there furher analysis. 

Throughout this project, I've had the chance to:

Dive deep into orders and restaurant data to uncover valuable insights.
Develop interactive dashboards to visualize key  metrics.
Provide data-driven recommendations for strategic decision-making.
Steps followed:

1. Data Gathering:

Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.

2. Data cleaning:

Cleaning is done by removing empty column, removing duplicates, errors etc.
Replacing values in column with proper values and naming.
Detecting data type of every column, using the auto detect data type function in Power query editor.

3. Data processing:
In the Power Query editor, replaced null city with other and made four KPI cards ( sales_value sales_amount, rating_count, order_count) and also used varous dax(data analysis expression) functions like
format(for date manipulation) , count (for getting restraunt raiting & count how many orders have been made)
This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.

5. Data analysis:

Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.


These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.
![z1](https://github.com/subhj/Zomato-Analytics-Dashboard-Using-PowerBI/assets/98201527/a5bcef88-8d44-45c5-bc1a-99eb56a3eb51)

![z2](https://github.com/subhj/Zomato-Analytics-Dashboard-Using-PowerBI/assets/98201527/3776d2ae-6b6e-41d6-b770-b49e53ad1021)

![z3](https://github.com/subhj/Zomato-Analytics-Dashboard-Using-PowerBI/assets/98201527/246e4fc9-c0c3-490a-a410-84cba8e66344)
