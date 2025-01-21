This project extracts data from Reddit using its API, manages ETL processes with Apache Airflow and Celery, stores data in Amazon S3, catalogs and transforms data with AWS Glue and Athena, and sets up and loads data into Amazon Redshift for analytics.

To run:

1. Set up an AWS Account with appropriate S3, Glue, Athena, and Redshift permissions.
2. Get a Reddit API key.
3. python3 -m venv venv
4. source venv/bin/activate
5. pip install -r requirements.txt
6. mv config/config.conf.example config/config.conf
7. docker-compose up -d

