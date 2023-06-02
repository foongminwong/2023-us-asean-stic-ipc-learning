# IBM Data Engineering

Link: https://www.coursera.org/professional-certificates/ibm-data-engineer

## Overview
This professional certificate track consists of 13 data engineering courses with hands-on labs on SQL, RDBMS, ETL, Data Warehousing, NoSQL, Bi Data, Spark, etc.

## Course Notes
[Introduction to Data Engineering](https://www.coursera.org/learn/introduction-to-data-engineering/)
#### Modern Data Ecosystem and role of Data Engineering
- "Data begets more data in a constant virtuos cycle."
- Data integrated from disparate sources in the enterprise data environment
- Structured & Unstructured data sources (They are diverse & dynamic!)
- Data Challenge: Reliability, security, integrity of the data
- Field of Data Engineering - To build a robust, scalable structure to make quality data available for decision-making, and that includes tools & technologies involved in data manipulation, plus the process involves understanding of data complexisits and how it is leveraged for fact-finding & decision-making
- Ensure data is highly available, consistent, secure, recoverable, seamless data flow within an organization
- Design, maintain, optimize data systems by choosing the righ databases, storage systems, cloud architecture or cloud platform
- Variety of databases: Wide column stores (Cassandra, Hbase), Key-value pair databases, Kadoop for Big Data, Document stores (MongoDB, Coachbase)
- Traditional Data Engineering: Database management, ETL pipelines, data visualization
- New things in Data Engineering: Distributed computing, DevOps, Implementation of ML models
- Emerging technologies such as Cloud Computing, Machine Learning, and Big Data, are continually reshaping the data ecosystem and the possibilities it offers.

#### Responsibilities and Skillsets of a Data Engineer
- Analytics-ready data: Accurate, Reliable, Complies to Regulations, Accessible to consumers when they need it
- Databases & Data Warehouses:
    - RDBMS: IBM DB2, MySQL, Oracle Database, PostgreSQL
    - NoSQL: Redis, MongoDB, Cassandra, Neo4J
    - Data Warehouses: Oracle Exadata, IBM Db2 Warehouse on Cloud, IB Netezza Performance Server, Amazon RedShift
- Data Pipelines: Apache beam, Airflow, DataFlow
- ETL Tools: IBM Infosphere, AWS Glue, Improvado
- Languages:
    - Query languages: SQL (Relational Databses), SQL-like query languages for NoSQL databses
    - Programming lnaguages: Python, R, Java
    - Shell & Scripting Languages: Unix/ Linux Shell & Powershell
- Big Data Processing tools: Hadoop, Hive, Spark
- Having a working knowledge of comparable technologies can help us evaluate the trade-offs between different tools and make appropriate recommendations. 
- Data Engineering = Intersection of Software Engineering & Data Science
- Functional Skills of DE:
    - Convert business requirements into technical specifications
    - Work with complete software development lifecycle: Ideation -> Architecture -> Design -> Prototyping -> Testing
    - Understand data's potential application in business
    - Understand risks of poor data management (Data Quality, Privacy, Security, Compliance)
- Detail-oriented control-freak ;-)

#### The Data Ecosystem and Languages for Data Professionals
- Extract data from disparate sources
- Architecture & manage data pipelines for transformation, integration, data storage
- Architect, manage repositories
- Automate & optimize workflows & data flow between systems
- Develop applications needed through the DEing workflow
- Types of Data
    - Structured: Follows a rigid format and can be organized into rows & columns (e.g. databases, spreadsheets, Online Transaction Processing, Online forms, Sensors GPS & RFID, Network & Web Server Logs), well-defined schemas
    - Semi-structured: Has some organization properties, data does not conform to a rigid structure (email, JSON, XML/ other markup languages, binary executables, TCP/IP packets, zipped files, integration of data), contains tags, elements or metadata which is used to group data & organize it in hierarchy
    - Unstructured: Complex data, mostly qualitative information cannot be structured into rows & columns, does not have an easily identifiable strcture (Photos, videos, audios, PPT, text files, PDFs, social media feeds, web pages, media logs, surveys), does not follow any particular format, sequence, semantics, rules
- Data sources: Relational & Non-Relational databases, APIs, Web Services, Web Scraping, Data Streams & Feeds, Social Platforms, Sensor Devices
- Data repositories:
    - Transactional/ Online Transaction Processing (OLTP)System: 
        - Store high volume day-to-day operational data (Banking, ATM transactions, airine bookings)
        - Typically relational, but can also be non-relational
    - Analytical/ Online Analytical Processing (OLAP) System
        - Optimized for conducting complex data analytics
        - Include R & NR databases, data ware houses, data marts, data lakes, big data stores
- Data pipeline
    -  A set of tools & processes that cover the journey of data from source to destination systems
    - Data integrated within a data pipeline using processes such as ETL, ELT
- Languages
    - Query: SQL for querying & manipulating data
    - Programming: Python for developing data applications
    - Shell & Scripting: Repetitive operational tasks
- Derive meaning from data
- Delimited text files: File used to store data as text, each value is separated by a delimiter (a sequence of 1 or more characters for specifying the boundary between independent entities/ values)
- XML/ Extensible Markup Language - markup language with set rules for encoding, self-descriptive, platform/ programming language  independent, simpler to share data between systems