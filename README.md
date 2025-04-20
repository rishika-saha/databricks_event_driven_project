# databricks_event_driven_project
# Order Tracking Event Driven Data Ingestion (Industrial Project)
#      -> Tech Stack - Google Storage, PySpark, Databricks, Delta Lake, Databricks Workflows, GitHub
#       -> Connect Databricks with GitHub & Setup new repository
#       -> Setup GitHub folder and create following notebooks under that accordingly
#       -> Load daily arrival file from Databricks Volume to staging Delta table
#       -> Archive file in different location once loaded in staging Delta table
#       -> Perform SCD1 merge from Staging Delta Table to Target Delta Table
#       -> Create Databricks Workflow to run stage & target delta table load sequentially
#       -> Setup File arrival trigger for Databricks Workflow
