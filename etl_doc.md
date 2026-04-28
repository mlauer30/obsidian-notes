# ETL Project Workflow
## Updated notes and diagrams
[https://github.com/mlauer30/obsidian-notes.git](https://github.com/mlauer30/obsidian-notes.git)

### As-is: 
> Current workflow involves manually normalizing data from the "LogMeIn Inventory" and the "UKG Active Employees" reports to do table joins and data queries in excel via Power Query.

### To-be:
> Still use excel but create an ETL workflow for "LogMeIn Inventory", "AirTable All Hardware Inventory", "OneLogin" and "UKG Active Employees" lists to automatically normalize data and focus efforts towards building relationships in Power Query.
#### Results
- Simple relationships between two to three tables is feasible, but is difficult to maintain.
- ETL strategies are not possible in Excel. Changing data will completely break data since Excel does not offer RDBMS level of normalization.
- Primary keys do not permananently fix themselves to data points in Excel tables, even with Power Query... 

### At-scale:
> Goal is to have a sound workflow in place for when cloud migration occurs so that options open up for larger reports or massive datasets can be referenced in with Fabric in OneLake and Power BI. 

## Research Links:
1. [Snow Flake data lakes concepts and more](https://www.snowflake.com/thankyou-snowflake-dummies-guide-series/)
2. [Power BI Guides and One Lake](https://learn.microsoft.com/en-us/power-bi/fundamentals/power-bi-overview)
