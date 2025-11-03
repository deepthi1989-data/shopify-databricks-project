# shopify databricks pipeline

Load data from ADLS gen2 and tranform using dataricks.
We loop over each file inthe source and load into Bronze layer We use parameterized file name and loop over each to load to bronze
From Bronze we do data cleaning and tranform it to load to silver
We aggregate this dat and load data to gold
