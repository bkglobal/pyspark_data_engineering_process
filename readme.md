Spark batch processing


Scala code
`
val data = 1 to 10000
val distData = sc.parallelize(data)
distData.filter(_ < 10).collect()
`