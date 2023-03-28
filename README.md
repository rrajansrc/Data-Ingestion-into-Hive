# Data-Ingestion-into-Hive
A small project to ingest the data from a MySQL table to the Hive warehouse. 

Introduction
	Implemented steps to Ingest the data from RDBMS table into Hive warehouse
	
Business Requirement
--------------------
	Perform data ingestion using sqoop: HDFS --> MySQL --> Hive
	
It Covers
	MySQL
	Sqoop (Import, Export and Sqoop Job)
	Hadoop-Linux commands
	Hive
	
Steps to implement the project;
-------------------------------

	1.	Create Required directories in HDFS using hdfs-linux commands and Load the data into HDFS.
	
	2.	Create Staging and Actual tables in MySQL.
	
	3.	Load the data into MySQL tables using Sqoop Export.
	
	4.	Create Sqoop jobs to import data from MySQL to HDFS.
	
	5.	Create Hive External table 
	
	6.	HDFS cmds for loading data into Hive tables;
	
	7.	Creating a shadow table for creating a data column for Partitioning.
	
	8.	Inserting data into the shadow table
	
	9.	Create an Hive optimized table
	
	10.	Insert data into the optimized table
