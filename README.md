Big-Data-Engineer-Healthcare-Project
This project demonstrates the end-to-end process of managing electronic health records (EHRs) with Azure cloud technologies, ensuring compliance with HIPAA regulations. It includes data storage, ETL pipelines, real-time health metrics, machine learning data preparation, and secure handling of sensitive data.

Project Structure
- adls_setup.py: Azure Data Lake setup and data storage.
- synapse_etl_pipeline.py: ETL pipeline for processing and transforming data.
- power_bi_dashboard.py: Power BI dashboard for visualizing health metrics.
- data_validation.py: Validates patient data for anomalies.
- ml_dataset_preparation.py: Prepares data for machine learning models.
- hl7_integration.py: HL7 message parsing and integration.
- key_vault_security.py: Secure handling of sensitive information with Azure Key Vault.
- sql_migration.py: Migrates on-prem SQL data to Azure SQL Managed Instance.

Setup
1. Install the required libraries: pip install azure-storage-file-datalake azure-synapse-artifacts azure-identity pandas pyodbc.
2. Configure your settings in config/settings.json.
3. Run the scripts as needed for each process (e.g., data loading, ETL pipeline, real-time monitoring).
