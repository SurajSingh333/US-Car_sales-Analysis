This is the random dataset I was working on, and this dataset(https://www.kaggle.com/sachinsachin/car-sales) has incomplete and irregular data, this data is not ideal data to create a visual report, but I just wanted to work with some random, unstructured, non-normalized, and huge data, due to such irregularities I was not completely able to perform predictive analysis because dates and months were not maintained in regular interval of time, there was only one data available i.e price in a thousand.

My approach was, 

First of all, 

-To normalize the data, 
-Create lookup tables and data tables for each, calendar lookup, company lookup, data table, customer lookup, customer data table, dealer lookup, dealer data table, territory lookup table.
-Performed Data modeling. 
-Created Relationships b/w lookup table and data table keeping in mind downward filter flow(& cardinality i.e. one to many) 
-Used Calculated Columns and Measures(Date Functions, Logical, String, Aggregate, Table Calculations)and Parameter, Sets, Action, and Filters (Date, Category, etc.) to create various Visuals and KPI for extracting key insights from Data. 
-Used all the key components Visual (Bar chart, Line chart, Donuts Chart, Tree-Map, etc.)which can together provide a holistic view in the form of Dashboard. Create custom measures as Explicit measures.
-Tried to create Stories for visual sequences to build the narrative and add context.
