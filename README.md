# End-to-End-Project-with-PowerBI--globalstore2016
This is my end to end project using Power Bi for some data cleaning and visualization of the Global store data 2016  .

In this end to end project we are using power bi for the final dashboard output which will help for some meaningfull insights to the marketing team.

Power BI is an interactive data visualization software product developed by Microsoft with a primary focus on business intelligence.It is part of the Microsoft Power Platform. Power BI is a collection of software services, apps, and connectors that work together to turn unrelated sources of data into coherent, visually immersive, and interactive insights. Data may be input by reading directly from a database, webpage, or structured files such as spreadsheets, CSV, XML, and JSON.
Microsoft Power BI Desktop is a data analysis and reporting application that a user can install on a computer to create dashboards and live reports. Integrated with Power BI Service, the user can also share these reports with decision-makers and stakeholders to help them understand the current state of the business.
It brings all the components and analytics features on a single platform. Power BI has a simple and easy-to-use interface that allows even a non-technical user to build compelling reports, data models, and custom dashboards


Connect with Data Sources
Power BI Desktop data sources include Excel spreadsheets, CSV files, Q-data feed, online services, and data on the cloud. This data could be structured, semi-structured, or unstructured, depending on the business type.


Transform Data & Create Models
Using Power Query Editor, you can extract valuable information, remove anomalies, and add some conditions for a better understanding of the data. It is similar to sculpting a block of wood by cutting the edges, removing extra wood, shaving off the projections, and adding other ingredients to make it look as intended.


Project Idea
In this Project we will connect the Power Bi Dekstop with database in our case it is in .xlxs format. The data base is about ‘Global_Superstore 2016 Data’ provided by ‘End To End’ Youtube channel. We will do some data Cleaning with the help of Power Query editor. Add Some data which is needed and Finally the Report using some Bar,Pie,map Charts etc. 

Project Goal
The Project Goal is to Build an End To End Report using power Bi dekstop. In this we will do Data Cleaning ,Filtering and Creating a Beautiful and Interactive Relational  dashboards. This Final report can be used to analyze the companies growth ,sales,markets etc. And these dashboard can help to take future decisions by the sales and marketing team.


Project Steps
1. Connecting Database with Power BI Desktop.
2. Analyzing the tables and relations. 
3. Data Cleaning using Power Query Editor with DAX (Data Analysis Expressions)  and ultimately .
4. Developing an Interactive BI Dashboard / Report

1.In the first step we have to download the power BI desktop application from apps store. The data file is provided with the report .This user interface will appear when we first open power Bi Dekstop
2. After that we have to choose data source in this we have data in excel format (you can use any data source like SQL,MongoDb  etc .PowerBI Supports all types of Data Sources that are available) .It shows the file and after that we have to select all the columns like Orders ,People, Returns. After that click load it will take some time depending on the size of the data.
3.All the data can be seen in the power Bi desktop app .
4.Our next step is doing some data Cleaning . We are adding one column for delivery days estimation for that we are using power Query editor and in that we will create new column ,named Delivery days.
5.And after that on the delivery days dropdown we will deselect 0 because it is an error and will deselecting this .
6.In the visualization menu we will add card and in fields area we will drag and drop sales from the right side orders dropdown.It will show the sum of total sales in the dashboard
7.Do in the same we will add some more cards to represent the data in the dashboards. 
8.We will be adding one more custom column in the data sheet to take out the trade year. 
9. Again in the power query editor we are creating a conditional column for returned items in the returns column 
10. In the Visualization menu we are adding some more visualizations to our dashboard  and one can create beautiful dashboards by using different visualizations.

After spending some time to beautify and filtering the dashboards we have finally created our final dashboard .One can add multiple dashboards as well in this we using only one one dashboard


Summary
Finally we have managed to create our dashboard using Power Bi and its functions .This Dashboard will help the marketing team to see the exact revenue and returned orders that customers did. The most selling products for that they can discount on that .The map where we can see most of the buyers belong from where . The dashboard has sales by year filter as well.


Future Work
We can now work forward to explore this dashboard more ,to fetch meaningful information out of it. With all the insights , and further analysis into the data, we can have answers to a lot of questions like –
1.What are the most selling product .
2.Which country has the most buyers of the products.
3.Which type of segment people buy the products etc.
And the list goes on—


References
End to end youtube channel  https://www.youtube.com/watch?v=et8tAUTwcvY
Data is provided by end to end channel as well.
Power Bi tutorial by COdeBAsics channel.
