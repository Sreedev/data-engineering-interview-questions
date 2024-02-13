# Data Engineering Interview Questions from various sources. 
## Created and maintained by Sreedev
This is a place where you can come to prepare for the data engineering interviews. I am consolidating questions from different sources to prepare the most relevant source of data engineering interview questions.  

## Interview Questions
#### *Please read more on links and resources available as this consolidation only includes questions and short answers.*
 * **Can you explain the design schemas relevant to data modeling?** 
      * There are three data modeling design schemas: Star, Snowflake, and Galaxy. Browse to understand more about these schemas.<br> <br> 
 * **Which ETL tools have you worked with? What is your favorite, and why?** 
      * You can list the tools you have used the most and are well versed with.<br> <br> 
 * **What is the difference between a data warehouse and an operational database?**
      * A Data warehouse serves historical data for data analytics tasks and decision-making, Operational Database Management Systems are used to manage dynamic datasets in real-time. <br> <br> 
 * **Why do you think every firm using data systems requires a disaster recovery plan?**
      * This task involves real-time backing up of files and media. The backup storage will be used to restore the files in case of a cyber-attack or equipment failure. Security protocols are placed to monitor, trace, and restrict both incoming and outgoing traffic.<br> <br>
 * **What is data orchestration, and what tools can you use to perform it?**
      * Data orchestration is an automated process for accessing raw data from multiple sources, performing data cleaning, transformation, and modeling techniques, and serving it for analytical tasks. The most popular tools are Apache Airflow, Prefect, Dagster, and AWS Glue. <br> <br>
* **What tools do you use for analytics engineering?**
     * Analytical engineering is a process where we access the processed data, transform it, apply statistical modeling, and visualize it in the form of reports and dashboards. The popular tools are DBT (data build tool), BigQuery, Postgres, Metabase, Google Data Studio, and Tableau. <br> <br>
* **What tools do you use for analytics engineering?**
     * Analytical engineering is a process where we access the processed data, transform it, apply statistical modeling, and visualize it in the form of reports and dashboards. The popular tools are DBT (data build tool), BigQuery, Postgres, Metabase, Google Data Studio, and Tableau. <br> <br>
     
### Python Questions
 * **How do you perform web scraping in Python?**
      * Access the webpage using the request library and URL
        Extract tables and information using BeautifulSoup,
        Convert it into the structure for using Pandas,
        Clean it using Pandas and Numpy,
        Save the data in the form of a CSV file. <br> <br>
* **Which Python libraries are most efficient for data processing?**
     * The most popular libraries for data processing are Pandas and Numpy. For parallel processing of large datasets, we use Dask, Pyspark, Datatable, and Rapids. They all have pros and cons, and we must understand the application based on data requirements. <br> <br>
     
### SQL Questions
* **What are Common Table Expressions in SQL?**
     * If we are using this subquery multiple times, we can create a temporary table “temp” and call it in our query using the SELECT command. <br> <br>
* **How to rank the data in SQL?**
     * Data engineers commonly rank values based on parameters such as sales and profit. The query below ranks the data based on sales. You can also use DENSE_RANK(), which does not skip subsequent ranks if the values are the same. <br> <br>
* **Can you create a simple Temporary Function and use it in SQL query?**
     * Just like Python, you can create a function in SQL and use it in your query. It looks elegant, and you can avoid writing huge case statements <br> <br>
---------------------------------------------------------------------------------
## References
1. Datacamp - https://www.datacamp.com/blog/top-21-data-engineering-interview-questions-and-answers
----------------------------------------------------------------------------------

### ☕[BUY ME A COFFEE](https://www.buymeacoffee.com/thelifeimprovised)!

#### Feel the Buzz of Knowledge! If this repo added a spark to your day, why not buy me a coffee? Your support fuels the inspiration behind each project.

-----------------------------------------------------------------------------------

#### Follow me on LinkedIn and X to see all my updates related to technology and follow me on Facebook, Thread, Instagram, and YouTube to see all updates on travel and life.
#### Personal Blog: www.thelifeimprovised.com
#### Let's learn and grow together 💚
