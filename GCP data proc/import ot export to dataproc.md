# to import 

-  text_source_path=" "
- for text ,csv,paq,json, other files 
 -df2=spark.read.text(text_source_path)
-df2.show(truncate=False)


# to export 

- "sink_source_path=" "
- same for text , qaq, csv, json, other files 
- "df.write.csv(sink_source_path,header=True)"
- while export pyspark deveide data into parts  if you want iit in a single file  use coalesce
- -df.coalesce(1).write.csv(sink_source_path,header=True)




 # in this there are two methods  of partitioning


- converting the data into smaller chunks

- 
  # re-partition: increase or decrease the of file or partititon
  - involve sufflering
  - data moved across the nords
  - costly 



   #coalesce:

  - to reduce the no of partititoning
  - no suffling
  - no data moment happing
 

" df.rdd.getNumPartitions() "
- to know number of partitions 
