# Spark 

Steps :)

1) Start the Hadoop deamon by using start-all.sh in hadoop*/bin directory 
2) Load the data into HDFS(Hadoop Distributed File System)
3) Then start spark deamon bin/start-all.sh followed by spark folder
4) By scala Implement word count project and build it by SBT(simple build tool) 
5) Finally run by using following command .
    
       spark-submit --class WordCount --master yarn --deploy-mode cluster /home/manohar/resource/sparkjar/wordcount.jar /input/Input.txt /output/spark/spark_yarn_out_dec_24


For more info   https://github.com/manoharjaya/repo/blob/Docs/myDocs/Docs/spark-tutorial.txt
