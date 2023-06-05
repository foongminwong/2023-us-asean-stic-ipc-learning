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

#### Data Repositories, Data Pieplines, Data Integration
- Types of data repositories: Datbases, Data Warehouses, Big Data Stores
- Factors influence the choice of database: Data Type & structure, uerying mechanisms, Latency requirements, Transaction Speeds, Intended use of data
- RDBMS vs NoSQL (Not Only SQL)
- NoSQL
    - Emerged in response to volume, diversity, speed
    - Built for speed, flexibility, scale
    - Data can be stored in a schema-less
    - Widely used for processing big data
- Data warehouse: Works as a central repository that merges information coming from disparate sources and consolidates them through ETL process into one comprehensive database for analytics, and business intelligence
- Data Marts & Data Warehouses have been historically relational, since much of the traditional enterprise data has resided in RDBMSes
- Big Data Stores - Distributed computational & storage infrastructure to store, scale, process VERY large data sets
- In summary, data repositories help isolate data & make reporting & analytics more efficient & credible while serving as a data archive.
- RDBMS
    - Collection of data organized into table structure, where the tables can be linked, or related, based on data common to each
    - Rows = records, Columns = attributes
    - Capability of relating tables based on common data enables you to retrieve an entirely new table from data in 1 or more tables with a single query (stuctured query language aka SQL)
    - Organizational principle, well-defined strcture, schema
    - Better than speadsheets (limited rows& columns), RDBMS is ideal for optimized storage, retrieval, processing large columes of data
    - Each table has unique set of rows & columns
    - Relationships can be defined between tables, which minimizes data redundancy
    - Fields can restricted to specific data types and values, to minize irregularities & leads to greater consistency & data integrity
    - Use SQL for querying to retrieve & process millions of records in seconds 
    - Provide control access of data, ensure the standards & policies for governing data can be enforced
    - Small desktop systems --> massive cloud-based systems
    - Open source w/ internal/ commercial support, commercial closed-source: IBM DB2, Microsoft SQL Server, MySQL, Oracle Database, PostgreSQL
    - Cloud-based Relational DB aka Database-as-a-Service: Limitless compute & storage capabilites offered by the cloud: Amazon Relational Database Service (RDS), Google CLoud SQL, IBM DB2 on CLoud, Oracle Cloud, SQL Azure
    - Pros: 
        - Create meaningful info by joining tables
        - Flexibility to add new columns/ new tables/rename relations & make other changes while database is in use
        - Minimize data redundancy by allowing relationships to be defined between tables
        - Offer export & import options that provide ease of backup & disaster recovery (run shell script daily to backup data)
        - ACID-compliance - Atomicity, Consistency, Isolation, Durability. Ensure data accurate and consistent despite failures & database transactions are procesed reliably
    - Use cases: OLTP, OLAP, IoT Solutions
    - Cons: 
        - Does not work well with semi-strucred & unsctructured data
        - Migration between 2 RDBMS's is possible only when the source & destination tables have identical schemas & data types
        - Limit on the length of data fields, entering a value greater than the defined length of a data field reslts in loss of information
- NoSQL
    - Provides flexible schemas for the storage & retrieval of data
    - Gained greater popularity due to the emergence of cloud computing, big data, high-volume web & mobile applications
    - Chosen for their attributes around scale, performance, ease of use
    - Do not, typically, use the structured query
    - Store data in a schema-less or free-form fashion
    - Types of NoSQL databases:
        - Key-value store:
            - Data stored as a collection of key-value pairs, A key represents an attribute of the data & is a unique identifier
            - Both keys & values can be anything from simple integers/ strings to complex JSON documents
            - Great for storing user session data, user preferences, real-time recommendations, targeted advertising, in-memory data caching
            - Not great fit if you want to query data on specific data value, need relationships between data values, need multiple unique keys
            - Redis, Memcached, DynamoDB
        - Document Based:
            - Store each record & its associated data within a single document
            - Enable flexible indexing, powerful ad hoc queries, analytics over collections of documents
            - preferred for eCommerce platforms, medical records storage, CRM platforms, analytics platforms
            - Not a great fit if you want to run complex search queries, perform multi-operation transactions
            - MongoDB, DocumentDB, CouchDB, Cloudant
        - Column Based:
            - Store data in cells grouped as columns of data instead of rows
            - Logical grouping of columns = columns that are usually accessed together  =  column family
            - all cells corresponding to a column are saved as a continuous disk entry, making access& search faster
            - great for systems that require heavy write requests, storing time-series data, weather data, IoT data
            - Not great fit if you want to run complex queries, change querying patterns frequently
            - Cassandra, Apache HBase
        - Graph Based
            - Graphical model to represent & store data
            - Useful for visualizing, analyzing, finding connections between different pieces of data
            - Nodes contain data, arrows represent relationships
            - Use cases: Social networks, product recommendations, network diagrams, fraud detection, access management
            - Not a great fit if you want to process high volumes of transactions, since graph DBs are not optimized for large-colume analytics queries
            - Neo4j, CosmoDB
        - Pros:
            - Ability to handle large volumes of structured, semi-structured, unstructured data
            - Ability to run as a distributed system scaled across multiple data centers, which enables them to take advantage of cloud computing infrastructure
            - An efficient & cost-effective scale-out architecture that provides additional capacity & performace with the addition of new nodes
            - Simpler design, better control over availability, improved scalability, that makes it agile, flexible, and support quick iterations
- RDBMS vs NoSQL: Rigid schemas, Typed & composed VS schema-agnostic, Expensive for maintaining high-end, commercial relational dbms VS specifically disgned for low-cost commodity hardware, ACID compliant vs not ACID compliant