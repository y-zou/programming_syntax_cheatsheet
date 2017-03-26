# scala in hdfs/spark-shell

## read files

	val lines = sc.textFile("hdfs:/myhdfs/mycsv.csv")	#config sc first!
	val item =  lines.map(line => line.split(","))
