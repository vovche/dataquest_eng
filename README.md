Zero to Hero: <a href = "https://www.dataquest.io/home">DATAQUEST</a>'s Become a Data Engineer
------
Here's how to get DataQuest's Data Engineering Track missions' content to work on your localhost.
Using data from my <a href = "https://github.com/nmolivo/valencia-data-projects/tree/master/valenbisi">Valenbisi ARIMA modeling project</a>, I will walk through steps using PostgreSQL, Postico, and the Command Line to get our DataQuest exercises running out of a Jupyter Notebook. 

This will not be a complete repitition of the many resources I used, so be sure to look out for any links I include if it seems I've skipped a few steps.

Important note: In DataQuest, each exercise re-initiates the connection and cursor class of `psycopg2` when interacting with the Postgres DB, with no deliberate closing of the connection. When we productionize our scripts, it will be more efficient and correct to use a `with` statement, which will close the connection once the operations are complete. For the sake of the exercises, I will follow DataQuest's format. I will switch to the `with` statement as we approach production.

There will be Three Directories in this Repository, each aligning with DataQuest's Data Engineer Track. Each directory will contain a `README.md` with more details on the content covered in it.
* <a href = "https://github.com/nmolivo/dataquest_eng/tree/master/1_production_databases"><b>Production Databases</b></a>
  * Postgres For Data Engineers
    * <a href = "https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/01_intro_postgres.ipynb">Intro to Postgres</a>
    * <a href = "https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/02_opt_tables.ipynb">Creating Tables</a>
    * <a href = "https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/03_manage_tables.ipynb">Managing Created Tables</a>
    * <a href="https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/04_extract_data.ipynb">Loading and Extracting Data with Tables</a>
    * <a href="https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/05_db_mgmt.ipynb">User and Database Management</a>
    * <a href="https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/06_proj_storm.ipynb"><b>Project: Storing Tropical Storm Data</b></a>
  * Optimizing Postgres Databases
    * <a href = "https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/07_postgres_internals.ipynb">Exploring Postgres Internals</a>
    * <a href = "https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/08_debugging_queries.ipynb">Debugging Postgres Queries</a>
    * <a href = "https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/09_index_intro.ipynb">Using an Index</a>
    * <a href = "https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/10_advanced_indexing.ipynb">Advanced Indexing</a>
    * <a href = "https://github.com/nmolivo/dataquest_eng/blob/master/1_production_databases/11_db_vacuuming.ipynb">Vacuuming Postgres Databases</a>
* <a href = "https://github.com/nmolivo/dataquest_eng/tree/master/2_handling_big_data_in_python"><b>Handling Large Data Sets In Python</b></a>
  * Processing Large Datasets in Pandas
    * Optimizing Dataframe Memory Footprint
    * Processing Dataframes in Chunks
    * <b>Guided Project: Practice Optimizing Dataframes and Processing in Chunks</b>
    * Augmenting Pandas with SQLite
    * <b>Guided Project: Analyzing Startup Fundraising Deals from Crunchbase</b>
  * Optimizing Code Performance on Large Datasets
    * CPU Bound Programs
    * I/O Bound Programs
    * Overcoming the Limitations of Threads
    * Quickly Analyzing Data with Parallel Processing
    * <b>Guided Project: Analyzing Wikipedia Pages</b>
  * Algorithms and Data Structures
    * Processing Tasks with Stacks and Queues
    * Effectively Using Arrays and Lists
    * Sorting Arrays and Lists
    * Searching Arrays and Lists
    * Hash Tables
    * <b>Guided Project: Analyzing Stock Prices</b>
  * Recursion and Trees
    * Overview of Recursion
    * Introduction to Binary Trees
    * Implementing a Binary Heap
    * Working with Binary Search Trees
    * Performance Boosts of Using a B-Tree
    * Performance Boosts of Using a B-Tree II
    * <b>Guided Project: Implementing a Key-Value Database</b>
* <a href = "https://github.com/nmolivo/dataquest_eng/tree/master/3_data_pipelines"><b>Data Pipelines</b></a>
  * Building a Data Pipeline
    * Functional Programming
    * Pipeline Tasks
    * Building a Pipeline Class
    * Multiple Dependency Pipeline
    * <b>Guided Project: Hackernews Pipeline</b>

For Non-Commercial Use Only
------
I highly reccommend participating in this course as a member of DATAQUEST.
