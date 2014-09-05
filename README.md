# Databricks Spark Knowledge Base

The contents contained here is also published in [Gitbook format](http://databricks.gitbooks.io/databricks-spark-knowledge-base/).

* [Best Practices](best_practices/README.md)
   * [Avoid GroupByKey](best_practices/prefer_reducebykey_over_groupbykey.md)
   * [Don't copy all elements of a large RDD to the driver](best_practices/dont_call_collect_on_a_very_large_rdd.md)
* [General Troubleshooting](troubleshooting/README.md)
   * [Job aborted due to stage failure: Task not serializable: ](troubleshooting/javaionotserializableexception.md)
   * [Missing Dependencies in Jar Files](troubleshooting/missing_dependencies_in_jar_files.md)
   * [Error running start-all.sh - Connection refused](troubleshooting/port_22_connection_refused.md)
* [Spark Streaming](spark_streaming/README.md)
   * [ERROR OneForOneStrategy](spark_streaming/error_oneforonestrategy.md)