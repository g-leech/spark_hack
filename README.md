# spark_hack
Lightly edited Spark. Just a jar with flipped regParam


### How to use in Pyspark:

* Pass in the new jar via `spark2-submit --jars [here]` or `pyspark2 --jars [here]`
* No spaces after commas!
* [See also](https://stackoverflow.com/questions/31093179/how-to-use-custom-classes-with-apache-spark-pyspark)
* `from pyspark.ml.regression import GeneralizedLinearRegressionLasso`

### Where?

In Cloudera the standard jars are here: `/opt/cloudera/parcels/SPARK2/lib/spark2/jars/spark-mllib_2.11-2.3.0.cloudera3.jar`
