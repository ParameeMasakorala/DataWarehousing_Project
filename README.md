# DataWarehousing_Project
This is a project developed by using SQL Server Management Studio(SSMS), SQL Server Data Tools(SSDT) and Visual Studio. Here I created data warehouse using the data in a source database.
## Step 01 - Setting-up the Environment
#### Following tools are required to develop this project
• SQL Server Management Studio

• SQL Server Data Tools

• SQL Server 2016 or higher

• Microsoft Office (Excel/ Word)

#### Below database backups are required (Resources)

• RetailSourceDB.bak -> This database backup contains the source system data.

• CustomerAddress.txt -> This file contains all customer address information.

## Step 02 - Creating Databases and load data 

In here main data sources are relational tables in a source database and a flat file. As the first step, data needs to be extracted from the source systems (database and flat file) and loaded in the 'Staging' area, which is an intermediate storage between source systems and target, data warehouse. Data model/table structures of the 'Staging' database is very much closer the structure of the sources. Main difference is all the source tables/files are available in a single database server. Next step is to extract data from 'Staging'
database tables, transform data and load them into corresponding tables in dimensional model created in the data warehouse(ETL). This step will contain considerable transformation as the data warehouse tables are based on a dimensional model.

![Staging](https://user-images.githubusercontent.com/88538105/236136610-4190cd46-6ba9-439f-be04-a55e18322de8.png)
![DW](https://user-images.githubusercontent.com/88538105/236136650-6d0337a5-4a58-43c8-8dac-130b085306a9.png)

![SCN](https://user-images.githubusercontent.com/88538105/236136673-d704409c-7771-422d-8745-b6635633e5db.png)

![stagingSSDB](https://user-images.githubusercontent.com/88538105/236136702-8867ce27-4256-4a6f-877e-a2777db0b47f.png)


![RetailSSDB](https://user-images.githubusercontent.com/88538105/236136718-871cc521-d448-4ab3-9572-f86f6342c3d6.png)








