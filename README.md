# Pyspark
**Spark**: A distibuted computing engine which distributes our data to process it.
<img width="1000" alt="Screenshot 2025-04-10 at 11 43 12 PM" src="https://github.com/user-attachments/assets/6b50fca4-8060-486c-8ad9-aee58d521831" />
Driver program (orchastrate) break down the code into executable task and requests the cluster manager to assign worker node.
<img width="613" alt="Screenshot 2025-04-11 at 11 48 12 AM" src="https://github.com/user-attachments/assets/8e51c757-6e48-4700-8fd0-2e9f89b72db7" />

Functions we apply to col(field): cast,alias,isin,isNull,desc

Parquet: Columnar storage, for analytical file processing we need selected columns not all the columns

Parquet vs Delta: Parquest stores the metadaa at the footer of the file. Delta stores as parquet but a separate log for meta data and transaction log.

Managed vs External Table locations. Managed: Table is stored in the default databricks location and is managed by databricks.
If it is external, table is in my own location so when we perform drop operation it will not delete the data it will just drop the schema not the data. data is managed by us.to create an external table we need to mention the location no other difference
