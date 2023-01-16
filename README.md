ETL for a Sales Data Warehouse using AWS - RDS
Sanjay Mamidi 5/17/2019
(Course work for Data Analysis and Vizualization Certification at UC Davis)
Summary
This ETL implemented by Extracting sample data from csv files and Transformed using Pandas. The data is then Loaded
into a MySQL database hosted via RDS service of AWS.The database design implemented is a Star schema.

Data Source
Kaggle Sample Data

ER Diagram
ER Pic [Shareable link] (https://drive.google.com/file/d/1WB0caaytEtTWGYAoHCIcloBJS3SFlCvr/view?usp=sharing)

Repository
Implemented using AWS MySQL RDS Data Repository. [AWS RDS Platform] etldb.cnbpyehug8lo.us-east-2.rds.amazonaws.com

Methodology
Data is extracted and loaded into five dimension tables(Geography,Time,Deal Size,ProductLine,Customer) and one Fact table holding numerical measures like Sales and Quantity. For purposes of meeting coursework requirements the dimension tables have not been futher decomposed into geography or customer Heirarchies. Also not all of the data columns have been used to develop this sample application. "todo" add info around data loading and keys
