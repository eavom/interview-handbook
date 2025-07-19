### suppose 2 wide transformation and one action and handling 2 GB data. How many stages and task/Partitions will get created?
 
Answer:
2 wide transformation 3 stages + 1 action means 1 job +  2 GB of data default size 120 MB i.e. 16 partitions or tasks


### What is the difference between repartition() and coalesce() in PySpark? When would you use each?

Answer:

### What are wide vs narrow transformations in Spark? Why does it matter for performance?

Answer:


### How does the Catalyst optimizer work in Spark SQL? What kinds of optimizations does it perform?

Answer:


### What are broadcast joins in PySpark, and when are they recommended? What are the limits?

Answer:

### How does Spark handle data skew, and what are techniques to mitigate it in joins or aggregations?

Answer:

### Explain how checkpointing differs from caching or persisting. When would you use checkpointing?

Answer:

### Describe the stages and tasks in a Spark job. How can you identify bottlenecks using the DAG?

Answer:


### What is the difference between an action and a transformation in PySpark? Give 2 examples of each

Answer:


11. You have a huge dataset with skewed keys causing stage failures. How do you redesign your PySpark job to handle skew?
12. How would you write a custom partitioner in PySpark, and why might you need one?
13. You observe shuffle spill to disk during a join. What are the root causes and possible fixes?
14. In a real-time streaming pipeline using Structured Streaming, how would you handle late-arriving data?
15. How do watermarking and windowing work together in Structured Streaming? Give an example.
16. How can you use explode() and posexplode() in PySpark to flatten nested JSON data?
17. What are the trade-offs of using DataFrame API vs RDD API in a large ETL pipeline?
18. Explain how Spark handles fault tolerance. What happens if an executor fails during a job?
19. You're dealing with a dataset of 100 TB. What configuration and design strategies would you apply to run efficiently on Spark?
20. How would you implement Slowly Changing Dimension Type 2 (SCD Type 2) in PySpark?