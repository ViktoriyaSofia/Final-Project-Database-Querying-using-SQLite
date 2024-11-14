# Task Overview & Summary of Work Done
## 1. Understood Three Chicago Datasets:
I reviewed three key datasets on Chicago's Schools, Crime, and Demographics. 
After loading each dataset into a Pandas DataFrame, I examined their structure, columns, and any missing or irregular data.

- Schools: Detailed info on schools (names, locations, performance metrics).
- Crime: Crime records (type, description, date, location, arrest status).
- Census: Demographic data (income, poverty, community areas).

## 2. Loaded the Datasets into an SQLite Database:
I created an SQLite database called FinalDB.db and uploaded the three datasets into separate tables.
I successfully loaded the datasets into three tables in the SQLite database, enabling efficient analysis using SQL.

- Chicago_Public_Schools: Data on schools, including performance metrics and locations.
- Chicago_Crime_Data: Information on crime incidents, types, locations, and arrests.
- Chicago_Census_Data: Demographic data such as income levels and poverty rates.

These tables allow for detailed analysis using SQL to explore relationships between schools, crime, and community conditions.

## 3. Executed SQL Queries to Answer Assignment Questions:
I used SQL queries to analyze crime and census data in Chicago, answering key questions about crime patterns, socio-economic conditions, 
and school performance across different neighborhoods. This analysis provides valuable insights into the relationship between 
socio-economic conditions, crime, and schools in Chicago, facilitating deeper urban studies and policy-making.

### Crime Data Analysis:
- Total number of crimes
  - The total number of crimes recorded in the dataset was 533
    
- Crimes involving minors
  - I identified crimes involving minors, such as liquor law violations and illegal consumption by minors
    
- Crimes recorded at schools
  - I listed various crimes recorded at schools, including assault, battery, narcotics, and criminal damage

- List all kidnapping crimes involving a child
  - This query returns all kidnapping crimes that involve a child, based on the case number, crime type, and description.
    It provides critical information for law enforcement,
    community safety planning, and policy-making aimed at protecting children.
    
- Most crime-prone community areas
  - The most crime-prone community area in Chicago, based on the frequency of crime reports,
    is Community Area 25 (Austin), which recorded 43 crimes

### Census and Demographics:
- Community areas with per capita income below $11,000
  - These areas include neighborhoods like West Garfield Park, South Lawndale, Fuller Park, and Riverdale,
    all of which have per capita income levels below $11,000
    
- Areas with the highest poverty rates
  - The top 5 community areas with the highest percentage of households below the poverty line are:
      - Riverdale (56.5%)
      - Fuller Park (51.2%)
      - Englewood (46.6%)
      - North Lawndale (43.1%)
      - East Garfield Park (42.4%)
        
- Community Area with the Highest Hardship Index
  - The community area with the highest hardship index is Riverdale, indicating a higher concentration of socio-economic challenges

### School Data Analysis:
- Breakdown of schools by type (elementary, middle, high)
  - The dataset includes different types of schools such as elementary, middle, and high schools
    
- List the kind of crimes that were recorded at schools
  - This query helps identify the various types of crimes that have been recorded at schools,
    including their specific locations (whether in a building or on school grounds) and a brief description of each crime type
    
- Schools along with the average safety score for each type
  - The query gives the average safety score for each type of school
