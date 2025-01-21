# Data Pipeline Project with Snowflake, dbt, and Airflow

This project sets up a data pipeline using Snowflake, dbt (data build tool), and Airflow. Below are the main commands and steps to set up and execute the pipeline.

## Steps Completed
1. Setup Snowflake Environment
2. Configure `dbt_profile.yml`
3. Create Source and Staging Files
4. Implement Macros
5. Transform Models (Fact Tables, Data Marts)
6. Implement Generic and Singular Tests
7. Deploy on Airflow

### Initialize Project  
To start a new dbt project:  
dbt init [project_name]  

### Compile Models  
To compile all the models in your project:  
```dbt compile```  

### Run Models  
To run all the models in your project:  
```dbt run```  

To run a specific model:  
```dbt run --select [model_name]```  

Run Tests  
To run all the tests defined in your project:  
```dbt test```

To run a specific test:  
```dbt test --select [test_name]```

### View Documentation  
To generate documentation for your project:  
```dbt docs generate```  

To start a server and view the documentation in your browser:  
```dbt docs serve```

### Update Source Data  
To update the source tables defined in the project:  
```dbt source freshness```