



## 1 command 
* time hadoop jar /opt/cloudera/parcels/CDH-5.11.0-1.cdh5.11.0.p0.34/jars/hadoop-examples.jar teragen -Dmapred.map.tasks=8 -Dmapreduce.map.memory.mb=512 -Ddfs.block.size=16777216 65536000  /user/zhou/tgen


## 2 job output

* [zhou@ip-172-31-34-224 /]$ time hadoop jar /opt/cloudera/parcels/CDH-5.11.0-1.cdh5.11.0.p0.34/jars/hadoop-examples.jar teragen -Dmapred.map.tasks=8 -Dmapreduce.map.memory.mb=512 -Ddfs.block.size=16777216 65536000  /user/zhou/tgen
* 17/05/12 04:11:38 INFO client.RMProxy: Connecting to ResourceManager at ip-172-31-32-94.us-west-2.compute.internal/172.31.32.94:8032
* 17/05/12 04:11:39 INFO terasort.TeraGen: Generating 65536000 using 8
* 17/05/12 04:11:39 INFO mapreduce.JobSubmitter: number of splits:8
* 17/05/12 04:11:39 INFO Configuration.deprecation: mapred.map.tasks is deprecated. Instead, use mapreduce.job.maps
* 17/05/12 04:11:39 INFO Configuration.deprecation: dfs.block.size is deprecated. Instead, use dfs.blocksize
* 17/05/12 04:11:39 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_1494559939430_0001
* 17/05/12 04:11:40 INFO impl.YarnClientImpl: Submitted application application_1494559939430_0001
* 17/05/12 04:11:40 INFO mapreduce.Job: The url to track the job: http://ip-172-31-32-94.us-west-2.compute.internal:8088/proxy/application_1494559939430_0001/
* 17/05/12 04:11:40 INFO mapreduce.Job: Running job: job_1494559939430_0001
* 17/05/12 04:11:48 INFO mapreduce.Job: Job job_1494559939430_0001 running in uber mode : false
* 17/05/12 04:11:48 INFO mapreduce.Job:  map 0% reduce 0%
* 17/05/12 04:12:06 INFO mapreduce.Job:  map 8% reduce 0%
* 17/05/12 04:12:10 INFO mapreduce.Job:  map 24% reduce 0%
* 17/05/12 04:12:11 INFO mapreduce.Job:  map 31% reduce 0%
* 17/05/12 04:12:13 INFO mapreduce.Job:  map 32% reduce 0%
* 17/05/12 04:12:16 INFO mapreduce.Job:  map 37% reduce 0%
* 17/05/12 04:12:17 INFO mapreduce.Job:  map 39% reduce 0%
* 17/05/12 04:12:19 INFO mapreduce.Job:  map 40% reduce 0%
* 17/05/12 04:12:22 INFO mapreduce.Job:  map 45% reduce 0%
* 17/05/12 04:12:23 INFO mapreduce.Job:  map 47% reduce 0%
* 17/05/12 04:12:25 INFO mapreduce.Job:  map 48% reduce 0%
* 17/05/12 04:12:28 INFO mapreduce.Job:  map 56% reduce 0%
* 17/05/12 04:12:29 INFO mapreduce.Job:  map 57% reduce 0%
* 17/05/12 04:12:34 INFO mapreduce.Job:  map 64% reduce 0%
* 17/05/12 04:12:35 INFO mapreduce.Job:  map 66% reduce 0%
* 17/05/12 04:12:39 INFO mapreduce.Job:  map 68% reduce 0%
* 17/05/12 04:12:40 INFO mapreduce.Job:  map 73% reduce 0%
* 17/05/12 04:12:44 INFO mapreduce.Job:  map 75% reduce 0%
* 17/05/12 04:12:45 INFO mapreduce.Job:  map 78% reduce 0%
* 17/05/12 04:12:46 INFO mapreduce.Job:  map 82% reduce 0%
* 17/05/12 04:12:51 INFO mapreduce.Job:  map 84% reduce 0%
* 17/05/12 04:12:52 INFO mapreduce.Job:  map 86% reduce 0%
* 17/05/12 04:12:53 INFO mapreduce.Job:  map 91% reduce 0%
* 17/05/12 04:12:57 INFO mapreduce.Job:  map 95% reduce 0%
* 17/05/12 04:13:03 INFO mapreduce.Job:  map 100% reduce 0%
* 17/05/12 04:13:03 INFO mapreduce.Job: Job job_1494559939430_0001 completed successfully
* 17/05/12 04:13:03 INFO mapreduce.Job: Counters: 33
*         File System Counters
*                 FILE: Number of bytes read=0
*                 FILE: Number of bytes written=1020872
*                 FILE: Number of read operations=0
*                 FILE: Number of large read operations=0
*                 FILE: Number of write operations=0
*                 HDFS: Number of bytes read=682
*                 HDFS: Number of bytes written=6553600000
*                 HDFS: Number of read operations=32
*                 HDFS: Number of large read operations=0
*                 HDFS: Number of write operations=16
*         Job Counters 
*                 Launched map tasks=8
*                 Other local map tasks=8
*                 Total time spent by all maps in occupied slots (ms)=431234
*                 Total time spent by all reduces in occupied slots (ms)=0
*                 Total time spent by all map tasks (ms)=431234
*                 Total vcore-milliseconds taken by all map tasks=431234
*                 Total megabyte-milliseconds taken by all map tasks=441583616
*         Map-Reduce Framework
*                 Map input records=65536000
*                 Map output records=65536000
*                 Input split bytes=682
*                 Spilled Records=0
*                 Failed Shuffles=0
*                 Merged Map outputs=0
*                 GC time elapsed (ms)=1820
*                 CPU time spent (ms)=135810
*                 Physical memory (bytes) snapshot=1485037568
*                 Virtual memory (bytes) snapshot=9008410624
*                 Total committed heap usage (bytes)=1872232448
*                 Peak Map Physical memory (bytes)=255332352
*                 Peak Map Virtual memory (bytes)=1136533504
*         org.apache.hadoop.examples.terasort.TeraGen$Counters
*                 CHECKSUM=140750829423462787
*         File Input Format Counters 
*                 Bytes Read=0
*         File Output Format Counters 
*                 Bytes Written=6553600000
* 
* real    1m27.370s
* user    0m5.828s
* sys     0m0.729s
* [zhou@ip-172-31-34-224 /]$ 

## 3 time command
* real    1m27.370s
* user    0m5.828s
* sys     0m0.729s
* [zhou@ip-172-31-34-224 /]$ 

## 4 hdfs dfs -ls /user/zhou/tgen

* [zhou@ip-172-31-34-224 /]$ zhou dfs -ls /user/zhou/tgen
* Found 9 items
* -rw-r--r--   3 zhou beijin          0 2017-05-12 04:13 /user/zhou/tgen/_SUCCESS
* -rw-r--r--   3 zhou beijin  819200000 2017-05-12 04:12 /user/zhou/tgen/part-m-00000
* -rw-r--r--   3 zhou beijin  819200000 2017-05-12 04:12 /user/zhou/tgen/part-m-00001
* -rw-r--r--   3 zhou beijin  819200000 2017-05-12 04:12 /user/zhou/tgen/part-m-00002
* -rw-r--r--   3 zhou beijin  819200000 2017-05-12 04:12 /user/zhou/tgen/part-m-00003
* -rw-r--r--   3 zhou beijin  819200000 2017-05-12 04:12 /user/zhou/tgen/part-m-00004
* -rw-r--r--   3 zhou beijin  819200000 2017-05-12 04:12 /user/zhou/tgen/part-m-00005
* -rw-r--r--   3 zhou beijin  819200000 2017-05-12 04:12 /user/zhou/tgen/part-m-00006
* -rw-r--r--   3 zhou beijin  819200000 2017-05-12 04:13 /user/zhou/tgen/part-m-00007
* [zhou@ip-172-31-34-224 /]$ 

