The [Sqoop](../../data-proc/operations/sqoop-usage.md) utility lets you import databases to the {{ dataproc-full-name }} cluster. Depending on the {{ dataproc-full-name }} cluster configuration, you can import data to:

* An {{ objstorage-full-name }} bucket
* An HDFS directory
* Apache Hive
* Apache HBase

To use Sqoop to import the source cluster databases to the {{ dataproc-full-name }} target cluster:

1. [Prepare the source cluster](#prepare).
1. [Run the import](#import).
1. [Make sure the import is correct](#check).
