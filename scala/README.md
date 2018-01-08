# simple-spark-api-app > scala

Terminal output:

```bash
$ spark-submit \
> --class "SimpleApp" \
> --master local[4] \
> target/scala-2.10/scala_2.10-0.1.jar 
Using Spark\'s default log4j profile: org/apache/spark/log4j-defaults.properties
18/01/08 16:11:54 INFO SparkContext: Running Spark version 2.2.0
Lines with a: 61, Lines with b: 30
```