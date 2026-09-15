# Data Engineering & Analytics Portfolio  

Hi there! Welcome to my still developing data engineering & analytics portfolio. In this repository you will find projects completed from various data engineering/analytics courses or self development projects, each of which covers essential skills and techniques.  

## [Flight Data Pipeline](https://github.com/geoffreycloud/flight_data_pipeline)
- Summary: Apache Airflow was used to Automate an ETL pipeline extracting data hourly from [FlightLabs API](https://www.goflightlabs.com/real-time) transforming it, and loading it into a postgreSQL database.
- Technology used: _Python, pandas, psycopg2, PostgreSQL, Apache Airflow, Docker Desktop, Tableau_
- Final Results:
    - [Raw flight table](https://github.com/geoffreycloud/flight_data_pipeline/blob/main/data/flights_data_raw.csv) preserving API structure.
    - [Clean flight table](https://github.com/geoffreycloud/flight_data_pipeline/blob/main/data/flights_data_clean.csv) with normalized column names and transformations.  

## [Flight Delay Prediction Using Apache Spark](https://github.com/geoffreycloud/Flight-Delay-Prediction-Using-Apache-Spark)
- Summary: Built an end-to-end Structured Streaming pipeline in Apache Spark processing the full January 2023 flight dataset (538,837 records) across 8 streaming batches, computing delay-rate aggregations by airline, airport, hour, and day, and applying an MLlib classification model to predict flight delays.
- Technology used: _Python, Apache Spark, Spark Structured Streaming, Spark SQL, MLlib_
- Final Results:
    - [Final report](https://github.com/geoffreycloud/Flight-Delay-Prediction-Using-Apache-Spark/blob/main/docs/results.md) summarizing pipeline results and delay trends.
    - MLlib delay classifier achieving 99.1% precision / 24.1% recall on the delayed class, with limitations documented in [LIMITATIONS.md](https://github.com/geoffreycloud/Flight-Delay-Prediction-Using-Apache-Spark/blob/main/docs/limitations.md).

## [Serverless Spark ETL Pipeline on AWS](https://github.com/geoffreycloud/Hands-on-Spark-on-AWS)
- Summary: Built a fully automated, event-driven serverless pipeline where an S3 file upload triggers an AWS Lambda function, which kicks off an AWS Glue Spark job to clean product review data, run Spark SQL analytics, and write aggregated results back to S3.
- Technology used: _PySpark, AWS Glue, AWS Lambda, Amazon S3, AWS IAM, Parquet_
- Final Results: Automated pipeline producing daily review-count, top-customer, and rating-distribution aggregations stored as Parquet in S3, eliminating manual data processing.

## [Charlotte Parks & Greenways](https://github.com/geoffreycloud/ITIS-6112-Term-Project-Group-2-main)
_Role: Backend Developer_
- Summary: Designed and implemented backend services for an interactive web application that visualizes publicly available parks and recreation data in Mecklenburg County, NC, enabling filtering, keyword search, and address radius queries. Focused on building reliable APIs and geospatial data workflows to support dynamic map interactions.
- Technology used: _JavaScript, Node.js, Express.js, PostgreSQL (PostGIS), ArcGIS REST Services_
- Final results: Scalable backend and geospatial database powering a user friendly interactive map for navigating county parks, trails, and greenways.  

## [Country GDP ETL Pipeline](https://github.com/geoffreycloud/3_ETL_GDP_Data)
- Summary: Built an ETL pipeline as part of a data engineering course to scrape country GDP data from Wikipedia, clean and transform the values from millions to billions (USD), and store the processed data for analysis and verification. The focus was placed on web scraping techniques, data transformation, and structured data loading.
- Technology used: _Python, Beautiful Soup, requests, pandas, SQLite, SQL_
- Final results: [Cleaned and transformed GDP dataset](https://github.com/geoffreycloud/3_ETL_GDP_Data/blob/main/GDP_USD_Billions.csv)

## [iOS App Review Insights](https://github.com/geoffreycloud/ios-app-review-insights)
- Summary: Built a feature-level sentiment analysis pipeline for Strava iOS app reviews, extracting specific app features (e.g. subscription, workouts, Garmin integration) and scoring sentiment per feature to surface actionable product insights beyond traditional document-level classification.
- Technology used: _Python, spaCy, VADER, scikit-learn (TF-IDF, Logistic Regression), pandas_
- Final Results: Found fitness features (runs, workouts) drove strongly positive sentiment while monetization features (subscription, premium) skewed negative; baseline Logistic Regression classifier reached 80% accuracy.

## Others
- [Intro Data Analysis Project](https://github.com/geoffreycloud/CSV_Data_Analysis)
