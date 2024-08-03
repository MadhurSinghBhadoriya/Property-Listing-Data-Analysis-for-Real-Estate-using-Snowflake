# Property-Listing-Data-Analysis-for-Real-Estate-using-Snowflake

Part 1: Scrape, Load, and Flatten Data

    Data Source: Otodom website for Poland Real Estate properties, collected using a web scraping tool (Bright Data).
    Loading Data: Loaded data to Snowflake by creating a new database, warehouse, tables, stage, and file format. Utilized SnowSQL to load data from the local machine to Snowflake DW.
    Data Flattening: Flattened JSON data to individual table columns and removed unwanted data (e.g., URLs).

Part 2: Data Transformation

    Location Transformation: Transformed location coordinates (lat, long) into addresses using Python. The workflow was Snowflake -> Python -> CSV -> Snowflake.
    Language Translation: Set up APIs in Google Developer Console to convert the Polish title column to English using Google Sheets. The workflow was Python -> Sheets, Sheets -> Snowflake.

Part 3: Data Analysis, Cleaning, and Reporting

    Report Building: Analyzed and cleaned the data, then built reports to provide insights into the property market in Poland:
        Average rent for 1, 2, 3, and 4-room apartments in major cities.
        Sizes of apartments.
        Top 5 most affordable neighborhoods by city.
        Monthly rents across cities.
        Distribution of private vs. business ads on Otodom.
        Average sale and rental prices by suburb, surface area, and identifying the most expensive apartments in major cities (city, suburb, cost, size).

Technologies Used:

    Web Scraping: Bright Data.
    Data Loading and Management: Snowflake, SnowSQL.
    Data Transformation: SQL, Python, Google Sheets.
    Data Analysis and Reporting: SQL.

Role and Responsibilities:

    Led the entire project lifecycle from data scraping to report generation.
    Developed and maintained ETL processes to ensure data integrity and efficient retrieval.
    Transformed and translated data to make it more accessible and useful for analysis.
    Built comprehensive reports to provide actionable insights into the property market.

Achievements:

    Successfully integrated data from multiple sources, transforming raw data into valuable business insights.
    Improved data accessibility and usability by automating data transformation and translation processes.
