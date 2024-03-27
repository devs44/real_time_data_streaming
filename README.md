![real data streaming drawio](https://github.com/devs44/real_time_data_streaming/assets/62928989/f943decd-e63f-428f-9be2-d25b880dcfc0)

Project leverages the robust capabilities of Amazon Web Services (AWS) by utilizing EC2 as our compute service, powered by Amazon Linux. Employing Docker for containerization ensures seamless deployment and management of our applications.

At the heart of our data processing pipeline lies Apache NiFi, a powerful tool for data integration. Continuously ingesting data from various sources, NiFi orchestrates the flow of information with precision and efficiency. Integral to our architecture is the storage of processed data on Amazon S3, providing scalable and durable object storage for our needs.

To ensure data integrity and reliability, we harness the power of Snowflake, a modern cloud data platform. Leveraging Snowpipe, we seamlessly ingest data into Snowflake, where it undergoes further transformation and enrichment.

Our project incorporates sophisticated data modeling techniques, including Slowly Changing Dimensions (SCD) Type 1 and Type 2 methodologies. This allows us to accurately capture and manage changing data over time, ensuring our analytics are both comprehensive and up-to-date.
