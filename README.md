# Case: Business Intelligence Consultant
The case resolves around a hypothetical online store. They're selling merchandise
in different product categories to customers within the United States. Attached to the document you will find CSV files
which cover information about orders, returns and area managers of the e-commerce company. Please use this data
to prepare the following tasks.

### Tasks

1. Attached to this document you will find three CSV files:
    1. Orders.csv
    2. People.csv
    3. Returns.csv

Please load these files into a database of your choice. This database needs to be accessible to Tableau for the subsequent tasks. 
Examples for potential databases include Postgres database (server running on localhost or a location of your choice) and BigQuery. These are just examples, please feel free to make your own choice. Just don't work simply based on the CSV files. You can choose whether to import the data into your database via a data import wizard (e.g. provided as part of the SQL IDE Dbeaver) or by writing a Python script.


2. For Visualization, please use Tableau Desktop (if you do not have a license, you can start a [free trial](https://www.tableau.com/en-gb/products/trial)).


3. Using SQL on your database, we're interested in customers who are spending quite a lot with individual orders. Can you
tell us how many customers there are which have placed at least one order in which their
total sales amount exceeded 2,000$?
  
5. Using either queries on your database or Tableau, please provide answers to the following questions:
    1. We're a bit worried about the increasing number of returns. Can you look into the data
on returns and see whether you can find any valuable information on these returns, e.g., in
the context of product category, time?
    2. Imagine you – in the role of a BI consultant – had a meeting with one of the area managers coming up next week (which of them you'd like to meet is up to your choice).
       1. Can you prepare a dashboard which allows you to evaluate key performance indicators (KPI) of the region. The manager didn't provide you with many requirements except the message below; however, the manager wants you to take your own initiative and have something ready when you meet.

          "I want to be able to quickly compare current period vs previous period for each KPI for my region. Ideally, I would have a filter with these options: This Year, This Quarter and This Month. When one of those are selected, I would also see the performance of one of those: Previous Year, Previous               Quarter and Previous Month. Additionally, it would be great to have one compeletly custom date range option, e.g., 1/2/2021 as a start date and 15/3/2022 as an end date. It should be affecting the same KPIs charts and similarly as above showing in addition the performance in the previous period as             in the range of the selected custom date option. Do you think you can make this happen?"

       2. Using the developed dashboard and any additional analysis, can you dive into the data and come up with some valuable insights on the business in the respective manager's region which you think would provide value for them in the future?
       NOTE: All four area managers are not too data-savvy and prefer visual analyses over plain numbers and text.


6. Archive your work and send it to the person who provided you the case via email.
   NOTE: The archive file should contain your SQL queries and Tableau's outcome – ideally in a format which allows us to review your work..
   
### What we’ll be evaluating your submissions on

1. Your work is accurate, easy to read & interpret and shows tendency for reusability & maintainability.
2. Your work follows best data visualisation practices, e.g., appropriate chart types, suitable dashboard structure.
3. Your work considers the business / data at hand and the likely requirements of the stakeholder.
