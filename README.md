# Career Path - Data Engineer - Python

## What's the differmce beetwen OLTP and OLAP 
OLAP and OLTO are online processing systems.
- OLAP(Online Analytics Processing): Is an Analytical processing systems that enables users to easily and selectively EXTRACT and query data in order ro analyze it from different points of view. to facilitate this kind of analysis data is collected from multiples data sources and stored in data warehouses then cleansed and organized into datacubes. Each OLAP cube contains data categorized by dimensions (susg as customers, geographics sales region and time period).
    OLAP analytical operations:
        1. Roll-up. Also known as consolidation or drill-up, this operation summarizes the data along the dimension.
        2. Drill-down: This allows analysts to navigate deeper among the dimensions of data, for example drilling down from "time period" to "years" and "months" to chart sales growth for a product
        3. Slice: This enables an analystic to take one level of information for display, such as "sales in 2017"
        4. Dice: This allows an analyst to select data from multiple dimensions to analyze, such as "sales of blue beach balls in lowa in 2017"
        5. Pivot: Analysts can gain a new view of data by rotating the data axes fo the cube.

- OLTP (Online Transaction Processing): Is an operational system that supports transactions, the main focus of this is to record the current UPDATE, INSERT and DELETE, OLTP is basically focused on query processing, maintaining data integrity in multi access environments as well as effectiveness that is measured by the total numbers of transaction per second.
    1. Uses traditional DBMS
    2. Insert, Update and Delete information from databases
    3. It's response time is in a miliseconds
    4. It is used by Data critical users like DBA & Data Base professionals
    
- Data Warehouses: Is a repository for data generated and collected by an enterprise's various operational systems. 
- OLAP Cube: Is multidimensional database that is optimized for data warehouse and online analytical processing