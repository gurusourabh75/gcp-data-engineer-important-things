# to import 

-  text_source_path=" "
- for text ,csv,paq,json, other files 
 -df2=spark.read.text(text_source_path)
-df2.show(truncate=False)


# to export 

- sink_source_path=" "
- same for text , qaq, csv, json, other files 
- df.write.csv(sink_source_path,header=True)
