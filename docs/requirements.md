# Modern Data Stack


### General Product Requirements
    1. Build a Data Platform which ingests various data sources, applies transformation, creates dataset and allows Machine Learning Engineers to build Models over the datasets.
    2. Use only tools to build the platform, no reinventing of wheel.
    3. Support Multi-Cloud from Start as customer may want to move thier data to region where regulations are supported.
    4. Dockerize everything as this will help in moving to Kubernetes if scale increases.
    5. Data Products will be built on top of the platform, add support for DevTools.
    6. TO be added


### Top Components Requirements:


    1. Use DBt + Airflow Sensors + Operators + Airflow Scheduling
    2. Use Postgresql for Metadata Storage
    3. AWS S3  Free Tier to be used as lake data to store original data and  transformed data, final datasets in Snowflake.
    4. Any BI Tool can loadup the dataset for visualisation
    5. 
    
