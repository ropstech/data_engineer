# data_engineer
Data Engineer specific learnings

## Day 1

1. **Key Concepts**
    ### Short description Data Engineer
    
    A data engineer is a professional responsible for designing, building, and maintaining the infrastructure that enables data storage, transformation, and analysis. Think of them as the architects and builders of data systems.
    Their role is crucial in preparing raw data so that it can be used effectively by data scientists, analysts, and other business users to derive insights or build models.

    ### Key Responsibilities of a Data Engineer
    - Designing and Building Data Pipelines:

    - Ensuring Data Quality and Integrity:

    - Data Integration:

    - Scaling Data Infrastructure:

        As companies grow, their data grows too. Data engineers ensure that the systems they build can handle increasing amounts of data efficiently.

    - Automation and Monitoring:

    - Collaborating with Other Teams:

    ### What is a Data Pipeline?
    A data pipeline is a system or a series of steps that processes data. It helps move data from one place (source) to another (destination) while performing operations on it to make it useful.

    Imagine you’re getting raw sensor data from an airplane. The data pipeline is like a conveyor belt that takes the data, cleans it up, processes it, and stores it in a way that the company can use it to make decisions.

    The process of collecting and importing data from the sources into your pipeline is called **Data Ingestion**\
        You can differentiate between **Ingested data** can be streamed (real-time) or **batched** (collected periodically).<br/>
    
    ### Tools:

    **Stream:** Google Pub/Sub, Kafka, AWS Kinesis.\
    **Batch:** Apache Beam Airflow, cron jobs.\
            
    ### ETL vs. ELT

    E = Extract <br>
    L = Load <br>
    T = Transform <br>

    ELT is the standard to use. <br><br><br>

    - Learn about **batch vs. stream processing**.
        - Technologies: Apache Beam (for stream processing) and Airflow (for orchestration).
2. **Resources**
    - Read about **big data architectures** in cloud environments (search for Google Cloud documentation).
    - Watch a YouTube crash course on data engineering (e.g., "Data Engineering Full Course" by Simplilearn or DataCamp).
3. **Hands-On**
    - Write a basic Python script to simulate an ETL pipeline:
        - Extract a dataset (e.g., CSV).
        - Transform it (clean, filter, add new columns).
        - Load it into another format or database (SQLite or Google BigQuery).
4. **Optional**
    - Explore SQL and NoSQL basics:
        - SQL: Basic queries, joins, and aggregations.
        - NoSQL: Look into MongoDB or Firebase.