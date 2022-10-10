# seattlehousingdashboard
When market conditions turn for the worst it has a knock on effect for real estate, and more specifically home loans. This project looks at Seattle Washington distressed home loan market with the aim to provide up to date information, there by improving market clearing. 

## Topic
Build a simple analitics tool for real estate investors for the purpose of improving market based real-time information. This project uses the King County Records online resource to collect and format data from a set time period. The resulting dashboard will display map and list details of each property along with investor metrics and overall market view.

## Roadmap

1. Extract, Transform, and Load
    - Pull list of distressed properties from King County Records
    - Pull property details from related resources
    - Pull Home Mortgage Database dataset
    - Sort and transform data in Pandas
    - import dataframes into SQL Postgres Database
2. Create subsets in Azure Data Studio
    - Using SQL queries to create data tables
3. Design Tableau dashboard
    - Map feature to filter by location
    - List for selection
    - Past due home loan data line chart
    - Display investment potential figures with params
    - Walkability Score

## Tableau Dashboard

![screenshot](/seattlehousing.gif "Seattle Housing Dashboard")

[View Dashboard in Tableau Public](https://public.tableau.com/views/Book2_16641659196370/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)