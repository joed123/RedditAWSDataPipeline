This project extracts data from Reddit using its API, manages ETL processes with Apache Airflow and Celery, stores data in Amazon S3, catalogs and transforms data with AWS Glue and Athena, and sets up and loads data into Amazon Redshift for analytics.

To run:

1. python3 -m venv venv
2. source venv/bin/activate
3. pip install -r requirements.txt
4. mv config/config.conf.example config/config.conf
5. docker-compose up -d

