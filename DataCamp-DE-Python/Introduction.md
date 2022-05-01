

# Introduction DE

## **What is data engineering?**

### Data engineering and big data

**A Example of these data engineering concepts are implemented:**

​		A Data workflow as follows: 

![image-20220430132434932](https://github.com/YimingXu1/DS-notes/tree/main/DataCamp-DE-Python/img/intro1.png)

​		Data engineers are responsible for the first step of the process: ingesting collected data and storing it, so it's easily accessible and ready to be analyzed.



**A Data engineer's responsibilities:**

​		Ingest data from different sources

​		Optimize the databases for analysis

​		Manage data corruption

​		Develop, construct, test, and maintain data architectures



**Five Vs of Big Data: ** Volume (how much), Variety (what kind), Velocity (how frequent), Veracity 		(how accurate), Value (how useful).



### Data engineering vs. data scientists

​		

​		Data scientists intervene on the rest of the workflow, they prepare the data according to their analysis, explore it, build insightful visualizations, and then run experiments or build predictive models. 

![image-20220430140441967](https://github.com/YimingXu1/DS-notes/tree/main/DataCamp-DE-Python/img/intro2.png)

### Data pipeline





## **How data storage works?**

1. Structured vs. Unstructured data
   - structured data
     - Easy to search and organize
     - Consistent model, rows and columns
     - Defined types
     - Can be grouped to form relations
     - Stored in relational databases
     - About 20% of the data is structured
     - Created and queried using SQL
   - Semi-structured data
     - Relatively easy to search and organize
     - Consistent model, less-rigid implementation: different observations have different sizes 
     - Different types
     - Can be grouped, but needs more work
     - NoSQL databases: JSON, XML, YAML
   - Unstructured data
     - Does not follow a model, can't be contained in rows and columns
     - Difficult to search and organize
     - Usually text, sound, pictures or videos
     - Usually stored in datalakes, can appear in data warehouses or databases
     - Most of the data is unstructured
     - Can be extremely valuable
2. SQL databases
   1. - Structured Query Language
      - Industry standard for Relational Database Management System (RDBMS)
      - Allows you to access many records at once ,and group, filter or aggregate them
      - Close to written English, easy to write and understand
      - Data engineers use SQL to create and maintain databases
      - Data scientists use SQL to query( request information from) databases
   2. Several implementations
      - SQLite
      - MySQL
      - PostgreSQL
      - Oracle SQL
      - SQL Server
3. Data warehouse and data lakes
   1. ![image-20220501212521758](https://github.com/YimingXu1/DS-notes/tree/main/DataCamp-DE-Python/img/intro3.png)



## **How to move and process data?**

1. Processing data
2. Scheduling data
3. Parallel computing
4. Cloud computing