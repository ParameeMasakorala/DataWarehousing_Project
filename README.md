# DataWarehousing_Project
This is a project develop using SQL Server Management Studio(SSMS) and Visual Studio. Here I created data warehouse using the data in a source database.
## Setting-up the Environment
#### Following tools are required to develop this project
• SQL Server Management Studio

• SQL Server Data Tools

• SQL Server 2016 or higher

• Microsoft Office (Excel/ Word)

#### Below database backups are required (Resources)

• RetailSourceDB.bak -> This database backup contains the source system data.

• CustomerAddress.txt -> This file contains all customer address information.

## Creating Databases and load data 

In here main data sources are relational tables in a source database and a flat file. As the first step, data needs to be extracted from the source systems (database and flat file) and loaded in the 'Staging' area, which is an intermediate storage between source systems and target, data warehouse. Data model/table structures of the 'Staging' database is very much closer the structure of the sources. Main difference is all the source tables/files are available in a single database server. Next step is to extract data from 'Staging'
database tables, transform data and load them into corresponding tables in dimensional model created in the data warehouse(ETL). This step will contain considerable transformation as the data warehouse tables are based on a dimensional model.
