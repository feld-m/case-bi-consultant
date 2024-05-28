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

Please load these files into a database of your choice. This database needs to be accessible to Power BI for the subsequent tasks. 
Examples for potential databases include Postgres database (server running on localhost or a location of your choice) and BigQuery. These are just examples, please feel free to make your own choice. Just don't work simply based on the CSV files. You can choose whether to import the data into your database via a data import wizard (e.g. provided as part of the SQL IDE Dbeaver) or by writing a Python script.


2. For Visualization, please use Microsoft Power BI.


3. Using either queries on your database or Power BI, please prepare
answers to the following questions:
    1. We're interested in customers who are spending quite a lot with individual orders. Can you
tell us how many customers there are which have placed at least one order in which their
total sales amount exceeded 2,000$?
    2. We're a bit worried about the increasing number of returns. Can you look into the data
on returns and see whether you can find any valuable information on these returns, e.g., in
the context of product category, time?
    3. Imagine you – in the role of a BI consultant – had a meeting with one of the area managers
coming up next week (which of them you'd like to meet is up to your choice). 
       1. Can you prepare a dashboard which allows you to evaluate key performance indicators (KPI) of the region. The manager didn't provide you with any requirements and expects to take the first shot. Therefore, be prepared to discuss your approach in the meeting.
       2. Using the developed dashboard and any additional analysis, can you dive into the data and come up with some valuable insights on the business in the respective manager's region which you think would provide value for them in the future?
       NOTE: All four area managers are not too data-savvy and prefer visual analyses over plain numbers and text.


4. Archive your work and send it to the person who provided you the case via email.
   NOTE: The archive file should contain your SQL queries and Power BI's outcome – ideally in a format which allows us to review your work (e.g., use import query mode or provide us the DB's credentials in use).
   
### What we’ll be evaluating your submissions on

1. Your work is accurate, easy to read & interpret and shows tendency for reusability & maintainability
2. Your work work follows best data visualisation practices, e.g., appropriate chart types, suitable dashboard structure
3. Your work considers the business / data at hand and the likely requirements of the stakeholder
