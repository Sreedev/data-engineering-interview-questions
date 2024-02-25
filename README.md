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
* **What Do * args and ** kwargs Mean?**
     * args defines an ordered function and that ** kwargs represent unordered arguments used in a function. To impress your interviewer, you may want to write down this code in a visual example to demonstrate your expertise.  <br> <br>
* **As a data engineer, how have you handled a job-related crisis?**
     * Data engineers have a lot of responsibilities, and it’s a genuine possibility that you’ll face challenges while on the job, or even emergencies. Just be honest and let them know what you did to solve the problem. If you have yet to encounter an urgent issue while on the job or this is your first data engineering role, tell your interviewer what you would do in a hypothetical situation. For example, you can say that if data were to get lost or corrupted, you would work with IT to make sure data backups were ready to be loaded, and that other team members have access to what they need.<br> <br>
* **Do you have any experience with data modeling?**
     * Start with a simple yes or no. Even if you don’t have experience with data modeling, you’ll want to be at least able to define it: the act of transforming and processing fetched data and then sending it to the right individual(s). If you are experienced, you can go into detail about what you’ve done specifically. Perhaps you used tools like Talend, Pentaho, or Informatica. <br> <br>
* **What are the essential skills required to be a data engineer?** <br>
     - Comprehensive knowledge about Data Modelling.<br>
     - Understanding about database design & database architecture. In-Depth Database Knowledge – SQL and NoSQL.<br>
     - Working experience of data stores and distributed systems like Hadoop (HDFS).
     - Data Visualization Skills.<br>
     - Experience in Data Warehousing and ETL (Extract Transform Load) Tools.<br>
     - You should have robust computing and math skills.<br>
     - Outstanding communication, leadership, critical thinking, and problem-solving capabilities are an added advantage. <br> <br>
* **Can you name the essential frameworks and applications for data engineers?** <br>
     * You can list all of the technical applications like SQL, Hadoop, Python, and more, along with your proficiency level in each. You can also state the frameworks which want to learn more about if given the opportunity.<br> <br>
* **Are you experienced in Python, Java, Bash, or other scripting languages?** <br>
     * It is essential to have a comprehensive knowledge of scripting languages, as it allows you to perform analytical tasks efficiently and automate data flow.<br> <br>
* **Can you differentiate between a Data Engineer and a Data Scientist?** <br>
     * Data Engineers develop, test, and maintain the complete architecture for data generation, whereas data scientists analyze and interpret complex data. They tend to focus on organization and translation of Big Data. Data scientists require data engineers to create the infrastructure for them to work.<br> <br>
* **What, according to you, are the daily responsibilities of a data engineer?** <br>
     - Development, testing, and maintenance of architectures.<br>
     - Aligning the design with business requisites.<br>
     - Data acquisition and development of data set processes.<br>
     - Deploying machine learning and statistical models<br>
     - Developing pipelines for various ETL operations and data transformation<br>
     - Simplifying data cleansing and improving the de-duplication and building of data.<br>
     - Identifying ways to improve data reliability, flexibility, accuracy, and quality.<br><br>
* **What is your approach to developing a new analytical product as a data engineer??** <br>
     * Your first step would be to understand the outline of the entire product to comprehend the complete requirements and scope. Your second step would be to look into the details and reasons for each metric. Think about as many issues that could occur, and it helps you to create a more robust system with a suitable level of granularity.<br><br>
* **What was the algorithm you used on a recent project?** <br>
     * Can ask some follow-up questions like: Why did you choose this algorithm, and can you contrast this with other similar ones?, What is the scalability of this algorithm with more data? Are you happy with the results? If you were given more time, what could you improve?<br><br>
* **How can you deploy a big data solution?** <br>
     * Data Integration/Ingestion: In this step, the extraction of data using data sources like RDBMS, Salesforce, SAP, MySQL is done.<br>
     * Data storage: The extracted data would be stored in an HDFS or NoSQL database.<br>
     * Data processing: the last step should be deploying the solution using processing frameworks like MapReduce, Pig, and Spark.<br><br>

### Python Questions
 * **How do you perform web scraping in Python?**
      * Access the webpage using the request library and URL
        Extract tables and information using BeautifulSoup,
        Convert it into the structure for using Pandas,
        Clean it using Pandas and Numpy,
        Save the data in the form of a CSV file. <br> <br>
* **Which Python libraries are most efficient for data processing?**
     * The most popular libraries for data processing are Pandas and Numpy. For parallel processing of large datasets, we use Dask, Pyspark, Datatable, and Rapids. They all have pros and cons, and we must understand the application based on data requirements. <br> <br>
* **Which Python libraries would you utilize for proficient data processing?**
     * Your answer should include NumPy as it is utilized for efficient processing of arrays of numbers and pandas, which is great for statistics and data preparation for machine learning work. The interviewer can ask you questions like why would you use these libraries and list some examples where you would not use them.<br> <br>
     
### SQL Questions
* **What are Common Table Expressions in SQL?**
     * If we are using this subquery multiple times, we can create a temporary table “temp” and call it in our query using the SELECT command. <br> <br>
* **How to rank the data in SQL?**
     * Data engineers commonly rank values based on parameters such as sales and profit. The query below ranks the data based on sales. You can also use DENSE_RANK(), which does not skip subsequent ranks if the values are the same. <br> <br>
* **Can you create a simple Temporary Function and use it in SQL query?**
     * Just like Python, you can create a function in SQL and use it in your query. It looks elegant, and you can avoid writing huge case statements <br> <br>
---------------------------------------------------------------------------------
## References and sources
1. Datacamp - https://www.datacamp.com/blog/top-21-data-engineering-interview-questions-and-answers
2. Simplilearn - https://www.simplilearn.com/data-engineer-interview-questions-and-answers-article
----------------------------------------------------------------------------------

### ☕[BUY ME A COFFEE](https://www.buymeacoffee.com/thelifeimprovised)!

#### Feel the Buzz of Knowledge! If this repo added a spark to your day, why not buy me a coffee? Your support fuels the inspiration behind each project.

-----------------------------------------------------------------------------------

#### Follow me on LinkedIn and X to see all my updates related to technology and follow me on Facebook, Thread, Instagram, and YouTube to see all updates on travel and life.
#### Personal Blog: www.thelifeimprovised.com
#### Let's learn and grow together 💚
